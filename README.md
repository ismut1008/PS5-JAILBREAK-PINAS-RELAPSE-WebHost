
# PS5-JAILBREAK-PINAS-RELAPSE-WebHost
Webhost base on Karo's version of Relapse for FW7.00 to FW13.60 with UNLI PAYLOADS ability where users can add Payloads on PS5's INTERNAL STORAGE and will auto populate on the webhost itself, without rebooting.

<img width="2048" height="1280" alt="pic1" src="https://github.com/user-attachments/assets/e0168494-6ab8-4ce9-86a7-48cf7d8a6cf7" />

What if offers?
--------------------

- MEDIA TAB "shortcut icon" for quick navigation of the page
- COMES WITH 16 PAYLOADS
- UNLI PAYLOADS feature (add Payloads on PS5's INTERNAL STORAGE and will auto populate on the webhost itself, without rebooting)
- base on Karo's Relapse Webhost with Stability Fix

UNLI PAYLOADS FEATURE
--------------------

- UNLIMITED PAYLOADS (users can add payloads on console's internal storage and will auto populate on the webhost itself, without rebooting)
    - run web file manager, ftp or any payload manager then copy the payloads you want on the designated path (you can add and delete payloads that you want, except the pre-embedded payloads)
    - comes with pre-embed "lapy_jb_daemon" payload, so you can use PS5-Xplorer app to transfer payloads that you want or you can also use bfpilotv044.elf and web-file-mgr-v1.6.elf
      
    - payload path:
    /user/home/(user-id)/webkit/shell/esp-payloads

    - payload path example:
    /user/home/(user-id)/webkit/shell/esp-payloads/onionhen.elf

    
PS5-Xplorer fpkg link:
https://pkg-zone.com/details/LAPY20011

----------------
HOW TO:
----------------

----------------
not jailbroken:
----------------

- use dns: 62.210.38.117, open users guide(echo's host), select playstation 5 then enter "https://ps5jailbreakpinasrelapse.netlify.app/" on the address bar and hit "GO". Once jailbroken, install the media tab fpkg shortcut, then no need to go to users guide again.

----------------
jailbroken:
----------------

- just install the media tab fpkg shortcut

Fpkg Media Tab Shortcut Installer:
https://www.mediafire.com/file/8suws6xx0kynqaz/PS5_Jailbreak_Pinas_Relapse_Media_Tab.pkg/file

--------------------------------------------
Autoload Payload
--------------------------------------------

PS5 AUTOLOAD folder structure:

/data/ps5_autoloader/
For example:

     /data/ps5_autoloader/
     ├── autoload.txt
     ├── ftpsrv-ps5-0.19.elf
     ├── shadowmountplus.elf
     ├── kstuff.elf
     ├── elf-arsenal.elf
     ├── lapy_jb_daemon.elf
     ├── pegasus_dl.elf
     ├── pldmgr_v0.3.6.elf
     └── ps5shopappkg-dpi.elf

--------------------------------------------


autoload.txt
--------------------------------------------

autoload.txt controls the payload execution sequence.

Example:


--------------------------------------------
      !4000
      ftpsrv-ps5-0.19.elf
      !4000
      shadowmountplus.elf
      !4000
      kstuff.elf
      !4000
      onionhen.elf
--------------------------------------------
     
Entries beginning with ! represent a delay before continuing with the next entry.
--------------------------------------------

For example:

      !4000 (means a delay of approximately: 4000 ms)
      onionhen.elf (the following line specifies the ELF that should be loaded)

--------------------------------------------

Quick Q and A
--------------------------------------------

- Q: Why does Relapse "does not support offline caching"?
- A: Relapse has an "klsr" issue, where the exploit would not run without an active network connection (with or without internet will do, just like VUEJB on PS4... we don't know if this can be resolve in the future)


--------------------------------------
Special Thanks
--------------------------------------

Arksama https://github.com/ArkSama
Idlesauce https://github.com/idlesauce
Stooged https://github.com/stooged
Echostretch https://github.com/EchoStretch
Drakmor https://github.com/drakmor
TheOfficialFloW https://github.com/theofficialflow
BestPig https://github.com/BestPig
VoidWhisper https://github.com/voidwhisper-ps
cy33hc https://github.com/cy33hc
Jordy https://github.com/jordyidk
notmajor https://github.com/notmaj0r
vladimir-cucu https://github.com/vladimir-cucu
Pippo, kerrdec97, Speed-007, Mr.Cat, Karo all devs, dumpers, testers
