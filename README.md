# IIS---Perfect-Forward-Secrecy-and-TLS-1.2

I am not the original author of this PowerShell script. 

You can find the original post here - https://www.hass.de/content/setup-your-iis-ssl-perfect-forward-secrecy-and-tls-12

I will work on updating this if I see any updates from the original author or come across any tweaking myself.

### PowerShell Tips

* If you get the error for unsigned scripts then do the following:
```powershell
Get-ExecutionPolicy -List
Set-ExecutionPolicy -ExecutionPolicy Unrestricted
```
**note: set your policy back to Restricted unless you already have an existing policy in place**
