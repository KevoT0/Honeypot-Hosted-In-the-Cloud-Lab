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
Logging into putty using the Username and Password created in Azure and updating the OS <br/>
<img src="https://i.imgur.com/j7bDskk.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br /> 
Installing Git (Used to install TPot) <br/>
<img src="https://i.imgur.com/5Kn2BgF.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
Code used to install TPot on the Virtual Machine <br/>
<img src="https://i.imgur.com/yLKKQ13.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
Setting up username and Password of TPot <br/>
<img src="https://i.imgur.com/WoTMiaf.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
Installing TPot Dependancies <br/>
<img src="https://i.imgur.com/C7fwIKt.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
Logging into TPot using the username and password created during the installation of TPot <br/>
<img src="https://i.imgur.com/eDxunw0.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
TPot interface show <br/>
<img src="https://i.imgur.com/MyliqMJ.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
Attack Map Interface <br/>
<img src="https://i.imgur.com/UgH0Kxv.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br /> 
ElasticVUE Dashboard Interface <br/>
<img src="https://i.imgur.com/bPstjwo.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
Attckers IP Address and CVE <br/>
<img src="https://i.imgur.com/3fjbhcb.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
AbuseIPDB <br/>
<img src="https://i.imgur.com/gyVg3YU.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
<br />
Spiderfoot for gathering information <br/>
<img src="https://i.imgur.com/ZT4RW3m.png" height="80%" width="80%" alt="Honey Pot Hosted in the Cloud Steps"/>
<br />
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
