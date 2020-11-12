## [source](https://googlecoursera.qwiklabs.com/focuses/11598)
## Lab1: Create a Folder with Windows

![remote desktop connection](img/remote-network-server.png)

Create a Folder with Windows
1 hour
1 Credit
Rate Lab
Introduction
This lab will introduce you to the Qwiklabs online learning platform’s hands-on lab experience. You'll interact with hands-on labs in lots of courses of the IT Support Professional Certificate program, so it's important that you follow these instructions carefully. We'll give you some background information about what Qwiklabs are, and how these labs will help train you as an IT Support Specialist. Finally, you'll interact with the lab materials themselves. Ready? Let's get started!

Head's up: You'll experience a delay as the labs initially load (particularly for Windows labs). So, please wait a couple of minutes for the labs to load. The grade is calculated when the lab is complete, so be sure to hit "End Lab" when you're done!

What is Qwiklabs?

Qwiklabs is an online learning environment that will take you through a live, real-world tech scenario that you may encounter as an IT Support Specialist. Qwiklabs "spin up," or create, virtual machines. A virtual machine (VM) is exactly how it sounds: it creates a "virtual" (rather than actual) simulation of software. As you've learned throughout the Technical Support Fundamentals course, the Windows operating system (OS) is just a piece of software. This way, you don't have to purchase this software to complete the courses in the IT Support Professional Certificate. This also allows you to use Windows OS as if it was installed on your local machine, so you can practice and familiarize yourself with this technology.

In this Qwiklab, you'll spin up a virtual machine of the Windows OS. In other Qwiklabs throughout the IT Support Professional Certificate, you may spin up other instances (or other occurrences) of software; Qwiklabs isn't just limited to operating systems. You'll soon learn that, with Qwiklabs, you can interact with many other real-world scenarios that you may see as an IT Support Specialist.

Head's up: Each Qwiklab will create temporary VM credentials that will last only for the duration of the lab. In other words, you'll need to connect VM for each Qwiklab offered in the IT Support Professional Certificate program.

Learning tip:

Whenever possible, we encourage you to try these exercises on your local machines or home computers -- if that's an option for you! When you're learning something new for the first time, or you're trying to improve a skill that you already have, remember that "practice makes perfect." So, practice the skills you'll learn in the Qwiklabs as much as you can!

What you'll do

There are two learning objectives for this lab:

Familiarize yourself with the Qwiklabs environment.
Access a Windows VM instance and create a basic folder using the graphical user interface (GUI).
You'll have 60 minutes to complete this lab.

Start the lab
You'll need to start the lab before you can access the materials in the virtual machine OS. To do this, click the green “Start Lab” button at the top of the screen.

Note: For this lab you are going to access the Windows VM through your local RDP Client, and not use the Google Console (Open GCP Console button is not available for this lab).
Start Lab

After you click the “Start Lab” button, you will see all the connection details on the left-hand side of your screen. You should have a screen that looks like this:

Connection Details

Note: Working with Qwiklabs may be similar to the work you'd perform as an IT Support Specialist; you'll be interfacing with a cutting-edge technology that requires multiple steps to access, and perhaps healthy doses of patience and persistence(!). You'll also be using RDP to enter the labs -- a critical skill in IT Support that you’ll be able to practice through the labs.
Accessing the virtual machine
Please find one of the four relevant options below based on your device's operating system.

Option 1: Windows Users: Connecting to your VM via RDP
In this section, you will use Remote Desktop Connection to connect to your windows instance using its external IP address.

Open Remote Desktop Connection by clicking the Start button. In the search box, type Remote Desktop Connection, and then, in the list of results, click Remote Desktop Connection.

Enter the external IP address of the instance you want to connect to in the Computer field. Find the external IP address for your instance from the Connection Details Panel on the left side. Click on connect.

Remote Desktop Connection home

Change the username to student. And use the password mentioned in the Connection Details Panel on the left side. Click OK.

Click Yes to accept the certificate.

You should now see a visual interface that looks exactly like the Windows 10 OS!

If you see any error message, close the window and wait a minute or so. Sometimes the VM-creation process takes a few minutes, and you won't be able to access the VM until it's finished. This also applies to any errors that say your credentials (username and password) are incorrect.

Option 2: OS X users: Connecting to your VM via RDP
In this section, you will use Microsoft Remote Desktop 10 to connect to your windows instance using its external IP address. OSX users can download Microsoft Remote Desktop from the Mac App Store. If you are using Microsoft Remote Desktop 8, note that the interface will vary slightly than what’s listed below.

Open Microsoft Remote Desktop 10 application.

Click on + sign above, followed by Add PC.

Add PC

Enter the external IP address of the instance you want to connect to in the PC name field. Find the external IP address for your instance from the Connection Details Panel on the left side. Click on the Add button.

Connect PC

You should now be able to see your desktop represented by the external IP address of your VM instance under PCs. Double click on your VM’s external IP address.

The application will now prompt you for username and password. Change the username to student. And use the password mentioned in the Connection Details Panel on the left side. Once you have entered the details click Continue.

For any prompt regarding ‘Certificate verification’, click continue.

Certificate verification

You should now see a visual interface that looks exactly like the Windows 10 OS!

If you see any error message, close the window and wait a minute or so. Sometimes the VM-creation process takes a few minutes, and you won't be able to access the VM until it's finished. This also applies to any errors that say your credentials (username and password) are incorrect.

Option 3: Chrome OS users: Connecting to your VM via RDP
In this section, you will use Chrome RDP to connect to your windows instance using its external IP address.

Chrome OS users can download Chrome RDP from Chrome Web Store. Once you navigate to the download page, click on the Add to Chrome button. Click on Add app in case of any pop-ups. Then, click on Launch app to start the application.

Open the Chrome RDP application.
Enter the external IP address of the instance you want to connect to in the Enter the computer name or address to connect to field. Find the external IP address for your instance from the Connection Details Panel on the left side. Click on connect.
Leave the domain field blank. Change the username to student. And use the password mentioned in the Connection Details Panel on the left side. Click OK.
Click Continue for any window related to certificate verification.
You should now see a visual interface that looks exactly like the Windows 10 OS!

If you see any error message (an example of one is shown below), close RDP and wait a minute or so. Sometimes the VM-creation process takes a few minutes, and you won't be able to access the VM until it's finished. This also applies to any errors that say your credentials (username and password) are incorrect.

RDP error

Option 4: Linux users: Connecting to your VM via RDP
In this section, you will use Remmina to connect to your windows instance using its external IP address. Open Remmina in your Linux machine. Linux users can install Remmina if it is not pre-installed.

Open Remmina.

Enter the external IP address of the instance you want to connect to. Find the external IP address for your instance from the Connection Details Panel on the left side. Click on Connect.

Make sure the connection protocol is set to RDP, as shown in the image below:

Remmina home

A window appears asking you accept the certificate, click Ok to continue.

Leave the domain field blank. Change the username to student. And use the password mentioned in the Connection Details Panel on the left side, for the Password field. Click Ok to continue.

You should now see a visual interface that looks exactly like the Windows 10 OS!

If you see any error message, close the window and wait a minute or so. Sometimes the VM-creation process takes a few minutes, and you won't be able to access the VM until it's finished. This also applies to any errors that say your credentials (username and password) are incorrect.

Using the Windows instance
Now you have access to the Windows instance, you're ready to start using it! This version of Windows is intended to be used on a Server, and auto-starts a server-management program. We don't need this for this lab, so wait for it to finish starting and then close it. You may see the desktop appear for a few seconds before the program launches.

Server manager Server manager home

Once that's closed, the Windows OS is ready for you to use.

Finishing the login process

Now you‘ll see a Windows desktop background that looks like this:

Windows Desktop

Creating a folder
Creating a folder in Windows is super simple. Right-click anywhere on the desktop and you should see this menu appear:

893440b27ea1a524.png

Hover your cursor over "New," and another menu should appear that looks like this:

70a7615a3ee13ba5.png

Move your cursor to the first option ("Folder"), and select it. If your cursor leaves the menus, they may disappear; if this happens, just repeat the steps again. A new folder should appear on the desktop. It'll be called "New folder" by default, and the text should already be highlighted for you to edit.

2ac63b2a6d11354e.png

If you click anywhere before changing the name, you'll need to right-click the folder and select the "Rename" option to be able to edit it. Change the name to "My Super Cool Folder".

38c32d91cb7bdf4f.png a35df2f7ca600795.png

Your folder has been created and named! To verify, double-click on the folder and a Windows Explorer window should pop up, showing you the contents of your currently empty folder.

182f872fa223868a.png

Click Check my progress to verify the objective.

Create a folder
Congratulations!
That's it! You've successfully accessed a Windows virtual machine using an RDP connection, and created a folder in the instance. There will be much more interesting labs to come, but the steps of connecting to Windows instances will remain the same. So, feel free to use this lab as a refresher if you ever forget the process.

You can now close the RDP/SSH window. You can manually end the lab, or it will automatically end when the time runs out.

***

## Lab2: Create a Folder with Linux

1 hour
1 Credit
Rate Lab
Introduction
This lab will introduce you to the Qwiklabs online learning platform. You'll interact with Qwiklabs in lots of courses of the IT Support Professional Certificate program, so it's important that you follow these instructions carefully. We'll give you some background information about what Qwiklabs are, and how these labs will help train you as an IT Support Specialist. Finally, you'll interact with the lab materials themselves. Ready? Let's get started!

Head's up: You'll experience a delay as the labs initially load (particularly for Windows labs). So, please wait a couple of minutes for the labs to load. Please also make sure to access the labs directly through Coursera and not in the Qwiklabs catalog. If you access the labs through the Qwiklabs catalog, you will not receive a grade. (As you know, a passing grade is required to matriculate through the course.) The grade is calculated when the lab is complete, so be sure to hit "End Lab" when you're done!

What is Qwiklabs?
Qwiklabs is an online learning environment that will take you through a live, real-world tech scenario that you may encounter as an IT Support Specialist. Qwiklabs "spin up," or create, virtual machines. A virtual machine (VM) is exactly how it sounds: it creates a "virtual" (rather than actual) simulation of software. As you've learned throughout the Technical Support Fundamentals course, a Linux operating system (OS) is just a piece of software. This way, you don't have to purchase this software to complete the courses in the IT Support Professional Certificate. This also allows you to use Linux OS as if it was installed on your local machine, so you can practice and familiarize yourself with this technology.

In this Qwiklab, you'll spin up a virtual machine of the Linux OS. In other Qwiklabs throughout the IT Support Professional Certificate, you may spin up other instances (or other occurrences) of software; Qwiklabs isn't just limited to operating systems. You'll soon learn that, with Qwiklabs, you can interact with many other real-world scenarios that you may see as an IT Support Specialist.

Head's up: Each Qwiklab will create a temporary VM credentials that will last only for the duration of the lab. In other words, you'll need to connect VM for each Qwiklab offered in the IT Support Professional Certificate program.

Learning tip:
Whenever possible, we encourage you to try these exercises on your local machines or home computers -- if that's an option for you! When you're learning something new for the first time, or you're trying to improve a skill that you already have, remember that "practice makes perfect." So, practice the skills you'll learn in the Qwiklabs as much as you can!

What you'll do
There are two learning objectives for this lab:

Familiarize yourself with the Qwiklabs environment.
Access a Linux virtual machine and create a basic folder using the command line interface.
You'll have 60 minutes to complete this lab.

Start the lab
You'll need to start the lab before you can access the materials in the virtual machine OS. To do this, click the green “Start Lab” button at the top of the screen.

Note: For this lab you are going to access the Linux VM through your local SSH Client, and not use the Google Console (Open GCP Console button is not available for this lab).
Start Lab

After you click the “Start Lab” button, you will see all the SSH connection details on the left-hand side of your screen. You should have a screen that looks like this:

Connection details

Accessing the virtual machine
Please find one of the three relevant options below based on your device's operating system.

Note: Working with Qwiklabs may be similar to the work you'd perform as an IT Support Specialist; you'll be interfacing with a cutting-edge technology that requires multiple steps to access, and perhaps healthy doses of patience and persistence(!). You'll also be using SSH to enter the labs -- a critical skill in IT Support that you’ll be able to practice through the labs.
Option 1: Windows Users: Connecting to your VM
In this section, you will use the PuTTY Secure Shell (SSH) client and your VM’s External IP address to connect.

Download your PPK key file

You can download the VM’s private key file in the PuTTY-compatible PPK format from the Qwiklabs Start Lab page. Click on Download PPK.

PPK

Connect to your VM using SSH and PuTTY

You can download Putty from here

In the Host Name (or IP address) box, enter username@external_ip_address.

# student-01-1419dc0c6473@34.68.238.232

Note: Replace username and external_ip_address with values provided in the lab.
Putty_1

In the Category list, expand SSH.

Click Auth (don’t expand it).

In the Private key file for authentication box, browse to the PPK file that you downloaded and double-click it.

Click on the Open button.

Note: PPK file is to be imported into PuTTY tool using the Browse option available in it. It should not be opened directly but only to be used in PuTTY.
Putty_2

Click Yes when prompted to allow a first connection to this remote SSH server. Because you are using a key pair for authentication, you will not be prompted for a password.
Common issues

If PuTTY fails to connect to your Linux VM, verify that:

You entered <username>@<external ip address> in PuTTY.

You downloaded the fresh new PPK file for this lab from Qwiklabs.

You are using the downloaded PPK file in PuTTY.

Option 2: OSX and Linux users: Connecting to your VM via SSH
Download your VM’s private key file.

You can download the private key file in PEM format from the Qwiklabs Start Lab page. Click on Download PEM.

PEM

Connect to the VM using the local Terminal application

A terminal is a program which provides a text-based interface for typing commands. Here you will use your terminal as an SSH client to connect with lab provided Linux VM.

Open the Terminal application.

To open the terminal in Linux use the shortcut key Ctrl+Alt+t.

To open terminal in Mac (OSX) enter cmd + space and search for terminal.

Enter the following commands.

Note: Substitute the path/filename for the PEM file you downloaded, username and External IP Address.
You will most likely find the PEM file in Downloads. If you have not changed the download settings of your system, then the path of the PEM key will be ~/Downloads/qwikLABS-XXXXX.pem

chmod 600 ~/Downloads/qwikLABS-XXXXX.pem
ssh -i ~/Downloads/qwikLABS-XXXXX.pem username@External Ip Address
SSH

Option 3: Chrome OS users: Connecting to your VM via SSH
Note: Make sure you are not in Incognito/Private mode while launching the application.
Download your VM’s private key file.

You can download the private key file in PEM format from the Qwiklabs Start Lab page. Click on Download PEM.

PEM

Connect to your VM

Add Secure Shell from here to your Chrome browser.

Open the Secure Shell app and click on [New Connection].

new-connection-button

In the username section, enter the username given in the Connection Details Panel of the lab. And for the hostname section, enter the external IP of your VM instance that is mentioned in the Connection Details Panel of the lab.

username-hostname-fields

In the Identity section, import the downloaded PEM key by clicking on the Import… button beside the field. Choose your PEM key and click on the OPEN button.

Note: If the key is still not available after importing it, refresh the application, and select it from the Identity drop-down menu.
Once your key is uploaded, click on the [ENTER] Connect button below.

import-button

For any prompts, type yes to continue.

You have now successfully connected to your Linux VM.

You're now ready to continue with the lab!

Creating a Folder
To create a sample folder, enter this command into the terminal:

mkdir my-super-cool-folder
This creates a directory called "my-super-cool-folder" in your current directory.

![new folder on linux VM](img/linux-vm1.png)

Click Check my progress to verify the objective.

Create a folder
Congratulations!
That's it! You've successfully accessed the Linux virtual machine using a SSH connection, and created a folder in the instance. There will be much more interesting labs to come, but the steps of connecting to Linux VM instances will remain the same. So, feel free to use this lab as a refresher if you ever forget the process.

You can now close the RDP/SSH window. You can manually end the lab, or it will automatically end when the time runs out.


***


## Lab3: Install, Update, and Remove Software in Windows
1 hour
1 Credit
Rate Lab
Introduction
This lab will teach you how to perform basic software maintenance on Windows machines. This includes installing software that's not already present on the machines, updating existing software to the newest version, and uninstalling software that‘s no longer needed. All of these tasks are very common in the IT world, so it's important that you're able to do them quickly and effectively.

Head's up: You'll experience a delay as the labs initially load (particularly for Windows labs). So, please wait a couple of minutes for the labs to load. The grade is calculated when the lab is complete, so be sure to hit "End Lab" when you're done!

You'll have 60 minutes to complete this lab.

What you'll do
There are three learning objectives for this lab:

Install- You'll install the Mozilla Firefox web browser. There's currently no version of Firefox on the machine you'll be using, so it will be a fresh installation.

Update- The machine you'll be using comes preinstalled with an old version of the VLC Media Player. You'll update VLC to the newest version.

Uninstall- You'll uninstall the GIMP photo-editing tool from the machine, removing it entirely.

Verifying Windows configuration
The first steps of this lab will be to verify that the initial software setup, or "configuration," of programs on your machines is correct. These should already be set exactly as you'll need them, but it's important to know how to check for this information when working in an IT role.

You'll verify that Mozilla Firefox isn't installed on your Windows machine, and that both GIMP and version 2.2.8 of VLC Media Player are installed.

Start the lab
You'll need to start the lab before you can access the materials in the virtual machine OS. To do this, click the green “Start Lab” button at the top of the screen.

Note: For this lab you are going to access the Windows VM through your local RDP Client, and not use the Google Console (Open GCP Console button is not available for this lab).
Start Lab

After you click the “Start Lab” button, you will see all the connection details on the left-hand side of your screen. You should have a screen that looks like this:

Connection Details

Note: Working with Qwiklabs may be similar to the work you'd perform as an IT Support Specialist; you'll be interfacing with a cutting-edge technology that requires multiple steps to access, and perhaps healthy doses of patience and persistence(!). You'll also be using RDP to enter the labs -- a critical skill in IT Support that you’ll be able to practice through the labs.
Accessing the virtual machine
Please find one of the four relevant options below based on your device's operating system.

Option 1: Windows Users: Connecting to your VM via RDP
In this section, you will use Remote Desktop Connection to connect to your windows instance using its external IP address.

Open Remote Desktop Connection by clicking the Start button. In the search box, type Remote Desktop Connection, and then, in the list of results, click Remote Desktop Connection.

Enter the external IP address of the instance you want to connect to in the Computer field. Find the external IP address for your instance from the Connection Details Panel on the left side. Click on connect.

Remote Desktop Connection home

Change the username to student. And use the password mentioned in the Connection Details Panel on the left side. Click OK.

Click Yes to accept the certificate.

You should now see a visual interface that looks exactly like the Windows 10 OS!

If you see any error message, close the window and wait a minute or so. Sometimes the VM-creation process takes a few minutes, and you won't be able to access the VM until it's finished. This also applies to any errors that say your credentials (username and password) are incorrect.

Option 2: OS X users: Connecting to your VM via RDP
In this section, you will use Microsoft Remote Desktop 10 to connect to your windows instance using its external IP address. OSX users can download Microsoft Remote Desktop from the Mac App Store. If you are using Microsoft Remote Desktop 8, note that the interface will vary slightly than what’s listed below.

Open Microsoft Remote Desktop 10 application.

Click on + sign above, followed by Add PC.

Add PC

Enter the external IP address of the instance you want to connect to in the PC name field. Find the external IP address for your instance from the Connection Details Panel on the left side. Click on the Add button.

Connect PC

You should now be able to see your desktop represented by the external IP address of your VM instance under PCs. Double click on your VM’s external IP address.

The application will now prompt you for username and password. Change the username to student. And use the password mentioned in the Connection Details Panel on the left side. Once you have entered the details click Continue.

For any prompt regarding ‘Certificate verification’, click continue.

Certificate verification

You should now see a visual interface that looks exactly like the Windows 10 OS!

If you see any error message, close the window and wait a minute or so. Sometimes the VM-creation process takes a few minutes, and you won't be able to access the VM until it's finished. This also applies to any errors that say your credentials (username and password) are incorrect.

Option 3: Chrome OS users: Connecting to your VM via RDP
In this section, you will use Chrome RDP to connect to your windows instance using its external IP address.

Chrome OS users can download Chrome RDP from Chrome Web Store. Once you navigate to the download page, click on the Add to Chrome button. Click on Add app in case of any pop-ups. Then, click on Launch app to start the application.

Open the Chrome RDP application.
Enter the external IP address of the instance you want to connect to in the Enter the computer name or address to connect to field. Find the external IP address for your instance from the Connection Details Panel on the left side. Click on connect.
Leave the domain field blank. Change the username to student. And use the password mentioned in the Connection Details Panel on the left side. Click OK.
Click Continue for any window related to certificate verification.
You should now see a visual interface that looks exactly like the Windows 10 OS!

If you see any error message (an example of one is shown below), close RDP and wait a minute or so. Sometimes the VM-creation process takes a few minutes, and you won't be able to access the VM until it's finished. This also applies to any errors that say your credentials (username and password) are incorrect.

RDP error

Option 4: Linux users: Connecting to your VM via RDP
In this section, you will use Remmina to connect to your windows instance using its external IP address. Open Remmina in your Linux machine. Linux users can install Remmina if it is not pre-installed.

Open Remmina.

Enter the external IP address of the instance you want to connect to. Find the external IP address for your instance from the Connection Details Panel on the left side. Click on Connect.

Make sure the connection protocol is set to RDP, as shown in the image below:

Remmina home

A window appears asking you accept the certificate, click Ok to continue.

Leave the domain field blank. Change the username to student. And use the password mentioned in the Connection Details Panel on the left side, for the Password field. Click Ok to continue.

You should now see a visual interface that looks exactly like the Windows 10 OS!

If you see any error message, close the window and wait a minute or so. Sometimes the VM-creation process takes a few minutes, and you won't be able to access the VM until it's finished. This also applies to any errors that say your credentials (username and password) are incorrect.

Using the Windows instance
Now you have access to the Windows instance, you're ready to start using it! This version of Windows is intended to be used on a Server, and auto-starts a server-management program. We don't need this for this lab, so wait for it to finish starting and then close it. You may see the desktop appear for a few seconds before the program launches.

Server manager Server manager home

Once that's closed, the Windows OS is ready for you to use.

Finishing the login process

Now you‘ll see a Windows desktop background that looks like this:

Windows Desktop

Note:
Please make sure that you have connected your RDP session with the username ‘student’ otherwise you will not earn the score for your lab objectives.

Verifying initial setup on Windows
To verify whether or not a program is installed in Windows, click the Start icon in the bottom-left of the taskbar, and start typing "Programs and Features" to search (as shown below). Then, click "Programs and Features." You can also right-click on the Start icon, and click on "Programs and Features" at the top of the menu.

2a2176641e74ede3.png

This will bring up the Programs and Features Control Panel applet, which shows a list of every program that's installed on the computer.

fdce64c5cf949e0d.png

By looking at this applet, you can see that Mozilla software isn't present, so we know that it's not currently installed. Similarly, we can see that VLC and GIMP are both already installed, so we're ready to proceed. Note that the installed version of VLC is 2.2.8; this isn't the most recent version, so we'll update it later on in this lab.

Maintaining software on Windows
Now that we know that the Windows instance is properly configured (i.e. we have verified that Mozilla is not installed, but VLC and GIMP are both already installed), you can move on to the hands-on part of the lab; maintaining the software.

Installing Mozilla Firefox
First, you'll install the Mozilla Firefox browser in the Windows instance. To install Firefox, you need to download the Windows installer from the Firefox website. To do this, double-click the Google Chrome icon on the left side of the desktop screen, and navigate to this url:

https://www.mozilla.org/en-US/firefox/new/

From this site, click the "Download" link to download the installer.

7a9e0a8d8a20cbbb.png

Once the installation finishes, click the installer icon in the bottom-left side of the browser window.

98c6a98875a1a3d9.png

This launches the installer, and starts the installation process. Click "Yes" if Windows asks if you wish to install it, and the installer should open and begin.

14f41b191869d9ab.png

Click "Next" through any options that appear during the installation process. Wait for this process to finish, and Mozilla will be installed. A shortcut to Firefox will be added to the desktop, and you can double-click it to open your newly installed browser.

Congratulations! You've now done a "clean install" of software using Windows. Pretty simple, right? Next, you'll configure the updates for software already installed on your machine.

Click Check my progress to verify the objective.
Install Mozilla Firefox

Updating VLC Media Player
We saw before that an old version of VLC Media Player is already installed on the Windows VM we're using. This is an old version; we'll now learn how to update it in Windows. First, you need to get an installer for the new version from VLC's website. Open the link below to download the installer:

https://www.videolan.org/vlc/download-windows.html

Click on drop-down menu beside "Download VLC" and select "Installer for 64bit version" and wait for the installer to finish downloading.

7967e0aabedae075.png

Once done, click on the installer to open it (like you did for Firefox).

f9a31c338d89dd86.png

Once the installer opens, choose whichever language you're comfortable with, then click "Next" to begin the process.

Choose "Upgrade VLC using previous settings(recommended)" and then click "Next". A progress bar appears and the upgrade process begins.

72ef426043439664.png

When the process is finished, a confirmation message will appear. Uncheck the option to run VLC, then click "Finish" to close the installer.

7e6110b531ab7d7f.png

Reopen the "Programs and Features" window and you'll see that VLC is now at the latest version.

d46d4253bb967621.png

Click Check my progress to verify the objective.
Update VLC

Uninstalling GIMP
Uninstalling a program on Windows is super simple. Navigate back to "Programs and Features" and right click on the program you want to remove (i.e. GIMP). A single-item dropdown menu should appear:

1f46fa9598456c06.png

Click on the "Uninstall" option in the dropdown. A confirmation menu will appear, asking if you're sure you want to proceed. Click "Yes" and the uninstallation process will begin.

50d976971c8dd7c9.png

When this process finishes, a confirmation menu will appear. Clicking "OK" on that menu will close it, and GIMP should no longer appear on the list of installed programs. This completes the uninstallation process.

84e591712a2284bc.png

Click Check my progress to verify the objective.
Uninstall GIMP

Congratulations!
You've successfully installed Firefox, updated VLC, and uninstalled GIMP on a Windows machine. Wohoo! You've completed this lab, but please feel free to return to it if you ever need a refresher.

