<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"  "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>

</head><body>
<H2>VirtualNetwork</H2>
<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Description</th><th>ControlSeverity</th><th>Automated</th></tr>
<tr><td>Minimize the number of Public IPs (i.e. NICs with PublicIP) on a Virtual Network</td><td>High</td><td>Yes</td></tr>
<tr><td>Use of IP Forwarding on any NIC in a Virtual Network should be scrutinized</td><td>High</td><td>Yes</td></tr>
<tr><td>There must not be any NSGs on the GatewaySubnet of a Virtual Network</td><td>Medium</td><td>Yes</td></tr>
<tr><td>NSG should be used for subnets in a Virtual Network to permit traffic only on required inbound/outbound ports. NSGs should not have security rule to allow any-to-any traffic</td><td>Medium</td><td>Yes</td></tr>
<tr><td>All users/identities must be granted minimum required permissions using Role Based Access Control (RBAC)</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Presence of any virtual network gateways (GatewayType = VPN/ExpressRoute) in the Virtual Network must be justified</td><td>High</td><td>Yes</td></tr>
<tr><td>Use of any Virtual Network peerings should be justified</td><td>High</td><td>Yes</td></tr>
</table>
</body></html>
