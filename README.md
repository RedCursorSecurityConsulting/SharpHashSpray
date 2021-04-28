# SharpHashSpray
SharpHashSpray will automatically fetch a list of all domain joined hosts and check for local admin access, in parallel, using the provided username and NTLM hash. The tool does not require any elevated or special privileges but must be executed within the context of a domain user.

# Example Usage
`SharpHashSpray.exe Administrator 64F12CDDAA88057E06A81B54E73B949B`

# Thanks
99% of the code is from https://github.com/checkymander/Sharp-SMBExec which in turn is from https://github.com/Kevin-Robertson/Invoke-TheHash. Go thank these people.
