# **Class 10 Reading Notes**

## **Get Started with Veeam Backup**

### *Why is this topic important?*
- Veeam is one of many powerful tools used for file backups and image recovery in virtual environments. As Cybersecurity professionals we will often be working in virtual environments so it is good that we familiarize ourselves with tools that pertain to said environments.

### **Veeam Features**
1. VeeamZIP Backup
2. Veeam Explorer for Exchange
3. Veeam Explorer for Storage Snapshots
4. Veeam Explorer for SharePoint
5. Quick Migration for VMware
6. File Copy Job
7. VM Copy Job
8. FastSCP Editor
9. Native tape support
10. File level recovery from backup
11. Whole VM recovery from backup
12. VM file recovery from backup (VMX, VHD, VMDK, etc.)

# **Three Major Features of Veeam**
### **VeeamZip**
- Lets you create a backup of running VMs
- Only need two things;
  - VM you want to backup
  - Location result
- Backups are deduplicated and compressed
- Results in significantly lower backup storage requirements
- Helps with updating a VM
  - Users frequently take a VeeamZIP backup before making any changes to a VM, such as before applying updates or patches.
- Helps with archiving a VM
  - It’s simple to create a deduplicated and compressed copy of a VM before removing it from your virtual infrastructure.
- Helps with copying a VM
  - VeeamZIP encapsulates VM configuration settings so you can easily transfer and run a VM in a different location.
### **Powerful and flexible restores**
- Supports several data recovery scenarios
- Restoring VM files
  - Veeam Backup Free restores VM files directly from deduplicated, compressed backups without having to extract the VM from the backup.
- Restoring an entire VM.
  - You can restore an entire VM to the same location or to a new location.
- Restoring VM disks (VMware)
  - If a VM disk becomes corrupted by an OS failure or some other cause, you can simply restore the affected VM disk and connect it to the original or recovered VM.
- Restoring guest OS files.
  - You can restore guest OS files for Windows FAT and NTFS file systems, and also ReFS with OS-level deduplication when running Windows Server 2012. 

### **Quick migration (VMware)**
- Quick Migration lets you migrate live VMs between hosts or datastores without requiring clusters, shared storage or advanced functionality that is not available in lower-level hypervisor editions. Quick Migration works well even in environments with slow or high latency connections that prevent VMware vMotion and Hyper-V Live Migration from working!

[Source](https://www.veeam.com/blog/how-to-get-started-with-veeam-backup-free-edition.html)

---
## **Things I want to know more about**
- Are there any alternatives to Veeam?