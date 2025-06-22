
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






- <b>Select the graphical install.</b> <br/>

- <b>Configure our hostname. I’ll go with the defaults. kali</b>

- <b>Not going to specify a domain.</b>

- <b>We need to specify a username, I’m just going to go with Kali</b>

- <b>The password: Kali</b>

<img src="https://imgur.com/YOFGPu6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
NOTE: The user and password were just for the project; you should not use the defaults.

- <b>click continue.</b>
- <b> I used the entire disk and then clicked continue.</b>

<img src="https://imgur.com/V5LHpcj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 

- <b> So, I’m going to finish the partitioning and write changes to disk and 
 Click continue.</b>

 <img src="https://imgur.com/5Eg7KIX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 

- <b>I’m ok with these changes being made. So, say yes and continue.</b>

So the software is now being unpacked and installed.
(Wait, it’s going to take a while to install.)

<img src="https://imgur.com/1QMJ4SO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
- <b>Install the GRUB boot loader. Click yes and continue.</b>

<img src="https://imgur.com/OPzHz9q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
 
- <b>I’m going to specify the hard drive and continue.</b>
 The installation is now being finished.
 
 <img src="https://imgur.com/xjPb6OA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 

- <b>Then Reboot</b>
<img src="https://imgur.com/nJIP48D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

Now you can use your Kali Linux on your VirtualBox on Windows 11
<img src="https://imgur.com/jKCb6KB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />


- <b>TEST</b>
<img src="https://imgur.com/qbifMlK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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

