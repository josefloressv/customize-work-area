# iTerm 2 Customization

## Commandline with Powerline
https://gist.github.com/480/3b41f449686a089f34edb45d00672f28

```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### Themes
https://github.com/ohmyzsh/ohmyzsh/wiki/Themes

```bash
vi ~/.zshrc
ZSH_THEME="agnoster" #default robbyrussell


source ~/.zshrc
```

### Fonts
https://github.com/powerline/fonts/tree/master/DroidSansMono

Install in `iTerm2 > Preferences > Profiles > Text > Font` and choose `Droid Sans Mono for Powerline`


### Hidde user@hostname
```bash
comment Line 250 from the theme
vi ~/.oh-my-zsh/themes/agnoster.zsh-theme
#  prompt_context

# Apply the changes
source ~/.zshrc
```

# iTerm Default Widndows Size
`iTerm2 > Preferences > Profiles > Windows > Font` and set `Colums: 200, Rows:30`
