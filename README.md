# 💤 LazyVim

Refer to the [documentation](https://lazyvim.github.io/installation) to get started.


# Install the config

# Unix
## Make a backup of your current Neovim files:
### required
```
mv ~/.config/nvim{,.bak}
```
### optional but recommended
```
mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}
```
## Clone the starter
```
git clone https://github.com/FastCodeProfile/nvim ~/.config/nvim
```
## Remove the .git folder, so you can add it to your own repo later
```
rm -rf ~/.config/nvim/.git
```
## Start Neovim!
```
nvim
```

# Windows
## Make a backup of your current Neovim files:
### required
```
Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak
```
### optional but recommended
```
Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak
```
## Clone the starter
```
git clone https://github.com/FastCodeProfile/nvim $env:LOCALAPPDATA\nvim
```
## Remove the .git folder, so you can add it to your own repo later
```
Remove-Item $env:LOCALAPPDATA\nvim\.git -Recurse -Force
```
## Start Neovim!
```
nvim
```


