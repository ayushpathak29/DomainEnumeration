# DomainEnumeration

## Enumeration with Powerview
Powerview[https://github.com/PowerShellMafia/PowerSploit/blob/dev/Recon/PowerView.ps1] is a Powershell script, which is used for enumerating a domain after you have already gained a shell in the system. Now download the powerview.ps1 script in windows machine, and import it.

Get current Domain
![](images/3.png)

Get domain SID for the current domain
![](images/4.png)

Get domain controllers for current domain
![](images/6.png)

Get domain policy for the current domain
![](images/5.png)

Get a list of users in the current domain
![](images/7.png)

![](images/8.png)

Get list of all properties for users in the current domain
![](images/9.png)

![](images/10.png)

Search for a particular string in a user's attribute
![](images/14.png)

Get a list of computers in the current domain
![](images/11.png)

Get all the groups in the current domain
![](images/13.png)

List all local groups in machine
![](images/15.png)

Find shares on hosts in current domain.
![](images/16.png)

Find sesitive files on computers in current domain
``Invoke-FileFinder -Verbose``

Get all filservers of the domain
``Get-NetFileServer``

Get list of GPO in current domain
![](images/17.png)

Get OUs in a domain
![](images/18.png)

![](images/19.png)

Get details about the current forest
![](images/20.png)

Get all domains in the current forest
![](images/21.png)

Get all global catalogs for the current forest
![](images/22.png)

Find all machines on the current domain where the current user has local admin access
![](images/24.png)

Find local admins on all machines of the domain.
![](images/25.png)

Find computers where a domain admin has sessions
![](images/26.png)

To confirm admins access
![](images/27.png)

**AD Module**

Get current Domain
![](images/01.png)

Get domain SID for the current domain
![](images/02.png)

Get domain controllers for current domain
![](images/03.png)

Get a list of users in the current domain
![](images/04.png)

Get list of all properties for users in the current domain
![](images/05.png)

Get a list of computers in the current domain
![](images/07.png)

Get all the groups in the current domain
![](images/06.png)

Get list of GPO in current domain
![](images/08.png)

Get details about the current forest
![](images/09.png)

Get all domains in the current forest
![](images/010.png)

Get all global catalogs for the current forest
![](images/23.png)

