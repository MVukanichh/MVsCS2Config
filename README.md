# MEICSGOConfig
Counter-Strike: Global Offensive Config by MilesExInferno

This config is personalized config made by MilesExInferno.
You can edit it as you want; change any values/parameters to any you want.

Updates will happen every one (1) week, adding/tweaking/removing certain dvars.

# How to use

### How to download

1. Press green "Code" button found at the top of the repository.
2. Press "Download ZIP"
3. Press "Save File" and choose in which Location do you want to save ZIP File.

### Launch Options

1. You must right click "Counter-Strike: Global Offensive" in your Steam Library.
2. Press "Properties" and new window will pop-up.
3. In the very first tab in the new window, you will see "Set Launch Options".
4. Copy everything from "Launch Options" text file found in the downloaded ZIP file and click "Set Launch Options" button.
5. Paste everything in there and press ok.
6. Close that window and start game to check if it works.

### Configs

1. Right click on "Counter-strike: Global Offensive" in your Steam Library.
2. Press "Properties" and new window will pop-up.
3. Go to tab called "Local Files"
4. Press "Browse Local Files" button.
5. Windows Explorer window will pop-up with main folder within "Counter-Strike: Global Offensive" game folder.
6. Open folder named "csgo"
7. Copy folders named "cfg" and "resource" and paste them to the "csgo" folder.
  * Only if you already extracted the ZIP File, if not, follow next step.
8. Hold down shift and select folders named "cfg" and "resource" within opened ZIP File and drag them to "csgo" folder.
9. Press YES to everything prompted up, even though nothing should.

# Changelog

### Main Version 1.1.0.0

#### Version 1.1.1.1

* Version in "autoexec" config file changed from 1.1.1.0 to 1.1.1.1
* Project's name changed from "MilesExInferno Autoexec/Config" to "AvatarOfLust's Autoexec/Config"
* Tweaks in initial message brought up in console by autoexec
* Tweaks in "numpad" config file
* -noubershader Launch Option Removed from "Launch Options" text document
* -limitvsconst Launch Option Removed from "Launch Options" text document
* Changes to "Network" config file:
  * More Values for "rate" cvar listed
  * "net_maxroutable" cvar's value changed from "1200" to "1000"
  * "mm_dedicated_search_maxping" cvar's value changed from "60" to "75"
  * "cl_invites_only_mainmenu" cvar's value changed from "0" to "1"
  * "sdr_spew_level" cvar removed
  * Cvar "net_droponsendoverflow" now has info; value changed from "1" to "0"
  * "net_maxfragments" cvar removed
  * Cvar "net_splitrate" now has info
  * "net_allow_multicast" cvar removed
* Changes to "Video" config file:
  * "fps_max" cvar's value changed from "400" to "432"
  * "fps_max_menu" cvar's value changed from "120" to "288"
  * "r_dynamic" cvar's value changed from "0" to "1"
* Changes to "Audio" config file:
  * "volume" cvar's value changed from "0.215" to "0.22"
  * snd_mixahead" cvar's value changed from "0.5" to "0.025"
* Changes to "Binds" config file:
  * "r_cleardecals" cvar removed from being binded to "w", "a", "s", "d", "tab", "shift", "ctrl", "space" and "mouse1"
  * "r_cleardecals" cvar binded to "mouse2"

#### Version 1.1.1.0

* Version in "autoexec" config file changed from 1.1.0.0 to 1.1.1.0
* Changes in "audio" config file.
  * <!> **Reverted** Snd_mix_async from previous version, back to "1".
  * Snd_pitchquality changed from "0" to "1".
  * <!> **Reverted** Dsp_slow_cpu from previous version, back to "1".
* Changes in "network" config file.
  * Rate changed from "655360" to "786432".
  * Net_maxroutable changed from "900" to "1200".

#### Version 1.1.0.0

* Version in "autoexec" config file changed from 1.0.1.2 to 1.1.0.0.
* Many grammar errors fixed.
* Display Message "autoexec" config file echoes into Console changed.
* "exec "MilesExInferno\notsorted.cfg"" removed from "autoexec" config file.
* Changes in "audio" config file.
  * Main sound volume increased from 0.2 to 0.215
  * Snd_mix_async defaulted to 0
  * Snd_mixahead changed from 1.0 to 0.5
  * Snd_tensecondwarning_volume increased from 0.1 to 0.15
  * Snd_mvp_volume decreased from 0.05 to 0.025
  * Snd_dzmusic_volume changed from 0.05 to 0
  * Dsp_slow_cpu defaulted to 1
* Changes in "binds" config file.
  * "TagBind" alias binded by default to W, A, S, D movement keys.
  * "r_cleardecals" cvar added to TAB, SHIFT, JUMP and CTRL.
  * Fixed BindToggle for "cl_righthand" binded to F5
* Changes in "network" config file.
  * Cl_timeout changed from 30 to 15
  * Cl_resend_timeout changed from 20 to 15
  * Cl_resend changed from 6 to 5
  * Mm_dedicated_search_maxping changed from 50 to 60
  * Net_maxroutable changed from 800 to 900
  * Rate changed from 524288 to 655360
* "notsorted" config file **Removed**.
 

### Main Version 1.0.1.0

#### Version 1.0.1.2

* Version in "autoexec" config file changed from 1.0.1.1 to 1.0.1.2.
* Added C4 drop script to "scripts" config file.
* Togglebind for chaning hands added to "binds" config file.
  * Togglebinded to button "F5".
* Few tweaks to "scripts" config file.
  * Jumpthrow script tweaked.
  * Crouch Jump tweaked.

#### Version 1.0.1.1

* "How to use" added in README.md.
* Version in "autoexec" config file changed from 1.0.1.0c to 1.0.1.1.
* Few text fixes in "autoexec" config file.
* Minor tweaks in "audio" config file.

#### Version 1.0.1.0c

* Version in "autoexec" config file changed from 1.0.1.0b to 1.0.1.0c.
* Minor modification to "scripts" config file.

#### Version 1.0.1.0b

* Version in "autoexec" config file changed from 1.0.0.9 to 1.0.1.0b.
* Now executes "scripts" config file.
* Added "scripts" config file.
  * Template for Auto Clantag Changer
  * Jumpthrow
  * Crouch Jump
  * Afk-Move
* Modification to "binds" config file.
  * "afk-move" alias binded to F4.
* Minor tweaks to "nadepractice" config file.

### Main Version 1.0.0.0

#### Version 1.0.0.9

* Version in "autoexec" config file changed from 1.0.0.8 to 1.0.0.9.
* Minor tweaks to "csgo_custom" language file.
* Minor tweaks to "binds" config file.

#### Version 1.0.0.8

* Version in "autoexec" config file changed from 1.0.0.7b to 1.0.0.8.
* Added "nadepractice" config file.
* Adjustments to "binds" config file.
  * F2 binded to exec nadepractice config file.
  * F3 binded to exec binds config file.
    * <i> This bind is added so you can revert keybinds from executing NadePractice config file.

#### Version 1.0.0.7b

* <!> **Reverted** +mat_queue_mode change from previous version.
* Version in "autoexec" config file changed from 1.0.0.6. to 1.0.0.7b.
* Minor tweaks to "video" config file.
  * <!> **Reverted** mat_queue_mode change from previous version.
* Adjustments to few values in "audio" config file.

#### Version 1.0.0.6

* Launch Options Tweaked.
  * Removed Launch Commands that do not work/do not exist anymore.
  * +mat_queue_mode adjusted.
  * Removed Launch Options which can be in Config files instead of Launch Options.
* Minor tweaks to "csgo_custom" language file.
* Minor tweaks to "autoexec" config file.
* Minor tweaks to "video" config file.
  * mat_queue_mode adjusted.
* Minor tweaks to "network" config file.
* Minor tweaks to "hud" config file.
* "clan" config file **Removed**.
* Minor tweak to "binds" config file.
    * alias "TagBind" removed from movement binds (W A S D).
* Minor tweaks to "audio" config file.
