# ![](/Screenshots/Square44x44Logo.altform-lightunplated_targetsize-32.png) BenderDeck 3.0 Beta
Free soundboard app for streamers for playing sound effects with the press of a key.
### [:arrow_right: Download the latest version](https://github.com/PavlikBender/BenderDeck/releases/download/v3.0/BenderDeckSetup.msi)
### [:arrow_right: Download the portable version](https://github.com/PavlikBender/BenderDeck/releases/download/v3.0/BenderDeck.3.0.Portable.zip)

*The portable version is launched through the file BenderDeck.exe*

#### Don't forget to support me: [DonationAlerts](https://www.donationalerts.com/r/pavlikbender) 

### **Attention!** The application is in the Beta stage, and some bugs and issues may occur.

You can report them on my [Discord](https://discord.com/invite/gaVrv6k).

### Known Bugs
1. Windows Defender may prevent downloading the installation file; you can resolve the issue by disabling real-time protection and cloud protection. **OR DOWNLOAD THE PORTABLE VERSION**. This behavior is due to the installer being unsigned; a digital signature is costly for me, and do not forget the application is free.
2. **Presumably, it might be, not exactly, BUT** some antivirus programs **may** prevent start of the application because it INTERCEPTS keystrokes, which the antivirus **may** interpret incorrectly. If you encounter this problem, you can solve it by adding the application to the antivirus exceptions.

## Table of Contents
- [Quick Start](#quick-start)
- [Description](#description)
  - [Button Grid](#button-grid)
  - [Settings Menu](#settings-menu)
  - [Button Properties](#button-properties)
- [F.A.Q.](#frequently-asked-questions)
- [Contact Me](#contact-me)

### Quick Start
1. Open the application.

![](/Screenshots/1.png)

2. Click the settings menu button in the top left corner to open the settings.

![](/Screenshots/EN1.png)

3. Click on "Add button" to add the desired number of buttons.

![](/Screenshots/EN8.png)

4. Adjust the number of columns for better display.

![](/Screenshots/EN2.png)

5. Click on the added button to configure it.

![](/Screenshots/EN3.png)

6. Specify the hotkey that will play the audio file.

![](/Screenshots/EN4.png)

7. Specify the audio file to be played when the key is pressed.

![](/Screenshots/EN5.png)

8. Configure the remaining buttons.

![](/Screenshots/EN6.png)

9. Close the settings menu. The application is now configured.

![](/Screenshots/9.png)

10. Press the hotkey or click on the configured button.

![](/Screenshots/10.png)

### Description

I created this application to help streamers diversify their streams. The application allows you to instantly play any of your audio files by pressing a key on the keyboard or clicking with the mouse.

Before diving into the interface description, it's important to note that the window sizes are strictly fixed and adjust automatically based on the number of buttons, columns configured, etc.

### Button Grid
![](/Screenshots/D1.png)

1. Button that opens the settings menu.
2. The basic element of the application is a Button. The Button is clickable and draggable. It displays its label and configured hotkey (both properties can be empty).
3. Button currently playing an audio file. Playback occurs when the hotkey is pressed or when clicked with the mouse. By default, pressing the hotkey again will replay the sound from the beginning, but clicking the mouse again will stop playback.
5. Button currently playing an audio file simultaneously with the main button, i.e., with the "Individual playback" property enabled.

### Settings Menu
![](/Screenshots/END1.png)

1. Action "Add button" adds an empty button to the button grid.
2. Adjusting the number of columns in the button grid.
3. Property enabling the application to stay on top of all windows.
4. Setting the current language of the application - English and Russian languages are supported.
5. Link to the application's page.
6. (X) Action to delete a button.

![](/Screenshots/EN7.png)

All buttons in the grid can be moved, and when clicked on a button in edit mode, the button properties window opens.

### Button Properties
![](/Screenshots/END2.png)

1. Button Name, which can be empty.
2. Hotkey setting field. Clicking "Set" opens the hotkey assignment window. Clicking "Clear" clears the hotkey. If no hotkey is specified but an audio file is named, the button will play upon mouse click.
4. Audio file selection field for playback. Clicking "Choose" opens a file selection window for MP3 and WAV formats. If the button name is empty, it is automatically filled with the file name. Clicking "Clear" clears the "Filename" property.
5. Playback volume of the audio file, defaulting to 50 out of 100.
6. "Start-Stop" function determines the behavior of a playing button when the hotkey is pressed again. By default, playback restarts, but with "Start-Stop" enabled, another press stops playback.
7. "Individual playback" function defines how the button will play. By default, when a button is playing and another is clicked, the first stops and the second starts. With "Individual playback" enabled, the first button continues playing alongside the second. This feature allows for playing multiple buttons simultaneously.

## Frequently Asked Questions

**Q**: The sound does not play when I press the hotkey.

**A**: Try selecting the audio file again. Check the volume settings. In some cases, the application might not capture the pressed key, so try running the application as an administrator.

**Q**: Why do Windows Defender and antivirus programs prevent downloading/start of your application?

**A**: Windows Defender prevent downloading the installation file. To resolve this, disable real-time and cloud protection or download the portable version. This behavior is due to the installer lacking a certificate, which costs a lot while the application is free. Antivirus programs may prevent start of the application because it intercepts keystrokes. Solution: add the application to the antivirus exceptions.

**Q:** There is *APP NAME*, which is lighter and has better functionality. Why should I use your application?

**A:** The advantages of my application are its free cost, easy setup, and modern interface (although the UI is unfortunately heavy). I personally tested the concept of this application during streams. Other alternatives are usually harder to configure and require a lot of time, despite a potentially better end result. I've invested the time for you to make it simpler. However, the final choice is always yours.

**Q:** The application won't start.

**A:** Navigate to "C:\Users\{Username}\AppData\Roaming\BenderDeck 3.0" and delete the settings.json file (WARNING! This will delete all your settings). Then, restart the application.

**Q:** Will your application run on Windows 10, 8, 7?

**A:** The application is built for Windows 10, 11 x64. It is not supported on Windows 8 and 7. It has been tested only on Windows 11.

**Q:** Why didn't the application settings save?

**A:** Settings are saved when the settings menu is closed. Make sure to close the settings menu before exiting the application.

## Contact Me
If you have any questions about the application, feel free to ask them in my [Discord](https://discord.com/invite/gaVrv6k).

<sub>*Tags: Stream Deck, Soundboard, Sound board, Free StreamDeck, Stream Deck alternatives, StreamDeck alternatives, OBS, For streamers, hotkey, sound effects, Play SFX with hotkeys, Soundpad, Soundpad alternatives, AutoHotKey, AutoHotKey alternatives*</sub>
