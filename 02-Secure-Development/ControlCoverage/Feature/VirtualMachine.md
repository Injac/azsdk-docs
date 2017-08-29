﻿<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"  "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>

</head><body>
<H2>VirtualMachine</H2>
<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Description & Rationale</th><th>ControlSeverity</th><th>Automated</th></tr>
<tr><td><b>Virtual Machine should have latest OS version installed</b><br/></td><td>Medium</td><td>Yes</td></tr>
<tr><td><b>OS automatic updates must be enabled on Windows Virtual Machine</b><br/>VMs where automatic updates are disabled are likely to miss important security patches due to human error. This may lead to compromise from various malware/trojan attacks that exploit known vulnerabilities in operating systems and related software.</td><td>High</td><td>Yes</td></tr>
<tr><td><b>Antimalware must be enabled with real time protection on Windows Virtual Machine</b><br/>Microsoft Antimalware provide real-time protection, scheduled scanning, malware remediation, signature updates, engine updates, samples reporting, exclusion event collection etc.</td><td>High</td><td>Yes</td></tr>
<tr><td><b>NSG must be configured for Virtual Machine</b><br/>A network security group (NSG) tightly control the network communication by providing security rules to allow or deny network traffic .</td><td>Medium</td><td>Yes</td></tr>
<tr><td><b>Public IPs on a Virtual Machine should carefully reviewed</b><br/>Public IPs provide direct access over the internet exposing the VM to all type of attacks over the public network.</td><td>High</td><td>Yes</td></tr>
<tr><td><b>Disk encryption must be enabled on both OS and data disks for Windows Virtual Machine</b><br/>In the case of VMs, both OS and data disks may contain sensitive information that needs to be protected at rest. Hence disk encryption must be enabled for both.</td><td>High</td><td>Yes</td></tr>
<tr><td><b>Virtual Machine must be in a healthy state in Azure Security Center</b><br/>Security Center  recommendations must be addressed and fixed to protect a VM against potential security vulnerabilities.</td><td>High</td><td>Yes</td></tr>
<tr><td><b>Diagnostics (IaaSDiagnostics extension on Windows; LinuxDiagnostic extension on Linux) must be enabled on Virtual Machine</b><br/></td><td>Medium</td><td>Yes</td></tr>
<tr><td><b>Do not leave management ports open on Virtual Machines</b><br/></td><td>Critical</td><td>Yes</td></tr>
</table>
</body></html>