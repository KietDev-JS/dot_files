# MACOS dot files

This folder contains configuration files for my macos setup and services used on this system.

## Apps:

- **marta/conf.marta**: Configuration file for Marta file manager.
- **wezterm/** Configuration file for WezTerm terminal emulator.
- **sketchybar**: Script for updating the clock display in SketchyBar.
- **btop/btop.conf**: Configuration file for btop, a resource monitor.
- **aerospace**: Configuration file for AeroSpace, a window manager for macOS.

## Usage
- **brew**:
- fzf
- neofetch
- neovim                 
- borders
- gh
- lua                     
- node           
- btop
- sketchybar
- starship (zsh setup)
- yt-dlp (youtube cli)
- zellij (tmux alternative)
- eza (better ls)                
- zoxide (better cd)
- zsh-autosuggestions 
- zsh-syntax-highlighting

- **zshrc**:
- Add following lines to ~/.zshrc
- eval "$(starship init zsh)"
- eval "$(zoxide init zsh)"
- source $(brew --prefix)/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
- source $(brew --prefix)/share/zsh-autosuggestions/zsh-autosuggestions.zsh
- export PATH="$(brew --prefix python)/libexec/bin:$PATH"
- alias cd=z
- alias ls=eza


