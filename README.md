# virtual_machine_startup
Creating A Virtual Machine through Azure Networks with MAC OS
<p align="center">
<img src="https://i.imgur.com/shXFZUv.png"/>
</p>

<h1>Azure Virtual Machine - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the Azure Network Virtual Machine. Tutorial will also showcase how to connect to the virtual machine with a client computer on Mac Operating Systems with Microsoft Remote Desktop .<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Microsoft Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a subsription with Microsoft Azure
- Create a resource group
- Create a virtal machine
- Connect to virtual machine with remote desktop.

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/IgAKwEY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Microsoft Azure, often referred to as Azure, is a cloud computing platform operated by Microsoft. Create a subsription by making an microsoft account,(or logging into exsiting one). 
</p>
<br />

<p>
<img src="https://i.imgur.com/TuhZ53p.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under Resource Groups click create Resource Group. There you'll create a name and and you'll chooose the Azure region that's right for you and your cutomers. Tags can be created also, at the end review and create.
</p>
<br />

<p>
<img src="https://i.imgur.com/E8X3bAL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Virtual Machine and click Azure VirtuaL Machine. Pick the resource group you already made before. Create a name for your VM and choose the same region as your resource group. Under image you can choose the base Operating System or application for the VM, for example Windows 10 pro. Select a VM size to support the workload that you want to run. The size that you choose then determines factors such as processing power, memory, and storage capacity. Then create a username and password that will work as your log in for the VM. You can finally confirm licensing and review/ create.
</p>
<br />

<p>
<img src="https://i.imgur.com/JTJ8FdZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On Mac Operating system, go to appstore and search for remote desktop. Download the application and run it. Click Add PC and for the PC name copy and paste the public IP adress of the Virtual Machine. To find the Public IP adress, click on your Virtual Machine on Microsft Azure. The public IP adress should be towards the right or you can also click networking and find it there also. The final step is to log in with the username and password created when making the VM.
</p>
<br />
