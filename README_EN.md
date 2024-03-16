# ![](/Screenshots/Square44x44Logo.altform-lightunplated_targetsize-32.png) BenderDeck 3.0 Beta
Free soundboard app for streamers for playing sound effects with the press of a key.
### [:arrow_right: Download the latest version](https://github.com/PavlikBender/BenderDeck/releases/download/v3.0.2/BenderDeck302.zip)
### [:arrow_right: Download the portable version](https://github.com/PavlikBender/BenderDeck/releases/download/v3.0.2/BenderDeck302Portable.zip)

*The portable version is launched through the file BenderDeck.exe*

#### Don't forget to support me: [DonationAlerts](https://www.donationalerts.com/r/pavlikbender) 

### **Attention!** The application is in the Beta stage, and some bugs and issues may occur.

You can report them on my [Discord](https://discord.com/invite/gaVrv6k).

## Table of Contents
- [Quick Start](#quick-start)
- [Description](#description)
  - [Button Grid](#button-grid)
  - [Settings Menu](#settings-menu)
  - [Button Properties](#button-properties)
  - [Devices](#devices)
- [F.A.Q.](#frequently-asked-questions)
- [Contact Me](#contact-me)

### Quick Start
1. Setup button grid.

![](/Screenshots/QS1En.gif)

2. Configure button.

![](/Screenshots/QS2En.gif)

3. Click on the configured button or press the hotkey.

![](/Screenshots/QS3.gif)

### Description

I created this application to help streamers diversify their streams. The application allows you to instantly play any of your audio files by pressing a key on the keyboard or clicking with the mouse.It also supports connecting multiple keyboards and can recognize from which specific keyboard a key was pressed.

Before diving into the interface description, it's important to note that the window sizes are strictly fixed and adjust automatically based on the number of buttons, columns configured, etc.

![](/Screenshots/Resizability.gif)

### Button Grid
![](/Screenshots/ButtonGrid.png)

1. Button that opens the settings menu.
2. The basic element of the application is a Button. The Button is clickable and draggable. It displays its label and configured hotkey (both properties can be empty).
3. Button currently playing an audio file. Playback occurs when the hotkey is pressed or when clicked with the mouse. By default, pressing the hotkey again will replay the sound from the beginning, but clicking the mouse again will stop playback.
5. Button currently playing an audio file simultaneously with the main button, i.e., with the "Individual playback" property enabled.

### Settings Menu
![](/Screenshots/MenuEn.png)

1. Action "Add button" adds an empty button to the button grid.
2. Adjusting the number of columns in the button grid.
3. Property enabling the application to stay on top of all windows.
4. Action "Devices", opens list of [devices](#devices).
5. Setting the current language of the application - English and Russian languages are supported.
6. Link to the application's page.
7. (X) Action to delete a button.

All buttons in the grid can be moved, and when clicked on a button in edit mode, the button properties window opens.

![](/Screenshots/Moving.gif)

### Button Properties
![](/Screenshots/ButtonEn.png)

1. Button Name, which can be empty.
2. Hotkey setting field. Clicking "Set" opens the hotkey assignment window. Clicking "Clear" clears the hotkey. Additionally, the app remembers from which device the key was pressed. If no hotkey is specified but an audio file is named, the button will play upon mouse click.
3. Audio file selection field for playback. Clicking "Choose" opens a file selection window for MP3 and WAV formats. If the button name is empty, it is automatically filled with the file name. Clicking "Clear" clears the "Filename" property.
4. Playback volume of the audio file, defaulting to 50 out of 100.
5. The behavior determines how a button will behave when activated by pressing a hotkey:
   - "Start over": if the file is already playing, pressing the hotkey again will restart the playback of the file. This behavior is set as default.
   - "Start-Stop": if the file is already playing, pressing the hotkey again will stop the playback.
   - "Hold to play": the file will play only when the hotkey is held down; releasing the key will stop the playback.

6. The "Ignore device" function, when enabled, allows a button to play if the same hotkey is pressed on different devices. By default, this function is disabled. For example, enable this if you have two keyboards and want the sound to play when pressing NumPad1 on any of these keyboards.
7. "Individual playback" function defines how the button will play. By default, when a button is playing and another is clicked, the first stops and the second starts. With "Individual playback" enabled, the first button continues playing alongside the second. This feature allows for playing multiple buttons simultaneously.

### Devices
![](/Screenshots/DevicesEn.png)

1. The list of devices that the application has discovered throughout its entire work-time.
2. The displayed device name, editable field.
3. The path to the device. Information by which the application recognizes a specific device.

## Frequently Asked Questions

**Q**: The sound does not play when I press the hotkey.

**A**: Try selecting the audio file again. Check the volume settings. In some cases, the application might not capture the pressed key, so try running the application as an administrator.

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

<sub>*Tags: Stream Deck, Soundboard, Sound board, Free StreamDeck, Stream Deck alternatives, StreamDeck alternatives, OBS, For streamers, hotkey, sound effects, Play SFX with hotkeys, Soundpad, Soundpad alternatives, AutoHotKey, AutoHotKey alternatives, HID Macros*</sub>
