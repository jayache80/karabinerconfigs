# My Karabiner configs
Mildly useful Karabiner configs

Get this repo and traverse into it:
```
git clone https://github.com/jayache80/karabinerconfigs.git
cd karabinerconfigs
```

Put soft links in your Karabiner installation's config directory to these configs:
```
for cfg in *.json; do ln -s "${PWD}/${cfg}" "~/.config/karabiner/assets/complex_modifications"; done
```

Use them by selecting the Karabiner menu item -> Preferences -> Complex
Modifcations -> (+) Add Rule, and then Enable which ones you'd like to use.
