4. Cisco routers and catalyst switch Configurations

4.1 Cisco routers and catalyst switch ports

Cisco routers and switches can be accessed for configuration using console ports (CON ports) with console cables and terminal emulation software on your computer.
Auxiliary (AUX) ports on routers were traditionally used for remote modem connections but are less common today.
Ethernet-based LAN ports are used to interconnect network devices like routers, switches, and end devices using Ethernet cables, with port speeds needing to match on both ends.
Cisco Catalyst switches have CON ports but typically no AUX ports, and end devices connect through LAN ports.

4.2 Cisco Internetwork Operating System (IOS)

Cisco IOS is the traditional operating system used on most Cisco routers and switches, with commands you'll use for configuration.
Cisco IOS XE is an evolved, more stable version that runs Cisco IOS on top of a Linux-based system, improving stability without changing the command interface.
Cisco NX-OS is used on Cisco Nexus data center switches, and Cisco IOS XR is for large service provider routers; these are different from Cisco IOS.

4.3 Basic Cisco IOS commands

Cisco IOS has different command modes: user mode (limited commands), privilege mode (more commands, entered with 'enable'), global configuration mode (for global changes, entered with 'configure terminal'), and interface configuration mode (for specific interface settings).
You can navigate between modes using commands like 'exit' and 'end', and use '?' to see available commands.
Basic configuration tasks include changing the router's hostname and enabling interfaces with the 'no shutdown' command.
The 'show version' command reveals the IOS version and license details.

4.4 Secure Cisco devices with passwords

Set a password for privileged mode using the enable secret command to protect access to advanced configuration.
Create local user accounts with usernames and passwords (using the username and secret commands) to control who can log in.
Configure the console port to require login authentication using the local user database with the login local command.
These steps add layers of security by requiring credentials both to access user mode and to escalate to privileged mode, helping prevent unauthorized or accidental changes.

4.5 Configure a router interface

You can configure a Cisco router interface's speed and duplex settings manually or set them to auto-negotiate to ensure proper communication.
To enable the interface, use the "no shutdown" command, and you can configure the IP address either statically or dynamically via DHCP.
It's important to save your running configuration to non-volatile memory (startup configuration) to retain changes after a reboot.
You can verify interface status and IP address assignments with commands like "show ip interface brief" and test connectivity using the "ping" command.

4.6 Work with configuration files

Changes made to a Cisco router or switch take effect immediately in the running configuration, but these changes are lost on reboot unless saved to the startup configuration stored in non-volatile memory (NVRAM).
It's important to regularly save your running configuration to the startup configuration using commands like copy running-config startup-config (often abbreviated as copy run start).
Backing up configurations to an external server, such as a TFTP server, provides an extra layer of protection in case of device failure or loss.
You can restore configurations from the external server back to the device, ensuring quick recovery.