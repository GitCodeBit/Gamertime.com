==================================================================
Medal of Honor Allied Assault(tm) Version 1.0
Read Me File
December 13, 2001
==================================================================

Thank you for purchasing Medal of Honor Allied Assault. This
readme file contains last minute information that did not make it
into the manual, as well as more detailed information on various
features already covered in the manual.

==================================================================
System Requirements
==================================================================

MINIMUM CONFIGURATION

Windows XP, Windows Me, Windows 2000, Windows 98, or Windows 95 
(Windows NT is not supported)
450 MHz Intel Pentium II or 500 MHz AMD Athlon processor
128 MB RAM 
8x CD-ROM/DVD-ROM drive 
1.2 GB free hard disk space plus space for saved games (additional
space required for Windows swap-file and DirectX 8.0 installation)
16 MB OpenGL capable video card using an NVIDIA GeForce3, NVIDIA
GeForce2, NVIDIA GeForce 256, NVIDIA Riva TNT2, NVIDIA Riva TNT,
ATI Radeon, ATI Rage 128 Pro, ATI Rage 128, PowerVR3 Kyro II, or
PowerVR Kyro chipset with OpenGL and DirectX 8.0 compatible driver
DirectX 8.0 compatible sound card
Keyboard
Mouse

RECOMMENDED

700 MHz or faster Intel Pentium III or AMD Athlon processor
32 MB or greater supported OpenGL capable video card with OpenGL
and DirectX 8.0 compatible driver


The following 16MB or greater 3D accelerators are not fully
supported and do not work properly with the game:

-3Dfx Voodoo 4 and 5
	No intro movies play. Various textures are corrupted.
        Breakable windows are opaque until broken. Once
        broken they have a corrupted texture.
-3Dfx Voodoo 3
	Various textures are corrupted. Breakable windows are
        opaque until broken. Once broken they have a corrupted
        texture. Transparent red bomb placements are invisible.
-3Dfx Voodoo Banshee cards
-Matrox G400 and G450
	Frame rate is often below 10 frames per second even at
        the lowest video settings. Level load times are longer
        than normal.
-Nvidia Vanta
        These older cards yield a frame rate that is often
        below 10 frames per second even at the lowest video
        settings.
-PowerVR NEON 250 cards:
	Video Logic PowerVR Neon 250
-S3 Savage 2000 cards:
	Diamond Viper II
-S3 Savage 4 cards:
	Diamond Stealth III S540
	Diamond Stealth III S540 Extreme
-SiS 300 cards

The following sound card isn't supported:
-Ensoniq SoundScape PNP

The following sound cards have known problems:
-Diamond Monster Sound MX 400
	Requires turning off "DirectSound Acceleration" in the
	driver. See the detailed explanation under
	"Troubleshooting."
-Creative Labs Audigy
	Currently hardware acceleration for this card does not
	work correctly.


==================================================================
Hard Drive Space
==================================================================

1.2 GB of free hard drive space is required to install the game.

More space is also needed for save games. Each save game is nearly
0.5 MB and there are 34 single-player levels in the game. At the 
start of each level a new auto-save game is created. So another
30 MB of space is a good idea for both auto saves and manually
saved games.

Additionally, Windows will require its own free hard drive space
for its operating system (virtual memory). The amount of space
required varies from 100 MB to 250 MB. If you have less than
250 MB free space you may encounter the following message in an
error dialog:

	"Ran out of virtual memory"

If you encounter this message, free up some hard drive space.


==================================================================
Installing DirectX 8.0a
==================================================================

If you declined to install DirectX 8.0a when initially installing
Medal of Honor Allied Assault, you can install at a later time by 
simply inserting Disk 1 into your CD-ROM drive and clicking on the
"Install DirectX" link of the Medal of Honor Allied Assault window
that appears. If the window doesn't automatically appear, run
"Autorun.exe" from within Disk 1. You can also directly run
"dxsetup.exe", located in the DirectX directory on the install
CDROM. This is found on Disk 1 under the "redist\directx80a"
folder. Just double-click on "dxsetup.exe".


==================================================================
Improving Gameplay Performance
==================================================================

Some machines will benefit from experimenting with your
video/sound options:

	- From the Main Menu choose the "Options" menu signified
          by some electronic equipment towards the left side on
          the table. Then select the "Video" menu, select "Texture
          Detail" and choose "LOW".

	- Also from the "Video" menu uncheck the "WALL DECALS"
          check box. This will prevent the game from creating 
          bullet marks on walls and should improve performance.

        - Try reducing your video resolution to 640x480 or even
          512x384 in your "Video" menu. The lower the resolution,
          the easier it is for your computer to run the game.

	- From the "Video" menu you can try lowering your color
          depth from 32 to 16 bit.

	- Video cards with less than 64MB Video memory cannot set
	  texture detail to high and texture color depth to 32
          bit simultaneously. These cards can get very poor
	  performance at times, so lower your texture detail
          and/or lower your texture depth to 16 bit.

	- From the "Advanced" menu under the "Options" menu try
          turning the "SHADOWS" down to "simple" or "none".

        - In Advanced Video Options you can change your View
          Model. This allows one to choose how much of their own
          player model is shown. 
          NONE means player's arm and weapon will not appear.
          GUN ONLY means the gun and not the arms of Powell will
          appear. 
          FULL means that you will see both Lt. Powell's hands
          and the weapon he is holding during gameplay. The less
          of Lt. Powell that is showing, the faster the game
          should run.


==================================================================
Troubleshooting
==================================================================

Safe Mode

-Safe mode can be accessed from the "Safe Mode" link in the Medal
of Honor Allied Assault section of the "Start" menu. It is
provided as a means of isolating the cause of problems you may
have with sound or video card drivers. When launching with safe
mode, you can disable 3D video accelerator support or hardware
support for sound cards in its menu. The default location on the
Start Menu is as follows:
Start->Program Files->EA GAMES->Medal of Honor Allied Assault->
Safe Mode.

DirectX 8.0a

-It is highly recommended that you install DirectX 8.0a as this is
known to resolve a number of video card and other issues. Previous
versions of DirectX are not fully supported.

Windows XP

-If you are using Windows XP, you must have administrator rights to
install and run Medal of Honor Allied Assault.  If you have 
administrator rights, and wish to give a "limited user" administrator 
rights, you can do this in "Users" section of the Windows XP Control
Panel.  

Video Card Drivers

-Some video card drivers do not support OpenGL correctly. Typical
problems that may occur with these drivers include:

	- Crashing on starting up
	- Crashing when changing video resolutions
	- Corrupted textures
	- Garbage artifacts on screen
	- Unexpected bright flashing on screen
	- Unusually slow performance.

The solution is to go to your video card manufacturer's website
and download updated drivers for your card. It is highly
recommended that, given an option, you download and install
Microsoft-certified (WHQL) drivers.

-Video Resolution of 1600x1200
A resolution of 1600 x 1200 pixels is not fully supported and has 
been found to have problems with various video cards. If the game
crashes you can run in safe mode and adjust your resolution back 
to a stable and desirable setting.

-Win95 OpenGL Fix
Users of Windows 95 and Windows 95a may get a missing dll error.
The error message occurs when starting the game on either of these
operating systems stating, "Error Starting Program - A required
.DLL file, GLU32.dll, was not found."  This is a result of the
OpenGL runtime libraries for Windows95 not being bundled with the
earlier versions of Windows 95.  There is an OpenGL v.1.1 patch
for Windows 95 available on Disk 2 of Medal of Honor Allied
Assault. It is located in the "Win95OpenGLfix" folder and is
called "opengl95.exe". Simply run this file from the CD. Once this
OpenGL update is installed the game will run fine on Windows 95
and Windows 95a.

-Dual Monitors
Dual monitors are not supported. Disabling the secondary video
card will allow the game to run with dual monitors.

Sound Card Drivers

-Diamond Monster Sound MX 400
How to fix the MX 400 for use by Medal of Honor Allied Assault:
	1)	Exit from Medal of Honor Allied Assault if you are
                running the game.
	2)	Open up the "Diamond Monster Sound" utility from
		the toolbar; this is a small red and white icon
		near the clock.
	3)	Make sure the "Enable DirectSound Acceleration"
		checkbox is off.
        4)      Click on the "Apply And Exit" button. You should
                be able to run Medal of Honor Allied Assault
                without a problem.


==================================================================
Other Issues
==================================================================

Multiplayer:

-The IPX Protocol is not supported, only TCP/IP is.

-Weather effects are not supported in multiplayer.

-Players can, on rare occasion, turn invisible in multiplayer.
You may see another player's model appear over a spawn point
stuck in mid-stride. That player will be able to move around and
will appear invisible to you although he may be visible to other
players. Simply disconnect and re-connect to the server to fix
this.

Keyboard Controls:

-Some PC keyboards cannot recognize certain combinations of 3 or
more simultaneously pressed keys. This is an inherent problem
unrelated to Medal of Honor Allied Assault.

Advanced Console Commands from the Advanced Options menu:

-By default the advanced console will not be available
unless the option is checked in the "Options" menu. From this
console you will be able to make advanced console commands. The
normal console is active by default and allows you to post
messages to everyone else in multiplayer.


==================================================================
Electronic Arts Copyright
==================================================================

Software and Documentation Copyright © 2002 Electronic Arts Inc.