This Bash script is designed to enhance the security of a Raspberry Pi system. Here's a breakdown of what it does:

1- Updates and upgrades the system packages to ensure they are up to date.
2-Installs and configures the Uncomplicated Firewall (ufw), setting default policies to deny incoming traffic 
and allow outgoing traffic. It allows SSH access (port 22) while blocking VNC port 5900 to enhance security.
3- Configures SSH to use key-based authentication and disables root login for improved security.
4- Updates the Raspberry Pi firmware to the latest version using rpi-update.
5- Prompts the user to change the default user password for additional security.

This script is useful for securing Raspberry Pi devices, especially when they are exposed to the internet or 
connected to insecure networks. It helps protect against unauthorized access and potential security threats.

Instructions for Use:
1- Copy the script to your Raspberry Pi device.
2- Make the script executable using the command: chmod +x script_name.sh.
3- Execute the script using: ./script_name.sh.
4- Follow the prompts and input any required information, such as the new user password.
Ensure that you have sudo privileges to execute the script, as it performs system-level operations that require
elevated permissions. Additionally, review and customize the script as needed to fit your specific security
requirements and environment.
