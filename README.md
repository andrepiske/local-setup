# Local setup

This is a repo for myself every time I setup a new local computer.

## MacOS

### Disable desktop swoosh

Stop MacOS from annoyingly automatically changing desktops on Cmd+Tab.

```
defaults write com.apple.dock workspaces-auto-swoosh -bool FALSE
killall Dock
```

Source: https://superuser.com/a/1802693


### Basic Tooling:

```
brew install --cask monitorcontrol
brew install --cask sourcetree
brew install --cask todoist
brew install --cask dash
brew install --cask spotify
brew install --cask notion
brew install --cask vlc
brew install ffmpeg
brew install bat
brew install ripgrep
brew install the_silver_searcher
brew install httpie
brew install openssl@1.1 # check version
brew install openssl@3 # check version
```

Optional:

```
brew install circleci
brew install awscli
brew install gh
brew install colima
```

