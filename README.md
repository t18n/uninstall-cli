# Uninstall CLI

This script is an open-sourced alternative for [App Cleaner](https://freemacsoft.net/appcleaner/) on Mac OS

The script is created following Sun Knudsen's [How to clean uninstall macOS apps using AppCleaner open source alternative](https://github.com/sunknudsen/privacy-guides/tree/master/how-to-clean-uninstall-macos-apps-using-appcleaner-open-source-alternative) tutorial. The repo is set up so that people can clone and contribute to make it better.

## Installation

### Homebrew
Tap can be found in [my homebrew-taps](https://github.com/turboninh/homebrew-taps) repo
```
brew install turboninh/taps/uninstall-cli
```

or 
```
brew tap turboninh/taps
brew install uninstall-cli
```

### Manual
1. Clone the repo into your computer. Put it somewhere static.
2. Create an alias in your shell by adding this line
   ```
   alias uninstall="~/<your_cloned_path>/uninstall-cli.sh"
   ```
   then source your shell.
3. Usage: In your terminal, 
   ```
   uninstall /Applications/<name_of_your_evil_app>.app 
   ```