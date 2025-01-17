# XcodeProjects
Switch between projects in 2 clicks. Don't write "pod install", "pod update" and "cd <your project>" in the terminal anymore!<br />
**NEW**: Remove derived data of particular project!
**NEW**: Add your custom commands for a project! 
  
# When do you need this tool
- you want to **open** quickly specific **Xcode project**
- you want to **clear derived data for a specific project only**
- you type "pod install", "pod update" and "pod deintegrate" in the terminal too often. Do it in 2 clicks
- you need to **remove Podfile.lock file** quickly
- you need to change directory to point to your project in the terminal 
- you want quickly **open your project in SourceTree**
- you want to **execute custom command for a project**
- you have a lot of projects or modules/frameworks and you need to switch between them quickly
  
# How to install
Go to release section in this repo and download the binary. Drag & drop XcodeProjects.app to your Application folder. Enjoy! 

# How to use 
When you open the app for the first time you would see empty screen

![alt text](Images/example_empty_list.png?raw=true)

click "+" button to add folder of you project within system dialog (Hint: choose multiple projects)

![alt text](Images/example_list_of_projects_dark.png?raw=true)

![alt text](Images/example_list_of_projects_light.png?raw=true)

**Click "arrows" button to open your Xcode workspace/project**

**Click "..." button to see the menu options** 

![alt text](Images/example_context_menu_dark.png?raw=true)

**Open in Terminal** - opens the path to the project in terminal. Handy to quickly switch to the folder of the project

**Open in Finder** - opens the folder of the project in Finder

**Open in Sourcetree** - opens the folder of the project in Sourcetree (if you have Sourcetree)

**Pod install** - runs "pod install" command in terminal for the project

**Pod update** - runs "pod update" command in terminal for the project

**Pod deintegrate** - runs "pod deintegrate" command in terminal for the project

**Remove Podfile.lock** - removes file Podfile.lock from the project

**Clear derived data** - removes project's derived data folder

**Rename project** - opens new window to rename the project. Note: renames in the Xcode Projects app only - not physical folder/project etc.

**Remove from the list** - removes project from the list

If you have added custom commands then they would appear at the bottom of the list with option to remove the command

![alt text](Images/custom_command.png?raw=true)

Also it is possible to drag projects around.

![alt text](Images/example_drag_and_drop_dark.png?raw=true)

# Preferences

![alt text](Images/preferences_dark.png?raw=true)

**Open in GitHub** - opens the github webpage of  XcodeProjects

**Remove all projects** - removes all projects from XcodeProjects app

**Open derived data in Finder** - opens Xcode derived data folder in Finder

**Clear Xcode derived data** - removes Xcode derived data from default location ~/Library/Developer/Xcode/DerivedData

**Launch at Login** - XcodeProjects app will be launched when MacOS was restarted/started

**Show project's icon** - show/hide project's icon next to the project's name

**Add custom command** - add custom command for all projects

> Hint: Click on project icon to change its color

# Support
Just simple star ⭐️ will make my life happier :) 

If you want to support this project, feel free to send some coffee money to this [link](https://paypal.me/dkalachniuk)
If you don't want to spend money, you can still support me if you will share this tool with your colleagues and/or give me a star.

# Ideas
- add command to support carthage update
- add sorting to the list of projects
- add favourites projects
- configure the actions when you press on the project. so you will be able to see only those that you need

# TODO
- ~~update commands logic so some commands like: open workspace, open in finder will not use terminal to open the files~~
- ~~put action "open in Xcode" in the main view~~
- ~~remove project's derived data folder~~
- ~~ability to rename project name~~
- ~~add ability to add custom command~~
- add Sparkle framework to check for updates automatically

# Special Thanks
Special thanks to 
- [Solokub](https://github.com/Solokub) - for providing awesome design for the app. 🥳
- [Gui Rambo](https://gumroad.com/insidegui) - for his awesome project "StatusBuddy". [Gui Rambo's github](https://github.com/insidegui)

# Badges
[![HitCount](http://hits.dwyl.com/DKalachniuk/XcodeProjects.svg)](http://hits.dwyl.com/DKalachniuk/XcodeProjects)
