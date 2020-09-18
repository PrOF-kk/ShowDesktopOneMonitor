# ShowDesktopOneMonitor

## Description
Adds ability to Show Desktop (Win + D) only for one monitor.
Works exactly like Win + D does **plus additional features**:
- Shows desktop (minimizes all windows)
- Restores windows to their previous states
- Minimizes all windows if user changed state of any window or one of the windows opened / closed (exactly how Win + D works)  
### Plus: ###
- Minimizes/Restores only windows on specific monitor, remembering their states

## Installation
1. Download and extract archive somewhere  
*See Releases section: https://github.com/PrOF-kk/ShowDesktopOneMonitor/releases*
2. Create task in Task Scheduler:  
- Specify path to *ShowDesktopOneMonitor.exe*
- Trigger: *Run only when user is logged on*
- On *Settings* tab make sure that task will not be stopped after running longer than some days, for example.  
Note: program has icon in tray, but unfortunately it is invisible if the app is started from Task Scheduler :(
Adding a slight delay before starting the app might fix the issue

## Usage
Press key combination: *Alt + ~ (the key to the left of the "1" key for any keyboard layout)* to minimize/restore windows **on the monitor where cursor is currently on**.
This combination might be changed in future releases, and will eventually hopefully be user-configurable

## Credits
In core of the project is @FrigoCoder's code: https://github.com/FrigoCoder/FrigoTab  
His code allows to get list of windows exactly like Alt + Tab does, what was excellent for my task.

## License
Copyright (c) 2019 Robert Ruzin. Licensed under the GPL-3.0 license.
