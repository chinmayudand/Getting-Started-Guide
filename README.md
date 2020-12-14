# Getting Started Guide - ownCloud Server
## Introduction
Welcome to the ownCloud Server Getting Started Guide. This guide describes administration tasks for ownCloud, the flexible open source file synchronization and sharing solution.  ownCloud includes the ownCloud server, which runs on Linux, client applications for Microsoft Windows, Mac OS X and Linux, and mobile clients for the Android and
Apple iOS operating systems.


## Audience
This guide is for users who want to install ownCloud servers. 

## Prerequisite
- RAM : 512 MB
- Virtulization software: VirtualBox
- Operating system: Windows, macOS, Linux and Solaris





# Getting Started
To start with ownCloud server you need to [download](https://owncloud.com/download-server/) the package in ZIP or TAR format. 

In order to run the ownCloud server package you require virtualization software. 
Download [Virtual Box](https://owncloud.com/download-server/).


## Import Appliance file
Once you have downloaded the appliance file, import it into your virtualization software, accept the Terms and Conditions of the license agreement, and launch it. 

Follow the below steps to import the appliance file:

1. Click **Import**.

![alt text](https://github.com/chinmayudand/Getting-Started-Guide/blob/main/1.png)

2. Select the .ova file you just downloaded containing the ownCloud appliance.Then click **'Next'** button.

![alt text](https://github.com/chinmayudand/Getting-Started-Guide/blob/main/2.png)

3. In the next screen, check the settings and click **'Import'**.

![alt text](https://github.com/chinmayudand/Getting-Started-Guide/blob/main/3.png)

If you try to install an ownCloud appliance in your domain after removing an existing one, please remember to remove the original one from you DNS configuration. 


## Configuration wizard
Once imported, start the appliance. This will launch the installer wizard which helps you specify the core configuration. This guide is used to securely and easily configure your appliance:

![alt text](https://github.com/chinmayudand/Getting-Started-Guide/blob/main/4.png)

Choose your language: Currently there are two options, English and German. You can set your city, which will then automatically set the localization settings in the next screen.


![alt text](https://github.com/chinmayudand/Getting-Started-Guide/blob/main/5.png)

Set your default language, time zone and keyboard layout. This will be set automatically if you enter your City in the previous screen.

### Domain Setup
Here, you will see the automatically obtained network configuration if you have a DHCP server in your network. If not – you will have to set this yourself. You can also enter an alternate DNS server if you need one.

![alt text](https://github.com/chinmayudand/Getting-Started-Guide/blob/main/6.png)

Domain setup screen below is an important setting.

![alt text](https://github.com/chinmayudand/Getting-Started-Guide/blob/main/7.png)

Select option **'Manage users and permissions on this system'**

### Account creation

In the next screen, enter the name of your organization, your email address and set a password. Be sure to write down or remember the password, it is the root password for your appliance. Make sure you use a real, working email address you can access for it is used to activate the Univention Corporate Server so you have access to the Univention App Center.


![alt text](https://github.com/chinmayudand/Getting-Started-Guide/blob/main/8.png)

Below screen is the default host settings:

![alt text](https://github.com/chinmayudand/Getting-Started-Guide/blob/main/9.png)


You get a finalized confirmation screen of what you have entered / set, and you can finish the process. Note that if you let the check box to update your system in – the installation will take considerably longer. Keep this in mind. You can apply the updates later on if you choose to skip it during the installation.


![alt text](https://github.com/chinmayudand/Getting-Started-Guide/blob/main/10.png)

When the installation is complete, you will see this screen informing you that the installation was successful.


![alt text](https://github.com/chinmayudand/Getting-Started-Guide/blob/main/11.png)

The virtual machine will show you this screen, showing the IP address you have to navigate to in order to activate your appliance.

![alt text](https://github.com/chinmayudand/Getting-Started-Guide/blob/main/12.png)


