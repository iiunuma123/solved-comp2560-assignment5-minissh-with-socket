Download Link: https://assignmentchef.com/product/solved-comp2560-assignment5-minissh-with-socket
<br>
Use socket to write a client/server application to simulate the basic functionality of secure shell. Once the client is connected to the server, it can keep sending shell commands to the server. For each command, the server will return the result of executing the shell command.

<ul>

 <li>The server and client programs can be run on different machines.</li>

 <li>The server program is started first, waiting for client to connect.</li>

 <li>When the server program is terminated with CTRL-C, the client program is also terminated.</li>

 <li>When the client program is terminated with CTRL-C, the server program will wait for the next connection from client.</li>

</ul>

Simplification:

<ul>

 <li>The shell commands from the client are simple ones without arguments.</li>

 <li>The commands from the client can be executed on the server side by different shell processes.</li>

</ul>








