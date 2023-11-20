# Belkin n52te programming/reprogramming

Since this device is no longer supported in the most recent OS the best way of reprograming this keyboard/keypad is to install an older OS like Windows 7 or 8 and play with it.

## Reprogramming a Belkin n52te in Windows 11 thru a Windows 7 Virtual Machine

Requirements:
- [VMWare](https://customerconnect.vmware.com/en/downloads/details?downloadGroup=WKST-PLAYER-1750&productId=1377&rPId=111473)
- VMWare Guest additions
- A functional VM with Windows 7 32 bits
  - Microsoft no longer have it available, [get into pc](https://getintopc.com/softwares/operating-systems/windows-7-professional-sp1-multilingual-april-2023-free-download-9753788/?id=000993163391) could be a source for it, you should have a license to use it
- A folder shared with this VM to transfer the driver
- Last Belkin n52te driver/controller V2.1.2 (in this repo)

## How to do and what to do

- Create a new VM in VM Ware
- Install Windows 7 or 8 (32 bits Windows 7 recommended)
- Install VM Ware Guest Additions
- Share a folder in you host
- Access the host share with the Virtual Machine
- Copy and install the driver
- Program the device with the n52te editor
- Upload configurations and use it

## Help

- If with this you still don’t know exactly what to do just post a message here
