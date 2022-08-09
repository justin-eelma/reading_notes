# Data Restoration, Startup Repair, and Secure Disposal

## SSD Data Recovery Best Practices

Unlike HDD, SSD's do not have audible signals to signify a faulty drive. 
Common indicators that your SSD may be approaching its read/write cycle:

- Bad Blocks: data storage and retrieval functions become delayed or non-functional 
- File System Repair: the file system notifies the user that the system needs to be repaired without a physical defect
- Crashing: or intermident crashing - the computer crashes during boot up but seems to work fine after several reboots
- Read-Only Mode: the drive ceases writing functionality but can still operate in read-only to backup and thus recover valuable data. It is inadvisable to depend on this SSD again as it could corrupt and destroy data further down the line.

How to fix a failed SSD:

- Format drive, reinstall OS.
- Power cycle the SSD: disconnect and re-aply power. 
- Idling in the Boot Menu: similar to a power cycle, but stay on the BIOS screen.
- Updating SSD firmware: specific to manufacture. 
- Updating Drivers: through Device Manager. 


## How to Erase a Hard Drive Using DBAN

DBAN stands for Darik's Boot and Nuke.

The program is designed to securely erase a hard disk until its data is permanently removed and no longer recoverable, which is achieved by overwriting the data with pseudorandom numbers.

DBAN comes in an ISO format which is an image file designed to be bootable from local storage, either from a CD or USB stick. 
When booting into DBAN, it looks similar to the BIOS settings of your computer. The F3 key enters the quick command menu where you can choose how to "nuke" your harddrives:

- dod - DoD 5220.22-M
- dodshort - Same as dod except only 3 passes are run instead of 7
- ops2 - RCMP TSSIT OPS-II
- gutmann - Gutmann
- prng - Random Data
- quick - Write Zero

The autonuke command is the same thing as dodshort, and is the recommended way of destroying your harddrives. 
