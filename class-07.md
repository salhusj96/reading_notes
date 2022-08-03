# **Class 07 Reading Notes**
## **Powershell**

### *Why is this topic important?*
- Powershell is a command line interface used by both engineers and administrators to manage computers and networks straight from the command line. However, it is also used by Cyber criminals as a medium for attack. Modern hackers are able to use the tool run their attacks entirely wthin memory, where little to no change is made to the host's file system, instead injecting malicious code directly into memory, enhancing obfuscation and evading security controls designed around detecting malware deployments. In 2018, IBM's X-Force found that just 43% of attacks analyzed utilized any sort of locally installed files, indicating a sharp increase in usage of Powershell scripts. Though it is possible to wrap protections around Powershell, such as requiring scripts to be digitally signed. In the world of Cybersecurity, it is imperative that we develop our understanding and practice of this tool so that we are on the same playing field.

### **The Basics**
- Powershell is a command line interface used by both engineers and administrators to manage computers and networks straight from the command line.
- Powershell is also  a scripting language builr on the .NET Framework which can be used for automating administrative tasks and configuration management.
- Shares commonality with several other languages in that it creates something, usually an application.
  - Javascript
  - Java
  - Python
  - C#
  - Ruby
- Powershell is an interpreted language for doing things, in the context of managing a technological environment
### **What's in a shell?**
- Systems and Network Admins/Engineers often gravitate toward a particular OS associated with a commonly used language in that OS
  - Linux > Bash > Python
  - Windows > Powershell > C#
- Bash is now available on Windows, Powershell is now available on Linux
### **Powershell vs. Bash**
- Bash is the primary shell of Linux
  - Combines a scipting language as well as native Linux tools to automate and manage Linux devices
  - Works with 'strings'
  - Passes output and input as plain text; makes it easy to move more info to the next program
- Powershell is a Microsoft command-line shell and associated scripting language used for task automation and configuration management
  - Works with 'Objects'
  - Not just a shell; is a complete scripting environment. Scripts share comple data, passing entire data objects structures between commands.
- Both Bash and Powershell rely on the pipeline concept
  - Powershell pipes objects, passing along the output of one cmdlet as the input for another.
  - Bash shells push around globs of text.
### **Strings vs. Objects**
- Bash requires a lot of string manipulation and parsing to get the information you're after
  - Can be cumbersome; all the tools at Bash's disposal deal with a simple string, easy to pass around everywhere
- Powershell very easily passes objects between cmdlets allows you to move complex data with little effort
  - Objects are not always universal; not as readily made accessible outside of Powershell.
- Bash / Python mix more closely resembles Powershell while Powershell cant typically reach capabilities that Python can achieve
### **Where to use Powershell**
- Most companies aren't running a single technology stack
- Supported on nearly every major platform today
  - Windows
  - Linux
  - Hyper-V
  - VMWare
  - AWS
  - Azure
  - Oracle
### **Why you should learn PowerShell**
- Automation – you’ll be faster
- Accuracy – reduce mistakes
- Versatility – learning once enhances you everywhere
- Community – PowerShell has one of the most connected and welcoming communities in tech. Plugging into it will only help you become a better admin/engineer.
- Relevant – PowerShell continues to grow and be adopted. If you’re not learning it, you won’t remain competitive in the job market.

## **Things I want to know more about**
- What other commonly used tools do Hackers utilize to inject code into memory?
- Is there some way that code injected into memory can be tracked?
- Does the macOS have a similar tool?