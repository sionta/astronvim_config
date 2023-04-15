# AstroNvim User Configuration

A user configuration for [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

- Linux

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

- Windows

```cmd
move "%LOCALAPPDATA%\nvim" "%LOCALAPPDATA%\nvim.bak"
move "%LOCALAPPDATA%\nvim-data" "%LOCALAPPDATA%\nvim-data.bak"
```

#### Clone AstroNvim and User Config

- Linux

```shell
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
git clone https://github.com/sionta/astronvim_config.git ~/.config/nvim/lua/user
```

- Windows

```cmd
git clone https://github.com/AstroNvim/AstroNvim "%LOCALAPPDATA%\nvim"
git clone https://github.com/sionta/astronvim_config.git "%LOCALAPPDATA%\nvim\lua\user"
```

#### Start Neovim

```shell
nvim
```
