dotfiles
===

Backup of my dotfiles.

### TODO:
* Bash script for auto installation and backup.

### vim:
`.vimrc` and `.vim/`
* Should work out of box.
* Vim version 7.4.253 with lua, python support required.
* Various TERM tweaks for theme Solarized required.
* Plugins should be managed by Vundle, you need to manually install vundle into `.vim/vundle`.
* Other notable plugins that does NOT work out of box: ghc-mod (install from cabal), powerline (python standalone), ack.
* Installation:
    * Copy `.vimrc` and `.vim/`.
    * Install powerline (standalone version).
    * Install ack.
    * Clone `Vundle.vim` into `.vim/bundle/vundle`.
    * Optional: install ghc-mod from cabal if writing Haskell.
    * Run `make` on `.vim/bundle/vimproc/`.
    * Finally, open up vim and `:BundleInstall`.
* TODO: install script.

### tmux:
`.tmux.conf`
* Should work out of box.
* Changed bind key to Ctrl-A.
* TODO: separate OS X-only scripts.

### slate:
`.slate`
* Should work out of box.

### amethyst:
`.amethyst`
* Should work out of box.
* Collaborates with slate.

### oh-my-zsh:
`.oh-my-zsh/custom/`
* Includes my gentoo-style theme.
* TODO: separate user configurations that works for any shell.

### ghc:
`.ghc/ghci.conf`
* Hoogle and Hlint required.

### xmonad:
`.xmobarrc` and `.xmonad/xmonad.hs`
* Should work out of box.

### xorg:
`.xinitrc`, `.Xresources`, `.Xmodmap` and `.xbindkeysrc`
* Includes configurations for urxvt.
* xbindkey also required.

### gtk+:
`.gtkrc-2.0`
* GTK+ theme settings.

### fonts:
`.fonts/`
* Arch Linux-only.
* Run `fc-cache -vf` to update fonts.
* Other required binary: wqy-microhei, wqy-zenhei.

### urxvt:
`.urxvt/`
* Basically works out of box.
* Required package: `urxvt-perls` and `autocutsel`.
* Please note that urxvt's settings are in `.Xresources`.
