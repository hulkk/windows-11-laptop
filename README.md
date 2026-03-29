# windows-11-laptop
## Install media
- Media language, English (United states) / Finnish
- rufus
- enable local account usage

## Post-install
### initial
- network driver
- windows update
- display scaling 150% -> 125%
- enable bitlocker

### scripted
- install.ps1
- clean.ps1

### hardening
- baseline: NNN
- deviations
  - UAC: "Configure the system to only elevate executables that are signed and Validated."
