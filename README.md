# Installing Brew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Add Brew to PATH
```bash
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

# Install Yabai
```bash
brew install koekeishiya/formulae/yabai
```

# Install SKHD
```bash
brew install koekeishiya/formulae/skhd
```

# Adding config files for Yabai
- Create a new directory `~/.config/yabai` and `cd` into it
- Create a new file `yabairc`
- Paste the content of `yabairc-temaplate` into the new file and save it

# Start the services
```bash
brew services start yabai
```

# Adding config files for SKHD
- Create a new directory `~/.config/skhd` and `cd` into it
- Create a new file `skhdrc`
- Paste the content of `skhd-template` into the new file and save it

# Start SKHD service
```bash
brew services start skhd
```

# More Resources
- For more info you can visit this blog [post](https://www.josean.com/posts/yabai-setup)
- And this Youtube [video](https://www.youtube.com/watch?v=k94qImbFKWE)