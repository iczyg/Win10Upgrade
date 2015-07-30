W10 Upgrade log:

Make sure enough space.
Change Data (100 MB if there) to some drive letter, like Y:
UAC on.

Start W10 upg.

Check Wi-fi.  Settings > Net > Wifi > Manage settings.
Check update torrent off.
Check resolution sizing & taskbar sizing.
Check Edge settings.
Host file:  http://winhelp2002.mvps.org/hosts.txt for ads.
Powershell: Get-AppxPackage *xbox* | Remove-AppxPackage
Disable Telemetry:
	echo. &gt;%programdata%\Microsoft\Diagnosis\ETLLogs\AutoLogger\AutoLogger-Diagtrack-Listener.etl 

cacls.exe "%programdata%\Microsoft\Diagnosis\ETLLogs\AutoLogger\AutoLogger-Diagtrack-Listener.etl" /d SYSTEM


Create system restore point.
Remove old windows.

Personalization:
3rd party thumbnail preview resizer for taskbar.
Winaero for customization.
Regedit Old volume meter: http://winaero.com/blog/enable-old-volume-control-in-windows-10/

System restore point when done.