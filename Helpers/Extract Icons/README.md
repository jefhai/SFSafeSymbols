# Extract Icons Script

A super hacky script to extract the icons and icon names from SF Symbols app in list mode. Don't judge the code quality, I don't usually AppleScript much ;)

Please note this makes use of the GUI Scripting Library that can be downloaded [here](https://pfiddlesoft.com/uibrowser/index-downloads.html).

The script will copy the icon names to the clipboard in a format like this:

`some.name, *icon*, some.other,*icon* ..., the.last.icon, *icon* "`

This string can then be further processed.

Please note that the script runs for a very long time (~1 hour) as AppleScript UI scripting is super-slow.