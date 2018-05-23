# Windows
## Check for patches
`wmic qfe list full /format:csv > Updates.html`


If the Windows 7 bug hits you with "Invalid XSL format (or) file name." use the XSL files directly: 

`wmic qfe list full /format:"%WINDIR%\system32\wbem\en-us\csv" > patches.csv`

### Automate with Windows Exploit Suggestor
Find it [here](https://github.com/GDSSecurity/Windows-Exploit-Suggester). 

# Services
Simple one-line services
## Python Web-Server
python -m SimpleHTTPServer 8000

## Python Upload form
https://github.com/stackp/Droopy

## Quick pastebin
TODO: still looking for a quick way to upload files to my attacking-server
