# Ubuntu-VirtualBox
Installing Ubuntu 22.04 LTS on VirtualBox

Step 1: Install virtual box
First, virtual box was downloaded from the official oracle virtual box website and installed on the computer, after installation, virtual box was opened successfully.

Step 2: Download Ubuntu 22.04 LTS
The Ubuntu 22.04 LTS ISO file was downloaded from the official Ubuntu website. This ISO file is used to install Ubuntu inside virtual box.
Step 3: Create a New Virtual Machine
Inside virtual box:
1.	The New button was clicked.
2.	The virtual machine name was set to Ubuntu 22.04.
3.	The operating system type was selected as Linux and version as Ubuntu(64 –bits).
4.	A new virtual hard disk was created

Step 4: Attach the Ubuntu ISO File
1.	The Ubuntu virtual machine was selected.
2.	Settings → Storage was opened.
3.	Under the IDE controller, the empty optical drive was selected.
4.	The Ubuntu 22.04 ISO file (ubuntu-22.04.5-desktop-amd64.iso) was attached.
5.	Settings were saved.
6.	
Step 5: Enable Virtualization
When starting the virtual machine, an error occurred indicating that virtualization was disabled.
To fix this:
1.	The computer was restarted.
2.	Virtualization Technology (VT-x) was enabled from the BIOS.
3.	Hyper-V and related features were disabled in Windows.
4.	The computer was restarted again.
After this, the virtual machine started successfully.

Step 6: Start Ubuntu Installation
1.	The Start button was clicked in virtual box.
2.	Ubuntu loaded and the option Try or Install Ubuntu appeared.
3.	Install Ubuntu was selected.
4.	The keyboard layout was chosen.
5.	Normal installation was selected.
6.	Disk option Erase disk and install Ubuntu was chosen (only affects the virtual disk).
7.	Time zone and user details were configured.

Step 7: Finish Installation
After installation completed:
1.	The system was restarted.
2.	Ubuntu booted into the desktop environment.
3.	The “Online Accounts” screen appeared and skip was selected.
4.	Ubuntu 22.04 desktop loaded successfully.

 






