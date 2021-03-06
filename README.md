# SharpHashSpray
Check for local admin access using the provided username and NTLM hash. 

By default SharpHashSpray will automatically fetch a list of all domain joined hosts to check. The tool must be executed within the context of a domain user for this to work.

Alternatively a target range can be provided in CIDR notation (e.g. 192.168.100.0/24) or in the format 192.168.0-255.0-255.

SharpHashSpray does not require admin or any special privileges.

# Example Usage
```
SharpHashSpray.exe Administrator 64F12CDDAA88057E06A81B54E73B949B
SharpHashSpray.exe Administrator 64F12CDDAA88057E06A81B54E73B949B 192.168.1.0/24
```

# Thanks
99% of the code is from https://github.com/checkymander/Sharp-SMBExec which in turn is from https://github.com/Kevin-Robertson/Invoke-TheHash. Go thank these people.
