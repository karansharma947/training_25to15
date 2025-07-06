## PC Hardware Trouble shooting:
### Components of a CPU:
### 1. Motherboard:
A motherboard is the main circuit board in a computer system. It connects all of the internal components, like the memory, processor, graphics card and other hardware. Its also known as PCB (Printed circuit board).

*Some components of Motherboard:*  <br>
- **Processor Socket:** <br>
   It is mechanical and electrical interface on a motherboard that securely connects a central processing unit (CPU) to the rest of the computer system.
  
- **CMOS backup battery:** <br>
   It is a small, coin-shaped battery that helps to keep the date and time accurate on computer. It ensures these settings are retained even when the computer is turned off and disconnected from a power source.
  
- **LAN (Local area network):**<br>
   It is the built-in Ethernet port that allows the computer to connect to a wired local area network for internet and data communication.
  
- **RAM Slots:** <br>
   Slots for installing RAM (Random Access Memory) modules.
  
- **Chipset**<br>
   Communication between Northbridge (handles CPU, RAM, GPU communication) and Southbridge (handles I/O, storage devices).
  
- **Expansion Slots:** <br>
  - Expansion slots on a motherboard are sockets designed to accommodate expansion cards, which add or enhance a computer's functionality
  - Common types: PCI.
    
- **Power Connectors** <br>
   Connects to the power supply unit (PSU).
  
- **Storage Connectors:** <br>
   SATA ports for connecting hard drives (HDD), solid-state drives (SSD), and optical drives.
  
- **BIOS Chip:** <br>
   Firmware that initializes hardware during startup and provides runtime services for the OS.
  
- **Input/Output (I/O) Ports:** <br>
  - Located on the back of the motherboard.
  - Includes USB ports, audio jacks, Ethernet, HDMI, DisplayPort, PS/2, etc.
    
- **Heat Sinks:** <br>
 Passive cooling components for chipsets and VRMs.

![](https://github.com/KamaljeetKaur00/Daily_bash_notes_2025/blob/main/images/components-of-motherboard.png)

### 2. **Fan:**

* Used for cooling the motherboard.
* Prevents overheatingt.

### 3. **Power Supply with Fan**

* Provides **electrical power** to all parts of the computer.
* Has a **built-in fan** to cool itself & CPU cabinet during operation.
* Converts electricity from the wall (AC) to usable computer power (DC).

### 4. **Connectors**

* Cables and plugs that connect components to the power supply and motherboard.

### 5. **Expansion Slots**
* Used to insert extra cards like:<br>
  * **Graphics cards**
  * **Sound cards**
  * **Wi-Fi/network cards**


### 6. **Hard Disk Drive (HDD):**
* Stores data, software, and the operating system.
* Located **under the optical drive** in the cabinet.

### 7. **Optical Drive (CD/DVD Drive):**

* Used to read/write **CDs and DVDs**

*How to locate components of a CPU?*

- Look for the power supply with fan (usually at the back top or bottom of the cabinet).
- In front of it is the optical drive.
- On it's side is the Motherboard.
- Below the optical drive is the hard disk drive.

### Difference between RAM and Cache memory:

| Feature        | **RAM (Random Access Memory)**            | **Cache Memory**                          |
| -------------- | ----------------------------------------- | ----------------------------------------- |
| **Purpose**    | It holds programs and data that are currently executed by the CPU. | It holds frequently used data by the CPU.  |
| **Speed**      | Slower than cache                         | Much faster than RAM                      |
| **Size**       | Larger (in GBs, e.g., 8GB, 16GB)          | Smaller than RAM  |

**Why do we need Cache memory?**
- It helps the **CPU work faster and more efficiently** by reducing the time it takes to access data.
  * Cache memory is **much faster** than RAM.
  * It stores **frequently used instructions and data**, so the CPU doesn’t have to wait for slower RAM.
  * Without cache, the Processor would **waste cycles**.<br>
So it is used to remove mismatch between RAM and Processor speed.

### Difference between RAM and Hard Disk:

| Feature              | RAM (Random Access Memory)           | Hard Disk                            |
| -------------------- | ----------------------------------------------- | ---------------------------------------------- |
| **Purpose**          | Temporary memory for currently running programs | Permanent storage for files, software, and OS  |
| **Storage Type**   | Temporary (loses data when off)                   | Permanent (keeps data when off)|
| **Speed**            | Much faster                                     | Slower compared to RAM                         |
| **Storage Capacity** | Smaller                   | Larger                  |
| **Access Method**    | Direct access by CPU                            | Slower access through file system              |
| **Cost**      |  Expensive                                  | Cheaper                                        |
| **Function**         | Helps run active programs and processes         | Stores data, files, OS, and installed programs |

**Process of Booting:**
| **Step**                                        | **Description**                                                                                                               |
| ----------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **1. Power On**                                 | You press the **power button**. Electricity flows to all components.                                                          |
| **2. Signal to RAM (Firmware loads Bootstrap)** | The **BIOS/UEFI firmware** stored in ROM sends a signal to RAM and loads Bootstrap Loader. |
| **3. Hard Disk Copy Transferred to RAM**        | The Bootstrap Loader finds the operating system (OS) on the hard disk and copies essential OS files into RAM.     |
| **4. OS Starts (OS gets control)**              | Once the OS is loaded into RAM, it takes over the system. The desktop/interface appears, and the system is ready for use.     |

  # Day-5

#  What is HDD?

**HDD (Hard Disk Drive)** is a **non-volatile storage device** that stores and retrieves digital data using **magnetic storage**. It contains spinning disks (platters) and read/write heads.

---

##  Key Features
- Long-term data storage
- Uses magnetic platters and mechanical arms
- Slower than SSDs
- Large storage capacity at low cost

---

##  Types of HDD

| Type                    | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **PATA (IDE)**          | Older standard, slow, now obsolete                                           |
| **SATA**                | Common in modern desktops/laptops, faster and more reliable than PATA       |
| **SCSI**                | Used in servers, supports multiple devices, high performance                |
| **SSHD (Hybrid Drive)** | Combines SSD speed with HDD capacity                                        |
| **External HDD**        | Portable, connects via USB, used for backups and additional storage         |
| **Enterprise HDD**      | High-performance, for servers/data centers, designed for 24/7 operation     |

---

##  HDD Form Factors

| Form Factor | Usage               |
|-------------|---------------------|
| 3.5 inch    | Desktop computers   |
| 2.5 inch    | Laptops, compact PCs|

---

## Note:
>  **SSD (Solid-State Drive)** is not a type of HDD, but is often compared with HDD due to similar purpose (storage). SSDs have no moving parts and are much faster.

---

**Common issues and problems in PC:**

-GPU:
 GPU (Graphics Processing Unit) is a specialized processor designed to handle graphics and visual computations. It’s mainly responsible for rendering images, videos, and animations — especially in games, video editing, and 3D rendering.

-What Causes GPU Failure?

| Cause                | Description                                              |
| -------------------- | -------------------------------------------------------- |
| **Overheating**      | Due to dust, poor ventilation, or fan failure.           |
| **Power Surges**     | PSU instability or electric surge can damage the GPU.    |
| **Driver Conflicts** | Corrupt or outdated drivers may crash the GPU system.    |
| **Physical Damage**  | Dropping or improper handling of the GPU.                |
| **Age/Wear**         | Older GPUs eventually wear out after years of heavy use. |

- What to Do When GPU Fails:
  
| Step                                 | Action                                                                                             |
| ------------------------------------ | -------------------------------------------------------------------------------------------------- |
|  **Check Connections**             | Reseat the GPU and check cables.                                                                   |
|  **Clean the Card**                | Remove dust, check fans.                                                                           |
|  **Switch to Integrated Graphics** | Remove the GPU and boot using onboard graphics to isolate the issue.                               |
|  **Try GPU on Another PC**         | To confirm if the GPU is really faulty.                                                            |
|  **Stress Test**                   | Use software like FurMark or GPU-Z (if it still works) to monitor GPU performance and temperature. |
|  **Reinstall Drivers**             | Use DDU (Display Driver Uninstaller) and reinstall clean drivers.                                  |
|  **Check Temperature**             | Ensure GPU isn’t overheating. Use tools like MSI Afterburner.                                      |

- If GPU Is Dead:
1. Warranty? If under warranty, contact the manufacturer for replacement.

2. Out of Warranty? You may need to replace it. Repairs are rarely cost-effective unless it’s a minor issue like fan replacement.

<h3>PSU(Power supply Unit)</h3>:
 - Symptoms:
1. PC doesn’t power on

2. Random shutdowns or reboots

3. Burning smell or electrical noise

4. Fans or lights flicker inconsistently

-Diagnosis Steps:

| **Method**                          | **How To Do It**                                                                                  |
| ----------------------------------- | ------------------------------------------------------------------------------------------------- |
| **Check Power Cable/Outlet**      | Test with a known working outlet and cable.                                                       |
| **Paperclip Test** (for ATX PSU) | Short green and black wires on 24-pin connector to check if PSU turns on (fans spin). Be careful. |
| **Test with Multimeter**          | Check voltage output of 12V, 5V, and 3.3V rails.                                                  |
| **Try Another PSU**              | Swap with a known good PSU to confirm failure.                                                    |


- Safety Tips:
1. Always turn off and unplug the PC before opening the case.

2. Ground yourself to avoid static damage.

3. Don’t attempt PSU repairs unless you're trained — dangerous voltages are involved.



- Speed low(issue and solution):
  
| **Issue**                           | **Explanation**                                           | **Fix / Solution**                                                             |
| ----------------------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------ |
| **Too Many Startup Programs**       | Apps launch at boot and slow down performance.            | Press `Ctrl + Shift + Esc` → Go to **Startup** tab → Disable unnecessary apps. |
| **Low RAM**                         | Not enough memory for multitasking.                       | Upgrade your RAM (e.g., from 4 GB to 8 or 16 GB).                              |
| **Fragmented Hard Disk (HDD only)** | Slows down file access time.                              | Run **Defragment and Optimize Drives** (for HDDs only).                        |
| **Old or Failing HDD**              | Mechanical drives become slower with age.                 | Replace with a **Solid State Drive (SSD)**.                                    |
| **Too Many Background Processes**   | Apps running in the background eat up CPU and memory.     | Use **Task Manager** to identify and end unnecessary processes.                |
| **Virus or Malware**                | Malicious software slows down system and uses resources.  | Run a full system scan with **Windows Defender** or a good antivirus.          |
| **Outdated Drivers or Software**    | Compatibility issues and slow performance.                | Update Windows, drivers (especially graphics and chipset), and installed apps. |
| **Overheating**                     | CPU/GPU slow down to reduce heat (thermal throttling).    | Clean dust from fans, use thermal paste, improve ventilation.                  |
| **Too Many Browser Tabs**           | Web browsers (especially Chrome) can consume lots of RAM. | Close unused tabs and extensions. Use lighter browsers.                        |
| **Windows Updates Running**         | Updates in the background can slow things down.           | Let updates complete or schedule them for off-hours.                           |
| **Old or Underpowered CPU**         | Not enough processing power for modern apps.              | Upgrade to a newer CPU if possible.                                            |

- Common Printer issues and solutions:

| **Issue**                   | **Cause**                                   | **Solution**                                                  |
| --------------------------- | ------------------------------------------- | ------------------------------------------------------------- |
| **1. Printer not printing** | Loose cables, offline mode, or driver error | Check power and USB/Wi-Fi connection; reinstall/update driver |
| **2. Printer is offline**   | Network issue or manual setting             | Set printer to online from Control Panel or settings          |
| **3. Paper jam**            | Misaligned or stuck paper                   | Open printer, carefully remove paper, check for debris        |
| **4. Low or empty ink**     | Empty or clogged cartridge                  | Replace or refill cartridge; clean printhead                  |
| **5. Poor print quality**   | Dirty nozzle or wrong paper settings        | Run nozzle                                                    |


# BSOD(Blue screen of Death):

BSOD stands for Blue Screen of Death — it’s a critical error screen displayed by Windows when the operating system crashes and can’t continue running safely.

 **What Does It Look Like?**
 
A full blue screen with a sad face :(, an error message (like CRITICAL_PROCESS_DIED or MEMORY_MANAGEMENT), and a stop code.

**What Causes a BSOD?**

| **Cause**                       | **Explanation**                           |
| --------------------------------| ----------------------------------------- |
| **Faulty drivers**              | Incompatible or corrupt hardware drivers. |
| **Hardware failure**            | Bad RAM, GPU, hard drive, or overheating. |
| **Corrupt system files**        | Damaged Windows files or registry issues. |
| **Malware infection**           | Can corrupt system processes or files.    |
| **Windows update issues**       | Failed or incomplete updates.             |
| **Overclocking or BIOS issues** | Unstable system configuration.            |

**System Crash Analysis:**

After a BSOD, Windows creates a dump file that records what happened before the crash.

**Tools for Analysis:**

- Event Viewer:
Windows tool to check detailed system and crash logs.
- WinDbg:
Microsoft Debugging Tool for analyzing dump files |

# BIOS/UEFI Settings and POST Errors:

| Term                                             | Meaning                                                                                                     |
| ------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| **BIOS (Basic Input/Output System)**             | The traditional firmware that initializes hardware during boot before handing over to the OS.               |
| **UEFI (Unified Extensible Firmware Interface)** | A modern, more advanced replacement for BIOS with a graphical interface, mouse support, and faster booting. |

- Common BIOS/UEFI Settings:

| Setting                         | Description                                                                 |
| ------------------------------- | --------------------------------------------------------------------------- |
| **Boot Order**                  | Controls which drive the system tries to boot from first (e.g., SSD, USB).  |
| **Secure Boot**                 | Prevents unauthorized OS booting; may need to be disabled to install Linux. |
| **XMP Profile**                 | Enables RAM to run at its rated speed.                                      |
| **CPU Fan Control**             | Adjusts fan speed and thermal behavior.                                     |
| **Virtualization (VT-x/AMD-V)** | Enables virtual machines (VMware, VirtualBox).                              |
| **SATA Mode**                   | Switches between AHCI/IDE modes for SSD/HDD performance.                    |


- What is POST?

POST stands for Power-On Self-Test.
It is a diagnostic test run by the BIOS/UEFI when the PC starts to check hardware (RAM, CPU, GPU, etc.).

- Common POST Errors and Beep Codes:

| **Error**                 | **Cause**                        | **Fix**                                            |
| ------------------------- | -------------------------------- | -------------------------------------------------- |
| **No Display / Beeping**  | RAM not detected                 | Reseat or replace RAM                              |
| **Continuous Beeps**      | Keyboard, GPU, or CPU error      | Check/replace component                            |
| **No Beep, No Boot**      | PSU or motherboard issue         | Test with another PSU or check board               |
| **CMOS Checksum Error**   | Battery dead or settings corrupt | Replace CMOS battery (CR2032) and reconfigure BIOS |
| **Boot Device Not Found** | HDD/SSD not detected             | Check drive connection and boot order              |
| **Overclocking Failed**   | Unsafe system settings           | Reset BIOS to default or clear CMOS                |


- How to Access and Reset BIOS/UEFI:

| Action                    | Key Steps                                                                               |
| ------------------------- | --------------------------------------------------------------------------------------- |
| **Access BIOS**           | Press **Del**, **F2**, or **Esc** right after turning on PC                             |
| **Reset BIOS to Default** | Use “Load Setup Defaults” or remove the **CMOS battery** for 30 seconds                 |
| **Update BIOS**           | Download latest version from motherboard brand's site and follow instructions carefully |
# Defragmentation
* Your hard disk stores files in small pieces. Over time, the pieces get scattered. This is called fragmentation.

* Defragmentation means putting all the scattered file pieces back together, so your computer can find them faster.

# Optimization

* Optimization means making your computer or software work faster and more efficiently. It involves cleaning up unnecessary files, fixing errors, managing startup programs, and adjusting settings so everything runs smoothly.

* By optimizing your system, you can improve speed, reduce crashes, and get better overall performance.

  ### **_Scheduled Optimization_**
  * Scheduled Optimization is setting your computer or device to automatically perform maintenance tasks at regular times—like cleaning up junk files, defragmenting the disk, or scanning for errors—without you having to do it manually.
  * This helps keep your system running smoothly and fast without interrupting your work.

  ### **_Delivery Optimization_**
  Delivery Optimization is a Windows feature that helps manage and speed up downloading Windows updates and Microsoft Store apps by using peer-to-peer (P2P) sharing across your local network or the internet.

  
# Why Install an Antivirus Scanner?
An antivirus is like a bodyguard for your computer.
It protects your computer from:
* Viruses (harmful programs)
* Malware (spyware, ransomware, etc.)
* Hackers trying to steal your data
* Dangerous files from pen drives, emails, or the internet

  ### **_Protects Your Computer :_** 
  Detects and removes viruses, malware, spyware, and other harmful software that can damage your files or system.

  ### **_Prevents Data Theft :_** 
  Stops hackers and malicious software from stealing your personal information like passwords, bank details, and documents.

  ### **_Keeps System Running Smoothly :_** 
  Removes unwanted programs that slow down your computer or cause crashes.

  ### **_Safeguards Against New Threats :_** 
  Regular updates help protect you from the latest viruses and cyberattacks.

# Printer Problems and Solutions

| No. | Problem                    | Reason                           | Easy Solution               |
| ------ | ------------------ | ----------------------------------- | ----------------------------- |
| 1      | **Printer says "No Paper"**   | No paper in tray                    | Put fresh paper into the paper tray                  |
| 2      | **Paper Jam**                 | Paper stuck inside the printer      | Turn off printer, open the back, remove paper gently |
| 3      | **Low or No Ink**             | Ink cartridge is empty              | Replace or refill the ink cartridge                  |
| 4      | **Printer not detected**      | Loose cable or not connected        | Check USB cable or Wi-Fi connection                  |
| 5      | **Printer driver missing**    | Driver not installed or outdated    | Download and install the correct driver              |
| 6      | **Printing is too slow**      | High-quality print mode is on       | Change settings to "Draft" mode                      |
| 7      | **Print is faded or patchy**  | Dirty or clogged print head         | Clean the print head from printer settings           |
| 8      | **Wi-Fi printer not working** | Printer not connected to same Wi-Fi | Reconnect printer and computer to same Wi-Fi         |
| 9      | **Stuck in queue**            | Old print jobs not cleared          | Cancel or restart the print queue                    |
| 10     | **Error messages blinking**   | Various printer errors              | Restart the printer or check the manual    |

  ### **_Tips for Printer Maintenance_**
  * Regularly update printer drivers.
  * Use recommended paper and ink/toner.
  * Keep printer clean and free of dust.
  * Restart printer and computer if issues persist.
  * Consult printer manual for model-specific troubleshooting.

  ### **_Benefits of Updates_**

  **_Improved Security :_** Updates patch vulnerabilities that hackers could exploit.
  
  **_Bug Fixes :_** They fix software errors and glitches for smoother performance.
  
  **_New Features :_** Updates often add new tools and functionalities.
  
  **_Better Compatibility :_** Ensure your software works well with new hardware and other programs.
  
  **_Performance Enhancements :_** Updates can speed up software and make it more efficient.
  
  **_Stability Improvements :_** Reduce crashes and unexpected errors.
  
  **_Compliance :_** Keeps software up to date with industry standards and regulations.

# Blue Screen of Death (BSOD)
The Blue Screen of Death (also called STOP error) is when your computer suddenly stops working and shows a blue screen with a sad face and some error message.

  ### **_Why BSOD happens_**
  * Faulty or incompatible hardware (like bad RAM or hard drives)
  * Driver problems (corrupted or outdated drivers)
  * Software bugs or corrupted system files
  * Overheating or hardware failures
  * Malware or virus infections
  * Conflicts between software and hardware
  When BSOD occurs, Windows shows an error code to help identify the problem.

# System crash analysis
System crash analysis is the process of investigating why a computer suddenly stops working or restarts unexpectedly. The goal is to find the cause and fix it to prevent future crashes.

  ### **_How it’s done?_**

  * Check error messages or codes shown during the crash.
  * Review system logs using tools like Event Viewer.
  * Analyze crash dump files with utilities such as BlueScreenView or WinDbg.
  * Look for recent changes in hardware, software, or drivers that might have caused the crash.
  * Run hardware diagnostics to check for failing components.
    
  ### **_Fixes usually involve_**
  * Updating or rolling back drivers.
  * Removing problematic software.
  * Repairing corrupted system files.
  * Replacing faulty hardware.

# Key Concepts
  ### **_Dump Files_**
  When Windows crashes, it creates dump files—snapshots of system memory at the crash moment. These files contain critical information to analyze the error and are usually saved on the C: drive in locations like:

  Having sufficient free space on the C: drive is essential to allow these files to be saved.

  ### **_Windows Debugging_**
  Windows debugging involves using specialized tools to analyze dump files and understand the crash cause. Common tools include:

  * **_WinDbg :_** Microsoft's official debugger for detailed dump analysis.
  * **_BlueScreenView :_** A simpler tool that summarizes BSOD dump files.

  Debugging helps identify :
  * Faulty drivers or system files
  * Hardware issues
  * Software conflicts
    
  ### **_Role of the C: Drive_**
  * Stores dump files and system logs
  * Houses Windows OS files required for crash analysis
  * Needs enough space to save crash dumps; without it, useful diagnostic data may be lost
    
  ### **_Basic Crash Analysis Workflow_**
  * Locate dump files on the C: drive.
  * Use debugging tools (WinDbg or BlueScreenView) to analyze the dumps.
  * Identify error codes and faulting modules or drivers.
  * Review Windows Event Viewer for related system events.
  * Test hardware components if indicated.
  * Update, rollback, or reinstall drivers/software as needed.
  * Monitor system for stability after applying fixes.
    
# ASSIGNMENT
---

### **_BIOS_**
* BIOS = Basic Input Output System
* It's the first software that runs when you turn on your computer.
* It checks your hardware (keyboard, RAM, hard disk, etc.) and then loads Windows or Linux.

### **_UEFI_**
* UEFI = Unified Extensible Firmware Interface
* It's the modern version of BIOS.
* It looks better (with mouse support), is faster, and supports bigger hard drives.

# Day-6

**Safe Mode**

- Safe Mode is a special diagnostic mode in operating systems like Windows or Linux.
- It starts the computer with a minimal set of drivers and services, which helps identify and fix problems.
- Safe Mode loads only essential system files, basic drivers (keyboard, mouse, display), and core services.
- It skips third-party software, startup programs, and advanced drivers, helping diagnose and fix system issues.

 # How to Start Safe Mode (Windows 10/11):
1. Using Settings:

- Go to Settings > Update & Security > Recovery
- Under Advanced startup, click Restart now
- After restart: Troubleshoot > Advanced options > Startup Settings > Restart
- Press 4 to enable Safe Mode

2. Using Shift + Restart:

- Hold Shift and click Restart from the Start menu
- Then follow: Troubleshoot > Advanced options > Startup Settings > Restart > Press 4

3. During Boot (for older systems):
- Repeatedly press F8 or Shift + F8 while booting (works on some PCs)

# Why We Use Safe Mode:

- To troubleshoot system issues like crashes, freezing, or boot failures.
- To remove malware or viruses that don’t run in Safe Mode.
- To uninstall faulty drivers or software causing errors.
- To perform System Restore and undo harmful changes.
- To identify whether a problem is caused by Windows or third-party apps.

# Types of safe mode:

1. Safe Mode:
- Used to diagnose and fix basic system issues.

2. Safe Mode with Networking:
- Includes network drivers and services. Allowing access to the internet or network drives for troubleshooting.

3. Safe Mode with Command Prompt:
- Loads a minimal environment with Command Prompt instead of the normal desktop interface

# What are recovery tools?

Recovery tools are built-in features in an operating system used to fix boot problems, restore the system, or repair corrupted files. Examples include System Restore,
Startup Repair, and Reset this PC in Windows.

**Common recovery tools:**

1. System Restore – Reverts the system to a previous working state.

2. Startup Repair – Fixes boot and startup issues automatically.

3. Reset this PC – Reinstalls Windows with or without keeping files.

4. System Image Recovery – Restores system from a saved backup image.

5. Command Prompt – Allows advanced troubleshooting using commands.

# What is OS repair:

- Methods to fix corrupted or missing OS files.OS Repair means fixing the software that runs your computer — called the Operating System (OS). For most PCs, this is Windows.
- When the OS has problems (like crashes, errors, or slow performance), OS repair tools help find and fix these problems so your computer works well again.
- Fixing corrupted or missing system files without reinstalling the whole operating system.

# Common methods:
- SFC (System File Checker) – Repairs corrupted or missing system files using sfc /scannow in Command Prompt.
- DISM Tool – Fixes Windows image issues using DISM /Online /Cleanup-Image /RestoreHealth.
- Bootable USB for repair and system reinstall.

# How does OS repair work?

- It checks important system files and replaces damaged or missing ones.
- It can restore Windows to an earlier, healthy state.
- It can fix startup problems so Windows boots correctly.
- If needed, it can reset or reinstall Windows without deleting your personal files.

# Why might you need OS repair?

- Your computer is freezing or crashing
- You get error messages or blue screens
- Windows doesn’t start properly
- Programs don’t open or keep closing
- Files or settings are missing or broken

# Virus malware

A virus is a type of malicious software that attaches to files or programs and spreads when the file is run.

Malware (short for malicious software) is a broad term for any harmful software, including viruses, worms, trojans, ransomware, spyware, etc.

- Virus = a type of malware
- Malware = all harmful software type

**Symptoms and Removal Methods:**

| Symptoms**                          | **Removal Methods**                              |
| ----------------------------------- | --------------------------------------------------- |
| Slow system performance             | Boot into **Safe Mode**                             |
| Frequent pop-ups or ads             | **Run antivirus/malware scan** (e.g., Malwarebytes) |
| Programs crash or behave oddly      | **Uninstall suspicious programs**                   |
| Unknown apps or processes           | **Use Task Manager** to end unknown tasks           |
| Files are missing or corrupted      | **Restore from backup** or System Restore           |
| Browser redirects or changes        | **Reset browser settings**                          |
| Antivirus is disabled automatically | **Re-enable security settings** in Safe Mode        |
| Automatic restarts or shutdowns     | **Run System File Checker** (\`sfc /sc              |


**What Are Plug-ins?**

Plug-ins are small software add-ons that you can install to add new features or functions to a program or app.

**Where Are Plug-ins Used?**

- Web browsers (like Chrome or Firefox) use plug-ins or extensions to block ads, translate pages, or play videos.
- Photo or video editors use plug-ins to add new effects or filters.
- Music players or games can use plug-ins for extra sounds or tools.

# What is a Backup?

A backup is a copy of your important files and data saved somewhere safe — like on another drive or in the cloud.
It helps you recover your files if something bad happens, like your computer breaking or a virus deleting data.

**Why Backup?**

- Protect important photos, documents, and files
- Restore your data if your computer crashes
- Avoid losing work or memories

  **How to Backup**

- Copy files manually to an external hard drive or USB

- Use built-in backup tools like:

Windows: File History or Backup and Restore

Mac: Time Machine

- Use cloud services like Google Drive, OneDrive, or Dropbox

**Backup Tips**

- Backup regularly (once a week or more)
- Keep backups in a safe place
- Test your backups sometimes to make sure they work

# What is  an RJ45 Connector?

An RJ45 connector is a plastic plug used to connect Ethernet cables to computers, routers, or switches.
It’s the most common type of connector for network cables.


**What is a Crimping Tool?**
- It’s a handheld tool used to attach the RJ45 connector to the Ethernet cable.
- It pushes small metal pins inside the connector down into the wires of the cable.
- It also secures the connector onto the cable so it doesn’t come loose.

**What is an Ethernet Cable?**

An Ethernet cable is a wire that connects your computer or device to a router, modem, or network switch.
It helps devices talk to each other and access the internet.

# How to Make a RJ‐45 Cable:

- Strip the cable to remove 1 inch of the outer sheath.
- Untwist and straighten the wires inside of the cable
- Arrange the wires into the right order.

| Pin | Wire Color   |
| --- | ------------ |
| 1   | White-Orange |
| 2   | Orange       |
| 3   | White-Green  |
| 4   | Blue         |
| 5   | White-Blue   |
| 6   | Green        |
| 7   | White-Brown  |
| 8   | Brown        |

- Trim the wires into an even line 1⁄2 inch (13 mm) from sheathing
- Insert the wires into the RJ-45 connector.
- Stick the connector into the crimping part of the tool and squeeze twice.
- Remove the cable from the tool and check that all of the pins are down & test the cable.


*Rj45 colour combinations*

![image](https://github.com/user-attachments/assets/9e4ced9f-65ec-475c-ba0a-c2721c8cb768)


## Networking Basics
**Network Definition:** <br>
  Any time two or more hosts are connected and can communicate, you have a network.



### 1. Hosts and Traffic:

* **Host:**
   Host is any device which sends or receive data traffic over a network. While often a computer, it can also include other networked devices like smartphones, tablets, and IoT (Internet of Things) devices.
* **Client:**
   Client is a host that initiates requests for services from another device on the network.
* **Server:**
   Server is a computer designed to respond to requests from clients. It "serves" the requested data or services to the user.
* **Traffic:**
   It refers to the data that is transmitted between devices on a network. This can include anything from web pages and emails to video streams and sensor data from IoT devices.


### 2. IP Address (Internet Protocol Address):

An IP address is a unique numerical identifier assigned to every device connected to a computer network that uses the Internet Protocol for communication.

* **Protocol:**
   Protocol is a set of rules governing how data is formatted, transmitted, and received between devices.
* **Properties:**
    * **Unique:** Each device on a network must have a unique IP address.
    * **Universal:** IP addresses are a globally recognized standard for network communication.
* **Types:**
    * **Public IP Address:** Used on the internet, these addresses are globally unique and routable.
    * **Private IP Address:** Used within private networks (e.g., home or school networks), these addresses are not directly routable on the internet.
* **Dynamic Nature:** IP address can change over time, especially for devices on dynamic IP assignments. However, its fundamental properties (uniqueness and universality) remain constant.

### 3. IPv4 (Internet Protocol Version 4):

IPv4 is the fourth version of the Internet Protocol.

* **Length:** 32 bits long.
* **Address Space:** Can theoretically support $2^{32}$ unique addresses.
* **Notation:** Represented in dotted-decimal format, consisting of four **octets** (groups of 8 bits) separated by dots. Each octet can range from 0 to 255.
    * Example: `192.168.1.1`
 
#### Address Structure:

* **Network ID (Prefix):**
   Defines the network segment to which the device belongs. This part is common for all devices within the same network.
* **Host ID (Suffix):**
  Uniquely identifies a specific device (host) within that network segment.

*Example*:
An international phone number where the country code represent network and the phone number represents the "host.


### 4. IPv6 (Internet Protocol Version 6)

IPv6 is the latest version of the Internet Protocol, designed to address the limitations of IPv4, primarily the exhaustion of available addresses.

* **Length:** 128 bits long.
* **Address Space:** Can support a vastly larger number of addresses, approximately $2^{128}$.
* **Notation:** Represented in hexadecimal, often with colons separating groups of 16 bits.


### 5. Classful Addressing (IPv4)

It is used to categorizing IP addresses into different classes based on the range of their first octet. There are five classes: A, B, C, D, and E.


| **Class** | **Starting Bits** | **IP Range** | **Length of Network (Bits)** | Reseved bits  | Number of Networks | Number of Hosts     | **Default Subnet Mask** | Purpose                                |
| --------- | ----------------- | ------------  | ---------------------------- | ------------- | ------------------ | ---------------     | ----------------------- | -----------------------------------------------|
| **A**     | 0                 | 0 - 126      | 8                            | First         | $2^{7}$ = 128         |  $2^{24}$ = 16 million | 255.0.0.0               | Very large organizations. exp: Indian railways |
| **B**     | 10                | 128 – 191    | 16                           |  First 2      | $2^{14}$              |  $2^{16}$               | 255.255.0.0             | Medium-sized organizations                      |
| **C**     | 110               | 192 – 223    | 24                           |   First 3     | $2^{21}$               |  $2^{8}$ = 256         | 255.255.255.0           | Small networks (like LANs)                       |
| **D**     | 1110              | 224 – 239    | N/A (Multicast)              |         N/A   |N/A                 | N/A                 | N/A                     | Multicast groups                               |
| **E**     | 1111              | 240– 255     | Reserved                     |     N/A       |N/A                 | N/A                 | N/A                     | Experimental or research use only                   


*Note: As the prefix (network ID) increases, the number of available host IDs decreases*


### 6. Broadcast vs. Multicast vs. Unicast

| **Parameters**             | **Unicast**                                                                  | **Broadcast**                                                         | **Multicast**                                                                       |
| -------------------------- | ---------------------------------------------------------------------------- | --------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| **Basics**                 | There is only **one receiver** and **one sender**.                           | There are **multiple receivers** and **one sender**.                  | There are **multiple receivers** and **multiple senders**.                          |
| **Meaning and Definition** | Unicast is used to transfer data from a single sender to a single recipient. | Broadcast sends data from one sender to **all devices** on a network. | Multicast sends data from one or more senders to a **selected group** of receivers. |
| **Mapping**                | **One-to-one** type of communication.                                        | **One-to-many** type of communication.                                | **Many-to-many** type of communication.                                             |
| **Uses**                   | Used for **direct communication** like web browsing, emails, etc.            | Used in **TV/radio networks**, ARP, DHCP discovery, etc.              | Used in **stock exchanges**, **live video streaming**, **multimedia delivery**.     |




### 7. Subnetting:
* Dividing a large network into smaller, more manageable sub-networks. It helps to utilize the network bandwidth in more intelligent way.
* **Bandwidth:** Capacity of network; data transmission rate (e.g., Mbps). Should be maximum.
* **Latency:** Delay in data transmission. Should be minimum.

  
* **Host Bits:** Denoted by '0's in subnet mask.
* **Network IP:** First IP of a subnet (cannot be assigned to host).
* **Broadcast IP:** Last IP of a subnet (cannot be assigned to host).

### Some other small concepts:
#### MAC (Media Access Control Address)

* **Nature:** A unique, 12-character hexadecimal (alphanumeric) attribute used to identify individual electronic devices on a network.
* **Distinction from IP Address:**
    * **MAC Address:** Identifies the physical location of a device within a *local network*. It's like your permanent home address. The manufacturer provides it.
    * **IP Address:** Signifies the device's *global or internet-accessible identity*. It's more like a temporary vacation rental address, changing depending on your network connection.

####  DNS (Domain Name System):
It is a naming system for computers, service etc connected to the Internet or a private network. It translates domain names (`www.google.com`) into machine-readable IP addresses (`172.217.160.142`).

#### Default Gateway:
Its a device (typically a router) that acts as a pathway for data to leave a local network and reach other networks, including the internet.


####  CIDR (Classless Inter-Domain Routing):
* Modern method for IP allocation and routing, replacing classful addressing with more flexible network sizing (e.g., `/24`).

#### Types of Cables
* **Twisted Pair:**
    * **Types:** Shielded (STP) and Unshielded (UTP).
    * **Use:** LANs (Ethernet).
* **Coaxial:**
    * **Use:** TV networks, older computer networks.
* **Fiber-Optic:**
    * **Use:** High-speed networks, long distances (most commonly used today).
 
## Numericals:
### For `205.150.65.0/26`. Find:
1. Subset mask
2. Number of subsets
3. Number of hosts
4. Network IP
5. Broadcast IP.
### Answer:
*Here /26 is CIDR*
**Class:** Class C.
1. **Subnet Mask:** `255.255.255.192`
    * In binary: `11111111.11111111.11111111.11000000`
    * This means 26 bits are used for the network.
    * Convering `11000000` to decimal = $2^{7}$ + $2^{6}$  = 192
    * SO Subset mask is: `255.255.255.192`

2. **Number of Subnets:**
     * 26 network bits - 24 default network bits = 2 subnet bits
     * Number of subnets = $2^{\text{subnet bits}} = 2^2 = 4$

3. **Number of Hosts**
    * **Host ID Bits:** 32 - 26 = 6
    * Number of hosts = $2^{\text{host bits}} - 2 = 2^6 - 2 = 64 - 2 = 62$

4. **Network IP:**
   - Given IP `AND` (AND operation) Subset mask:
    - 205.105.65.0

5. **Broadcast IP:**
   - As maximum number of hosts are 62:
   - `205.105.65.63`

# Day-8
# Networking Notes

## DHCP (Dynamic Host Configuration Protocol)

- A network protocol that automatically assigns IP addresses to devices in a network.
- Removes the need for manual IP configuration.
- Helps devices connect easily without user intervention.

---

## Network Command: `ping`

**Simple Meaning:**
- It's like asking another device: *"Hey, are you there?"*
- Used to check if a computer, server, or website is reachable.

**Technical Meaning:**
- Sends ICMP (Internet Control Message Protocol) Echo Request packets to a target host.
- If a reply is received → the host is reachable.
- If no reply → the host may be offline or blocked.

**Syntax:**
```
ping <website_address>
```

**Example:**
```
ping youtube.com
```

**To stop ping:**
- Press `Ctrl + C` in the terminal or command prompt.

---

## Loopback Address: `127.0.0.1`

- Refers to **your own computer**.
- Used to test your own network setup.
- Like sending a letter to yourself to see if your mailbox works.




## Network Command: `traceroute` (Windows: `tracert`)

**Purpose:**
- Displays the **exact path** that data takes from your computer to a target website or server.
- Shows all the intermediate **hops** (routers) that your data passes through.

**Each hop** = one router in the path.

**Syntax:**
- On **Linux/macOS**:
  ```
  traceroute <hostname_or_IP_address>
  ```
- On **Windows**:
  ```
  tracert <hostname_or_IP_address>
  ```

**Note on Output:**
- If you see `* * *` (asterisks), it means that particular router **did not respond** to the request.

**Example:**
```
tracert youtube.com
```

**Use Case:**
- Helps diagnose network routing issues or delays in connectivity.






## Network Command: `ipconfig` (Windows) / `ifconfig` (macOS/Linux)

### `ipconfig` (Windows)

**Purpose:**
- Displays the current **network configuration** of your Windows PC.

**Details it shows:**
- IP address
- Subnet mask
- Default gateway
- DNS servers
- Network adapter status

**Syntax:**
```
ipconfig
```

**Additional Usage:**
- To release IP: 
  ```
  ipconfig /release
  ```
- To renew IP:
  ```
  ipconfig /renew
  ```

---

### `ifconfig` (macOS/Linux)

**Purpose:**
- Similar to `ipconfig`, used to view or configure network interfaces.

**Syntax:**
```
ifconfig
```

**Note:** On newer Linux systems, `ifconfig` is deprecated and replaced by:
```
ip a
```

**Use Case:**
- Check current IP settings
- Troubleshoot network issue


## Ethernet

**Definition:**
- Ethernet is a wired networking technology used to connect devices using a physical cable, allowing them to communicate or access the internet.

### How It Works:
1. Plug one end of an Ethernet cable into your PC's Ethernet port.
2. Plug the other end into a modem or router.
3. Your PC can now connect to the network or internet.

---

## Ethernet vs. Wi-Fi

| **Feature**   | **Ethernet**                       | **Wi-Fi**                             |
|---------------|------------------------------------|----------------------------------------|
| Signal        | Through cable (copper/fiber)       | Through air (radio waves)              |
| Speed         | Faster                             | Varies, can be slower than wired       |
| Stability     | More stable                        | Can be affected by walls, distance     |
| Security      | More secure                        | Less secure                            |
| Mobility      | No (wired)                         | Yes (wireless mobility)                |

---

## Comparison of Network Types

| **Network Type** | **Definition**                                                         | **Type**                  |
|------------------|------------------------------------------------------------------------|---------------------------|
| Ethernet         | A specific wired technology for local area networking.                 | LAN Technology (Wired)    |
| Wi-Fi            | A specific wireless technology for local area networking.              | LAN Technology (Wireless) |
| LAN              | A network within a limited area (e.g., home, office).                  | Local Network             |
| WAN              | A network over a large geographical area, connects multiple LANs.      | Wide Network              |
| Internet         | A global system of interconnected networks using the IP protocol.      | Global WAN                |
