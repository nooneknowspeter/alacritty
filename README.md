alacritty config / setup

![screenshot]()
![screenshot]()

```sh
rm -rf ~/.config/alacritty
git clone https://github.com/nooneknowspeter/alacritty ~/.config/alacritty
cd ~/.config/alacritty
git clone https://github.com/alacritty/alacritty-theme ./themes
```

```powershell
rm $env:APPDATA\alacritty
git clone https://github.com/nooneknowspeter/alacritty $env:APPDATA\alacritty
cd $env:APPDATA\alacritty
git clone https://github.com/alacritty/alacritty-theme .\themes
```
