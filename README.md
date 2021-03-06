# Restart-WiFi-Adapter
Restart your WiFi adapter automatically after your Windows 8.1 or Windows 10 machine resumes from sleep.

I wrote this because I bought a Surface Pro 3 and my WiFi wouldn't reconnect on resumption from sleep/hibernate, even after trying multiple fixes and updates. If you're having similar issues then maybe it will help you.

Just right-click on `install.bat` and *Run as administrator*. It will be imported as a Windows Scheduled Task and should work on any Windows 8.1 or Windows 10 machine.

Full instructions here: https://tomssl.com/2015/01/15/fix-the-wifi-on-your-surface-pro-3

**NOTE:** Do read the blog post. It has some advice about what to do if the fix doesn't work initially. e.g. On some machines the WiFi adapter may be named differently, requiring you to edit `RestartWiFiAdapter.xml` prior to running the install.
