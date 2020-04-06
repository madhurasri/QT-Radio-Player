# QT-Radio-Player
Simple cross-platform desktop application created using Qt’s QMediaPlayer Class.

## Screenshots

###### on Linux
![Linux](https://raw.githubusercontent.com/madhurasri/QT-Radio-Player/master/Screenshots/Linux.png)
###### on Windows
![Windows 10](https://raw.githubusercontent.com/madhurasri/QT-Radio-Player/master/Screenshots/Windows.jpg)
###### on Mac
![Mac](https://raw.githubusercontent.com/madhurasri/QT-Radio-Player/master/Screenshots/Mac.png)

## Additional Notes
- Audio playback can be lag if your internet connection is very slow.
- Wait a few seconds after clicking on a Radio Channel icon if it didn’t start playing immediately. It will take some time to connect to the radio streaming server if your internet connection is slow.
- Some radio channels may unavailable sometimes due to issues in their side. (Server changes / Offline hours / Stop Streaming / System Maintenance etc.)

## GUI Design

![UI](https://raw.githubusercontent.com/madhurasri/QT-Radio-Player/master/Screenshots/GUI_Design.jpg)

### Player Status
**Element**: QLabel
**Functionality**: Displays the channel name when clicked on a channel icon.
###### Channel Buttons
**Element**: QPushButton
**Functionality**: Start playing the channel when clicked on.
###### Volume Level Indication
**Element**: QLabel
**Functionality**: Displays the current volume level.
###### Volume Controller
**Element**: QDial
**Functionality**: Controls the volume.
###### Stop/Play Buttons
**Element**: QPushButton
**Functionality**: Stops/Starts Playing

Vertical, Horizontal, and Grid Layout elements used to design the layout of the application.
![layout](https://raw.githubusercontent.com/madhurasri/QT-Radio-Player/master/Screenshots/layout_elements.JPG)
