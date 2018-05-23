# Windows
## Check for patches
`wmic qfe list full /format:csv > Updates.html`


If the Windows 7 bug hits you with "Invalid XSL format (or) file name." use the XSL files directly: 

`wmic qfe list full /format:"%WINDIR%\system32\wbem\en-us\csv" > patches.csv`
