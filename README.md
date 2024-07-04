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


# SORDUM BASIC APPS

[WINDOWS UPDATE BLOCKER](https://www.sordum.org/downloads/?st-windows-update-blocker)

[DNS PROBLEM SOLVER](https://www.sordum.org/downloads/?dns-angel)

[EASY CONTEXT MENU](https://www.sordum.org/downloads/?easy-context-menu)


# J2534 SCANNER DRIVERS

[AUTEL DEVICES](https://autel.com/us/software-downloads/) 

[CARDAQ DEVICES](https://www.opusivs.com/support/product-downloads/)

[BOSCH MASTERTECH 2](https://www.boschdiagnostics.com/software-updates/mastertech-ii-vci-firmware)

[FORD VCM3](https://www.fordtechservice.dealerconnection.com/Rotunda/MCSIDSDownloadSoftware) OR [FORD VCM3](https://www.maverickdiagnostics.com/ford-dealer-diagnostic-software-updates/)

[SCANMATIK 2](https://scanmatik.pro/pages/downloads)

[TOPDON RLINK LITE](https://www.topdon.com/pages/pro-down.html?fuzzy=RLink%20Lite)
