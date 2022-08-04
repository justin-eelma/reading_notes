# System Log Analysis, Registry, Control Panel
## Windows Registry Demystified: What You Can Do With It
The Windows Registry is a database where Windows (among other programs within Windows) can store configuration settings. 
Settings are both system wide, and specific to accounts on the OS; System wide registry settings are located in \Windows\System32\Config; user specific keys are located on \Windows\Users\Name in a NTUSER.dat file. 
The registry contains "keys", and within keys are "values" that contain variables, in other words, configuration settings. In the registry, you'll see groups of keys and values, known as "hives".
The registry can be accessed by all programs, which share universal settings for the user, as opposed to the older way of storing configuration settings accross the OS. But this is up to the discretion of the developer whether or not, and to what extent, to use the registry. 
#### Why Edit the Registry?
Registry Editor allows the user to edit the registry, this action is known as "registry hacking". Professional enivronments can do this through "Group Policy" which affects entire active directories. It is recommended to back up the registry before altering it because the wrong edit could render the system unbootable. The registry can be edited through .reg files, which can be created or downloaded, and then applied to the registry --.reg files perform similar to a script containing multiple settings and actions. List of Registry Hacks available at: https://www.howtogeek.com/370022/windows-registry-demystified-what-you-can-do-with-it/
