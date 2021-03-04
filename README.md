# rpi4bp-hello-world-flask
Basic flask server on Raspberry Pi 4B+

pi@rpi4bp:~ sudo nano mywebserver.py

# Once running, point your local web browser to <localhost of your Raspberry Pi>:80, which is the default port.  You should then see "Hello, World!" in your browser.
 
pi@rpi4bp:~ $ sudo python3 mywebserver.py 

 * Serving Flask app "mywebserver" (lazy loading)
 * Environment: production
   WARNING: Do not use the development server in a production environment.
   Use a production WSGI server instead.
 * Debug mode: on
 * Running on http://0.0.0.0:80/ (Press CTRL+C to quit)
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 159-169-173

192.168.254.23 - - [04/Mar/2021 10:28:38] "GET / HTTP/1.1" 200 -

192.168.254.23 - - [04/Mar/2021 10:28:44] "GET / HTTP/1.1" 200 -

192.168.254.23 - - [04/Mar/2021 10:28:45] "GET / HTTP/1.1" 200 -
