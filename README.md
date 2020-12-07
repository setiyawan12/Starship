# Starship

  # Install the starship binary: 

With Shell:
  
    curl -fsSL https://starship.rs/install.sh | bash
    
  # Install via Package Manager:

  With Homebrew:

    brew install starship

  With Scoop:

    scoop install starship
    
 
# Add the init script to your shell's config file:

  Bash
  Add the following to the end of ~/.bashrc:
  
    eval "$(starship init bash)"
    
  Fish
  Add the following to the end of ~/.config/fish/config.fish:
  
    starship init fish | source
    
  Zsh
  Add the following to the end of ~/.zshrc:
  
    eval "$(starship init zsh)"
