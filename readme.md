# Birth by Sleep HD ReMix Nightly
A Texture Pack for Kingdom Hearts Birth by Sleep Final Mix, for use in the PPSSPP Emulator.

<b>Warning:</b>
This Texture Pack was made for the <b>Japanese/English patched Kingdom Hearts Birth by Sleep FINAL MIX.</b>
<br>Although I can't help you if you have issues with it <b>a compatibility patch was made for it but it's not perfect.</b> 
<br>It should work automatically if you change the folder from ULJM05775 to ULES01441 and properly check the Button Swaps folder in Optional.

If you want to contribute to this project, you can either contact me in Discord(AkiraJkr#6764) or do a pull request with your changes/submit issues.

![There Should Be a Fancy Image Here](https://i.imgur.com/0v2XaQ1.png)

# Latest Version: 1.1.0-part1

Original Forum Thread: https://forums.ppsspp.org/showthread.php?tid=24126

<br><b>Download Links:</b>

<br>Stable Version: https://github.com/AkiraJkr/Birth-by-Sleep-HD-ReMix/archive/master.zip
<br>Nightly Version:  https://github.com/AkiraJkr/Birth-by-Sleep-HD-ReMix-Nightly/archive/master.zip


<br>To install, first download, then go to the TEXTURES Folder found in:
PPSSPPDir/memstick/PSP

If it doesn't exist, create it, along with a ULJM05775 folder, and then drag'n'drop all contents from the ZIP to ULJM05775.

In the end, it should look like this: **PPSSPPDir/memstick/PSP/TEXTURES/ULJM05775/AllOfThisGitContents**

It should automatically work if you have not disabled texture replacement.

Please delete the folder before updating or it may cause errors.

# Extras

<b>Button swaps is avaiable in the Optional folder.</b>


<b>Pre-Censor Aqua:</b> Check the Optional folder.

Preview: https://imgur.com/a/S9uri



<b>Playing in 60 FPS and/or with Japanese Voices:</b>

Step 1: Go to Settings ---> System and turn on [Enable cheats].

Step 2: Go back to the pause menu(Or unpause then pause), press [Cheats], [Edit cheat file] and input the following on the text file. Then Save.

<br>_S ULJM-05775
<br>_G Kingdom Hearts Birth by Sleep Final Mix
<br>_C0 60 FPS Mode
<br>_L 0x21725EC8 0x00000000
<br>_C0 Japanese Audio
<br>_L 0x0035B02E 0x00000001
<br>_C0 Disable Subtitles(Broken outside Theater)
<br>_L 0x017189FC 0x00000000

# FAQ
<br>Q:Place XXXXX is not in HD pls fix
<br>A:The project is currently not finished, do not expect too many things made at the moment, I am one man working on the textures.ini alone.

<br>Q: Why do the faces look blocky/robotic?
<br>A: Limitation in the texture replacement feature, trying to replace all of the avaiable faces in the game for one character will result in them being stuck in one expression forever. See here: https://goo.gl/p5a1Pn
<br>If you know a breakthrough, tell me.

