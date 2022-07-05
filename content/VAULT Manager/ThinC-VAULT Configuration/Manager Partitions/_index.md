---
description: ""
title: Patition Management
weight: 2
---


This section of the document describes the process of creating, deleting partitions with and without password in ThinC-Manager application.  

## Set / Edit / Manage Partitions without Password

### Create Partition 

To manage the partitions on ThinC-VAULT device, goto ThinC Manager tool partition tab (by clicking on partitions). This tab shows the partition information (Name & Size) and unallocated space in the form of doughnut chart.



To create a new partition, click on the doughnut chart. Enter the partition name and required partition size. Select one or more users in the list of "Assign Access to user / group". Assign access rights to the partition by clicking on  under Manage column. Now drop down menu under Under Permissions Tab choose the required access control - "Read Only" or "Read / Write".  After modifying the access rights, click on  to save the changes. Clicking on will discard the modified changes. Click on "Create" to create the partition.



 The maximum of 15 characters are allowed for partition name.
 If User is not assigned to the partition, tool displays a prompt "Please select at least one user for creating partition" requesting the user to select a user to continue the partition creation process.
 Partition can either be assigned to a user or a group.



The tool displays a pop up "Partition Added successfully. The new partition will be accessible from next device connection". Remove the ThinC-VAULT device from computer, reconnect and authenticate to enumerate the newly created partitions. 





### Deletion of Partitions

ThinC-VAULT supports deletion of selected partitions. Please use the following procedure to delete partition(s).  

In the partition management tab click on 'Delete Partition' to delete the selected partition. Click on "Yes, delete" to proceed with the deletion or click on "No" to abort the operation. 






After successful deletion of the partition "Deleting partition successful" notification will be displayed by the tool. Kindly remove the ThinC-VAULT device and reconnect. Authenticate the device using enrolled fingerprint to re-login .  



Please remove and reconnect ThinC-VAULT device after delete operations
Deleting a given partition will delete the contents stored in the partition. Deleting all partitions will delete contents stored in all partitions.




## Set / Edit / Manage Partitions with Password


### Create Partition 

To manage the partitions on ThinC-VAULT device, goto ThinC Manager tool partition tab (by clicking on partitions). This tab shows the partition information (Name, Size, User access rights) and storage capacities in the form of doughnut chart.



To create a new partition, click on the doughnut chart. Enter the partition name and required partition size. Select one or more users in the list of "Assign Access to user / group".  The default access rights will be Read/Write. Assign access rights to the partition by clicking on  under Manage column . Now drop down menu under Under Permissions tab, choose the required access control - "Read Only"  or "Read / Write".  After modifying the access rights, click on  to save the changes. Clicking on will discard the modified changes. Click on "Create" to create the partition.



 If User / Group is not assigned to the partition, tool displays a prompt "Please select at least one User / Group for creating partition" requesting the admin to select a user / group to continue the partition creation process.



Tool supports assigning of  Password based access control to the partition during the creation of partition. Click on "Enable Password" check box. Please enter Password and confirm Password, click on Create button to create the partition.

 Partition Password supports only 16 characters.



The tool displays a pop up "Partition Added successfully. The new partition will be accessible from next device connection".   Remove the ThinC-VAULT device from computer, reconnect and authenticate to enumerate the newly created partitions. 





### Deletion of Partitions

ThinC-VAULT supports deletion of selected partitions. Please use the following procedure to delete partition.  

In the partition management tab click on 'Delete Partition' to delete the selected partition. 



Click on "Yes, delete" to proceed with the deletion or click on "No" to abort the operation



Unlock the partition by entering the Password to proceed with the deletion. 



After successful deletion of the partition "Deleting partition successful" notification will be displayed by the tool. Kindly disconnect and reconnect the ThinC-VAULT device. Authenticate the device using enrolled fingerprint to re-login .  


Please remove and reconnect ThinC-VAULT device after delete operations
Deleting a given partition will delete the contents stored in the partition. Deleting all partitions will delete contents stored in all partitions.


