# Permanently Stop Windows Updates (Windows 11)
![Registry](https://img.shields.io/badge/File-.reg-orange)

Stop Windows 11 automatic updates and prevent forced upgrades (like 25H2) by pausing updates until the year 2199.

If you are fed up with the problem causing Windows 11 updates like 25H2 and KB5074109, you can use this .reg file to pause Windows updates until Microslop (Microsoft) stops release slop updates that mostly cause issues.

## How does it work?
This simple .reg file modifies Windows Update  to extend the pause expiry date far into the future. it does this by modifying the date saved in the Windows registry, instead of 7 days in the future, it will be set many years in the future.

## Can I undo the modification?
Yes, here's how:
- Open Settings
- Go to Windows Update
- Click Resume updates

and that's it. It's that simple

## How to use
Follow these steps carefully

**Pause Updates First**
- Open Settings
- Go to Windows Update
- Click Pause updates

_This step is important. Windows must already be in a paused state before running the .reg, otherwise Windows Update will override the values._

**Run the Registry (.reg) File**
- [Download](https://github.com/PixelIndieDev/PermanentlyStopWindows11Updates/releases/download/V1/WindowsUpdateDisable.reg) the .reg file
- Double-click the file to run it.
- Click *Yes* when the User Account Control (UAC) prompt appears.
- Click *Yes* to confirm you want to add the information to the registry.

**Verify**
- Reopen Settings → Windows Update
- You should see:
`Updates paused until 2199`

Done.


## Keywords
Stop Windows 11 update
Block Windows 11 25H2
Block Windows 11 KB5074109
Disable Windows 11 feature updates
Prevent Windows automatic updates
Pause Windows updates permanently
Windows 11 update blocker
Stop forced Windows upgrade
Block Windows 11 version update
Disable Windows Update Windows 11
Turn off Windows 11 updates
How to stop Windows 11 from updating
How to block Windows 11 25H2
How to block Windows 11 25HKB5074109
Stop Windows 11 from auto downloading updates
Windows 11 update problems
Windows 11 update causing issues
Windows 11 buggy update fix
Windows 11 25H2 problems
Windows 11 25H2 issues
Block Windows feature updates registry
Windows Update registry tweak
Windows Update pause registry hack
Stop Windows cumulative updates
Prevent Windows security update install
Disable Windows Update without group policy
Stop Windows update download
Keep current Windows 11 version
Avoid Windows 11 unstable updates
Block Windows update via registry
How to stop Windows from upgrading
Prevent Windows version upgrade
