<h1>Windows Server 2019 Setup</h1>

<h2>Introduction</h2>
Virtualization has become a crucial tool for IT professionals, allowing them to create multiple environments on a single physical machine. In this guide, we will walk you through the process of setting up Windows Server 2019 using VirtualBox. Whether you’re preparing for a certification, testing a new application, or learning about Active Directory, this tutorial will get you up and running quickly.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Windows Server</b> (2019)

<h2>Downloading Windows Server 2019</h2>

- Visit Microsoft’s Evaluation Center: Go to the Microsoft Evaluation Center and download the Windows Server 2019 ISO. You may need to register with your email.

- Select the ISO option: When prompted, choose the ISO file option and save it to your computer.

<h2>Installing VirtualBox</h2>

- Download VirtualBox: Visit the VirtualBox website and download the latest version for your operating system.

- Run the installer: Follow the prompts to install VirtualBox. During installation, keep the default settings unless you have specific preferences.
  
- Launch VirtualBox: Once installed, open VirtualBox to get started.

<h2>Creating a New Virtual Machine:</h2>

<p align="center">
Open VirtualBox and click “New”: This will start the Virtual Machine creation wizard.: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Name your VM: Enter a name for your virtual machine (e.g., “Windows Server 2019”). The type should be “Microsoft Windows,” and the version should be “Windows 2019 (64-bit).” Also click the “Skip Unattended Installation” check box before continuing:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Allocate Memory: Allocate at least 4096MB (4GB) of RAM. More is better if your host system can support it: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a Virtual Hard Disk: Choose “Create a virtual hard disk now” and click “Create.” Select VDI (VirtualBox Disk Image) and then choose “Dynamically allocated” for storage. Set the disk size to at least 20GB:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
<br />
<p>
  
<h2>Installing Windows Server 2019:</h2>

<p align="center">
Begin Installation: Follow the prompts to install Windows Server 2019. Choose the “Custom” installation option:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Partition the Disk: Select the virtual disk you created and click “Next” to start the installation.  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Customize Settings: After installation, you’ll be prompted to set up your administrator account and initial settings:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After creating your Administrator password is completed you will now be able to login to you Windows 2019 Server with the password you previously selected for your Administrator account!:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Post-Installation Configuration</h2>

<p align="center">
Open VirtualBox and click “New”: This will start the Virtual Machine creation wizard.: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Conclusion</h2>
Congratulations! You’ve successfully set up Windows Server 2019 on VirtualBox. This setup is ideal for testing environments, learning new skills, or preparing for certifications. As you get more comfortable with the server, you can start exploring more advanced features like Active Directory, DNS, and more.

