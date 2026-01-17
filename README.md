# Windows Server Framework
An opensource toolbox of 60 automations for Windows Server that streamlines website updates and ensures robust cybersecurity.


**Overview:**
The Windows Server Framework is a free and opensource Windows PowerShell module that automates the most common website maintenance tasks. 

What is especially helpful is these commands are presented in an ordered sequence within the **WSF main menu**. The main menu shows which **system menus** are supported. Once a system menu is selected, it presents a step-by-step guide which teaches users how to use each automation and ensure the maintenance process is successful.

Compatible with all Windows Servers versions 2012 or newer.

The following systems are supported:
* Windows Server 
* Microsoft Sharepoint 
* SSL renewals for Internet Information Services
* SQL Server
* Microsoft Azure deployment

⠀

**Benefits:**
* **Save time** - turn multihour workflows and hundreds of mouse clicks, into automated processes that can be finished in half the time

* **Ensure system stability** - the step-by-step process of each automation guarantees all Windows administrators on your team, complete the same verified process
⠀
* **Deepen your knowledge** - the readable structure for each system’s menu is designed to teach users and reinforce deeper knowledge of complex processes

⠀

**How to install:**
1. Download or clone the **wsf.ps1** file, which is the main executable containing the PowerShell commands
2. Enable the script, by enabling the execution policy. Here is the most secure method for one-time enablement: *==🔴powershell.exe -ExecutionPolicy Bypass -File "C:\path\to\wsf.ps1"==*
3. Enter **wsf** in a PowerShell window to activate the WSF Main Menu, which will ask you for which system menu. Enter the corresponding number in the terminal.
4. The system menu will then show the step-by-step process for each automation.

⠀
**Customization:**
The Windows Server Framework has a **config** hashtable, which can be customized for your organization. It allows you to change global settings for the automation. These include: documentation links, databases to update and other settings.



**All commands supported:**

* Windows Server update
  * Stop services
  * Open patch directory
  * Restart computer
  * Update Central Administration of the status of the farm’s patches 
  * Check Central Administration dashboard

⠀

* Microsoft Sharepoint update
  * List the server farms and port numbers
  * Open each, using Remote Desktop Connection
  * Stop sharepoint services
  * Open patch directory
  * Restart computer
  * Upgrade databases
  * Force Sharepoint upgrade
  * Open Sharepoint Products Configuration Wizard
  * Update Central Administration of the status of the farm’s patches 
  * Open services
  * Open hostfile
  * Open test websites
  * Check Central Administration dashboard

⠀
* SSL renewals for Internet Information Services
  * Generate CSR for Certificate Authority
  * Generate secure 23 character alphanumeric password
  * Open Windows IIS Certificate menu
  * Open Windows IIS website, SSL binding
  * Open MMC, with the Certificates snapon enabled
  * Export certificate
  * Export private key

⠀
* SQL Server
  * In development

⠀
* Microsoft Azure deployment
  * In development


