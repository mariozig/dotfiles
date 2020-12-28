# dotfiles

## Prerequisites

* Install [iTerm2](https://www.iterm2.com/)
* Install [Homebrew](http://brew.sh/)
* Install wget: `brew install wget`
* Install zsh:
  * `brew install zsh`
  * `brew install zsh-completions`
 

## Terminal Look

* Update login shell to point @ homebrew's zsh path. (hint: `which zsh`)
* Install oh-my-zsh:
  * `sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"`
* Install Powerline fonts
  * `git clone git@github.com:powerline/fonts.git /tmp/fonts`
  * `cd /tmp/fonts`
  * `./install.sh`
* Install oh-my-zsh `bullet-train` theme
  * `wget -O $ZSH_CUSTOM/themes/bullet-train.zsh-theme http://raw.github.com/caiogondim/bullet-train-oh-my-zsh-theme/master/bullet-train.zsh-theme`
* Configure iTerm2
  * Install the "Space Gray Eighties" theme for iTerm 2
    * `wget -O /tmp/SpaceGray%20Eighties.itermcolors https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/SpaceGray%20Eighties.itermcolors`
  * iTerm2 > Preferences > Profiles > Colors > Load Presets..
    * Select .itermcolors file from /tmp
  * iTerm2 > Preferences > Profiles > Colors > Cursor Colors
    * Set `Smart Cursor Color` to `true`
  * iTerm2 > Preferences > Profiles > Text
    * Regular Font: 12pt Sauce Code Powerline
    * Non-ASCII Font: 11pt Sauce Code Powerline 12pt
  * iTerm2 > Preferences > Profiles > Window
    * Transparency to 0

## ZSH Configs

* In `~/.zshrc` use the following plugins:
 * `plugins=(zsh-completions git rails ruby docker git-flow history tmux sublime bundler chucknorris)` 
