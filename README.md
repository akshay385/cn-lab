# cn-lab

## Commands
  sudo apt update

## command for program1 [point-to-point networks with duplex links]
  gedit ns1.tcl

  ns ns1.tcl
 
 ## command for program2 [transmission of ping messages/trace route over a network]
  gedit program2.tcl

  ns program2.tcl
  
  ## command for program3 [Ethernet LAN using n nodes] 
  gedit prog3.tcl
  ns prog3.tcl
  
  ## command for prog4 [GSM implementation]
  install the package ns-allinone2.35
  ## it is recommended to use gcc4 .8, that is executed under the command line
  sudo apt install gcc-4.8 & g++-4.8
  ## After the installation is complete, enter the nc-allinone-2.35 directory to execute
  export CC=gcc-4.8 CXX=g++-4.8 && ./install
  ## I also installed several dependent modules first
  sudo apt-get install build-essential
  sudo apt-get install tcl8.5 tcl8.5-dev tk8.5 tk8.5-dev
  sudo apt-get install libxmu-dev libxmu-headers
  
  ## command for prog5 [CDMA]
  ns prog6.tcl
   
  ## command for prog6 [error detecting code using CRC-CCITT]
  gedit CRC1.java
  javac CRC1.java
  java CRC1
  
  ## command for prog7 [bellman-ford algorithm]
  gedit bellmanford.java
  javac bellmanford.java
  java bellmanford
  
  ## command for prog8 [RSA algorithm to encrypt and decrypt the data]
  gedit RSA.java
  javac RSA.java
  java RSA
  
   ## command for prog9 [UDP Socket programming]
  gedit udpserver.java 
  javac udpserver.java
  java udpserver
  
   
  once the server is ready in an other terminal execute client
   
  gedit udpclient.java
  javac udpclient
  java udpclient
   
   ## commmand for prog10 [TCP/IP sockets]
  gedit TCPS.java
  javac TCPS.java
  java TCPS
  
  once the server is ready in an other terminal execute client
   
  gedit TCPC.java
  javac TCPS.java
  java TCPS
  
  ## commmand for prog10 [leaky bucket]
  gedit prog10.java
  javac prog10.java
  java prog10
  
  
  
   
