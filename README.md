# new-mac

The things I do when setting up a new Mac

## Setup shell

- [ ] Install [homebrew](https://brew.sh)
- [ ] `brew install git`
- [ ] `cd ~; mkdir git; cd git; git clone https://github.com/flowolf/new-mac; cd new-mac`
- [ ] Install [Brewfile](Brewfile) `brew bundle`
- [ ] Setup [dotfiles](https://github.com/flowolf/dotfiles/)
- [ ] Copy some files
  - [ ] Applications/Scripts
  - [ ] Documents
  - [ ] ...

## VS Code

- [ ] Login for settings sync

## Finder

- [ ] Show Path Bar

## Dock

- [ ] Auto-hide dock
  - [ ] `defaults write com.apple.dock autohide -bool true && defaults write com.apple.dock autohide-delay -float 0.3 && defaults write com.apple.dock autohide-time-modifier -float 0.3 && killall Dock ` defaults (`defaults delete com.apple.dock autohide && defaults delete com.apple.dock autohide-delay && defaults delete com.apple.dock autohide-time-modifier && killall Dock`)
- [ ] Remove all the  things

## Install and setup

- [ ] Login to Firefox
- [ ] [Signal](https://signal.org/)
  - start Signal, and link.
- [ ] [Element](https://element.io/)
  - start and login.
- [ ] [Slack](https://slack.com/)
  - start and login.
- [ ] Login to OneDrive
  - [ ] link one directory in Documents
- [ ] [Spotify](https://spotify.com)
  - start and login.

## dev tools setup

- [install nvm ](https://github.com/nvm-sh/nvm#install--update-script)
  - install nvm
- install cocoapods:
  - sudo gem install activesupport -v 6.1.7.6
  - sudo gem install cocoapods

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
- [ ] Keyboard `Key Repeat` to the fastest, `Delay` to the second shortest
- [ ] Disable all app dock bouncing `defaults write com.apple.dock no-bouncing -bool TRUE`
- [ ] Disable Siri system wide, and remove Siri button from touch bar
- [ ] Setup `/etc/hosts` using [someonewhocares.org/hosts](https://someonewhocares.org/hosts/) ‼️
  - [ ] Don't use Little Snitch for this, as it will slow down their UI a lot, better use the hosts file
- [ ] Keyboard settings -> Shortcuts -> Input Sources -> Uncheck both input source switching options
- [ ] iTerm Tab Bar Location to bottom
- [ ] iTerm Profiles Terminal -> Scrollback lines -> `Unlimited scrollback`

# maybe:

- [ ] [Disable all kinds of animations](https://apple.stackexchange.com/questions/14001/how-to-turn-off-all-animations-on-os-x)
  - [ ] `defaults write -g NSAutomaticWindowAnimationsEnabled -bool false` (disable popover animations)
  - [ ] `defaults write -g NSWindowResizeTime -float 0.001`
