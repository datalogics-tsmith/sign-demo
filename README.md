# sign-demo

Steps to run:
   - Make a server.pem file and place it next to the simple-https-server.py (or acquire one from somewhere)
   -- openssl req -new -x509 -keyout server.pem -out server.pem -days 365 -nodes
   - Fill in the server url and port number in simple-https-server.py
   - Ensure that you have python installed
   - Start the server with 'python simple-https.py'
