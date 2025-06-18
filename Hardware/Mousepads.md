# Troubleshoot: Mouspad Unfunctional
A touchpad not working after a Windows update is a common issue, often due to driver problems. To fix this, try updating or reinstalling the touchpad drivers through Device Manager. If that doesn't work, consider rolling back the Windows update or checking for hardware issues.  

## Check mousepad settings: 
Check mousepad settings in Windows to ensure it's enabled and sensitivity is adjusted.
1. Go to **Settings** > **Bluetooh & Devices** > **Touchpad**
   ![image](https://github.com/user-attachments/assets/3899dc5d-753a-4c40-9719-aab39612b723)

3. Ensure the touchpad is enabled and adjust sensitivity or gestures if needed
   ![image](https://github.com/user-attachments/assets/5babe5e3-55d0-4249-b33f-8943ecde54f8)


## Update touchpad drivers: 
1. Right-click the Start button and navigate to **Device Manager**
2. Expand "Mice and other pointing devices" or "Human Interface Devices"
3. Locate the appropriate mouse driver for the touchpad, right-click on it > "Update driver"
   ![image](https://github.com/user-attachments/assets/3b494fd5-b9d5-484a-95e4-3db9a1ed12cf)

## Uninstall touchpad drivers:
1. If updating doesn't help, try uninstalling the driver and restarting your computer to allow Windows to reinstall it automatically.
2. Follow the same steps for "Update touchpad drivers" (above) > Uninstall device
3. Restart the device
   
   ![image](https://github.com/user-attachments/assets/7f6afccf-7680-4bc2-8cf7-de7a5a8b6797)

## Roll back drivers:
1. If the issue started after a specific update, try rolling back to the previous driver version
2. To do this, go to **Device Manager** (right-click the Start button click on it) and right-click on the touchpad and select "Properties"

  ![image](https://github.com/user-attachments/assets/985d0467-492f-406c-8dac-9c7697159415)

3. Go to the Driver tab and click "Roll Back Driver"

   ![image](https://github.com/user-attachments/assets/3966f827-5050-4b12-bdbb-fe6f2a43dd64)

5. If the option is available, click on it to run.

## Consider a system restore: (Consult with IT)
1. If the problem persists, you can try a system restore point before the update
2. To do this, search "Create a restore point" in the Windows search bar and click to open
3. In the pop-up menu, click "System Restore" and click Next
   
   ![image](https://github.com/user-attachments/assets/b66b6552-898b-4fb5-a278-b8424b20224b)

5. In the system restore settings, click Next and select a restore point you want to use (a point that is before the issue occurred)
   ![image](https://github.com/user-attachments/assets/c2bb07c1-d919-4b2c-b65e-6e396adc3b16)

7. If you don't see the one you're looking for, check the "Show more restore points" box.
8. Click Next after selecting a restore point, confirm, then Finish
9. Select Yes to start the restoration process

**Note:** Your device will restart and revert to the chosen restore point. This process may take some time, so ensure your device is connected to a power source. After the restart, your system will be restored to the selected point. This only reverts system files and settings, not your personal files. 
 

## Check for third-pary software conflicts: 
1. Sometimes, newly installed software can interfere with the touchpad.
2. Try disabling or uninstalling recently installed software to see if it resolves the issue.

## Use an external mouse: 
1. If you have an external mouse, connect it to your laptop to see if it works.
2. This can help determine if the problem is isolated to the touchpad itself.

## Resources
1. [Fix touchpad problems in Windows](https://support.microsoft.com/en-us/windows/fix-touchpad-problems-in-windows-30b498e5-0caa-9740-2b21-336ea75ee756)
2. [How to Fix Laptop's Touchpad Not Working Windows 10/11](https://youtu.be/jA4WmVv-p78?si=oxQ8sX8MvyT4C_fC)
