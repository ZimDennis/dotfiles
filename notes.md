# Additional Setup

* brew
  * /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
* zsh
  * sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
  * chsh -s $(which zsh)
* nvm
  * curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
* git-flow
  * git flow init -d
  * git config gitflow.prefix.versiontag v
* vs-code
  * Use extension 'Settings Sync' to restore all other extensions and settings
* android development
  * Add the following lines to ~/.shrc
    * `export ANDROID_HOME=/usr/local/share/android-sdk`
    * `export PATH=$PATH:$ANDROID_HOME/platform-tools/:$ANDROID_HOME/emulator`
  * run `source ~/.zshrc`
  * setup android-studio