<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"  "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>

</head><body>
<H2>RedisCache</H2>
<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Description</th><th>ControlSeverity</th><th>Automated</th></tr>
<tr><td>All users/identities must be granted minimum required permissions using Role Based Access Control (RBAC)</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Diagnostics logs must be enabled with a retention period of at least 365 days.</td><td>Medium</td><td>No</td></tr>
<tr><td>Configure Redis Cache firewall settings for additional protection</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Redis Data Persistence should be enabled to back up Redis Cache data</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Non-SSL port must not be enabled</td><td>High</td><td>Yes</td></tr>
<tr><td>Access keys must be rotated periodically</td><td>Medium</td><td>No</td></tr>
<tr><td>Do not share cache instances across applications</td><td>High</td><td>No</td></tr>
<tr><td>Redis Cache instance should be confined within a virtual network for domain-joined scenarios</td><td>Medium</td><td>No</td></tr>
</table>
</body></html>
