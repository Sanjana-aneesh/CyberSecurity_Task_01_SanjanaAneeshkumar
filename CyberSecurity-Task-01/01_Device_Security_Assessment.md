# Part A: Device Security Assessment

## System Security

| Item | Details |
|---|---|
| Operating System | Windows 11 Home Single Language |
| OS Version | 25H2 (OS Build 26200.8655), installed 09-04-2025 |
| Is the system updated? | Yes — "You're up to date" |
| Antivirus Installed? | Yes — 360 Total Security (active, last scan: 0 threats found across 28,896 files) |
| Firewall Enabled? | Yes — on for Domain, Private, and Public networks |

## How to check (quick reference)

**Windows**
- OS version: `Settings > System > About`
- Updates: `Settings > Windows Update`
- Antivirus: `Settings > Privacy & Security > Windows Security > Virus & threat protection`
- Firewall: `Settings > Privacy & Security > Windows Security > Firewall & network protection`

**macOS**
- OS version: Apple menu `> About This Mac`
- Updates: `System Settings > General > Software Update`
- Firewall: `System Settings > Network > Firewall`
- Antivirus: macOS has built-in protection (XProtect, Gatekeeper); note if you use third-party AV

**Linux (Ubuntu example)**
- OS version: `lsb_release -a`
- Updates: `sudo apt update && apt list --upgradable`
- Firewall: `sudo ufw status`
- Antivirus: note if ClamAV or similar is installed

## Screenshots
- [x] OS version screenshot
- [x] Windows Update / Software Update screenshot
- [x] Antivirus status screenshot
- [x] Firewall status screenshot

All 4 screenshots are included in the `screenshots/` subfolder: `os_version.png`, `update_status.png`, `antivirus.png`, `firewall.png`.
