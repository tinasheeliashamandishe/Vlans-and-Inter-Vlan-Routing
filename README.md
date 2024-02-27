<h1>VLANs and Inter-VLAN Routing</h1>

<h2>Description</h2>
This lab is a VLAN configuration for a small campus network. It includes Virtual Trunking Protocol, Access and Trunk ports, and inter-VLAN routing.
<br />

<h2>Environments Used </h2>

- <b>Packet Tracer</b>

<h2>Lab walk-through:</h2>

<p align="center">
<h4>Lab Topology:</h4>
In this Lab topology there is 3 switches( server, transparent and client) in the VTP domain Tinashe. <br/>
There is 3 VLANS: VLAN 10 for support, VLAN 20 for Accouting, VLAN 30 for Administrators and VLAN 199 as the native VLAN. <br/>
<img src="https://i.imgur.com/ReHyYg7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h4>Vlan Database:</h4> 
VLAN database on the switches.  <br/>
VLAN 10 for support, VLAN 20 for Accouting, VLAN 30 for Administrators and VLAN 199 as the native VLAN. <br/>
<img src="https://i.imgur.com/ij5OQV9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<h4>Intra VLAN connectivity from Support 1 to Support 2: </h4>
Once the PCs have been placed into the correct VLANs, it can be seen that there is connectivity within the VLANs. <br/>
<img src="https://i.imgur.com/JmpG0pl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<h4>No Inter Vlan connectivity between Support 1 and Accouting 2 : </h4>
However there is no connectivity between the VLANs  <br/>
<img src="https://i.imgur.com/pBpscT8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<h4>Inter VLAN Configuration 1: Router-on-a-stick:</h4>
To enable inter VLAN connectivty we use the Router-on-a-stick method  <br/>
<img src="https://i.imgur.com/8t4DPuT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<h4>Inter Vlan connectivity between Support 1 and Accouting 2:</h4>
Inter VLAN connectivity has been achieved between Support 1 and Accouting 2(VALN 10 and VLAN 20) <br/>
<img src="https://i.imgur.com/d4TlSsB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<h4>Inter VLAN Configuration 2: Layer 3 Switch: </h4>
We can also use a layer 3 switch to enable inter-VLAN connectivity  <br/>
<img src="https://i.imgur.com/ReHyYg7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h4>Inter Vlan connectivity between Support 1 , Accouting 2 and Administrator 2: </h4>
Inter VLAN connectivity has been between Support 1 , Accouting 2 and Administrator 2(VLAN 10 and VLAN 20)  <br/>
<img src="https://i.imgur.com/Mj9gcge.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
