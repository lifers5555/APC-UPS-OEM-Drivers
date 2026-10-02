USB based APC UPSs install into Windows with a Microsoft HID UPS driver. Some APC UPSs have quirks on their USB interface that leads Windows to believe that it's lost communication with the UPS and/or the UPS is offline, which causes to enact the critical event setting in Windows Power Settings.

This is a copy of the APC by Schneider Electric drivers, extracted from PowerChute, that can be loaded into Device Manager manually to (hopefully) fix the random shutdown issue, without installing PowerChute.

PowerChute Serial Shutdown Windows for Back-UPS, Smart-UPS and Easy UPS Online (x64) version 1.6
for Windows 10, Windows 11, Server 2022, Server 2025
https://www.se.com/au/en/product/SFPCSS/powerchute-serial-shutdown-unattended-graceful-shutdown-ups-monitoring-configuration-energy-management/
