# Senko Theme (Windows)

<img src="https://i.redd.it/v5vl6ynldhdf1.png" />

Sorry for how long this has taken for me to upload x3

> [!IMPORTANT]
> I highly recommend using [AltSnap](https://github.com/RamonUnch/AltSnap) to be able to move your terminal around after applying my config, unless you already use something like Komorebi or GlazeWM. <br>
> To access the settings on your terminal after applying my config, do `Win + Shift + P` to open the command palette and just type settings. <br>
> To enable the titlebar, type *'focus'* in the command palette and click the `toggle focus mode` button.

> [!NOTE]
> Some of these configs are modified versions of already existing configs, such as YASB, oh-my-posh, and Spicetify. <br>
> `Spicetify text Theme`: [GitHub Repo](https://github.com/spicetify/spicetify-themes/tree/master/text) <br>
> `Original YASB Theme`: [GitHub Repo](https://github.com/amnweb/yasb-themes/tree/main/themes/764a14e0-2d6a-4826-994a-9289857886ba) <br>
> `Catppuccin oh-my-posh`: [Raw JSON Link](https://raw.githubusercontent.com/JanDeDobbeleer/oh-my-posh/refs/heads/main/themes/catppuccin_mocha.omp.json)

## This repo includes configs for:
- Windows Terminal
- Winfetch
- YASB
- VSCode
- Spicetify
- Oh-my-posh
- Discord
- (More to come in the future)

Ensure you have properly installed these programs first, I don't want there to be unnecessary GitHub issues where you have likely not installed or set up a program x3

# Requirements
These configs include fonts such as JetbrainsMono Nerd Font which is needed in YASB and Windows Terminal. <br>
I do highly also recommend using the latest version of Powershell (you can download by using `winget install Powershell` in your terminal)

## Windows Terminal

##### READ THE IMPORTANT NOTE AT THE TOP OF THIS README <br>
<img width="700" alt="{492E9617-732F-4E98-954E-936BFF40586F}" src="https://github.com/user-attachments/assets/e83ef265-19de-4bc2-9ae2-420893ab3d61" />

Copy the code from https://github.com/Hi-doki/senkotheme/blob/main/windowsTerminal/settings.json and replace it into your Windows Terminal settings JSON file located at `C:\Users\USERNAME\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json`

## Winfetch
<img width="700" alt="{EFCC80D8-0A82-4F92-B8F3-B61621A7C3DA}" src="https://github.com/user-attachments/assets/475ea9a2-cbeb-4ee2-8d01-b2551aab207a" />

Copy code from https://github.com/Hi-doki/senkotheme/blob/main/winfetch/config.ps1 and paste into `C:\Users\USERNAME\.config\winfetch\config.ps1`

## YASB
<img width="1920" alt="{48329DC2-5D2F-4DFB-BFB2-DB3675E4DE1A}" src="https://github.com/user-attachments/assets/45cada3b-67fa-4302-99a1-1e725a9d1871" />

Copy both the `config.yaml` and `styles.css` from https://github.com/Hi-doki/senkotheme/tree/main/yasb and replace the files from `C:\Users\USERNAME\.config\yasb` with the new files. (Make sure you backup your original config just incase :3)

## VSCode
<img width="700" alt="{06807C65-7ACE-40CC-9057-CEDE6F069C8B}" src="https://github.com/user-attachments/assets/7bc7e3d8-bb6d-4760-9a7c-39ab5b2721fb" />

I have made the VSCode theme an extension which you can download from https://marketplace.visualstudio.com/items?itemName=Michii.senkorange or type in `Senkorange` on VSCode to download.

## Spicetify
<img width="700" alt="{F65CC627-E2DB-4905-AB3E-321BFD6F1EE6}" src="https://github.com/user-attachments/assets/cf5dd320-2160-4bc1-9f85-19b16ad2dd20" />

Download the `text` folder by using this url: https://downgit.github.io/#/home?url=https://github.com/Hi-doki/senkotheme/tree/main/spicetify/ and place the `text` folder into `C:\Users\USERNAME\AppData\Roaming\spicetify\Themes`.
Edit the `config-xpui.ini` in spicetify's main folder so that `current_theme` is set to `text` and `color_scheme` is set to `SenkoSan`.
After that just type in your console `spicetify apply` and everything should work ^^

## Oh-my-posh
<img width="700" alt="{12A5AF7E-F985-40B5-A2A5-7302B618EC1C}" src="https://github.com/user-attachments/assets/3f19c214-3b53-4dd0-a419-5ee1f3472ad4" />

Create a folder in `C:\Users\USERNAME\.config` called `oh-my-posh`, download https://github.com/Hi-doki/senkotheme/blob/main/oh-my-posh/SenkoSan.json and move it over to that newly created folder.

## Discord
<img width="700" alt="{903C510A-3460-451C-ADB3-264B751BE1B0}" src="https://github.com/user-attachments/assets/0747ba5b-fc4f-4c41-ab94-4493cc6fc142" /> <br>
#### USING VENCORD:

Download the css file from https://github.com/Hi-doki/senkotheme/blob/main/discord/senkotheme.theme.css and place it into `C:\Users\USERNAME\AppData\Roaming\Vencord\themes`. Then go over to Discord's settings, Themes, and enable senkotheme. <br>
Alternatively, you can copy the url https://raw.githubusercontent.com/Hi-doki/senkotheme/refs/heads/main/discord/senkotheme.theme.css and paste into the `Online Themes` section of the Themes tab in Vencord.



## How to setup Powershell to use oh-my-posh and Winfetch
On your terminal, type in the command `notepad $PROFILE`, this will most likely bring a popup on your screen that it will create the file for you. Once you are on the config file `Microsoft.Powershell_profile.ps1`, copy the code from https://github.com/Hi-doki/senkotheme/blob/main/PowerShell/Microsoft.PowerShell_profile.ps1 and paste it in, then save. 
**==(Make sure to change the username in the code as I left my account's username in it)==**

*If you have any problems with getting the configs to work, please create an issue on the GitHub repository or just DM me on discord (mi.\_.chiii)*
