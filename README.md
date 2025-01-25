# Linux From Scratch (LFS)

## Overview
This project is a custom-built Linux From Scratch (LFS) system, designed to provide a deeper understanding of operating systems by building one from scratch. The system is lightweight, functional, and includes `links`, a terminal-based web browser, for basic internet browsing.

---

## Key Features
- Fully custom-built Linux operating system.
- Lightweight design with idle RAM usage around **70-80 MiB**.
- Includes `links` for terminal-based internet browsing.
- Capable of performing most tasks of a typical Linux system.

---

## Technologies Used
- **Linux From Scratch**: Built following the official LFS book and guidelines.
- **Custom Kernel & Bootloader Configuration**: Customized for the system.
- **Links Web Browser**: For terminal-based internet access.

---

## My Role
- Managed the entire build process: from compiling the kernel to configuring essential utilities.
- Debugged and resolved kernel and bootloader issues to ensure successful booting.
- Conducted research and troubleshooting to overcome challenges during system configuration.

---

## Prerequisites
- VirtualBox installed on your system.
- At least **512 MB of RAM** available for the virtual machine.
- A system with internet access (if using a bridged adapter for the VM).

---

## How to Run the LFS System

### 1. Download the LFS Files
Clone the repository to your local system:
```shell
git clone https://github.com/AvinashAbbigeri/LFS
```

### 2. Extract the Files
Use any zip extraction tool to extract the downloaded `.zip` file.

### 3. Create a New Virtual Machine in VirtualBox
1. Open VirtualBox.
2. Click **New** to create a new virtual machine.
3. Configure the VM:
   - Name: `Linux From Scratch`
   - Type: `Linux`
   - Version: `Other Linux (64-bit)`
   - RAM: Assign **512 MB** (or more, based on your resources).
   - Hard Disk: Choose `Use an existing virtual hard disk file`, browse to the extracted `.vdi` file, and select it.

### 4. Adjust VM Settings (Optional)
- **System Settings**:  
  Go to `Settings > System`, and ensure **Enable EFI (Special OSes only)** is unchecked.
- **Network Settings**:  
  Under `Network`, select either **NAT** or **Bridged Adapter** for internet access.

### 5. Start the Virtual Machine
Once the setup is complete:
1. Start the VM from the VirtualBox interface.
2. The LFS system will boot, and you can log in using the credentials below.

---

## Default Credentials
- **Username**: `root`
- **Password**: `root`

---

## Outcome
- Gained a deeper understanding of operating system internals and build processes.
- Built a lightweight, fully functional Linux system from scratch.
- Successfully integrated terminal-based internet browsing with the `links` web browser.

---

## Challenges Solved
- Resolved kernel and bootloader issues to ensure successful booting.
- Debugged system configurations by researching and troubleshooting effectively.

---

## Notes
- For questions or support, feel free to reach out via [GitHub Issues](https://github.com/your-repo/issues).
- This system is educational and intended for exploring OS internals. Not recommended for production use.

---
