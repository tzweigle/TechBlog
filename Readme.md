﻿﻿﻿**CIS 141 TechBlog**
##**Tyler Zweigle**
###**Quick Bio**
I am 31 years old and have lived in Grass valley all my life.
My Interest include

1. Video games

1. Cosplay

1. Anime 

I have been married for ten years and have a 9 month old daughter. I have also been a home owner
for the last five years. I hope to pursue an career in IT. 

####**Skill 1.1-Prepare for installation Requirements**
A. Determine hardware requirements

* Processor:1 ghz or faster
* RAM:1GB for 32, or 2 GB for 64
* Hard disk space: 16 GB for 32 bit os or 20 GB for 64
* Graphics Direct X9

B. Determine Appropriate edition 

* 10 home
* 10 pro
* 10 enterprise
* 10 mobile
* 10 mobile enterprises
* 10 education
* 10 IO,T Core

C. Deployment options

**1.Wipe &load/Clean**

* Capture data settings
* Deploy custom os
* Inject drivers
* Restore data settings
* usmt:capture tool for data
* DISM; disk image management tool

**2.In place upgrade**

* Preserve data
* Install standard os
* Restore everything

**3.provisioning**

* Transform into an enterprise device
* Remove unneeded components
* Add organizational apps
* Add organizational configuration


###**August 27th Warm up**
There are currently 62 computers in the room, that includes PC's in the class as well as every
student with a smartphone and the odd personal laptop.

####**Tech Blog prompt 1**
For this assignment I used the computer that i currently use at my place of work.
The primary users for this desktop computer would be basic data entry workers, using a bare minimum of applications outside of work parameters
of the given programs.
##**The specs for this computer are as follows**
* Running windows 7 Pro ver 6.1
* Processor Intel I5 3.2 Ghz
* Ram is 8 GB and using a SSD for hard drive
With this knowledge I can safely assume that this workstation can be upgraded to windows 10.
My work place currently takes advantage of a shared server memory called the H drive and with this knowledge i would suggest using a Wipe and load migration
I used the simple properties section to see my hardware and with the information i have gathered i would recommend installing windows 10 Pro.
This is a professional workplace with many employees, so the features of bitlocker as well as the ability to assign access level and access the computer
remotely makes Windows 10 pro the prefect choice. 

###**September 27th Warm up**
I found a few recent articles in regards to Google privacy concerning Mastercard customers. Apparently a long standing
4 year deal has just been closed between Google and Mastercard that allows google to track purchases made while offline.
we have given google permission to track all of our online activity (more or less) and this wouldn't be much different
I feel as long as both companies are forthright, which at this point they have not been, customers don't have much to fear.
her is the link to one of the articles I've located.

[Google's Mastercard deal] (https://thehackernews.com/2018/09/google-mastercard-advertising.html)

###in class notes 9/10
Using VMware player 14 to install virtual machine. 
VM windows install key 8PHVNVYCHHQKM76CQM93C37Y9

####**Tech blog 1.2 prompt**

**1.** Why would a user be interested in multiple partitions on a hard drive?  

 * Use a Windows tool (GUI or CLI) to create a partition and describe the steps that you took to create multiple partitions.

 * Multiple partitions on a hard drive are helpful for organization, especially for the purpose of later installing multiple drives or multiple users are present.
 * Using the disk management tool i cant split my available space and label it accordingly for future use. I can also reallocate my available space.

**2.**Describe each step that requires "user attention" during the clean installation of Windows 10.

* I needed to select to install from the DVD-rom in BIOS
* I was required to supply a key and choose language options
* I also was told to log in or create user information for the computer

3.What is one Windows Feature that you chose to add after installation?  How did you add that feature?

* Hyper V (which seems to assist in server management) is a feature i added after the fact using optionalfeatures.exe

####**Tech Blog 1.2 blog part 2**

Answer the following questions and, when applicable, be sure to include screenshots and links to the Internet:

**1.** On Windows 8.1, install an application that may not be Windows 10 compatible.  Why do you think this application may not be compatible?

* I installed VLC media player on my windows 8.1 machine.

**2.** Create a very special text file that you would like to be included in the upgrade.  What is in the file?  Where is it located?

* I created a Txt file on my desktop that says hello world.

**3.** Describe each step that requires "user attention" during the in-place upgrade of Windows 10.

* First it asked me to install any appropriate updates that have come for windows 10 prior to today current version. for personal use this would be fine but for the prompt I opted out. I was then asked to agree to the user agreement. next the system checked to see if my hardware, memory etc was acceptable for windows 10. the update auto selected what version to upgrade to. I was given the option of what files to keep during the upgrade(files, apps or both).


**4.**  In what ways was the upgrade process similar to  the clean install process?  How did it differ?

* the clean install seemed to be faster that the upgrade. in addition I was prompted with similar customization options prior to launch. during the launch, a Microsoft edge page was on display inviting me to further customize and explorer new features 

**5.** Are there any additional folders that remain after the upgrade process is complete?  What are the contents of those folders?

* My txt documents remained where i had left them and the program VLC media player continued to run. Within the C drive I have a file named windows.old which contains an older version of windows that I have updated from. it was roughly 12.5 GB of space and if deleted would not affect my performance.


##**09/17/2018 warm up (Patch Tuesday)**
Patch Tuesday is the unofficial name given to Microsoft launch of updates given for their soft ware products. it occurs on the second and sometimes fourth Tuesday of each month.
Microsoft has been known to release a larger number of updates in even-numbered months, and fewer in odd-numbered months. the follow up
to this day is known as exploit Wednesday, in which developers and independent users alike, try to find any vulnerabilities in these updates.
September 11th was The latest Patch was on August 14, 2018 and consisted of 70 individual security updates, correcting 63 unique issues across Microsoft Windows operating systems and some other Microsoft software.
This included the Zero day flaw which allowed people to alter user privileges. 

[Most recent update] (https://krebsonsecurity.com/2018/09/patch-tuesday-september-2018-edition/)


####**Skill 1.3 Technical Blog Prompt**
**1.**Create a list of hardware that a user might have that require a driver installation.

* A practical list of devices that might require a drives would be the
	1.Optical disk drive 
	2.Printers 
	3.External microphones
	4.USB and external hard rives 

**2.**Locate a device from your list (for example, printer or external storage) and install it on Windows 10 (VM in class, machine at home, maybe the host machine in class?)

* I used my SanDisk cruzer USB thumb drive

**3.**Locate the version of the driver and see if it is the most current version available (in the case of the printer, check the manufacturer website).
If necessary update the device.

* The current version was up to date because Microsoft was the digital signer. this means that it would call its version directly from Microsoft therefore insuring an up to date driver.

**4.**Disable the device.  Does this affect Windows performance?  What happens when you disable other devices?  Try disabling your network card, how was that experience?

* When I disable my current device it gives me a device not recognized error and offers me a fix solution. When I disable my network card, like the name suggests I lose any network connection and cannot access the internet.

**5.**Why would I disable updates over metered connections?  Capture a screenshot of the screen on which you disabled this feature.

Image
![Screenshot](F:\CIS 141Metered Connection) 

* Disabling Metered connection allows you to set upload, download bandwidth in regards to your network connection. This is mainly importantin regards to LTE imbedded and Mobile hotspots as you will want to control the amount of data spent. 

**6.**Perform a "rollback" of a driver update.  Note, you will need to access a different USB device if you have been working with a printer.

* I was able to preform a rollback on my display adapter in my devices manager. it did not create a interference with normal operating of my machine but I was prompted with a popup to search for recent driver updates. 

**7.**After installing a USB microphone, a system has extremely poor performance.  How would you check to see if the performance issues are related to the USB microphone?

* The simplest answer would be to attempt to update the driver, if that doesn't work a simple uninstall/reinstall should do the trick.


###**September 24th Warm up**

Microsoft just made the announcement that windows 10, through Azure, will be able to fully run on the cloud. This means that a fully supported Microsoft virtual machine will become available along with their other cloud services and outlook 365. 
My feeling is that this is Microsoft leaning into Azure, a provider of many of their cloud based application, to further utilize windows 10 running on any and all available hardware. This would also include mobile and surface base operations for a company. 
This also means that you hardware wouldn't need to match the applications that you need to use, you'd only require a fast internet connection.



####**Skill 1.4 Tech blog**

First and foremost, windows 10 (depending on you device)takes advantage of the start menu and tiles.
In order to customize the features:

1. -Right click the start button
2. -Click settings
3. Click personalization
4. Select the start tab
5. From here you are given the option to Show more or less tiles, present as an app list show recent apps, show most used apps, use start full screen, choose which folders appear on start.

6. By right clicking any of the then shown tiles gives you further personalization options such as selecting size grouping tiles and even turning some tiles live.

7. Following the same steps, you can access other customization options such as

8. Background
9. Colors
10. Lock screen
11. Themes
12. Start
13. Taskbar
14. Next you will find the option to configure for convertible devices, incase your device can act as a tablet
15. Right click start
16. Click settings
17. Click system
18. Select tablet mode
19. Here you can select how you wish to have the interface launch. your choices are use tablet mode, use desktop mode or use appropriate mode for the hardware.
20. You can also elect to have a notification when theses changes happen. 
21. To set up the use of multiple desktops,
22. Click the task view button
23. New desktop
24. This will allow multiple fully customizes desktops for personal use or multiple usurers.
25. Lastly, it is important that you are familiar with your action center taskbar. To customize the action center,
26. Right start button
27. Select settings
28. Select system
29. Click notifications and actions.
30. Now you can select which items send you notifications as well as which action tiles are available in your quick select.


##**Warm up**

What is a UAC?

UAC stands for User Account control, this is the standard that Microsoft has introduced to differentiate what a user on a computer can do. 
When a user that has been given lower level permission on a specific machine attempt to do something that might cause data loss or harm 
A UAC alert pops up letting the user know they aren't an administrator.

When did Microsoft introduce UAC?

it was rolled out with windows vista.

Is the experience the same in the host computer as in a Virtual machine?

With my host computer and my VM, I am registered as an admin, which mean i am still alerted to changes being made but I am not prevented from doing so.

**-----1.5 key concepts (class Notes)-------**

Enterprise implementations 
Group policy is laid out with LSDO
default settings on a computer is always local "L" of LSDO. can be trumped by S which is sight
Site is permissions specific to a location of a computer or device
Domain is over arc above the other 2
Organizational units or OU can be a group of users or devices within the rest

[LOSD Breakdown] (http://www.omnisecu.com/windows-2003/group-policy/group-policy-processing-order.php)

####**Skill 1.5 challenge**

1.Block Microsoft accounts?

 * in my Local policies and the security option I am given the ability to either make it so a MS account cannot be added or worse yet that one cannot be logged into. making the machines OS all but worthless.

2.Change the password limit to 10?

* I can alter the password length (in my VM) using security settings, to account polices and then to password policy. Max it will allow is 20 characters and putting 000 will not require a password.

3.Disable secure desktop in UAC?

 * A Secure Desktop is a desktop that is out of scope of other applications accessibility that will display when a UAC alert is prompted. you can turn this setting off in Local policies, security options and scroll down to User account control: switch to the secure desktop when prompting for elevation. This will prevent the darkened background and locking of accessibility when UAC would prompt. 

Group policy editor changes the registry that windows loads

--Lets play around with local group policy editor

--centralized control for

1.user settings

2.computer settings

3.control and deployment of applications

4.control user experience

what does it change? 
gpupdate/force to change effective date of GPO change or control a remote machine.

###**October 8th Warm up**

Windows 1809 bug?

 * Microsoft 1809 update is being delayed because of a software bug that seems to be deleting user information. quite shocking that this was not caught in testing.

####**Skill 2.1 Blog prompt**

Create a "Top 5" list of Windows 10 networking best practices, tips, tricks and troubleshooting strategies.

1. If you are currently using a Limited data plan for your network connection, you may want to enable a metered connection. this will allow you to limit data usage from certain apps and set a data limit allowance for your computer. If data limit is not an option, disable this feature for slightly better performance.

1. Along this same vein you can restrict background data use in the "background data" option in network settings. this can prevent auto updated from Microsoft or their affiliated applications. 

1. It is a good practice to know you current IP address. This information can be located in your cmd line and entering in ipconfig or ipconfig/all. knowing this will allow you to validate outside interactions with you network.

1. Within your network settings, change adapter options and there you can alter your Ip address as well as what you DNS servers are. With this you can sign in to a trusted or preferred server.

1. Though you may never use them, you should be aware of VPN connections. A virtual private network can be used to further secure any internet usage and protect you against outside threats. There are free and paid versions on VPNS that focus on multiple levels of 

####**Skill 2.2 Tech blog**

###Scenario 1: Creating a Large Volume

You have a new desktop running Windows 10. However, you try to copy your file repository and find out that you do not have enough disk space. You have 400 GB of free disk space on your C drive and you have 3 smaller 500 GB drives. What can you do?

 * You have a couple of different options in order to optimize your drives, but the one I would suggest using Storage Spaces. With Microsoft Storage Spaces you can easily utilize RAID like technologies without purchasing new hardware. Benefits include
- Easily expandable storage with different size drives
- Security of Mirroring your drives to back up data
- Striping drives in order to maximize performance

###Scenario 2: Configuring a Storage Space/Storage Pool
You create a new storage pool for the following disks on your Windows 10 computer:

  
- Serial ATA (SATA): 1 TB
- Serial Attached SCSI (SAS): 1 TB
SATA and SAS are two different types of drives with different connectors/interfaces.

###what is the maximum size you can allocate for your new storage space?


- Using Storage Spaces will allow you to tell your computer to read the new drive pool as either a HDD or SSD and in doing so allocate the maximum amount to your storage space. So with both of your drives you can allocate 2TB of storage space.
