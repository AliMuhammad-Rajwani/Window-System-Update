# Window-System-Update

### Windows System Update Script

**Description:**

This batch script is designed to automate the process of updating a Windows system using PowerShell. It ensures that the necessary PowerShell module `PSWindowsUpdate` is installed and then checks for and installs any available updates. The script logs all activities, providing a detailed report of the update process.

**Features:**
- **Automated Module Installation**: Checks if the `PSWindowsUpdate` module is installed and installs it if necessary.
- **Logging**: Creates a log file (`system_update.log`) to record the update process, including timestamps for each step.
- **Transcript Logging**: Uses PowerShell's transcript feature to capture detailed command output during the update process.
- **User-Friendly**: Displays the log file contents at the end of the update process for easy review.
- **Automatic Reboot**: The update process accepts all updates and will automatically reboot the system if necessary.

**Steps Performed by the Script:**
1. **Log Initialization**: Creates a log file and logs the start time.
2. **Module Check and Installation**: Verifies if `PSWindowsUpdate` is installed; installs it if it is not.
3. **Module Import**: Imports the `PSWindowsUpdate` module.
4. **Update Check**: Checks for available updates and initiates the update process.
5. **Log Completion**: Logs the completion time and displays the log file content to the user.

**Usage:**
1. Save the script as a `.bat` file.
2. Run the script with administrative privileges to ensure it has the necessary permissions to install updates and reboot the system.

