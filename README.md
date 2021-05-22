## Please read before download 🔴



## Explain

I put together all sorts of scripts to make Windows 10 more efficient. For every script I write Cr. Who made it?
Tweaking will remove Bloatware and Bloatware Regedit.
You should backup your data before using Scripts, as it may delete programs you are using and delete programs loaded through Microsoft Store such as Netfrix, Skype, Spotify, Instargram, etc. Please consult Scripts before using them.

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Q5Q51QUJC)

<a href="https://yoomoney.ru/to/4100116615568835"><img src="https://yoomoney.ru/i/shop/iomoney_logo_color_example.png" width=220px height=46px></a>

## Supported Windows 10 versions

|Version|    Marketing name   | Build | Arch |      Editions     |
|:-----:|:-------------------:|:-----:|:----:|:-----------------:|
| 20H1  | May 2021 Update     | 19043 |  x64 |Home/Pro/Enterprise|
| 20H2  | October 2020 Update | 19042 |  x64 |Home/Pro/Enterprise|
| 21H1  |   May 2020 Update   | 19041 |  x64 |Home/Pro/Enterprise|

***
- Set up Privacy & Telemetry
- Uninstall OneDrive
- Remove Bloatware & Regedit
- Disable Windows Seach , Update , Sysmain , Workstation , TCP/IP NetBIOS , Print Spooler
- Disable Contana
- Regedit FPS Booster
- Make Windows 10 more private and secure
- DisableMemory Compression
- Turn off Microsoft Defender Prmanently
- reduced response time
- Reduce memory consumption
- Reduce CPU
- Make gaming a top priority
- Disable SmartScreen
- Install Runtime Visual CC+ 2005 - 2021
- Disable Dithering ( For Graphic AMD GPU )
- Disable CPU energy-saving technique that reduces CPU power consumption and synchronizing of process wake-ups.
- Adding more ram for applications in system memory caching to improve microstuttering (Enable LargeSystemCache)
- Disable Ram saving techniques Windows use (Paging Combining) to improve microstuttering
- Disable Start-up Telemetry and Programs to Improve Startup and Memory Usage
- Disable Delivery Optimization P2P Update downlods outside of local network
- Disable unnecessary System Services for less System Usage (116 Services Disabled)
- Speed up start time by Disabling DelayedDesktopSwitchTimeout
- Applying Optimal Win32Priority for balanced FPS and Latency
- Disable Settings App unnecessary and telemetry Options
- Change Windows Updates to "Notify to schedule restart"
- Install Timer Resolution Service to lower Input Delay.
- Turn off microsoft peer-to-peer networking services
- Enable Full-screen Exclusive for lower input delay
- Disable Telemetry & Data Collection bloatwares
- Remove unwanted unnecessary temporary files
- Disable Consumer experiences from Microsoft
- Enable Hardware Accelerated GPU Scheduling
- Enabling Normal Priority for Fortnite
- Disable Windows Automatic maintenance
- Run Windows Cleaner  (cleanmgr.exe)
- Turn off data execution prevention
- Add Take Ownership to Context menu
- Disable WPP SOFTWARE tracing logs
- Disable prefetcher and superfetch
- BCD Tweaks for lower Input Delay
- Import Custom Nvidia Profile
- Disable System Auto-Loggers 
- Disable Paging Executive
- Disable DistributeTimers
- Disable GPU Preemption
- Disable fast startup
- Disable Hibernation
- Disable Sleep study
- Disable Aero shake
***

[Image](https://i.imgur.com/Zv2YyFW.png)

The left side is before customization. The right side is after the adjustment.

If you have any problems, please contact me at Discord : Samcro#6499

## Contribute

I would be happy to extend the collection of scripts. 
Just open an issue or send me a pull request. (Yes, if its useful, you can).

### Thanks To

- [W4RH4WK](https://github.com/W4RH4WK) (For his project ^^)
- [Sergey Tkachenko](https://winaero.com/) (*WinAero Tweaker Dev.*)
- [O&O Software GmbH](https://www.oo-software.com/en/company) (*ShutUp10 Dev. Company*)
- [MalwareBytes](https://br.malwarebytes.com/company/) (*AdwCleaner Dev. Company*)

### Who inspired me to improve more:

- Special thanks to the [LowSpecGamer](https://youtu.be/IU5F01oOzQQ?t=324), he is the reason i've updated this script.

- [Adamx's channel](https://www.youtube.com/channel/UCjidjWX76LR1g5yx18NSrLA) - by [this video](https://youtu.be/hQSkPmZRCjc) 
- [Baboo's channel](https://www.youtube.com/user/baboo) - by [this video](https://youtu.be/qWESrvP_uU8)
- [ChrisTitusTech](https://www.youtube.com/channel/UCg6gPGh8HU2U01vaFCAsvmQ) - gave me more confidence to mess with PowerShell after [this video](https://youtu.be/ER27pGt5wH0)
- [Daniel Persson](https://www.youtube.com/channel/UCnG-TN23lswO6QbvWhMtxpA) - by [this video](https://youtu.be/EfrT_Bvgles)
- [matthewjberger](https://gist.github.com/matthewjberger) - by [this script](https://gist.github.com/matthewjberger/2f4295887d6cb5738fa34e597f457b7f)

## More Debloat Scripts (Community)

The scripts are designed to run With/Without (GUI/CLI) any user interaction. Modify them
beforehand. If you want a more interactive approach check out:

### Powershell (Sorted by complexity - Less to More)
- [windows-debloat](https://github.com/kalaspuffar/windows-debloat) from [kalaspuffar](https://github.com/kalaspuffar);
- [Windows10Debloater](https://github.com/Sycnex/Windows10Debloater) from [Sycnex](https://github.com/Sycnex) (Recommended);
- [win10script](https://github.com/ChrisTitusTech/win10script) from [ChrisTitusTech](https://github.com/ChrisTitusTech) (Recommended);
- [Windows 10 Sophia Script](https://github.com/farag2/Windows-10-Sophia-Script) from [farag2](https://github.com/farag2).

### Python
- [DisableWinTracking](https://github.com/10se1ucgo/DisableWinTracking) from [10se1ucgo](https://github.com/10se1ucgo).

## How did i find specific Tweaks?
<details>
    <summary>How To (Advanced Users)</summary>

By using [SysInternal Suite](https://docs.microsoft.com/pt-br/sysinternals/downloads/sysinternals-suite) `Procmon(64).exe`
i could track the `SystemSettings.exe` by filtering it per Process Name, then `Clearing the list (Ctrl + X)`
(But make sure it is `Capturing the Events (Ctrl + E)`) and finally, applying an option of the Windows Configurations
and searching the Registry Key inside `Procmon(64).exe`.

![Grab the current tweak on registry with Procmon64.exe](./lib/images/Grab-the-current-tweak-on-registry-with-Procmon64.png)

After finding the right register Key, you just need to Right-Click and select `Jump To... (Ctrl + J)` to get on its directory.

![Showing on regedit](./lib/images/Showing-on-regedit.png)

</details>
