- Open VitaShell (File Manager in VitaDeploy)
- hold LEFT on the DPAD and press Circle
- Scan the QR Code

(If your asked to visit the URL press NO and try again untill you get the message saying to INSTALL)

* Files downloaded will be in UX0:Downloads


![Screenshot](https://github.com/AntHJ/Quick-Remounter/blob/main/Quick%20ReMounter.png)

----------

# Quick-Remounter
* Utilises Lua Player Plus Vita (lpp-vita). [Learn more.](https://github.com/Rinnegatamante/lpp-vita)
#
![Screenshot](https://github.com/AntHJ/Quick-Remounter/blob/main/App-Page.png)
#
## What is this app for?

- The main reason for creating this app was to give you a quick and easy way to remove the YAMT plugin and replace it with the StorageMGR
plugin.

- Another reason for this app was to be a simple storage to UX0 mount tool.

## Why remove/replace YAMT?

If your system is booting your SD/USB with no issues then there is no real reason to remove/replace YAMT with StorageMGR. BUT its know that
there are some systems, USBs and SDs that for some reason are NOT fully compatible with the YAMT plugin and its recommended you replace it
with StorageMGR. 

Noticable symptoms of issues are.. 
- System not seeing your storage at all
- SD/USB Storage doesnt always boot properly
- system randomly crashes after coming out of sleep/standby (this can sometimes be fixed with the FD_Fix plugin)

## Will i loose any apps/games?

This app will not delete any apps or games or format your device so if for some reason you find your apps/games have vanished then there are
several reasons why this may have happened. 

    1. Did you select the correct storage device ?
    2. Are you spoofed to the latest firmware version
    3. Try deleting the ID.DAT on the root of the selected storage
    4. Is your SD card genuine
    5. Was it properly format/setup with data
    6. Is the adaptor/cable/device faulty
    7. Do you have the required plugins such as 0syscall6, NoNpDrm, NoPsmDrm
    -. plus possibly other factors
    
##
##
## What do i do?
After installing the tool just run it and if you have the YAMT plugin you will see this notice

![Screenshot](https://github.com/AntHJ/Quick-Remounter/blob/main/YAMT.png)

##
##
After selecting to continue you will be asked which storage device you would like to set as the primary UX0 / Boot

![Screenshot](https://github.com/AntHJ/Quick-Remounter/blob/main/Options.png)

Select whichever you will be using (usually X - SD2VITA) and the tool will then remove YAMT (if found) and install StorageMGR the system will then reboot.

- If you are swapping from YAMT to StorageMGR you wont see a difference other than YAMT will no longer be in the device settings
- If your remounting your storage from a previous setup then you should see the database rebuild window

##
##
If you need to manually change your storage allocations then you can use Autoplugin2 (Vita plugins, SD2Vita setup)
