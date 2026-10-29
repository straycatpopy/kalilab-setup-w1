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
