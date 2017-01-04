# mac-dev
These are instructions to set up my Mac development environment.

## Dependencies
1. git - installed by osx (accept agreement)
2. Homebrew

```bash
# make sure /usr/local/bin comes before /usr/bin in $PATH
brew install htop
brew install tmux
brew install reattach-to-user-namespace       # fixes some annoying tmux shortcomings on osx
brew install vim --with-python3 --with-lua    # replaces system vim with vim8 w/python and lua support

```

## Modules
```bash
npm i -g vtop         # Better top program
npm i -g speed-test   # speed test
```

## Essential Software
- [Alfred](https://www.alfredapp.com/) - Spotlight replacement
- [SizeUp](http://www.irradiatedsoftware.com/sizeup/) - window manager
- [iTerm2](https://www.iterm2.com/version3.html) - terminal replacement
