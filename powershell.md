# PowerShell Scriping

Windows Service:
```
installutil <yourproject>.exe // Install
installutil /u <yourproject>.exe // uninstall

sc.exe delete "<name>" // uninstall

// Install
New-Service -Name "YourServiceName" -BinaryPathName <yourproject>.exe
// Uninstall
Remove-Service -Name "YourServiceName"
```

MSI:
```
Start-Process <MSI file location>
```
