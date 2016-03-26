fonk-dudle
==========
Setup your own dudle!

### Docker image content
1. Debian
1. Apache webserver
1. Dudle software from https://github.com/kellerben/dudle

### usage
1. **docker run --name dudle -p 80:80 -d fonk/dudle**
1. **Point your browser to http://localhost/dudle**
1. **Enjoy making you own polls**

### persistent polls
Unfortunately the software put the poll data in the webroot, so if you want to persist the polls,
you have to put the whole webroot (/var/www/html/dudle) on an external storage.
