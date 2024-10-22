# Simple_System_Updater
This is a simple Bash script designed to perform system updates on Linux distributions based on either Arch or Debian (including Ubuntu and Parrot OS). It automatically detects the operating system and runs the appropriate update commands for the respective platform.

Features:
Detects the Linux distribution based on /etc/os-release.
If the OS is Arch-based, it uses pacman to update the system.
If the OS is Debian-based (such as Parrot Security or Ubuntu), it uses apt to perform the update and upgrade.
Logs all output to a specified log file.
Errors are captured and logged in a separate error log file.
