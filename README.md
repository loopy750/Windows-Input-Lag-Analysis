![BF4 Mouse Input Lag](/bf4_mouse_input_lag.gif)

# Windows Input Lag Analysis

### A quick overview of mouse input delay in Windows 10

Video on the bcdedit command **useplatformtick** that some "tweakers" use, and why that's a bad thing:  
https://www.youtube.com/watch?v=Rnk8mCB0IpU

#### What this is:

Very basic analysis to validate or invalidate online claims regarding input latency and older Windows versions being better for gaming.

240 FPS camera was used for testing mouse movement and input delay. MSI Afterburner 4.6.2 used for FPS measurements.


#### What this isn't:

An in-depth analysis into multiple games and how they function under multiple Windows versions using a high-speed camera, such as 1000 FPS.

There are several YouTube channels and GitHub accounts of users who spend hundreds of hours testing various scenarios. I don't have any plans to do that.

I performed 'just enough' testing to draw my own conclusion about which Windows OS to use and how much 'tweaking' I should do. Some may consider the lack of information inconclusive, and that's fine. It should all be weighed up against other online evidence, including any of your own, until you are happy enough with your own conclusion.

Results are incomplete and I may or may not ever update them.

* OS Version: **Windows 7 (7601 SP1) [MBR]**\
Nvidia Driver Version: 442.19\
Performance in game (FPS)+: not tested\
Performance in game (mouse input lag)+: not tested\
Performance on desktop (mouse input lag): 2-3 frames @ 250Hz (~10ms)

* OS Version: **Windows 7 (7601 SP1) [GPT]**\
Nvidia Driver Version: 442.19\
Performance in game (FPS)+: 0.1%: 255, 1%: 350, Min: 439, Avg: 534, Max: 605\
Performance in game (mouse input lag)+: 3 frames @ 250Hz (~12ms)\
Performance on desktop (mouse input lag): 2-3 frames @ 250Hz (~10ms)

* OS Version: **Windows 10 (1709) Build 16299.15**\
Nvidia Driver Version: 442.50\
CPU-Z: 591, 6030\
Cinebench R15: 2222\
AIDA64 (Memory): 50790 MB/s, 53570 MB/s, 50737 MB/s, 45.3 ns\
Performance in game (FPS)+: 0.1%: 353, 1%: 407, Min: 450, Avg: 549, Max: 650\
Performance in game (mouse input lag)+: 3 frames @ 250Hz (~12ms)\
Performance on desktop (mouse input lag): 2-3 frames @ 250Hz (~10ms)

* OS Version: **Windows 10 (1809) Build 17763.1**\
Nvidia Driver Version: 442.50\
Performance in game (FPS)+: not tested\
Performance in game (mouse input lag)+: not tested\
Performance on desktop (mouse input lag): 2-3 frames @ 250Hz (~10ms)

* OS Version: **Windows 10 (1909) Build 18363.693**\
Nvidia Driver Version: 442.50\
CPU-Z: 596, 6133\
Cinebench R15: 2232\
AIDA64 (Memory): 50648 MB/s, 53285 MB/s, 50309 MB/s, 45.5 ns\
Performance in game (FPS)+: 0.1%: 359, 1%: 399, Min: 442, Avg: 540, Max: 655\
Performance in game (mouse input lag)+: 3 frames @ 250Hz (~12ms)\
Performance on desktop (mouse input lag): 2-3 frames @ 250Hz (~10ms)

* OS Version: **Windows 10 (2004) Build 19041.113**\
Nvidia Driver Version: 450.12\
CPU-Z: 596, 6135\
Cinebench R15: 2233\
AIDA64 (Memory): 50625 MB/s, 53357 MB/s, 50519 MB/s, 45.3 ns\
Performance in game (FPS)+: 0.1%: 345, 1%: 405, Min: 460, Avg: 555, Max: 660\
Performance in game (mouse input lag)+: 3 frames @ 250Hz (~12ms)\
Performance on desktop (mouse input lag): 2-3 frames @ 250Hz (~10ms)


Conclusion: I'll be using the latest version of Windows for maximum performance. Common tweaks found online made no difference to the results, not with a 240 FPS camera anyway.

Hardware:

· CPU: Intel Core i9 9900K 3.60GHz (@ 5.00GHz)\
· GPU: ZOTAC GeForce GTX 1070 AMP! Extreme (@ 2100MHz core / 9060MHz memory)\
· RAM: Corsair Vengeance LPX 3200MHz CL16 DDR4 32GB (4x8GB) (@ 3400MHz CL15)\
· Motherboard: Gigabyte Z390 Aorus Elite\
· Monitor: BenQ XL2720Z 27 inch 144Hz (@ 250Hz)\
· Mouse: Zowie FK1

###### \* Some of the usual tweaks you see online, however most have little if any impact on performance. disabledynamictick = Yes, UMP apps removed, slimmed down Nvidia driver, Spectre and Meltdown disabled, services disabled (5 in Windows 10, several including DWM/Themes in Windows 7), etc.

###### \+ Game = Battlefield 4 using "Test Range" map for 120 seconds.
