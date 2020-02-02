# Brewfile
https://homebrew-file.readthedocs.io/en/latest/getting_started.html

# Set Up
# Install
```sh
brew install rcmdnk/file/brew-file
```

# Add to zsh
```sh
if [ -f $(brew --prefix)/etc/brew-wrap ];then
  source $(brew --prefix)/etc/brew-wrap
fi
```

# Add SSH keys
```sh
ssh-add -A
```
# Then set repo with
```sh
brew set_repo
```
Use git@github.com:Daddy-Badger/Brewfile.git

# Initialise repo
```sh
brew file install
```
