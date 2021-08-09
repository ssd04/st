# st - simple terminal

st is a simple terminal emulator for X which sucks less.

This is based on [suckless st](https://st.suckless.org/) project.

## Install
```bash
make clean install
```

Run with `sudo` if you want to override the system build.

## Xresources

`.Xresources` file is used for configuring colors, font and other variables.

Don't forget to run `xrdb` on the config file in order for the X server to load the settings:
```bash
xrdb ~/.Xresources
```

## Patches

* font2
* gruvbox
* ligatures
* xresources
