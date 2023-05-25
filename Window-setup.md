# Microsoft Windows 10 set up short processes without any pendrive:
*******************************************************************
# Steps:
********
1. Windows file download (Have to remind windows download file selector).

2. WinRar file download > somthing permission allow.

3. Windows file > mouse right button click > properties > extract to > drive select > C/D/E/F.

4. Setting > update & security > recovery > restart.

5. Troubleshoot > advanced option > command prompt > desktopName select > continue.

6. CMD > keyboard command: 
	:/driveName>diskpart
	:/driveName>list volume
	:/driveName>exit
	:/driveName>drive select (whereas have windows file downloaded)
	:/driveName>dir
	:/driveName>setup.exe

7. Somthing normal setting (permission, allow, next).

# Finally, there is more normal setting/command in their windows setup process that we know. Like as: (next, select, ok, allow, permission, use of mouse etc).