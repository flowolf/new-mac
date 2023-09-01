# new-mac

The things I do when setting up a new Mac

## Setup shell

- [ ] Install [homebrew](https://brew.sh)
- [ ] `brew install git`
- [ ] `cd ~; mkdir git; cd git; git clone https://github.com/flowolf/new-mac; cd new-mac`
- [ ] Install [Brewfile](Brewfile) `brew bundle`
- [ ] Login to Firefox
- [ ] Setup [dotfiles](https://github.com/flowolf/dotfiles/)
- [ ] Login to OneDrive
  - [ ] link one directory in Documents
- [ ] Copy some files
  - [ ] Applications/Scripts
  - [ ]

## VS Code

- [ ] Login for settings sync

## Finder

- [ ] Show Path Bar

## Dock

- [ ] Auto-hide dock
  - [ ] `defaults write com.apple.dock autohide -bool true && defaults write com.apple.dock autohide-delay -float 0.3 && defaults write com.apple.dock autohide-time-modifier -float 0.3 && killall Dock ` defaults (`defaults delete com.apple.dock autohide && defaults delete com.apple.dock autohide-delay && defaults delete com.apple.dock autohide-time-modifier && killall Dock`)
- [ ] Remove all the  things

## Install and setup

- [ ] [Signal](https://signal.org/)
  - start Signal, and link.
- [ ] [Element](https://element.io/)
  - start and login.
- [ ] [Slack](https://slack.com/)
  - start and login.
- [ ] [Spotify](https://spotify.com)
  - start and login.

## Mac App Store

- [ ] [XCode](https://apps.apple.com/at/app/xcode/id497799835?l=en-GB&mt=12)
  - download via AppStore
- [ ] [Lightshot](https://apps.apple.com/us/app/lightshot-screenshot/id526298438)
  - install Lightshot

## Other

- [ ] Make emojis faster using `defaults write NSGlobalDomain NSAutomaticWindowAnimationsEnabled -bool false`
- [ ] Enable taps for trackpad
- [ ] Increase trackpad speed
- [ ] Add email to lock message in `Lock Screen` settings: `Show message when locked`
- [ ] Enable zoom for `control` + scrolling (System Preferences -> Accessibility -> Zoom -> `Use scroll gesture ...`
- [ ] Custom keyboard shortcut for all apps: `control` + tab => `Select Next Tab` and `Next Tab`, same for previous (used in applications like Tweetbot)
- [ ] Keyboard `Key Repeat` to the fastest, `Delay` to the second shortest
- [ ] Enable US keyboard with German Umlaut mapping: https://hci.rwth-aachen.de/usgermankeyboard
- [ ] Install Bitbar and point to Google Drive Bitbar folder
- [ ] Disable all app dock bouncing `defaults write com.apple.dock no-bouncing -bool TRUE`
- [ ] Disable Siri system wide, and remove Siri button from touch bar
- [ ] `defaults write com.flexibits.fantastical2.mac HideLocationSuggestions -bool YES`
- [ ] `defaults write com.flexibits.fantastical2.mac AlwaysIgnoreLocation -bool YES`
- [ ] `defaults write com.flexibits.fantastical2.mac ShowEmailDefaultAlarm -bool YES`
- [ ] Fantastical Advanced setting `Go to today after adding items` (who even comes up with that default)
- [ ] [Disable all kinds of animations](https://apple.stackexchange.com/questions/14001/how-to-turn-off-all-animations-on-os-x)
  - [ ] `defaults write -g NSAutomaticWindowAnimationsEnabled -bool false` (disable popover animations)
  - [ ] `defaults write -g NSWindowResizeTime -float 0.001`
- [ ] System preferences -> Notifications -> `Tower` -> None, as Tower shows pretty useless notifications all the time, same for Sonos
- [ ] Setup `/etc/hosts` using [someonewhocares.org/hosts](https://someonewhocares.org/hosts/)
  - [ ] Don't use Little Snitch for this, as it will slow down their UI a lot, better use the hosts file
- [ ] Block port 80 using Little Snitch
- [ ] Change the screenshot location from BTT
- [ ] Transfer keybase.io account
- [ ] Keyboard settings -> Shortcuts -> Input Sources -> Uncheck both input source switching options
- [ ] iTerm Tab Bar Location to bottom
- [ ] iTerm Profiles Advanced -> Select Editor VS Code
- [ ] iTerm Profiles Terminal -> Scrollback lines -> `Unlimited scrollback`
