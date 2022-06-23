<h1>Displaying the structure of a TCP Segment</h1>



<h2>Description</h2>
In this lab, I learned to display the structure of a TCP(transmission Control Protocol) segment. TCP is a connection-oriented transport protocol. The TCP segment's header simply contains the sequence number, acknowledgment number, source and destination port numbers, TCP flags, the UDP checksum, urgent pointer, and so on. 
<br />



<h2>Environments Used </h2>

- <b>Windows Server 2016 Standard</b> 

<h2>Languages and Utilities</h2>

- <b>Wireshark</b>

<h2>Program walk-through:</h2>

<p align="center">
From the desktop open Wireshark application: <br/>
<img src="https://i.postimg.cc/1Rg3NqjW/Screen-Shot-2022-06-23-at-11-18-54-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<br />
In the Wirshark Network Analyzer window, select the Ethernet0 interface and click the start Capturing packets icon (sharkfin icon) </br>
<img src="https://i.postimg.cc/xC3yvZ82/Screen-Shot-2022-06-23-at-11-20-10-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
Stop capturing packets after you notice TCP (Transmission Control Protocol):</br>
<img src="https://i.postimg.cc/CxNYzW3g/Screen-Shot-2022-06-23-at-12-13-57-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
Under the Packet details pane, select TCP packet to observe the TCP segment:  <br/>
<img src="https://i.postimg.cc/LXrhNc4W/Screen-Shot-2022-06-23-at-12-17-21-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<p align="center">
click file and save for further observation: <br/>
<img src="https://i.postimg.cc/WpCyTT1y/Screen-Shot-2022-06-23-at-12-18-52-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  

  
  
  

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
