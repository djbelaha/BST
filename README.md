# BST 

This project is designed to enhance your gaming experience and help you get the most enjoyment out of the game by introducing new, realistic sounds created by BST.

------------------------------------------------------------
🚂 ABOUT THE PATCH
------------------------------------------------------------
The BST Patch is a modification for ZDSimulator™ that replaces the original sounds of locomotives and rolling stock with improved versions, while also modifying the mechanics of how these sounds are played.

------------------------------------------------------------
🛠 SYSTEM REQUIREMENTS
------------------------------------------------------------
For the patch to function correctly, you need:
- ZDSimulator™ version: 60.3 Steam
- Free disk space: 2500 MB
- Windows OS

------------------------------------------------------------
📌 INSTRUCTIONS FOR INSTALLATION, LAUNCH, AND USE
------------------------------------------------------------
Please follow these instructions carefully:
1.  We recommend backing up your original sound files (the 'sound' folder) and any custom sound files you may have added (the 'BST' folder). Also, please disable your antivirus software before installation.
2.  Uninstall any previous version of the patch using `unins.exe` (please be careful to use the `unins.exe` file that features the BST icon).
3.  Run the `BST_Setup_ver._Beta.exe` file and install the patch into the game's root directory (for example: `C:\Program Files\Steam\steamapps\common\ZDSimulator`). If the patch fails to automatically detect the location of the game folder on your PC, you will need to specify it manually.
Be sure to follow the steps below to ensure the patch works correctly.
4.  Launch the ZDSimulator™ game launcher and configure the necessary settings. DO NOT click the "Launch Simulator!" button; do not start the game yet!
5.  Run the patch (using the BST.exe file located in the game's root folder or the "BST Loader" shortcut on your desktop). The patch loader window will appear.
6.  Configure the patch settings by clicking the "Settings" button. You can select which sounds to use and adjust their volume levels.
7.  Click "START" in the patch loader window. It will then enter a standby mode, waiting for the game to start.
8.  Launch the game via the ZDSimulator™ launcher by clicking the "Launch Simulator!" button.
9.  Enjoy the updated sounds provided by BST.
10.  If you exit the game and switch to a different locomotive, there is no need to click "START" again; the patch will automatically detect the change and play the sounds corresponding to the locomotive you have selected.
11.  The original game sounds are muted when the patch is launched (using placeholder sound files from the `sound_mute` folder). When the patch loader is closed, the original game sounds are restored. To preserve this logic, the patch includes a safeguard: you cannot close the patch application while the game is running, nor can you launch a second instance of the patch if one is already active.
12.  If you plan to replace the patch's sounds with your own custom ones, they MUST meet the following specifications to play correctly in-game: 44100 Hz, 16-bit, WAV format.

------------------------------------------------------------
🔧 TROUBLESHOOTING (FAQ)
------------------------------------------------------------
Question: The game crashes during loading.
Answer: Ensure that you have the latest versions of both the game and the patch installed. Try verifying the integrity of the original game files via the Steam menu, or reinstall the game.

Question: Sounds do not play, or they overlap/duplicate with the original game sounds.
Answer: Exit the game and close the patch loader. Wait 10 seconds. Then, strictly follow the launch sequence outlined in steps 4–9. Alternatively, try unchecking the specific sound in the patch settings before launching the game; then, launch the game with the patch, exit once it has loaded, re-enable the sound in the settings, and launch the game again.

Question: The original game sounds do not work when the patch is disabled.
Answer: Close the game. Open and then close the patch loader. If that doesn't help, copy the contents of the "sound_bac" folder into the "sound" folder located in the game's root directory, and confirm that you want to replace the existing files. If the issue persists, try restoring the original game files via the Steam menu or reinstalling the game.

Please report any issues you encounter, or ask questions regarding the patch, in the comments section under the pinned post on the BST project's Telegram channel.

------------------------------------------------------------
📌 GUIDE: ADDING CUSTOM SOUNDS FOR SPECIFIC LIVERIES
------------------------------------------------------------
You can now add unique sounds for each locomotive livery (paint scheme). To do this, create a subfolder named after the livery inside the locomotive's folder (e.g., `ZDSimulator\BST\VL11M\VL8_222`, where `VL8_222` is the livery subfolder). IMPORTANT: The name of the livery subfolder must exactly match the name of the livery as it appears in the game launcher. Next, create subfolders for the required sounds within that folder and place the sound files inside them (if you are adding a whistle/horn, create a subfolder named `horn`; if adding compressors/fans, create a subfolder named `equip`). The structure of subfolders and files within the livery subfolder must be identical to the structure of the locomotive's main folder.
As an example, the patch includes specific sounds for the `VL8_222` livery.

------------------------------------------------------------
🤝 CREDITS AND ACKNOWLEDGMENTS
------------------------------------------------------------
Project Author: BELAHA (BST Team)
Special thanks to: ZLOI.PAROVOZ for providing sounds, as well as for active testing and promoting the patch.
Also, a big thank you to everyone who has contributed—or continues to contribute—to the fundraising campaign in support of the project, and to those who have helped (and continue to help) by spreading the word about this patch.

------------------------------------------------------------
⚠️ DISCLAIMER
------------------------------------------------------------
This patch is a fan-made product.
The author is not responsible for any damage to game files or your software.
You install this patch at your own risk.

------------------------------------------------------------
📨 CONTACT & SUPPORT
------------------------------------------------------------
TELEGRAM (always the latest version of the patch): https://t.me/BST_project
Support the project's development: 4874 1000 2723 0187 or https://send.monobank.ua/jar/6A83s5bBJ3
Patch creator's social media channels:
YOUTUBE: https://www.youtube.com/@BelahaGamer
TIKTOK: https://www.tiktok.com/@BelahaGamer
TWITCH: https://www.twitch.tv/belaha_streams

------------------------------------------------------------
🆕 LATEST UPDATES
------------------------------------------------------------
06.11.2026 - Ver 1.6 Beta
-  Patch adapted for ZDSimulator™ version 60.3;
-  External diesel engine sounds rebalanced;
-  Fixed traffic movement sounds in scenario mode;
-  Added volume ramp-up for traffic movement (from start-up to acceleration) for Multiplayer and scenario modes;
-  Added brake release sounds upon departure for passenger carriages and EMUs/DMUs (player and traffic) in Multiplayer and scenario modes;
-  Added sounds for the ER9p;
-  Improved numerous locomotive sounds;
-  Code adjustments for greater stability and smoother patch performance.

17.10.2026 - Ver 1.5 Beta
-  Added external diesel engine sounds; -  Modified traffic sound logic for all modes (Multiplayer, Scenario, Free Roam);
-  Added sounds for the TEM18;
-  Updated fan sounds;
-  Code adjustments for improved stability and smoother patch performance.

09.09.2026 - Ver 1.4.1 Beta
-  Patch adapted for ZDSimulator™ version 60.2.1;
-  Fixed fan sound playback for the ChS4, ChS4kvr, and VL80;
-  Fixed phase splitter sound playback for the VL80;
-  Added sounds for overtaking traffic (movement, locomotive operating sounds, signals) for Scenario and Free Roam modes;
-  Updated sounds for the 3SL2M speedometer and the EPK (automatic train stop system);
-  Restored compressor sounds for the 2TE10;
-  Balanced the volume of horn/whistle sounds across all locomotives.

03.09.2026 - Ver 1.4 Beta
-  Added movement sounds for rolling stock (EMU/DMU, passenger, freight);
-  Added traffic sounds (movement, locomotive operating sounds, signals) for all modes (Multiplayer, Scenario, Free Roam);
-  Added the ability to assign specific sounds to individual liveries (see the guide);
-  Added sounds for the 2ES5k locomotive;
-  Updated and added new sounds for toggle switches and controllers on VL-series and ES/EL-series locomotives. -  Added 10 new radio communication sounds;
-  Fixed radio communication playback logic; they are now audible only inside the cab;
-  Fixed compressor playback logic;
-  Fixed fan playback logic;
-  Added sounds for the 3SL2M (3СЛ2М) speedometer and the EPK (automatic train stop/vigilance device);
-  Added sounds for the 394/395 brake valve, including variations based on the number of positions switched;
-  Updated sounds for many locomotives.

20.05.2026 - Ver 1.3 Beta
-  Added sounds for ChS4, ChS4t, 2EL4, and 2ES4k locomotives;
-  Updated and added new sounds for VL11m, VL80t, VL80k, VL82m, ChS4kvr, ChS7, and ChS8 locomotives;
-  Updated movement sounds for all locomotives;
-  Reworked diesel engine sound logic for diesel locomotives to achieve more realistic audio during throttle-up and throttle-down sequences.

25.04.2026 - Ver 1.2 Beta
-  Reworked the patch launch mechanism and game parameter reading process for more reliable and stable operation;
-  Added safeguards to prevent errors when disabling or restoring original game files;
-  Adjusted the volume of compressor sound files for diesel locomotives;
-  Fixed a sound issue regarding the reverser on the 2M62 diesel locomotive.
