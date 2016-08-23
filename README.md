Various colorschemes for [vifm](http://vifm.info/).
- Astrell (by astrell)
- Darkdesert (by langner)
- Default
- Desert
- G80
- Matrix
- Midnight Commander
- ph (by pihao)
- reicheltd-light (by reicheltd)
- Solarized Dark
- Zenburn
- Zenburn_1 (by frgm)

The solarized-dark theme is based on [istib](https://github.com/istib)'s [version](https://github.com/istib/dotfiles/blob/master/vifm/vifm-colors).

# Get them #

## Distribution
Some distributions offer a package for vifm color schemes. In this case you can install them easily using your package manager.

### openSUSE

```
zypper in vifm-colors
```

## Manual
If you would like to have just one theme you could download it via wget, for example:
`wget -P ~/.vifm/colors https://raw.githubusercontent.com/vifm/vifm-colors/master/solarized-dark`

If you prefer to download all themes you could set it up with git, and stay up to date.

`rm -rf ~/.vifm/colors`

`git clone https://github.com/vifm/vifm-colors ~/.vifm/colors`

To check for updates just type `git pull` in `~/.vifm/colors`.

# Preview them #
A preview of all color themes contained in this repository are available at [this vifm site](http://vifm.info/colorschemes.shtml).

# Set them #
Load with `:colorscheme theme-name` in vifm, or write `colorscheme theme-name` in vifm's configuration file `~/.vifm/vifmrc`.

If you have any color themes that are not in this repo, feel free to fork, add it and send a pull request!
