
<h1>Install Windows Server 2022 on Virtual Box | Windows Server 2022 </h1>

 ### [YouTube Demonstration](https://youtu.be/Z-F_v1k)

<h2>Description</h2>
This repository provides a comprehensive step-by-step guide to install Windows Server 2022 as a virtual machine using Oracle VirtualBox. Designed for IT professionals, students, and homelab enthusiasts, this walkthrough covers everything from VirtualBox setup to post-installation configurations for Windows Server 2022.

<h2>What's Included?</h2>

✔️ VirtualBox optimization for server workloads.

✔️ Windows Server 2022 installation walkthrough. <br />

<h2>Environments Used </h2>

- <b>Windows 11</b> 
 
- <b>VirtualBox 7.1.10 platform packages (Windows hosts)</b>

- <b>SERVER_EVAL_x64FRE_en-us x86_64</b>

<h2>Links and Sites</h2>

<br />Download windows sever @ (https://www.microsoft.com/en-us/evalcenter/download-windows-server-2022) <br/>

<br />Download KaliLinux @ (https://www.kali.org/) <br/>

<h2>Installation walk-through:</h2>

First, to download the Windows Server 2022 image file, visit the official Microsoft evaluation page (https://www.microsoft.com/en-us/evalcenter/download-windows-server-2022) and select the ISO version that matches your requirements 

<img src="https://imgur.com/lw6tTET.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />Lunch VirtualBox. Go to a new virtual machine and create a new windows server.<br/>

Give it a name: Let’s say Windows Server 2022 

<img src="https://imgur.com/IPLJV4w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br /> Give it the amount of RAM that you want. (4000MB OR More) <br/>
 Number of CPUs. Let’s say 2-3CPUs.

<img src="https://imgur.com/jTIdlgD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />click finish.

- <b>Now we need to go to settings.</b>

- <b>Go to storage</b>

- <b>Click on this empty and choose this small disk you can</b>

- <b>Choose disk file.</b>

- <b>Select the ISO file windows server 2022 and click on open</b>

<img src="https://imgur.com/pp9ej0E.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />  

So, I’ve got the Windows Server machine running off the image that I downloaded.


<br /> Now, start your ISO image to start the configuration.

- <b>My language is English.</b>

- <b>Specify your Time format.</b>

- <b>Select that keyboard and Click next</b>

<img src="https://imgur.com/SzYwTSI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 

- <b>Click inatall Now.</b>

<img src="https://imgur.com/J9guLmI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 

 <b>Select the Operating system.</b> <br/>

Important Note: You’ll see four installation options:

- <b>Standard Evaluation</b>

- <b>Standard Evaluation (Desktop Experience)</b>

- <b>Datacenter Evaluation</b>

- <b>Datacenter Evaluation (Desktop Experience)</b>

The Desktop Experience variants include a graphical interface (GUI), while the non-GUI versions run in command-line mode only. For this lab, select "Windows Server 2022 Datacenter Evaluation (Desktop Experience)" (the last option), then click Next.

<img src="https://imgur.com/k3SVHET.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 

Select where you want to install the operating system 

<img src="https://imgur.com/aGJnuCa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 

Next, you’ll see two installation options: 

Upgrade (keeps files/settings from an older Windows Server OS)

Custom (clean installation). For best performance, select Custom installation

<img src="https://imgur.com/tc1YeU4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 

and wait for the installtion

<img src="https://imgur.com/sSoBEGl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
Customize Settings 
- <b>Username is fixed as ADMINISTRATOR </b>

- <b>Chose a Strong Password and Renter, then Finish </b>


<img src="https://imgur.com/1IeaoNF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 

When prompted to Press Ctrl+Alt+Delete, go to VirtualBox's Input menu, select Keyboard, and choose Insert Ctrl+Alt+Delete. 


- <b>Then enter your password when the login screen appears.
 </b>

<img src="https://imgur.com/afcI6uL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 

This is Server Manager, the central administration console for managing all system services and server roles in Windows Server 2022. Through this interface, you can configure, monitor, and maintain the various services running on your server.


<img src="https://imgur.com/0DvBw7X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/> 

 
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

