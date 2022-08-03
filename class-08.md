# **Class 08 Reading Notes**
## **Windows Registry**

### *Why is this topic important?*
- The Windows Registry is an important database tool that stores many program configurations, and it is crucial that we learn about this tool because it will be used often to edit the more complex parameters of certain programs, like Windows Defender or other built-in Windows programs.

### **What is the Windows Registry?**
- A collection of several databases where Windows and many programs store their configuration settings.
- System-wide registry settings that apply to all users.
  - Each user account has its own user-specific settings.
- On Windows 10/7, the system-wide registry settings are stored in files under 'C:\Windows\System32\Config\'.
  - Each user account has its own 'NTUSER.dat' file containing its user-specific keys in its 'C:\Windows\Users\Name' directory.
- When signing into Windows, settings are loaded from these files into memory.
- When launching programs, they can check the registry stored in memory to find their configuration settings.
### **Registry Structure**
- Registry contains folders-like "keys" and "values" inside those keys
  - Can contain numbers, text, or other data
- Registry is made up of multiple groups of keys and values
  - EX: `HKEY_CURRENT_USER` or `HKEY_LOCAL_MACHINE`
### **RegEdit**
- Included with Windows.
- Lets you navigate the Registry and change settings.
- Should only be used when you know what you're doing or have clear instructions.
  - Otherwise you can potentially damage the system and render Windows unbootable.
- Especially useful when looking for options that aren't normally exposed in Windows.
### **Using RegEdit**
- To open RegEdit;
1. press Windows+R to open the 'Run' dialog
2. Type "regedit" and hit enter
3. Agree to the User Account Control prompt before continuing
![RegEditmenu1](https://www.howtogeek.com/wp-content/uploads/2018/10/img_5bc8c069807fa.png?trim=1,1&bg-color=000&pad=1,1)
- Use the left pane to navigate to whatever key you want to modify
  - Win10: You can copy an address into the address bar to find a particular key
- To change a value;
1. double lick the value in the right pane
2. enter a new value
3.  press OK to save and close RegEdit
![RegEditmenu2](https://www.howtogeek.com/wp-content/uploads/2018/10/img_5bc8c092a2733.png?trim=1,1&bg-color=000&pad=1,1)
---
## **Things I want to know more about**
- Can you use PowerShell to run a 'reg' file and change the registry from the command line?
- How many major hacks/attacks performed in the last decade have used the Registry?