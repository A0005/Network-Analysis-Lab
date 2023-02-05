<h1>Wireshark Lab</h1>

Course Security Blue Team - Introduction to Network Analysis  

<h2>Description</h2>
This project is a Wireshark lab.
<br />


<h2>Environments Used </h2>

- <b>Wireshark</b>



<h2>Program walk-through:</h2>

<!-- <p align="center"> --!>
1 - Here I was required to find the number of UDP packets that have been captured. 
    By Typing in udp.port in the filter I got the number of packets at the bottom tab which is 3290 packets.  <br/>
<img width="900" alt="1" src="https://user-images.githubusercontent.com/103763124/216828448-8e4864d7-591d-4486-8d6f-1602d451d14e.png">
<br />
2 - Here I was required to find how many TCP packets have both the SYN and ACK flags set. 
    By typing tcp.flags.syn == 88 tcp.flags.ack == 1 I was able to find that it was 20 packets.<br/>
<img width="900" alt="2" src="https://user-images.githubusercontent.com/103763124/216828451-0443be9c-b565-4cf4-9bc3-4b76f2b04222.png">
<br />
3 - Here I was required to find the version of Chrome that was used to connect to securityblue.team. 
    By typing http.request.method = GET and expanding the Hypertext Transfer Protocol I was able to get the version 80.0.3987.87. <br/>
<img width="900" alt="3" src="https://user-images.githubusercontent.com/103763124/216828455-1292bfc6-9f34-45dc-bf5c-f3f7dd7ead23.png">
<br />
4 - Here I was required to find how many packets have a TTL value of 38. 
    By typing ip.ttl == 38 I was able to get 710 packets. <br/>
<img width="900" alt="4" src="https://user-images.githubusercontent.com/103763124/216828458-37053221-c3f2-4c0b-bc4a-237f25dff8b6.png">
<br />
5 - Here I was required to find what is the name of the PNG file on the web server at 192.168.56.111.
    By typing http in the filter then right clicking the IP Address 192.168.56.111 then selecting Follow then HTTP Stream.<br/>
<img width="900" alt="5" src="https://user-images.githubusercontent.com/103763124/216828462-ffd1baa0-dcab-45a6-bf66-2c23d8b7eda9.png">
     I was able to get the name of the file which is proprietary.png. <br/>
<img width="900" alt="6" src="https://user-images.githubusercontent.com/103763124/216829210-3472a031-f131-41c9-9613-a1e958456232.png">
<br />
6 - Here I was required to find which version of OpenSSh is running on the server. 
    By typing ssh in the filter I was able to determine that the version is 7.9p1. <br/>
<img width="900" alt="7" src="https://user-images.githubusercontent.com/103763124/216829212-59902830-d775-4249-9d62-bba7dd7c014d.png">
<br />
7 - Here I was required to find the MAC address of the attacker. 
    By typing eth.src I was able to find the MAC address which is 08:00:27:3d:27:5d. <br/>
<img width="900" alt="8" src="https://user-images.githubusercontent.com/103763124/216829213-6bdc62d1-2e99-484b-8dc7-505649966cc0.png">
<br />
8 - Here I was required to find what file was downloaded from the central server. 
    By following the TCP Stream tcp.stream eq 0 I found the file Alevis_Employee_Information_Chart.csv. <br/>
<img width="900" alt="9" src="https://user-images.githubusercontent.com/103763124/216830449-15444e21-179a-4eeb-98cb-0a25773b826a.png">
<br />



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
