# kalilab-setup-w1
Set up a lab environment using Oracle VirtualBox and Kali Linux
Configured a NAT Network with the subnet 10.0.0.0/24 for communication between virtual machines.
had an issue where virtual box could not find the location of my iso file so i could not start up kali machine
The screen displayed the error “Nothing to boot: No such file or directory.”
The virtual machine attempted to boot from the network.
I checked the Storage settings and confirmed that KaliLab.vdi was attached.
I confirmed that the virtual optical drive was empty.
I checked the boot order in the system settings.
I set the hard disk as the first boot device.
I disabled network boot.
I checked the EFI setting and found that it was unchecked.
The cause of the boot error is still being investigated.
I am verifying that the correct virtual disk is attached and contains a bootable Kali Linux system.
i used the wrong disk image 
i later changed the boot order and the machine started working

Encountered network connectivity issues while configuring the static IP address.
Investigated connection activation errors and DNS resolution failures.
Applied NetworkManager configuration changes to resolve the connectivity problems.
Tested network communication using the ping command.
Successfully established internet connectivity within the Kali Linux virtual machine.

Created a /downloads directory on the Kali Linux host machine.
Configured VirtualBox Shared Folders to allow file sharing between the host and guest operating systems.
Enabled automatic mounting of the shared directory.
Configured the necessary permissions to access shared files.
Created a test file and successfully verified file sharing between the host and virtual machine.<img width="1366" height="739" alt="Screenshot From 2026-10-29 18-32-20" src="https://github.com/user-attachments/assets/af949136-58dc-4e89-9b27-47847b6ede57" />

Enabled bidirectional clipboard sharing in VirtualBox settings.
Enabled bidirectional drag-and-drop functionality.
Configured VirtualBox guest integration features.
Successfully tested copying text and transferring files between the host and guest machines.
