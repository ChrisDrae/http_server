Demo Implementation of an HTTP Webserver 

run 
```
gcc http_server.c -o server
./server
```
On linux with gcc installed. To run it and serve files from your local directory.


If you don't already have gcc use 
```
sudo apt install build-essential
```
to install.

The server will spawn ip to 10 threads to handle the incoming requests. 
