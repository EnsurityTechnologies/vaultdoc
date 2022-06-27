---
description: ""
title: User Management
weight: 1
---


User Creation:

ThinC Manager tool has capability to automatically distinguish between fresh / reset / unregistered device and fingerprint enrolled / registered device. In case of fingerprint enrolled / registered device it is mandatory for the registered user to authenticate before accessing Management functions. The step 1 below provide process to access management function for device with enrolled fingerprint, see to step 2 for unregistered device or first time fingerprint enrollment. 

 The tool will automatically skip to step 2 to initiate the initial authentication process for new fresh / reset / unregistered device. 

Step 1:
Click on Authenticate and place enrolled finger on the Touch sensor. The tool will request ThinC-VAULT to verify the finger and provide access after successful verification. This step is skipped by tool automatically for fresh / reset / unregistered device.

 

 The device has mechanism to prevent unauthorized access. More than 10 continuous unsuccessful authentications  would initiate factory reset.
 
Step 2:
Click on Add User /Group button to register a new user to the device.



The tool displays a dialog box "Create New User". In the dialog box, select User option and enter the Display Name, User Name. Click on Create to create the user. By default the first user of the device is the Admin. Click Ok in the pop up.

 It is mandatory to enroll atleast one fingerprint associated with the created user for device to register and store the user. Clicking on  cancels the user creating process. 





 Only the device administrator can add / remove users or fingerprints.  

User Deletion:

In the user management window click on  in the user tile to delete the user. After successful deletion of the user "Delete User Successful" notification will be displayed by the tool. 





 The Admin user can only be deleted by performing a factory reset
  If the user is deleted, the corresponding access rights to the partition will be removed.


  
Register Users fingerprints

The tool will automatically showcase fingerprint management window for the user created. Fingerprint management window provides 10 slots to choose for enrolment of finger. Choose the finger slot of your choice by clicking on  icon to enroll the fingerprint. Click on "Yes enroll!" to initiate enrollment process, click No to abort enrollment process.



 Avoid using different finger for indicated fingerprint slots to minimize confusions later. All the enrolled fingerprints are securely stored on the ThinC-VAULT device. 
 No fingerprints or device access information is stored in the management tool. All fingerprint information is stored on ThinC-VAULT in an encrypted format. 

Place the finger repeatedly on fingerprint sensor to continue and complete the enrollment process, finger has to be repeatedly placed on fingerprint sensor till enrollment process reaches 100%. As a best practice placing finger repeatedly in slightly different angles each time to enroll finger quickly. 



After the fingerprint enrollment process is successfully completed, tool displays a notification stating "Adding Finger successfully" message and the screen would get updated.



 The tool would display the fingerprint slots that are available in USB device for enrollment with  symbol
 The Tool would display the fingerprint slots that are already used with fingerprint symbol  and  icon is displayed on the Management tool finger image.

ThinC Device supports upto 5 users and each user can enroll upto 3 fingerprints. If these slots are exceeded and after enrollment process instead of "Fingerprint enrolled Successfully" tool would notify "Maximum finger limit reached".  



Step 3:
Verification of finger is not a mandatory process for using services, as a best practice please choose to verify the enrolled fingerprints by using "Verify Finger" option. In Fingerprint management window click on Yes, verify, place the finger on sensor. 



Tool will automatically initiate the verification and shall provide results by notifying "Your fingerprint verified Successful" if fingerprint matches enrolled finger or "Authentication Failed" if fingerprint does not match 



De-Register Users fingerprints

The Fingerprint management allows deletion / de-registration of individual fingerprints.

In the fingerprint management window click on 'delete / trash icon' on the given slot to delete / de-register fingerprint. After successful deletion of the fingerprint " Your fingerprint data is successfully deleted from the device" notification will be displayed by the tool. 
 




 It is mandatory for the Admin to have at least one fingerprint enrolled. 

