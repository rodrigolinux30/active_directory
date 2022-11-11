# 01 - installing the Domain Controller


1. Use 'sconfig' in the Domain Controller to:
    - Change the hostname
    - Change the IP address to static
    - Change the DNS server to our own IP address

2. Install the Active Directory Windows Featuure

```Shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
```

3. Install Chocolatey
- This is a package manager for Windows. With the command choco you can for example install git from the powershell