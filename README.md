 #Automated Linux Backup & Archiving Script
 
 Robust Python script for automated Linux backups, ensuring critical data protection and integrity, with streamlined disaster recovery for enterprise environments.

Project Description
This project provides a robust and automated solution for Linux system administration, focusing on efficient file backup and archiving. The core of this project is a Python script designed to manage data integrity and optimize disk usage. By integrating with crontab, the script automates recurring backup tasks and ensures the timely cleanup of old archives, making it a valuable tool for maintaining a healthy and organized IT environment.

Key Features
Automated Backup: Automatically backs up specified files and directories on a scheduled basis.

Intelligent Archiving: Creates compressed archives of your data to save disk space.

Disk Usage Optimization: Automatically deletes old backup files (after 60 days) to prevent disk space from being consumed unnecessarily.

CRON Integration: Utilizes crontab -e to schedule and automate tasks, demonstrating proficiency in Linux command-line tools.

Customizable: The script can be easily modified to back up different directories and adjust the retention period based on specific needs.

Technologies Used
Python: The core scripting language used for the backup and archiving logic.

Linux/UNIX Environment: The operating system on which the script is designed to run.

Crontab: A command-line utility used to schedule and automate recurring tasks.

Instructions: How to Use the Script
Clone the Repository:

Bash

git clone [your-repository-url]
Navigate to the Project Directory:

Bash

cd [your-project-directory]
Run the Script Manually (Optional):

Bash

python your_script_name.py
Schedule the Backup with Crontab:

Open your crontab file in the editor:

Bash

crontab -e
Add a new line to schedule your backup (e.g., to run every day at 2 AM):

0 2 * * * python /path/to/your_script_name.py
(Note: Remember to replace /path/to/your_script_name.py with the actual path to your script.)
