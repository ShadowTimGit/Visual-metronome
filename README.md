# Visual Metronome ![Total installs](https://img.shields.io/endpoint?url=https://api.runelite.net/pluginhub/shields/installs/plugin/visual-metronome)
A simple overlay that changes every tick. It displays a box on your screen, displays a number, or displays your true tile that changes every game tick. 

Used for the same purposes as the regular metronome, timing based activities such as PvM or 3-tick fishing. Helpful for if you don't have sound, are listening to music, or just prefer a visual cue.

![](https://i.imgur.com/drcQDOn.gif) ![](https://i.imgur.com/wonUTcR.gif) ![](https://i.imgur.com/2qUetFH.gif) ![](https://i.imgur.com/RkpEBjl.gif)

# Usage
Alt+click on the border of the overlay to change the size

Alt+right click on the overlay to reset to default size

![](https://i.imgur.com/SWQKf9i.gif)

# Settings
![](https://i.imgur.com/tmT2v2l.png)

![](https://i.imgur.com/iFk0lsj.png)

# Changelog
- **V1.1**
    - Add ability to change width by alt+dragging the border. (Thanks to m0bilebtw for the suggestion)
    - Default settings change
- **V1.1.1**
    - Add back option to use fixed size since the overlay minimum size might be too high.
- **V1.2**
    - Add support for up to four colors instead of just two
- **V1.2.1**
    - Add tick count configuration
    - Fix code formatting from V1.2
- **V1.2.2**
    - Add support for up to ten colors
- **V1.2.3**
    - Fix bug that broke the plugin when certain config settings were changed
- **V1.3** *(Developed by [m0bilebtw](https://github.com/m0bilebtw))*
    - Rewrite overlay render so that you can now change both height and width
        - Remove title option
        - Remove set width option and fixed sizing as they now should be unnessecary
        - Add default size option for overlay
- **V1.3.1**
    - Add option to show the current tick number on the overlay
- **V1.3.2**
    - Add option to change color of tick number
    - Tick number position now centers itself on the overlay 
- **V1.3.3**
    - Fix tick number to show the correct tick number instead of being one tick off
- **V1.3.4**
    - Add setting to highlight the player's true current tile with the metronome colors
- **V1.3.5**
    - Add option to remove the visual metronome overlay
    - Add icon.png
- **V1.3.6**
    - Show Tick Number now starts at 1 instead of 0
    - Fix bug with Tick Count and Show Tick Number that makes it start from -1
- **V1.3.7**
    - Add true tile overlay settings
        - Add true tile border width option
        - Add true tile fill color
- **V1.3.8**
    - Add option to display tick number above player model
    - Rearrange config options
- **V1.3.8.1**
    - Fix overlay showing above interfaces
- **V1.4**
    - Add new section for Tick Number Settings
    - Add option to change font size of overhead Tick Number
    - Add option to change the font
        - Add FontTypes.Java 
        - RS Regular, Arial, Cambria, Rockwell, Segoe Ui, Times New Roman, and Verdana
    - Add automatic font size scaling for the Metronome Tick Number
        - removed TITLE_PADDING and change the way it scales
- **V1.4.1**  
    - Add option to change metronome tick number scaling back to how it previously worked
- **V1.4.2**  
    - Add option to reset the tick cycle with a hotkey
- **V1.4.3**
    - Allow up to 10 colors if Tick Count is higher than 1 (previously if Tick Count was higher than 1 then it would only support 2 colors)
- **V1.4.4** *(Thanks [Thource](https://github.com/Thource))*
    - Fix bug that causes metronome to randomly reset and not properly cycle colors if tick count is higher than 1
- **V1.4.5**
    - Add option to enable tile fill color to change with metronome
- **V1.4.5.1**
    - Fixed minor bug that caused the metronome to reset to default size on startup
- **V1.4.5.2**
    - Fixed bug where Default Box Size setting was not set correctly on startup
- **V1.4.5.3**
    - Change tile layer to ABOVE_SCENE to make compatible with Improved Tile Indicators "Draw Tile below Player" setting
- **V1.4.5.4**
    - Fixed bug from V1.4.5.3 where "Show Tick Number Above Player" was showing under prayers
- **V1.4.6**
    - Added option to enable 2 more overhead ticks with their own cycles *(Thanks [Jefeh](https://github.com/JorgeFernandezH))*
    - Added option to change height of overhead ticks
- **V1.4.7**
    - Added option to reset tick cycle to a specific tick when using the hotkey *(Thanks [Lapask](https://github.com/Lapask))*
    - Added option to use metronome tick color for overhead tick
    - Added option to offset the overhead tick on the X axis
    - Added option to set the gap distance between the extra overhead tick cycles
- **V1.4.7.1**
    - Fixed bug for Reset to Specific Tick feature *(Thanks [Slug-Man](https://github.com/Slug-Man))*
- **V1.4.8**
    - Added Tick Counter Follows Mouse *(Thanks [Manlet008](https://github.com/Manlet008))*

# Feedback
I'm open to all feedback on bugs or features you want to see in this plugin. Give feedback here on this github page or message me on discord, vincent58. 

Thank you to everyone who has left feedback so far, it is appreciated.

Oct 28, 2021 - 10,000 Total installs!

Oct 23, 2022 - 30,000 Total installs!

Oct 6, 2024 - 100,000 Total installs!
