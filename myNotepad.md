# Ubuntu Installation Guide

This guide provides the steps for installing Ubuntu on a system.

## Prerequisites
- A bootable USB drive or DVD with Ubuntu ISO.
- A system that supports booting from USB or DVD.
- At least 2GB of RAM and 25GB of free disk space.

## Steps for Installation

### 1. Download Ubuntu
1. Visit the official Ubuntu download page: [Ubuntu Downloads](https://ubuntu.com/download).
2. Choose the version you need (e.g., Ubuntu Desktop or Ubuntu Server).
3. Download the ISO file to your computer.

### 2. Create a Bootable USB Drive
1. Insert a USB drive (at least 4GB) into your computer.
2. Use a tool like **Rufus** (Windows) or **dd** (Linux/macOS) to create a bootable USB drive.
3. Select the Ubuntu ISO file you downloaded and choose your USB drive as the target.

### 3. Boot From USB or DVD
1. Restart your computer and enter the BIOS/UEFI settings (usually by pressing `F2`, `F12`, or `Del` during startup).
2. Set the USB or DVD drive as the primary boot device.
3. Save the changes and exit the BIOS/UEFI.

### 4. Install Ubuntu
1. After booting from the USB or DVD, you’ll be presented with the Ubuntu installation menu. Select **Install Ubuntu**.
2. Choose your language and click **Continue**.
3. Select your keyboard layout and click **Continue**.
4. **Prepare Installation Type**:
   - If you want to install Ubuntu alongside another operating system, choose **Install Ubuntu alongside [OS]**.
   - For a clean installation, choose **Erase disk and install Ubuntu** (this will delete all data on your disk).
5. Set your time zone by selecting a location on the map and click **Continue**.
6. Set up your user account by providing your name, computer’s name, username, and password.
7. Click **Continue** to start the installation.

### 5. Installation Process
- The installation process will begin, and Ubuntu will be installed on your system.
- This may take some time, depending on your system's hardware.

### 6. Complete the Installation
1. Once the installation is complete, you’ll be prompted to restart your system.
2. Remove the installation media (USB or DVD) before the system reboots.
3. Click **Restart Now**.

### 7. First Boot
- Your system will boot into Ubuntu for the first time.
- Log in with the user credentials you set during the installation process.
- You can now start using Ubuntu!

## Post-Installation Steps
1. **Update the system**:  
   Open a terminal and run:
   ```bash
   sudo apt update
   sudo apt upgrade
