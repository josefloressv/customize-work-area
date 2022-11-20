iTerm 2 Customization

Powerline

```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Themes
https://github.com/ohmyzsh/ohmyzsh/wiki/Themes

```bash
vi ~/.zshrc
ZSH_THEME="agnoster" #default robbyrussell


source ~/.zshrc
```


Fonts
https://github.com/powerline/fonts/tree/master/DroidSansMono

Install in `iTerm2 > Preferences > Profiles > Text> Font` and choose `Droid Sans Mono for Powerline`

Hidde user@hostname
```bash
comment Line 250 from the theme
vi ~/.oh-my-zsh/themes/agnoster.zsh-theme
#  prompt_context

# Apply the changes
source ~/.zshrc
```
