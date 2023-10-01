# Table of contents

* [Introduction](README.md)
* [News](news/README.md)
  * [v1.0.0 Release!](news/v1.0.0-release.md)
* [Changelog](changelog.md)

## Getting Started

* [Installation](getting-started/installation/README.md)
  * [🐧 Installation for Unix](getting-started/installation/installation-on-unix.md)
  * [🪟 Installation for Windows](getting-started/installation/installation-on-windows.md)
* [Selecting & Using a Protocol](getting-started/selecting-and-using-a-protocol.md)
* [Target Formats](getting-started/target-formats.md)
* [Using Credentials](getting-started/using-credentials.md)
* [Using Kerberos](getting-started/using-kerberos.md)
* [Using Modules](getting-started/using-modules.md)
* [Database General Usage](getting-started/database-general-usage.md)
* [BloodHound Integration](getting-started/bloodhound-integration.md)
* [Audit Mode](getting-started/audit-mode.md)
* [Ignore OpSec Warnings](getting-started/ignore-opsec-warnings.md)
* [Logging](getting-started/log-your-results.md)

## SMB protocol

* [Scan for Vulnerabilities](smb-protocol/scan-for-vulnerabilities.md)
* [Enumeration](smb-protocol/enumeration/README.md)
  * [Enumerate Hosts](smb-protocol/enumeration/untitled.md)
  * [Enumerate Null Sessions](smb-protocol/enumeration/enumerate-null-sessions.md)
  * [Enumerate Anonymous Logon](smb-protocol/enumeration/enumerate-anonymous-logon.md)
  * [Enumerate Hosts with SMB Signing Not Required](smb-protocol/enumeration/smb-signing-not-required.md)
  * [Enumerate Active Sessions](smb-protocol/enumeration/enumerate-active-sessions.md)
  * [Enumerate Shares and Access](smb-protocol/enumeration/enumerate-shares-and-access.md)
  * [Enumerate Disks](smb-protocol/enumeration/enumerate-disks.md)
  * [Enumerate Logged on Users](smb-protocol/enumeration/enumerate-logged-on-users.md)
  * [Enumerate Domain Users](smb-protocol/enumeration/enumerate-domain-users.md)
  * [Enumerate Users by Bruteforcing RID](smb-protocol/enumeration/enumerate-users-by-bruteforcing-rid.md)
  * [Enumerate Domain Groups](smb-protocol/enumeration/enumerate-domain-groups.md)
  * [Enumerate Local Groups](smb-protocol/enumeration/enumerate-local-groups.md)
  * [Enumerate Domain Password Policy](smb-protocol/enumeration/enumerate-domain-password-policy-1.md)
  * [🆕 Enumerate Anti-Virus & EDR](smb-protocol/enumeration/enumerate-antivirus-edr.md)
* [Password Spraying](smb-protocol/password-spraying.md)
* [Authentication](smb-protocol/authentication/README.md)
  * [Checking Credentials (Domain)](smb-protocol/authentication/checking-credentials-domain.md)
  * [Checking Credentials (Local)](smb-protocol/authentication/checking-credentials-local.md)
* [Command Execution](smb-protocol/command-execution/README.md)
  * [Executing Remote Commands](smb-protocol/command-execution/execute-remote-command.md)
  * [Getting Shells 101](smb-protocol/command-execution/getting-shells-101.md)
* [Spidering Shares](smb-protocol/spidering-shares.md)
* [Get and Put Files](smb-protocol/get-and-put-files.md)
* [Obtaining Credentials](smb-protocol/obtaining-credentials/README.md)
  * [Dump SAM](smb-protocol/obtaining-credentials/dump-sam.md)
  * [Dump LSA](smb-protocol/obtaining-credentials/dump-lsa.md)
  * [Dump NTDS.dit](smb-protocol/obtaining-credentials/dump-ntds.dit.md)
  * [Dump LSASS](smb-protocol/obtaining-credentials/dump-lsass.md)
  * [Dump WIFI password](smb-protocol/obtaining-credentials/dump-wifi-password.md)
  * [Dump KeePass](smb-protocol/obtaining-credentials/dump-keepass.md)
  * [Dump DPAPI](smb-protocol/obtaining-credentials/dump-dpapi.md)
* [Defeating LAPS](smb-protocol/defeating-laps.md)
* [Checking for Spooler & WebDav](smb-protocol/spooler-webdav-running.md)
* [Steal Microsoft Teams Cookies](smb-protocol/steal-microsoft-teams-cookies.md)

## LDAP protocol

* [Authentication](ldap-protocol/authentication.md)
* [ASREPRoast](ldap-protocol/asreproast.md)
* [Find domain SID](ldap-protocol/find-domain-sid.md)
* [Kerberoasting](ldap-protocol/kerberoasting.md)
* [Unconstrained Delegation](ldap-protocol/unconstrained-delegation.md)
* [Admin Count](ldap-protocol/admin-count.md)
* [Machine Account Quota](ldap-protocol/machine-account-quota.md)
* [Get User Descriptions](ldap-protocol/get-user-descriptions.md)
* [Dump gMSA](ldap-protocol/dump-gmsa.md)
* [Exploit ESC8 (ADCS)](ldap-protocol/exploit-esc8-adcs.md)
* [Extract Subnet](ldap-protocol/extract-subnet.md)
* [Check LDAP Signing](ldap-protocol/check-ldap-signing.md)
* [Read DACL Rights](ldap-protocol/read-dacl-right.md)
* [Extract gMSA Secrets](ldap-protocol/extract-gmsa-secrets.md)
* [Bloodhound Ingestor](ldap-protocol/bloodhound-ingestor.md)
* [List DC IP](ldap-protocol/list-dc-ip.md)
* [Enumerate Domain Trusts](ldap-protocol/enumerate-trusts.md)

## WINRM protocol

* [Password Spraying](winrm-protocol/password-spraying.md)
* [Authentication](winrm-protocol/authentication.md)
* [Command Execution](winrm-protocol/command-execution.md)
* [Defeating LAPS](winrm-protocol/defeating-laps.md)

## MSSQL protocol

* [Password Spraying](mssql-protocol/untitled.md)
* [Authentication](mssql-protocol/authentication.md)
* [MSSQL PrivEsc](mssql-protocol/mssql-privesc.md)
* [MSSQL Command Execution](mssql-protocol/mssql-command.md)
* [MSSQL Upload & Download](mssql-protocol/mssql-upload-download.md)
* [Execute via xp\_cmdshell](mssql-protocol/windows-command.md)

## SSH protocol

* [Password Spraying](ssh-protocol/password-spraying.md)
* [Authentication](ssh-protocol/untitled.md)
* [Command Execution](ssh-protocol/command-execution.md)

## FTP protocol

* [Password Spraying](ftp-protocol/password-spraying.md)
* [File Listing, etc](ftp-protocol/file-listing-etc.md)

## RDP Protocol

* [Password Spraying](rdp-protocol/password-spraying.md)
* [Screenshot (connected)](rdp-protocol/screenshot-connected.md)
* [Screenshot Without NLA (not connected)](rdp-protocol/screenshot-without-nla-not-connected.md)

## WMI Protocol

* [Password Spraying](wmi-protocol/password-spraying.md)
* [Authentication](wmi-protocol/authentication.md)
* [Command Execution](wmi-protocol/command-execution.md)