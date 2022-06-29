---
description: ""
title: ThinC-VAULT Specifications
weight: 2
---

Outlined below are the hardware specifications and the features available for ThinC-VAULT

## Hardware Specifications

The following table provides brief specification of ThinC-VAULT device.


<table>
  <tr>
    <th>Feature</th>
    <th>Specification / Description</th>
    </tr>
  <tr>
    <td>Connectivity</td>
    <td><li>High-speed USB 2.0</td>

  </tr>
   <tr>
    <td>Capacity</td>
    <td><li>32GB<li> 64GB <li> 128GB</td>
  
  </tr>
  <tr>
    <td>Fingerprint Biometrics</td>
    <td><li>Capacitive touch based fingerprint sensor 
        </td>
    </tr>
   <tr>
    <td>Security & Cryptology </td>
    <td><li> AES256 for Fingerprint store and data encryption </li>
<li>Dynamic on-chip Key generation </li>
<li>Design in compliance with FIPS 140-2 Level 2 standards </li>
<li>Individual partitions are encrypted with different key</li></td>
   
  </tr>
    <tr>
    <td>Certifications</td>
    <td><li> FCC
        <li>CE
    </td>
  </tr>
   <tr>
      <td>Access Control</td>
      <td><li>Read / Write
          <li>Read Only
          <li>Password for partition</td>
    </tr>
       <tr>
    <td>Performance</td>
    <td><li>Durability: ~20,000 insertion cycles
        <li>Typical Average Read speed: ~38 Mbps
        <li>Typical Average Write speed: ~35 Mbps </td>
  </tr>
</table>


## Software Features

This section describes the overall functional features / device configurations

<table>
  <tr>
    <th>Feature</th>
    <th>Description</th>
    </tr>
  <tr>
    <td>Number of configurable Users</td>
    <td>5</td>
  </tr>
  <tr>
    <td>Total Number of Fingerpint slots</td>
    <td>15</td>
  </tr>
   <tr>
    <td>Fingerprint slots available for each User  </td>
    <td>3</td>
  </tr>
  <tr>
    <td>Number of Groups supported</td>
    <td>3</td>
  </tr>
   <tr>
    <td>Number Partitions</td>
    <td>8</td>
  </tr>
    <tr>
    <td>Partition(s) assignment for single user</td>
    <td>No restriction</td>
  </tr>
    <tr>
        <td>Partitions assignment for Group</td>
        <td>1</td>
    </tr>
    <tr>
        <td>Binding types</td>
            <td>
                <li>PC Binding
                <li>IP Binding
                <li>MAC Binding
                <li>Network Binding
            </td>
    </tr>
</table>

~~~
Memory calculation for ThinC-VAULT considers the following:
1GB= 1,000,000,000 bytes or 1GB=1000MB
~~~

## LED Indications

The following table indicates the state of LED after the device is connected and powered on


<table>
  <tr>
  <th >Function</th>
  <th>State
  </th>
  <th>LED State
  </th>
  <th>Remarks
  </th>
  </tr>
  <tr>
  <td>Power On
  </td>
  <td>-
  </td>
  <td> <img alt="" style="padding : 1px;" src="GLOWPINK.png"></td>
  <td>Typically, 1-2 seconds
  </td>
  </tr>
  <tr>
  <td>BITE (Built In Test)
  </td>
  <td>-
  </td>
  <td><img alt="" style="padding : 1px;" src="BLUEBLINKING.png">
  </td>
  <td>BITE Successful
  </td>
  </tr>
  <tr>
  <td>
  </td>
  <td>
  </td>
  <td><img alt="" style="padding : 1px;  " src="GLOWRED.png">
  </td>
  <td>BITE Failure after 7 sec
  </td>
  </tr>
  <tr>
  <td >Fingerprint scan
  </td>
  <td>Wait
  </td>
  <td ><img alt="" style="padding : 1px;" src="GLOWPINK.png">
  </td>
  <td>Wait for fingerprint - typically 30 sec time out.
  </td>
  </tr>
  <tr>
  <td >Process
  </td>
  <td ><img alt="" style="padding : 1px; " src="SLOWBLINKING BLUE.png">
  </td>
  <td >
  </td>
  </tr>
  <tr >
  <td>Success
  </td>
  <td><img alt="" style="padding : 1px;" src="BLUEBLINKING.png">
  </td>
  <td>Typically, 1-2 seconds
  </td>
  </tr>
  <tr >
  <td >Fail
  </td>
  <td ><img alt="" style="padding : 1px; " src="REDBLINKING.png">
  </td>
  </tr>
  <tr>
  <td >Delete Fingerprint
  </td>
  <td>Success
  </td>
  <td><img alt="" style="padding : 1px;" src="BLUEBLINKING.png">
  </td>
  </tr>
  <tr >
  <td>Fail
  </td>
  <td><img alt="" style="padding : 1px; " src="REDBLINKING.png">
  </td>
  </tr>
  <tr>
  <td>Factory Reset
  </td>
  <td>Success
  </td>
  <td><img alt="" style="padding : 1px;" src="BLUEBLINKING.png">
  </td>
  </tr>
  <tr>
  <td >After Reset
  </td>
  <td><img alt="" style="padding : 1px;" src="REDBLINKING.png">
  </td>
  <td>Disconnect and reconnect the device
  </td>
  </tr>
  <tr>
  <td>Fail
  </td>
  <td><img alt="" style="padding : 1px; " src="SLOWBLINKING PINK.png">
  </td>
  <td>Typically, 1-2 seconds
  </td>
  </tr>
  <tr >
  <td >SD Card Operations
  </td>
  <td>Read/Write
  </td>
  <td><img alt="" style="padding : 1px; margin : 0px 20px;" src="SLOWBLINKINGBLUE.png">
  </td>
  <td>Data read / write from the device</td>
  </tr>
</table>

</div>

<table>
<tr >
  <td><img alt="" style="padding : 1px;" src="BLUEBLINKING.png">
  </td>
  
<td><img alt="" style="padding : 1px;" src="REDBLINKING.png">
</td>
<td><img alt="" style="padding : 1px;" src="SLOWBLINKING BLUE.png">
</td>
<td><img alt="" style="padding : 1px;" src="SLOWBLINKING RED.png">
</td>
<td><img alt="" style="padding : 1px;" src="GLOWPINK.png">
</td>
<td><img alt="" style="padding : 1px;" src="GLOWRED.png">
</td>
</tr>
<tr >
<td>Blinking
</td>
<td >Slow Blinking
</td>
<td >Glow
</td>
</tr>
</table>
