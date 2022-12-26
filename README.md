<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
osTicket is an open source ticketing system. Ticketing systems are used in Information Technology (IT) for users to create requests for service. It is widely used across all areas of IT especially IT help desk to security operations centers (SOCs). This tutorial will go over how to install osTicket on an Azure virtual machine. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Step 1: Install Internet Information Services 
- Step 2: Install Web Platform Installer
- Step 3: Install HeidiSQL
- Step 4: Install osTicket
<h2>Installation Steps</h2>

Prior to starting, make sure you are using a virtual machine in Azure. If don't know how to create a virtual machine in Azure, please see my tutorial [here](https://github.com/klcarpio/Create-an-Azure-Account-and-Deploy-a-Virtual-Machine).

Once the virtual machine is created, log into it. 

<p>
<img src="https://i.imgur.com/jthOoxy.png" height="80%" width="80%" alt="1."/>
</p>

<h3>Step 1: Install Internet Information Services </h3>
First step is to install Internet Information Services (IIS) in Windows. Go to the Start menu and type in "Control Panel" and open it. Click "Uninstall a program" and check Internet Information Services. 

<p>
<img src="https://i.imgur.com/jthOoxy.png" height="80%" width="80%" alt="1."/>
</p>

<p>
<img src="https://i.imgur.com/dSPCYFq.png" height="80%" width="80%" alt="2."/>
</p>

<p>
<img src="https://i.imgur.com/qNjLQUM.png" height="80%" width="80%" alt="3."/>
</p>

<p>
<img src="https://i.imgur.com/Gmqtcfp.png" height="80%" width="80%" alt="4."/>
</p>

<h3>Step 2: Install Web Platform Installer</h3> 
Second step is install Web Platform Installer. To start,open up these download files [here](https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6).

Once at the Google Drive where the download files are, download Web Platform Installer. Then open up the file in the Downloads folder and install the application. 

<p>
<img src="https://i.imgur.com/mKBPH6M.png" height="80%" width="80%" alt="5."/>
</p>

<p>
<img src="https://i.imgur.com/TVHltiS.png" height="80%" width="80%" alt="6."/>
</p>

Once installed, go to the Start menu, type it in, and open the application. 

<p>
<img src="https://i.imgur.com/Y9h8l05.png" height="80%" width="80%" alt="7."/>
</p>

Install the following:
- MySQL 5.5 (This will ask for credentials. Account: root Password: Password1.)
- All simple versions of x86 PHP up until 7.3

<p>
<img src="https://i.imgur.com/pqDM8rr.png" height="80%" width="80%" alt="8."/>
</p>

<p>
<img src="https://i.imgur.com/ykZCSNB.png" height="80%" width="80%" alt="9."/>
</p>

Follow the installation process. The Installer will inherently fail installing some of the items. Find those items in the Google Drive folder that was mentioned previously.

Install the following:
-PHP Version 7.3.8.
-Microsoft Visual C++ 2009 Redistributable Package.
-PHP Manager 1.5.0 for IIS 10.

<p>
<img src="https://i.imgur.com/nQoI9GZ.png" height="80%" width="80%" alt="10."/>
</p>

<p>
<img src="https://i.imgur.com/dI77INN.png" height="80%" width="80%" alt="11."/>
</p>

<p>
<img src="https://i.imgur.com/ht5QrzG.png" height="80%" width="80%" alt="12."/>
</p>

<p>
<img src="https://i.imgur.com/PMiBxmc.png" height="80%" width="80%" alt="13."/>
</p>


















