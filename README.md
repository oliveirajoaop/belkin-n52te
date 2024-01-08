# Belkin n52te programming/reprogramming

Since this device is no longer supported in the most recent OS the best way of reprograming this keyboard/keypad is to install an older OS like Windows 7 or 8 and play with its programming on one of those OSs.

## Programming/Reprogramming a Belkin n52te in Windows 11 thru a Windows 7 Virtual Machine

Requirements:
- [Oracle VirtualBox](https://download.virtualbox.org/virtualbox/7.0.12/VirtualBox-7.0.12-159484-Win.exe).
- [Guest additions](https://download.virtualbox.org/virtualbox/7.0.12/Oracle_VM_VirtualBox_Extension_Pack-7.0.12.vbox-extpack).
- A functional Virtual Machine with Windows 7 32 bits.
  - Microsoft no longer have it available, [get into pc](https://getintopc.com/softwares/operating-systems/windows-7-professional-sp1-multilingual-april-2023-free-download-9753788/?id=000993163391) could be a source for it, you should have a license to use it.
- A folder shared with this VM to transfer the driver.
- Last Belkin n52te driver/controller V2.1.2 (available in this repo).

## How to do and what to do

- Create a new Virtual Machine in Oracle VirtualBox
  - System
    - Motherboard, Base memory: 8192Mb
    - Processor, Processors: 2 CPU
  - Display
    - Screen, Video Memory: 128Mb
  - Storage
    - Controller: SATA
      - SATA Port 0: Windows7.iso
      - SATA Port 1: Windows 32.vdi (20Gb)
  - USB
    - Enable USB Controller selected
    - USB 1.1 (OHCI) Controller
    - Belkin n52te [2100]
- Install Windows 7 or 8 (32 bits Windows 7 recommended)
- Install Guest Additions for correct drivers install
- Share a folder in you host computer
- Access the host computer share with the Virtual Machine
- Copy and install the driver
- Reboot the Windows 7 Virtual Machine
- Share Belkin n52te with the Virtual Machine in USB Settings (Lower devices menu)
- Program the device with the n52te editor
- Upload configurations and use it

## Help

- If with this you still don’t know exactly what to do just post a message here
