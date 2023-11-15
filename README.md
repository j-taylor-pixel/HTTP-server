# Description
Web server built in python that handles http requests with support for GET and HEAD.
The server uses TCP web sockets and implements the HTTP protocol.

# How to use
Run the webserver

`python webserver.py`

Open a web browser

http://127.0.0.1:10200/HelloWorld.html
http://127.0.0.1:10200/data/foo.html

Enter a file which does not exist and 404 not found will be returned

http://127.0.0.1:10200/not/existingfile.html

Alternatively open Postman and submit the following requests.

GET http://127.0.0.1:10200/HelloWorld.html 

HEAD http://127.0.0.1:10200/data/foo.html

GET http://127.0.0.1:10200/not/existingfile.html

To close the webserver

`ctrl + c`

