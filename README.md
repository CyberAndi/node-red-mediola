# node-red-mediola
Node-Red Function and Flow for mediola (a.i.o.) Gateways for Smarthome <a href="https://www.mediola.com"><img src="mediola-logo-trans.png"></a>


1.  Create Enject-Node with 1 Minutes Intervall

2.  Insert a http-request-node with Get-Action
    and the URL: http://192.168.01.01/command?XC_USER=yourUser&XC_PASS=yourPassword&XC_FNC=GetStates 

3.  Replace the IP-Adress, Username and Password

4.  Insert a Function Node and put the source-code of function.json in

<img src="mediola-node-red.png"></img>
