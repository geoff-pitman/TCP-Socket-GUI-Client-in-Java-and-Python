# TCP-Socket-GUI-Client-in-Java
TCP GUI client front end written in Java, server back-end written in Python.

The purpose of this application is to demonstrate tcp/ip socket operations by transferring (ascii) files from the server's working directory, into the client's download directory.
Tested only in Windows, but should run on anything that Python 2.7 and Java jre8 can be installed on. 

Assuming the aforementioned is installed...
#TO RUN...
1. double click 'server.py' file to execute (on nix: 'bash$: python server.py')
2. compile and execute java application  (main is in Client.java)

#Server hardcoded address = "127.0.0.1"
#Server hardcoded port    =  55536
