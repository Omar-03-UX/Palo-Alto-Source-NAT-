# Palo Alto Source NAT

<h2>Description</h2>
In this hands-on lab, we will learn how to configure Source Network Address Translation (Source NAT or SNAT) on a Palo Alto firewall to enable inside users to connect to both the internet and a Demilitarized Zone (DMZ). Source NAT is a fundamental network security feature that allows you to rewrite the source IP address of outgoing packets, providing essential network protection and enabling communication between different network segments.

<br />

<h2>Languages and Utilities Used</h2>

- <b> Eve ng </b> 
- <b>VM Workstation </b>
- <b> Palo Alto Firewall </b>

<h2>Environments Used </h2>

- <b> Vm Workstation Pro </b> 

<h2>Program walk-through:</h2>

<p align="center">
Setup devices <br/>
<img src="https://i.imgur.com/RP2QiHE.jpg" height="80%" width="80%" alt="Palo Alto Source NAT"/>
<br />
<br />
Configure Zones for interfaces:  <br/>
<img src="https://i.imgur.com/lNRc5uB.jpg" height="80%" width="80%" alt="Zones"/>
<br />
<br />
Interface setup: <br/>
<img src="https://i.imgur.com/F6QnEuw.png" height="80%" width="80%" alt="Interfaces"/>
<br />
<br />
Security Policy : <br/>
<img src="https://i.imgur.com/gQSiAus.png" height="80%" width="80%" alt=""/>
<br />
<br />
NAT policy:  <br/>
<img src="https://i.imgur.com/h8UlWQh.png" height="80%" width="80%" alt="NAT"/>
<br />
<br />
PC configuration :  <br/>
<img src="https://i.imgur.com/J8mml4Q.png" height="80%" width="80%" alt="PC"/>
<br />
<br />
Configure Virtual Route:  <br/>
<img src="https://i.imgur.com/ji269BR.png" height="80%" width="80%" alt="Virtual Route"/>
</p>
Test internet connectivity after assigning DNS : <br/>
<img src="https://i.imgur.com/nNTef9A.png" height="80%" width="80%" alt=""/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
