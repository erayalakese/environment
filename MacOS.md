### Upgrade Ruby & Install Homebrew
```
curl -L https://get.rvm.io | bash -s stable
source ~/.rvm/scripts/rvm
rvm install ruby-2.4.1
rvm --default use 2.4.1
# Add to bashrc
export PATH="/usr/local/bin:$PATH"
```

### Configure Homebrew
```
brew analytics off
brew update
brew upgrade
```

### Git
```
brew install git
git config --global pull.rebase true
```

### ZSH
```
brew install zsh
```
