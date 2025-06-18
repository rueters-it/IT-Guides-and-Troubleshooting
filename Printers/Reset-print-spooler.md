# Reset print spooler 

The Print Spooler service is the service that tells your computer to print. It is a software servcies that acts as a temporary storage area for print jobs before they are sent to the printer. It basically manages the printing processes, ensuring jobs are sent in the correct order and that the printer resources are available. <br />

Resetting the print spooler may resolving majority of common printing errors, such as: 
- Stuck print jobs in queue
- Print error messages related to spooler or printer connection
- Communication issues between your computer and the printer
- General printing problems not associated with a particular error

### To reset print spooler:
1. Search "Run" in the Windows search bar. (Alternatively, you can press `Windows key` + `R` as the keyboard shortcut.)
2. The **Run dialog box** should have popped up.
3. In that dialog box, type `services.msc`, then press `Enter`.
4. The **Services windows** will open. In the list, scroll until you find "Print Spooler" and double-click on it. (Note: This service should be always be running and startup type is set to Automatic)
5. To reset the Print Spooler, simply press **Stop** then **Start** again.
6. Print spooler has been reset, attempt to process a print and see if the issue is resolved.
7. If this did not resolve the issue, contact IT.
 
![image](https://github.com/user-attachments/assets/70223d08-d43e-4122-85c4-72596ed9777f)

### Respources
1. [What is spooler service and how do I access it?](https://answers.microsoft.com/en-us/windows/forum/all/what-is-spooler-service-and-how-do-i-access-it/ccc1ddab-76d4-4a99-ac62-629cc89fe396)
