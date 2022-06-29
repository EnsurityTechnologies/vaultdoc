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


## Features

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
<td width="121" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 2px 10px; background-color: #f2f2f2;"><p class="rvps4"><span class="rvts15">Function</span></p>
</td>
<td width="95" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px; background-color: #f2f2f2;"><p class="rvps4"><span class="rvts15">State</span></p>
</td>
<td width="64" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px; background-color: #f2f2f2;"><p class="rvps4"><span class="rvts15">LED State</span></p>

</td>
<td width="197" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px; background-color: #f2f2f2;"><p class="rvps4"><span class="rvts15">Remarks</span></p>
</td>
</tr>
<tr valign="top">
<td width="121" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Power On</span></p>
</td>
<td width="95" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">-</span></p>
</td>
<td width="64" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps4"><img alt="" style="padding : 1px; margin : 0px 20px;" src="lib/GLOW PINK.png"></p>
</td>
<td width="197" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Typically, 1-2 seconds</span></p>
</td>
</tr>
<tr valign="top">
<td rowspan="2" width="121" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">BITE (Built In Test)</span></p>
</td>
<td width="95" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">-</span></p>
</td>
<td width="64" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps4"><img alt="" style="padding : 1px; margin : 0px 20px;" src="lib/BLUE BLINKING.png"></p>
</td>
<td width="197" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">BITE Successful </span></p>
</td>
</tr>
<tr valign="top">
<td width="95" height="23" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">-</span></p>
</td>
<td width="64" height="23" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps4"><img alt="" style="padding : 1px; margin : 0px 20px;" src="lib/GLOW RED.png"></p>
</td>
<td width="197" height="23" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">BITE Failure after 7 sec</span></p>
</td>
</tr>
<tr valign="top">
<td rowspan="4" width="121" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Fingerprint scan</span></p>
</td>
<td width="95" height="31" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Wait</span></p>
</td>
<td width="64" height="31" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps4"><img alt="" style="padding : 1px; margin : 0px 20px;" src="lib/GLOW PINK.png"></p>
</td>
<td width="197" height="31" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Wait for fingerprint - typically 30 sec time out. </span></p>
</td>
</tr>
<tr valign="top">
<td width="95" height="37" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Process</span></p>
</td>
<td width="64" height="37" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps4"><img alt="" style="padding : 1px; margin : 0px 20px;" src="lib/SLOW BLINKING BLUE.png"></p>
</td>
<td width="197" height="37" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15"><br/></span></p>
</td>
</tr>
<tr valign="top">
<td width="95" height="33" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Success</span></p>
</td>
<td width="64" height="33" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps4"><img alt="" style="margin : 0px 20px;" src="lib/BLUE BLINKING.png"></p>
</td>
<td rowspan="5" width="197" height="12" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Typically, 1-2 seconds</span></p>
</td>
</tr>
<tr valign="top">
<td width="95" height="30" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Fail</span></p>
</td>
<td width="64" height="30" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps4"><img alt="" style="padding : 1px; margin : 0px 20px;" src="lib/RED BLINKING.png"></p>
</td>
</tr>
<tr valign="top">
<td rowspan="2" width="121" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Delete Fingerprint</span></p>
</td>
<td width="95" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Success</span></p>
</td>
<td width="64" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps4"><img alt="" style="padding : 1px; margin : 0px 20px;" src="lib/BLUE BLINKING.png"></p>
</td>
</tr>
<tr valign="top">
<td width="95" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Fail</span></p>
</td>
<td width="64" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps4"><img alt="" style="padding : 1px; margin : 0px 20px;" src="lib/RED BLINKING.png"></p>
</td>
</tr>
<tr valign="top">
<td rowspan="3" width="121" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Factory Reset</span></p>
</td>
<td width="95" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Success</span></p>
</td>
<td width="64" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps4"><img alt="" style="padding : 1px; margin : 0px 20px;" src="lib/BLUE BLINKING.png"></p>
</td>
</tr>
<tr valign="top">
<td width="95" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">After Reset</span></p>
</td>
<td width="64" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps4"><img alt="" style="padding : 1px; margin : 0px 20px;" src="lib/RED BLINKING.png"></p>
</td>
<td width="197" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Disconnect and reconnect the device</span></p>
</td>
</tr>
<tr valign="top">
<td width="95" height="24" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Fail</span></p>
</td>
<td width="64" height="24" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps4"><img alt="" style="padding : 1px; margin : 0px 20px;" src="lib/SLOW BLINKING PINK.png"></p>
</td>
<td width="197" height="24" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Typically, 1-2 seconds</span></p>
</td>
</tr>
<tr valign="top">
<td width="121" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">SD Card Operations</span></p>
</td>
<td width="95" height="24" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Read/Write</span></p>
</td>
<td width="64" height="24" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps4"><img alt="" style="padding : 1px; margin : 0px 20px;" src="lib/SLOW BLINKING BLUE.png"></p>
</td>
<td width="197" height="24" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 5px 20px;"><p class="rvps8"><span class="rvts15">Data read / write from the device </span></p>
</td>
</tr>
</table>
</div>
<p class="rvps8"><span class="rvts15"><br/></span></p>
<div class="rvps8"><table width="500" border="1" cellpadding="1" cellspacing="-1" style="border-width: 0px; border-collapse: collapse;">
<tr valign="middle">
<td width="66" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 1px;"><p class="rvps3"><img alt="" style="padding : 1px;" src="lib/BLUE BLINKING.png"></p>
</td>
<td width="73" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 1px;"><p class="rvps3"><img alt="" style="padding : 1px;" src="lib/RED BLINKING.png"></p>
</td>
<td width="52" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 1px;"><p class="rvps3"><img alt="" style="padding : 1px;" src="lib/SLOW BLINKING BLUE.png"></p>
</td>
<td width="65" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 1px;"><p class="rvps3"><img alt="" style="padding : 1px;" src="lib/SLOW BLINKING RED.png"></p>
</td>
<td width="71" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 1px;"><p class="rvps3"><img alt="" style="padding : 1px;" src="lib/GLOW PINK.png"></p>
</td>
<td width="67" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 1px;"><p class="rvps3"><img alt="" style="padding : 1px;" src="lib/GLOW RED.png"></p>
</td>
</tr>
<tr valign="middle">
<td colspan="2" width="144" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 1px;"><p class="rvps3"><span class="rvts12">Blinking</span></p>
</td>
<td colspan="2" width="122" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 1px;"><p class="rvps3"><span class="rvts12">Slow Blinking</span></p>
</td>
<td colspan="2" width="110" valign="middle" style="border-width : 1px; border-color: #000000; border-style: solid; padding: 1px;"><p class="rvps3"><span class="rvts12">Glow</span></p>
</td>
</tr>
</table>
