
# Day 1 - 25th June 2025

##  What I Learned Today

###  Linux vs Windows

Today, I learned about *Linux* and how it is different from *Windows*:

- Linux is *open-source*, which means anyone can see its code and change it.
- Windows is *closed-source*, and only Microsoft controls it.
- Linux is mostly used by developers and in servers.
- Windows is used more in personal computers and offices.
- Linux has many versions like Ubuntu, Fedora, etc.
- Windows has only a few versions like Windows 10, 11.

###  Product vs Service vs Startup

I also understood the difference between:

- *Product*: A thing you can use or buy. Example: a mobile app or software.
- *Service*: Work done for someone. Example: food delivery, repair service.
- *Startup*: A new company with an idea to solve a problem. It can give product or service.

###  Installing VirtualBox and Ubuntu

We also learned how to *install VirtualBox*, which is a tool to run another operating system inside our computer.

Steps I followed:

1. Downloaded and installed *VirtualBox*.
2. Downloaded the *Ubuntu ISO file* (a Linux OS).
3. Created a new machine in VirtualBox.

# Day 2 of learning something new

## Booting and its types:
Booting is the process of starting up or restarting a computer, which involves initializing hardware, loading the operating system, and preparing the computer for use.
### Types of Booting:
- **Cold boot/ Hard boot:**
  This refers to starting the computer from a completely powered-off state.
- **Warm boot/ Soft boot:**
  This is when the operating system alone is restarted wihtout turning it off.

  ## Introduction to Linux Shell and basic commands:
### Kernel:
- The kernel is a computer program that is the core of a computer’s operating system, with complete control over everything in the system.
- Think of it as as Chef working in a hotel. You as a coustmer can't see the chef working but get your order (output).

### Shell:
- Shell is a special user program that provides an interface for the user to use operating system services.
- Using the same scenario, think of shell as a waiter, who takes your order (input) and gives it to the chef (Kernel).

Shell is divided into two categories-
1. Command Line Shell:
   
   ![1aewnq3r](https://github.com/user-attachments/assets/305cc43b-7804-47e1-ac08-7d82b372af07)


2. Graphical shell:

   ![image](https://github.com/user-attachments/assets/062b091d-d61d-466b-b6be-37b9057685d0)


   

**Types of shell:**
- BASH (Bourne Again SHell)
- CSH (C SHell)
- KSH (Korn SHell)

 ### File system structure:
| NAME | DESCRIPTION                                                                   |
| --------- | ----------------------------------------------------------------------------- |
| `/`       | The slash / character denotes the root of the filesystem tree. exp: Trunk of a tree.|
| `/home`   | Contains personal directories of user. |
| `/lib`    | Contains system libraries and critical file.|
| `/bin`    | Contains user executable files.|
| `/boot`   | Contains all the files that are required for booting.|
| `/dev`    | Contains hardware and development files.|
| `/media`  | Mount points for removable media.|
| `/mnt`    | Temporarily mounted filesystems.|
| `/opt`    | Contains optional files. |

## Commands:
- `date`: Returns current date.
- `whoami`: Returns the current domain and user name.
- `ls` (list): Returns content of a specified Directory
- `cd`: Changes directory.
- `mkdir`: Creates a new directory.
- `pwd`: Prints the current working directory.
- `touch`: Creates empty file.
- `cat`: Creates file with content.
- `whereis`: Finds the location of specified file.
- `mv`: To move or rename a file.
- `cp`: To copy content of a file to the other
- `whatis`: Gives short description of a command.
- 
  # Every image of above command that i used in my virtual box:
  ![VirtualBox_Ubuntu_26_06_2025_10_32_11](https://github.com/user-attachments/assets/13602ddf-9a80-489e-b168-32e780f1a29f)

  ![VirtualBox_Ubuntu_26_06_2025_10_52_44](https://github.com/user-attachments/assets/844de76e-d717-43c9-8100-7ef5505cfa43)

  ![VirtualBox_Ubuntu_26_06_2025_11_16_37](https://github.com/user-attachments/assets/93d5c676-fd03-49c7-9c63-c0d078ba8601)

  ![VirtualBox_Ubuntu_26_06_2025_11_22_35](https://github.com/user-attachments/assets/22b58721-3634-43eb-9e63-c0190dbd0cf2)

  ![VirtualBox_Ubuntu_26_06_2025_11_41_32](https://github.com/user-attachments/assets/6aea5baf-6888-4672-996a-6ce7ac3e4ef0)

# Day 3 of learning something new:
## Permissions & Shell programming:
### File and directory permissions:
`chmod` (Change mode): It is used to change the access permissions of files and directories.

Some different chmod permission notations are:<br>
 `chmod +x test.sh`:  Gives permission to run the script.<br>
 `chmod 444 test.sh`: Changes file to read-only
 `chmod 644 test.sh`: Changes file such that only owner can edit it. For others it remain read-only.

### Redirection:
 It allows user to redirect input and output functionalities to the files or folders. 

**Types of Redirection:**
1. Overwrite Redirection (For stdout):<br>
Redirects the standard output of a command to a file. If the file exists already contain script, it will be overwritten.<br>
">" standard output<br>


2. Append Redirection (For stdout): 
Append the output to the file without compromising the existing data of the file.

3. Overwrite Redirection (For stdin):<br> 
Redirects the standard input of a command to a file.<br>
"<" standard input

## Screen shot as i follow the above command some may be can reapeat for my clarity:

![VirtualBox_Ubuntu_27_06_2025_11_56_30](https://github.com/user-attachments/assets/7ae463fa-c180-4dfa-b47d-568fecb1b8d4)
![VirtualBox_Ubuntu_27_06_2025_12_00_22](https://github.com/user-attachments/assets/0f05cb69-600e-402a-909f-20f44ce233cf)
![VirtualBox_Ubuntu_27_06_2025_12_02_29](https://github.com/user-attachments/assets/f7dabbcc-8480-4397-ac6f-49ef42fa9127)
![VirtualBox_Ubuntu_27_06_2025_12_03_36](https://github.com/user-attachments/assets/54870b60-91cb-4733-8134-4b07af78cb99)
![VirtualBox_Ubuntu_27_06_2025_12_05_14](https://github.com/user-attachments/assets/4ae60a1e-87c7-4a99-9f93-b65331784b32)
![VirtualBox_Ubuntu_27_06_2025_12_06_27](https://github.com/user-attachments/assets/e4f7de29-d1a1-45ac-b25c-dab1d0ef3670)
![VirtualBox_Ubuntu_27_06_2025_12_08_33](https://github.com/user-attachments/assets/aa496a2d-e381-45a2-ade9-ac274a03562e)

### Shell programming:
1. Use of variables:
2. Multiplication table of any number:
3. Comparing two variables:

![VirtualBox_Ubuntu_29_06_2025_10_37_05](https://github.com/user-attachments/assets/4b2ac37b-e4d5-4500-af00-96fa3313641d)
![VirtualBox_Ubuntu_29_06_2025_10_45_09](https://github.com/user-attachments/assets/dff6799c-c032-483d-8840-521b62dcaabe)
![VirtualBox_Ubuntu_29_06_2025_10_46_42](https://github.com/user-attachments/assets/cf435abe-be0f-4e42-8d3e-b8bf9bae5c90)
![VirtualBox_Ubuntu_29_06_2025_12_54_42](https://github.com/user-attachments/assets/2f15e5a9-83ad-403f-8bb4-7f1540d5a43d)
![VirtualBox_Ubuntu_29_06_2025_12_56_27](https://github.com/user-attachments/assets/222ea98b-77be-4235-9fb6-45be5788831d)
![VirtualBox_Ubuntu_29_06_2025_12_56_53](https://github.com/user-attachments/assets/8a7a316e-dcf0-4b7e-9a56-e707a564922a)
![VirtualBox_Ubuntu_29_06_2025_12_43_19](https://github.com/user-attachments/assets/d766826e-7965-410d-afa4-85545dd25d05)
![VirtualBox_Ubuntu_29_06_2025_10_15_27](https://github.com/user-attachments/assets/fb76590c-cda8-4ce3-9337-a264b357fb63)
### Pipe '|':
The pipe is used to combine two or more commands, and in this, the output of one command acts as input to another command.

*Pipe can be used for filteration.* <br>
Multiple pipes can be used such as:

*to find number of file/directory with 't'* <br>






  
  
