# macOS_Dark_Mode_Switcher

## Usage for Alfred
- git clone this repository or download the file (***macOS_Dark_Mode_Switcher.alfredworkflow***)
- Double click the workflow file to import the workflow if you have Alfred installed in your macOS
- Wake up your Alfred and enter the keyword: ***darkmac*** to switch between Light and Dark mode

## Original AppleScript Code
```
tell application "System Events"
	tell appearance preferences
		set dark mode to not dark mode
	end tell
end tell
```