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


1.) Open VirtualBox and click “New”: This will start the Virtual Machine creation wizard: <br/>

<img src="https://i.imgur.com/3zh4xOt.jpg" height="80%" width="80%" alt="Creating a new Vitrual Machine"/>
<br />
<br />

2.) Name your VM: Enter a name for your virtual machine (e.g., “Windows Server 2019”). The type should be “Microsoft Windows,” and the version should be “Windows 2019 (64-bit).” Also click the “Skip Unattended Installation” check box before continuing:  <br/>

<img src="https://i.imgur.com/Ajq59M4.jpg" height="80%" width="80%" alt="Naming your VM"/>
<br />
<br />

3.) Allocate Memory: Allocate at least 4096MB (4GB) of RAM. More is better if your host system can support it: <br/>

<img src="https://i.imgur.com/69auWsa.jpg" height="80%" width="80%" alt="Allocating RAM"/>
<br />
<br />

4.) Create a Virtual Hard Disk: Choose “Create a virtual hard disk now” and click “Create.” Select VDI (VirtualBox Disk Image) and then choose “Dynamically allocated” for storage. Set the disk size to at least 20GB:  <br/>

<img src="https://i.imgur.com/aMGlKyt.jpg" height="80%" width="80%" alt="Creating Virtual Harddisk"/>
<br /> 
<br />

  
<h2>Installing Windows Server 2019:</h2>


Launch your newly created Virtual Machine

1.) Begin Installation: Follow the prompts to install Windows Server 2019. Choose the “Custom” installation option:  <br/>

<img src="https://i.imgur.com/u7jOkTw.jpg" height="80%" width="80%" alt="Install Now Screen"/>

<img src="https://i.imgur.com/oe6U9rg.jpg" height="80%" width="80%" alt="Custom Installation option"/>
<br />
<br />

2.) Partition the Disk: Select the virtual disk you created and click “Next” to start the installation.  <br/>

<img src="https://i.imgur.com/ke2Y29q.jpg" height="80%" width="80%" alt="Selecting Virtual Disk"/>
<br />
<br />

3.) Customize Settings: After installation, you’ll be prompted to set up your administrator account and initial settings:  <br/>

<img src="https://i.imgur.com/N6EvoxD.jpg" height="80%" width="80%" alt="Configuring Admin Password"/>
<br />
<br />

4.) After creating your Administrator password is completed you will now be able to login to you Windows 2019 Server with the password you previously selected for your Administrator account!:  <br/>

<img src="https://i.imgur.com/O5Ja46F.jpg" height="80%" width="80%" alt="Logging into Server"/>
<br />
<br />

5.) Congratulations you have sucessfully installed Windows Server 2019!:  <br/>
<img src="https://i.imgur.com/kSUkHtp.jpg" height="80%" width="80%" alt="Picture of Windows Server Screen"/>


<h2>Post-Installation Configuration</h2>

1.) Install Guest Additions: In VirtualBox, go to the ribbon located at the top of your virtual machine and select “Devices” > “Insert Guest Additions CD image” and follow the installation steps inside the VM. This improves performance and enables features like clipboard sharing: <br/>

<img src="https://i.imgur.com/qo46Zns.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>

2.) Nativgate to you File Explorer and launch the mounted VirtualBox Guest Additions CD Image and follow through the setup, your Virtual Machine will reboot after this: <br/>

<img src="https://i.imgur.com/SBQSJZ0.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Conclusion</h2>
Congratulations! You’ve successfully set up Windows Server 2019 on VirtualBox. This setup is ideal for testing environments, learning new skills, or preparing for certifications. As you get more comfortable with the server, you can start exploring more advanced features like Active Directory, DNS, and more.

