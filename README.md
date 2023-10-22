<h1>Honeypot Hosted on the Cloud</h1>


<h2>Description</h2>
This Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Putty</b> 
- <b>Microsoft Azure</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Brief Diagram showing the entire project <br/>
<img src="https://i.imgur.com/50IBCcy.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
Creating the Virtual Machine  <br/>
<img src="https://i.imgur.com/pN0vtCR.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
Selecting Virtual Machine specification <br/>
<img src="https://i.imgur.com/2d1XdMM.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
Selecting Disk size <br/>
<img src="https://i.imgur.com/T8oK48r.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
Opening all ports to gather traffic  <br/>
<img src="https://i.imgur.com/atO2mef.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
Opening Putty and pasting the Virtual Machine IP on Putty to gain remote Access <br/>
<img src="https://i.imgur.com/iT4Qc20.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
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
