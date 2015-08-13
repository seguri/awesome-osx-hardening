# Yosemite

  - Install LittleSnitch
  - Install OpenVPN

## System preferences

### Security and privacy

#### General

  - Require password after 5 seconds
  - Allow apps downloaded from Mac App Store and identified developers
  
#### FileVault

  - Turn on, no iCloud, use recovery key
  
#### Firewall

  - Turn on
  - Enable stealth mode
  - Block incoming connections
  
#### Privacy

  - Disable location services
  
### User & Groups

  - Add a new non-administrator user for daily use
  - Disable automatic login
  
## Terminal

### Firewall

  - enable pf at boot by editing `/System/Library/LaunchDaemons/com.apple.pfctl.plist`
  - allow traffic only through OpenVPN
  
### User & Groups

  - Hide admin users in login screen with `sudo defaults write /Library/Preferences/com.apple.loginwindow HideAdminUsers -bool YES`
