Linux From Scratch (LFS)

Brief Overview:
- This project is a custom-built Linux From Scratch (LFS) system to understand how operating systems work at a low level. The system is 
  lightweight, functional, and includes a web-based terminal browser, links, for internet browsing.

Key Features:
- Fully custom-built Linux operating system.
- Lightweight design with idle RAM usage around 70-80 MiB.
- Includes links, a web-based terminal browser for internet access.
- Can perform most tasks of a typical Linux system.

Technologies Used:
- Linux From Scratch book and guidelines.
- Custom kernel and bootloader configuration.
- Links web browser for terminal-based browsing.

My Role:
- I handled every step of the build process, from compiling the kernel to configuring essential utilities, and resolved issues independently 
  through research and troubleshooting.

Challenges Solved:
- Debugged and resolved issues while building the kernel and bootloader to ensure successful booting.
- Overcame minor hurdles during system configuration by researching online and troubleshooting effectively.

How to Run the LFS System:
1] Download the zip file:
   - Clone the repo into your system.

2] Extract the Files:
   - Use any zip extraction tool to extract zip file.

3] Create a New Virtual Machine in VirtualBox:

4] Open VirtualBox:
   - Click on New to create a new virtual machine.
   - Name your VM (e.g., "Linux From Scratch"), select Linux as the type, and choose the appropriate version (e.g., "Other Linux (64-bit)").
   - Assign at least 512 MB of RAM (or more, depending on your system resources).
   - When prompted for a virtual hard disk, choose Use an existing virtual hard disk file, browse to the extracted .vdi file, and select it.

5] Adjust VM Settings (Optional):
   - Go to Settings > System, and ensure "Enable EFI (Special OSes only)" is unchecked.
   - Under Network, select NAT or Bridged Adapter for internet access.

6] Start the VM:
   - Once the setup is complete, start the VM from the VirtualBox interface. The LFS system will boot, and you can log in and explore.

Outcome:
- Gained a deeper understanding of operating system internals and the build process.
- Created a lightweight and functional LFS system, complete with basic internet browsing capabilities through the terminal.

Notes:
Default credentials.
- Username: root
- Password: root
