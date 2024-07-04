# AIO_J2534Laptop
This GitHub page is for automotive diagnostic laptop build.


# Install Chocolatey Installer & APPS
https://chocolatey.org/install

1. Open powershell.exe with admin rights

```
Set-ExecutionPolicy AllSigned
```
```
Set-ExecutionPolicy Bypass -Scope Process
```
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
2. Keep Choco up-to-date
```
choco upgrade chocolatey
````

3.Install Basic software using Chocolately

```
choco install -y 7zip choco install microsoft-edge notepadplusplus.install correttojdk netfx-4.8 dotnet4.7
```
