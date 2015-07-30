Made this for friends and family who want to upgrade to Windows 10 securely & comfortably.

W10 Upgrade log by Simon Ho:


Make sure enough space.
Change Data (100 MB if there) to some drive letter, like Y:
UAC on.

Start W10 upg.

Check Wi-fi.  Settings > Net > Wifi > Manage settings.
Check update torrent off.
Check resolution sizing & taskbar sizing.
Host file:  http://winhelp2002.mvps.org/hosts.txt for ads.
Powershell: Get-AppxPackage *xbox* | Remove-AppxPackage
Disable Telemetry:
	echo. &gt;%programdata%\Microsoft\Diagnosis\ETLLogs\AutoLogger\AutoLogger-Diagtrack-Listener.etl 

cacls.exe "%programdata%\Microsoft\Diagnosis\ETLLogs\AutoLogger\AutoLogger-Diagtrack-Listener.etl" /d SYSTEM

Optional:
Check Edge settings.
Configure Cortana.

Create system restore point.
Remove old windows.

Personalization:
3rd party thumbnail preview resizer for taskbar.
Winaero for customization.
Regedit Old volume meter: http://winaero.com/blog/enable-old-volume-control-in-windows-10/

Updated Displayfusion to version 7.2 for W10 support. (For multi-monitor setups.)

System restore point when done.

YET to do:
3rd party details pane mod to put details on the bottom of window instead of on the side.  (Currently out for 8.1, do NOT use this version on W10 - will cause blue screens & will need to system restore.)

Wait for Winaero update to fix the highlighting of title bars of windows on secondary monitor(s) when they're not in focus.
