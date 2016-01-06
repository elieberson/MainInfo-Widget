# MainInfo-Widget
Simple and small Rainmeter widget that displays the essentials (time, day, date, and battery) and also has a few other handy tools

## Requirements
- Install Rainmeter for Windows
- Laptop (not required but half the widget is for battery monitoring)

## Setup
There are two methods for setting this up:

### Easy Way
1. Run the "MainInfo_1.5.rmskin" file. This will load everything and set the necessary parameters. From here, simply open open the Rainmeter context menu and choose the preferred widget.

### Harder Way
1. Move this folder with the rest of the skins in Rainmaker. Will probably be under "C:\Users\<user>\Documents\Rainmeter\Skins"
2. Open rainmeter context menu. One method of doing this is opening cmd, navigating to the rainmeter program, probably found at "C:\Program Files\Rainmeter" and then calling `Rainmeter.exe !Manage`
3. Inside the menu, Go to "MainInfo-Widget" and select the preferred widget.

## How to use
The idea behind this widget is that the user can hide the taskbar and still have the important information at all times. This will increase usable screen space.

Generally, the widget will always stay at the top of all programs. This include videos and other full screen applications. This may be annoying so there are several ways to deal with this.

1. If there is something directly behind the widget, just roll the mouse over it. The widget is click-throughable and will also temporarly disappear while the mouse is over it.
2. Hold Shift and scroll over the widget. This time, it will not disappear. For "InfoTop" and "InfoBottom", right click the widget anywhere except for the battery circle and it will jump to the other end of the screen. Top will go to bottom and bottom will go to top.
3. Hold Shift and scroll over the widget. For any of the widgets, left click and the widget will disapear. To get the widget back, just hold Shift, scroll back to where the widget was last seen and left click again. The widget will reappear.

## Advanced
The widget will also allow you to open one desired program. However, to do this, one must modify the code itself.

1. Under the varaibles section of any of the widgets, under the variables section, find the line that says `RightMouseDownAction=["C:\Program Files\Sublime Text 3\sublime_text.exe" "C:\Users\EFL\Dropbox\Work\work.txt"]` and replace the area inside the brackets with the desired command.
2. To activate, in the "InfoTop" and "InfoBottom" widgets, right click the battery circle area. for the "TopInfoCurve" and "TopInfoCurve2" widgets, right click anywhere inside the battery meter.