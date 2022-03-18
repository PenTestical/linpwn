# LINPWN COLLECTION

Collection of useful Linux privilege escalation exploits in 2022, which worked like a charm during pentest engagements.

## PwnKit: Local Privilege Escalation Vulnerability Discovered in polkit’s pkexec (CVE-2021-4034)

Polkit (formerly PolicyKit) is a component for controlling system-wide privileges in Unix-like operating systems. It provides an organized way for non-privileged processes to communicate with privileged processes. It is also possible to use polkit to execute commands with elevated privileges using the command pkexec followed by the command intended to be executed (with root permission). 

How to use:

```
./PwnKit
```

``` 
# whoami
root
``` 

