# Get-GPO-Backup-and-Reports
Get GPO Backup and Reports

Creates a Backup and HTML and XML Reports for all Group Policies in the current Active Directory domain. Version 1.20 allows you to restrict the processing to a specific OU tree.

This script requires at least PowerShell version 3 but runs best in version 5.

This script requires at least one domain controller running Windows Server 2008 R2.

This script outputs Text, XML and HTML files.

You do NOT have to run this script on a domain controller, and it is best if you didn't.

This script was developed and run from a Windows 10 domain-joined VM.

This script requires Domain Admin rights and an elevated PowerShell session.

To run the script from a workstation, RSAT is required.

Remote Server Administration Tools for Windows 7 with Service Pack 1 (SP1)
http://www.microsoft.com/en-us/download/details.aspx?id=7887

Remote Server Administration Tools for Windows 8
http://www.microsoft.com/en-us/download/details.aspx?id=28972

Remote Server Administration Tools for Windows 8.1
http://www.microsoft.com/en-us/download/details.aspx?id=39296

Remote Server Administration Tools for Windows 10
http://www.microsoft.com/en-us/download/details.aspx?id=45520
