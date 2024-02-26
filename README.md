<h1>VLANs and Inter-VLAN Routing</h1>

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />

<h2>Environments Used </h2>

- <b>Packet Trcaer</b> (21H2)

<h2>Lab walk-through:</h2>

<p align="center">
Lab Topology: <br/>
<img src="https://i.imgur.com/ReHyYg7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Vlan Database:  <br/>
<img src="https://i.imgur.com/ij5OQV9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Intra VLAN connectivity from Support 1 to Support 2: <br/>
<img src="https://i.imgur.com/JmpG0pl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
No Inter Vlan connectivity between Support 1 and Accouting 2 :  <br/>
<img src="https://i.imgur.com/pBpscT8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Inter VLAN Configuration 1: Router-on-a-stick:  <br/>
<img src="https://i.imgur.com/8t4DPuT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Inter Vlan connectivity between Support 1 and Accouting 2  <br/>
<img src="https://i.imgur.com/d4TlSsB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Inter VLAN Configuration 2: Layer 3 Switch:  <br/>
<img src="https://i.imgur.com/ReHyYg7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />  
<br />
Inter Vlan connectivity between Support 1 , Accouting 2 and Administrator 2  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
