<h1>Analyze Network Traffic with TCPDump Home Lab</h1>

<!-- ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo) -->

<h2>Description</h2>
With VS Code script, use one of the most versatile Linux networking utilities, tcpdump, to capture and analyze TCP traffic, and review the traffic in WireShark.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Linux</b> 
- <b>VS Code</b>
- <b>Wireshark</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Open VS Code: <br/>
<img src="https://i.imgur.com/AEhSlSu.png" height="80%" width="80%" alt="TCPDump project steps"/>
<br />
<br />
Create a file called watchdog.sh for script: <br/>
<img src="https://i.imgur.com/zaIyBDK.png" height="80%" width="80%" alt="TCPDump project steps"/>
<br />
<br />
Write a script to capture traffic for traffic to and from a website : <br/>
<img src="https://i.imgur.com/t4JqCwU.png" height="80%" width="80%" alt="TCPDump project steps"/>
<br />
<br />
Open the integrated terminal:  <br/>
<img src="https://i.imgur.com/KyUigyQ.png" height="80%" width="80%" alt="TCPDump project steps"/>
<br />
<br />
Use chmod (change mode) to make watchdog executable:  <br/>
<img src="https://i.imgur.com/9vvD9to.png" height="80%" width="80%" alt="TCPDump project steps"/>
<br />
<br />
Add '-w captured.pcap' for packet capture to a dump file, create the captured.pcap file, and create traffic to the site you are monitoring:  <br/>
<img src="https://i.imgur.com/8AykDrk.png" height="80%" width="80%" alt="TCPDump project steps"/>
<br />
<br />
Open Wireshark to view the captured packets:  <br/>
<img src="https://i.imgur.com/6fhvnJV.png" height="80%" width="80%" alt="TCPDump project steps"/>
<br />
<br />
Locate your captured.pcap file:  <br/>
<img src="https://i.imgur.com/sRbeRbQ.png" height="80%" width="80%" alt="TCPDump project steps"/>
<br />
<br />
Here you can view and analyze the captured information in a human readable format:  <br/>
<img src="https://i.imgur.com/WVT8d3C.png" height="80%" width="80%" alt="TCPDump project steps"/>
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
