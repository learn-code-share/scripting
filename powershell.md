# PowerShell Scriping

Windows Service:
```
// Install
New-Service -Name "YourServiceName" -BinaryPathName <yourproject>.exe

// Uninstall
Remove-Service -Name "YourServiceName"
```

MSI:
```
Start-Process <MSI file location>
```
