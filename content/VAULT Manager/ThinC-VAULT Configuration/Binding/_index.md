---
description: ""
title: Bindings
weight: 3
---

Binding a security function that couples ThinC-VAULT device to given computer (Laptop/Desktop), IP address, MAC address, Network Binding. Adding Computer will trigger and enable the binding security function in the device. Admin has the flexibility of activating multiple binding rules however when a Network Binding rule is enabled, rest of the rules can't be activated for the connected ThinC-VAULT device. ThinC-VAULT device has the capability of combination of IP, MAC and PC Binding can be combined as a single rule or can work independently. Admin can add upto 10 Binding rule to any given ThinC-VAULT device.


## IP Binding


IP Binding
Its an security function that binds ThinC-VAULT device to given IP address. If any ThinC-VAULT is binded to the IP address then it can only be used in a computer with that IP address and it does not work / function with any other IP based PC/Laptops. Adding IP will trigger and enable the binding security function in the device. 

### Adding IP Address to ThinC-VAULT Binding list
* To enable Add IP Address to the binding list, navigate to Binding tab. The bindings tab lists all the available Binding features. Check the checkbox IP Binding and the tool will provide a text area to enter the IP Address of the system that needs to be binded. Click on Add and a pop up warning window will be displayed requesting the permission to add the binding rule, choose "Yes, Add" and "Cancel" to abort.





* After successfully adding the rule to Device Binding Rule list the, tool displays a notification stating "Binding rule has been added successfully" message and the screen would get updated. 



### Removing PC/Laptop from ThinC-VAULT Binding list 

In the Device Binding Rule section click on  to delete the selected IP Address from the Binding rules. Click on "Delete" to proceed with the deletion or click on "Cancel" to abort the operation. 



* After successful deletion of the device from the binding list "Binding rule has been deleted successfully" notification will be displayed by the tool. 



* Deleting the computer will unbound all the bound partitions and also removes the computer binding.

### Binding ThinC-VAULT to IP Address

After adding the IP Address to the Binding list, check the check-box under Device Binding Rules section to bind the IP address to ThinC-VAULT device. Click on "Yes, Bind" to proceed with the Binding or click on "Cancel" to abort the operation.



After successfully adding the IP Address to the binding list the, tool displays a notification stating "Binding rule has been activated successfully." 



### Unbinding ThinC-VAULT from IP Address

In the Device Binding section click on  to delete the selected PC from the binding list. Click on "Yes, Unbind" to proceed with the unbinding or click on "No, keep" to abort the operation. 



After successful unbinding the tool will display a notification stating "Binding rule has been deactivated successfully". 


## PC Binding


Its an security function that binds ThinC-VAULT device to given computer (Laptop/Desktop). If any ThinC-VAULT is binded to computer then it can only be used in that computer and it does not work / function with any other computer machines. Adding Computer will trigger and enable the binding security function in the device. 

### Adding PC/Laptop to ThinC-VAULT Binding list
To enable bindings, navigate to Binding tab. The bindings tab lists all the available Binding features. Check the checkbox PC Binding and the tool will automatically read the computers name and populate the name under PC Name. Click on Add and a pop up warning window will be displayed requesting the permission to add the binding rule, choose "Yes, Add" and "Cancel" to abort.





* After successfully adding the computer to Device Binding Rule list the, tool displays a notification stating "Binding rule has been added successfully" message and the screen would get updated. 



* To add a different system to the binding list, click on the toggle the slider "Other PC" and enter the PC/Laptop name and PC Fingerprint Value obtained from the Computer ID tool and click on Add. 

### Removing PC/Laptop from ThinC-VAULT Binding list 

In the Device Binding section click on  to delete the selected PC from the Binding Rules. Click on "Delete" to proceed with the deletion or click on "Cancel" to abort the operation. 



* After successful deletion of the device from the binding list "Delete computer from device successful" notification will be displayed by the tool. 



* Deleting the computer will unbound all the bound partitions and also removes the computer binding.

### Binding ThinC-VAULT to PC/Laptop

After adding the PC/Laptop to the Binding list, check the check-box under Device Binding section to bind the computer to ThinC-VAULT device. Click on "Bind" to proceed with the Binding or click on "Cancel" to abort the operation.



* After successfully adding the computer to the binding list the, tool displays a notification stating "Computer has been bound to the device successfully." 



### Unbinding ThinC-VAULT from PC/Laptop

In the Device Binding section click on  to delete the selected PC from the binding list. Click on "Yes, Unbind" to proceed with the unbinding or click on "No, keep" to abort the operation. 



* After successful unbinding the tool will display a notification stating "Binding rule has been deactivated successfully". 


### PC-UniqueID-Generator

ThinC-VAULT accessibility can be restricted to a selective/designed PC systems (upto 10). The 'PC-UniqueID-Generator.exe' tool helps in generating Unique ID (UID) of the designated PC system. The UID will be configured in the 'PC Binding' section of VAULT Manager Tool.



## MAC Binding

Its an security function that binds ThinC-VAULT device to a computer using the MAC. If any ThinC-VAULT is binded to a computers MAC address then it can only be used in a computer with that MAC address and it does not work / function with any other computer machines. Adding MAC address will trigger and enable the binding security function in the device. 

### Adding MAC Address to ThinC-VAULT Binding list
To add the MAC Address to the binding list, navigate to Binding tab. The bindings tab lists all the available Binding features. Check the checkbox MAC Binding and enter the MAC address of the computer that needs to be added. Click on Add and a pop up warning window will be displayed requesting the permission to add the binding rule, choose "Yes, Add" and "Cancel" to abort.





* After successfully adding the MAC address to Device Binding Rule list the, tool displays a notification stating "Binding rule has been added successfully" message and the screen would get updated. 



### Removing MAC Address from ThinC-VAULT Binding list 

In the Device Binding section click on  to delete the selected MAC Address from the Binding list. Click on "Delete" to proceed with the deletion or click on "Cancel" to abort the operation. 



* After successful deletion of the device from the binding list "Binding rule has been deleted successfully" notification will be displayed by the tool. 



* Deleting the computer will unbound all the bound partitions and also removes the computer binding.

### Binding MAC address to ThinC-VAULT

After adding the MAC Address to the computer list, check the check-box under Device Binding section to bind the computer to ThinC-VAULT device. Click on "Bind" to proceed with the Binding or click on "Cancel" to abort the operation.



* After successfully adding the MAC Address to the binding list, the tool displays a notification stating "Binding rule has been activated successfully." 



### Unbinding MAC Address from ThinC-VAULT

In the Device Binding section click on  to delete the selected PC from the binding list. Click on "Yes, Unbind" to proceed with the unbinding or click on "No, keep" to abort the operation. 



* After successful unbinding the tool will display a notification stating "Binding rule has been deactivated successfully". 



## Network Binding

Its an security function that binds ThinC-VAULT device to a computer using the Network address range and Subnet Mask. If any ThinC-VAULT is binded to the Network range then it can only be used in a computer with in the network range and it does not work / function with any other computer machines. Adding MAC address will trigger and enable the binding security function in the device. 

### Adding Network information to ThinC-VAULT Binding list
To add a network range to the binding list, navigate to Binding tab. The bindings tab lists all the available Binding features. Check the checkbox PC Binding and enter the Network Address and Subnet Mask. Click on Add and a pop up warning window will be displayed requesting the permission to add the binding rule, choose "Yes, Add" and "Cancel" to abort.





* After successfully adding the Network Address to Device Binding Rule list the, tool displays a notification stating "Binding rule has been added successfully" message and the screen would get updated. 



### Removing Network information from ThinC-VAULT Binding list 

In the Device Binding section click on  to delete the selected Network Address from the Binding list. Click on "Delete" to proceed with the deletion or click on "Cancel" to abort the operation. 


* After successful deletion of the Network Address from the binding list "Delete computer from device successful" notification will be displayed by the tool. 



* Deleting the computer will unbound all the bound partitions and also removes the computer binding.

### Binding ThinC-VAULT to Network

After adding the Network Address to the binding list, check the check-box under Device Binding section to bind the Network Address to ThinC-VAULT device. Click on "Bind" to proceed with the Binding or click on "Cancel" to abort the operation.



After successfully adding the Network Address to the binding list the, tool displays a notification stating "Binding rule has been activated successfully." 



### Unbinding ThinC-VAULT from Network

In the Device Binding section click on  to delete the selected Network Address from the binding list. Click on "Yes, Unbind" to proceed with the unbinding or click on "No, keep" to abort the operation. 



After successful unbinding the tool will display a notification stating "Binding rule has been deactivated successfully". 




