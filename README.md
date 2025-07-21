# Senko Theme (Windows)

Sorry for how long this has taken for me to upload x3

Some of these configs are modified versions of already existing configs, such as YASB, oh-my-posh, and Spicetify.
https://github.com/spicetify/spicetify-themes/tree/master/text
https://github.com/amnweb/yasb-themes/tree/main/themes/764a14e0-2d6a-4826-994a-9289857886ba
https://raw.githubusercontent.com/JanDeDobbeleer/oh-my-posh/refs/heads/main/themes/catppuccin_mocha.omp.json

## This repo includes configs for:
- Windows Terminal
- Winfetch
- YASB
- VSCode
- Spicetify
- Oh-my-posh
- (More to come in the future)

Ensure you have properly installed these programs first, I don't want there to be unnecessary GitHub issues where you have likely not installed or set up a program x3

# Requirements
These configs include fonts such as JetbrainsMono Nerd Font which is needed in YASB and Windows Terminal.
I do highly also recommend using the latest version of Powershell (you can download by using `winget install Powershell` in your terminal)

## Windows Terminal
Copy the code from https://github.com/Hi-doki/senkotheme/blob/main/windowsTerminal/settings.json and replace it into your Windows Terminal settings JSON file located at `C:\Users\USERNAME\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json`

## Winfetch
Copy code from https://github.com/Hi-doki/senkotheme/blob/main/winfetch/config.ps1 and paste into `C:\Users\USERNAME\.config\winfetch\config.ps1`

## YASB
Copy both the `config.yaml` and `styles.css` from https://github.com/Hi-doki/senkotheme/tree/main/yasb and replace the files from `C:\Users\USERNAME\.config\yasb` with the new files. (Make sure you backup your original config just incase :3)

## VSCode
I have made the VSCode theme an extension which you can download from https://marketplace.visualstudio.com/items?itemName=Michii.senkorange or type in `Senkorange` on VSCode to download.

## Spicetify
Download the `text` folder by using this url: https://downgit.github.io/#/home?url=https://github.com/Hi-doki/senkotheme/tree/main/spicetify/ and place the `text` folder into `C:\Users\USERNAME\AppData\Roaming\spicetify\Themes`.
Edit the `config-xpui.ini` in spicetify's main folder so that `current_theme` is set to `text` and `color_scheme` is set to `SenkoSan`.
After that just type in your console `spicetify apply` and everything should work ^^

## Oh-my-posh
Create a folder in `C:\Users\michii\.config` called `oh-my-posh`, download https://github.com/Hi-doki/senkotheme/blob/main/oh-my-posh/SenkoSan.json and move it over to that newly created folder.

## How to setup Powershell to use oh-my-posh and Winfetch
On your terminal, type in the command `notepad $PROFILE`, this will most likely bring a popup on your screen that it will create the file for you. Once you are on the config file `Microsoft.Powershell_profile.ps1`, copy the code from https://github.com/Hi-doki/senkotheme/blob/main/PowerShell/Microsoft.PowerShell_profile.ps1 and paste it in, then save. 
**==(Make sure to change the username in the code as I left my account's username in it)==**

*If you have any problems with getting the configs to work, please create an issue on the GitHub repository or just DM me on discord (mi.\_.chiii)*
