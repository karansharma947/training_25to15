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
