## Installing Kitty
```bash
curl -L https://sw.kovidgoyal.net/kitty/installer.sh | sh /dev/stdin
```

## Color Theme
```bash
# Download the theme you like
THEME=https://raw.githubusercontent.com/dexpota/kitty-themes/master/themes/Brogrammer.conf
wget "$THEME" -P ~/.config/kitty/kitty-themes/themes

# Create a symlink to the downloaded theme
cd ~/.config/kitty
ln -s ./kitty-themes/themes/Brogrammer.conf ~/.config/kitty/theme.conf

# Create a kitty.conf file and add the downloaded theme
echo "include ./theme.conf" > kitty.conf
```

Another way is to type
```bash
kitten themes
```
Ref: https://sw.kovidgoyal.net/kitty/faq/#how-do-i-change-the-colors-in-a-running-kitty-instance

## Kitty Overview
https://sw.kovidgoyal.net/kitty/overview/
