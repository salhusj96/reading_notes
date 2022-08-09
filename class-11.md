# **Class 10 Reading Notes**

## **SSD Data Recovery Best Practices**

### *Why is this topic important?*
- In our travels as Cybersecurity professionals, we will often come across instances in time where a customer or user somehow has their data deleted, locked away by ransomware, or corrupted. Here in this article, we go over the best practices for data recovery on an SSD. It is important that we know the ins and outs of these practices because we will be dealing with crucial data on a daily basis in our careers, and you never know when you will need to recover it.

### **How do I know if my SSD is failing?**
- SSDs usually operate in silence until they stop functioning.
- Here are common indicators of failure;
  - Bad blocks
    - Storage segments that impede data storage and retrieval functions through corruption or physical dammage
  - File System repair
    - If computer or file requires repair but physical defect software shows no damage, could indicate issue with connector port
  - Crashing
    - If computer crashes while booting up but works normally after several reboots, it's likely failing
  - Read-only mode
    - Less common; SSD ceases function except in read-only mode 

### **How do you fix a failed SSD?**
- Formatting the drive and reinstalling the OS
- Power cycling
  - Unplug SATA data cable, leave power cable in
  - Leave power on for half an hour, then turn it off for 30 seconds, Repeat twice
  - Turn the power back on and reconnect the data cable
- Idling in boot menu
  - Similar to power cycling
  - Boot to BIOS and sit at the BIOS screen for a half hour, then turn it off for 30 seconds, Repeat twice
- Updating SSD Firmware
  - Run a formware update tool to see if it's the latest version
  - If firmware becomes too damaged, data may be lost forever
- Updating drivers
  - Check device manager
  - go to Disk drives
  - right-click the SSD to update the driver
  - After rebooting, may be able to see revived SSD

### **Is it possible to recover data from a failed SSD?**
- If an SSD begins operating again after a firmware update, its data is most likely completely accessible and the drive itself may be sound enough for continued use
- In cases where physical or firmware damage is too extensive, the drive may not be able to be revived.
- If the SSD enters read-only mode, you can still operate in read-only to backup and thus recover valuable data—but it is inadvisable to depend on this SSD again

### **SSD protection best practices**
1. Download a program from a selection of existing free software options designed to monitor SSD health by tracking operating temperature and performance metrics.
2. When investing in a new SSD, buy strategically. Many SSDs come equipped with S.M.A.R.T. (Self-Monitoring, Analysis, and Reporting Technology) that warns users of potential failure and prompts them to take preventative measures.
3. Have a backup strategy. Backup data regularly and routinely, even if your SSD was purchased recently and appears to be in good health. Unexpected corruption, power surges, viruses, or physical harm could befall your drive and cause permanent data loss. You truly never know what could happen—which is why valuable data should always be duplicated somewhere secure.