# dotfiles

Configs and stuff from `~/.*`

## Firefox config

Configs of firefox and addons

### Installation
1. Install extensions from links in `firefox-config/extensions`
2. Setup theme for tab-center-redux from `firefox-config/tabs-theme.css`
3. Enable dark theme
4. Move `userChrome.css` to `$FIREFOX_PROFILE_DIR/chrome/userChrome.css`
5. PROFIT

`$FIREFOX_PROFILE_DIR` - easy way to find it is: 
```bash
cd ~/.mozilla/firefox
cd $(find -mindepth 1 -maxdepth 1 -type d | head -n1)
```

