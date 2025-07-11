# Stuck Print Job

<img width="689" height="323" alt="image" src="https://github.com/user-attachments/assets/de26e2b4-b774-4397-bcdd-1930ab2d7fe1" />


To resolve a stuck print job, start by stopping the Print Spooler service, then delete the files in the spooler's printer directory, and finally restart the Spooler service and the printer. If the issue persists, consider updating the printer driver, checking the printer's connection, or potentially reinstalling the printer. 

## Troubleshoot  
1. Stop the Print Spooler:
   - Open the Services application (search for "services.msc").
   - Locate the "Print Spooler" service, right-click, and select "Stop".
     <img width="598" height="487" alt="image" src="https://github.com/user-attachments/assets/f00655f7-479c-48f6-bea6-92cb18a350bf" />


2. Delete Stuck Print Jobs:
   - Open File Explorer and navigate to: C:\Windows\System32\spool\PRINTERS.
   - Delete all files in this folder. 

3. Restart the Print Spooler:
   - Return to the Services application.
   - Right-click on "Print Spooler" and select "Start". 

4. Power Cycle the Printer:
   - Turn off the printer and unplug it from the power outlet.
   - Wait for 30 seconds, plug it back in, and turn it on. 

5. Check for Other Issues:
   - If the problem continues, verify the printer's connection (USB or wireless).
   - Ensure the printer drivers are up to date.
   - Consider uninstalling and reinstalling the printer.
   - If using a network printer, check the printer's IP address and network settings. 
