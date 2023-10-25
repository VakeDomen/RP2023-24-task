
# Backup Script (ENG)

## Objective:
- Write a Bash script that backs up a specified directory into a zip file and moves the zip file to a backup directory.

## Requirements:

### Script Input:
- The script should accept one argument: the path to the source directory you want to back up. If no argument is given, the script should default to backing up the current directory (".").

### Destination Directory:
- All backups should be saved in the ~/backups directory. (manually create the folder)

### Backup Filename:
- The backup should be a zip file named in the format YYYY-MM-DD-backup.zip, where YYYY-MM-DD is the current date.

### Error Handling:
- If the zipping process fails, print the message "Failed to zip..." and exit with a status code of 1.
- If the move process fails, print the message "Failed to move the backup file" and exit with a status code of 1.

### Notifications:
- If no source directory argument is provided, the script should notify the user with the message: "Current directory set as the backup directory."

### Script Structure:
- Use variables for the source directory, destination directory, and zip filename. Implement error checks after the zipping and moving processes.