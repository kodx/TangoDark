# [TangoDark](https://github.com/kodx/TangoDark)
### A dark interface and syntax theme for [Sublime Text 3](http://www.sublimetext.com/3), [rxvt-unicode](http://software.schmorp.de/pkg/rxvt-unicode.html), [Konsole](https://konsole.kde.org/) and [Emacs](http://www.gnu.org/software/emacs)

## About

TangoDark is a dark theme and a syntax color scheme based on [Tango Style Theme Guidelines](http://tango.freedesktop.org/Tango_Icon_Theme_Guidelines).

Filetype icons  from [Predawn Theme](https://github.com/jamiewilson/predawn).
Folder icons from [Soda Theme by Ian Hill](http://buymeasoda.com/).

## How to install the Tango Dark theme in Sublime Text 3

From sublime text open your Packages folder:
__Preferences -> Browse Packages__

![Sublime Text packages screenshot](doc/sublime_text_packages_screenshot.png)

### Manual mode

Create directory `TangoDark` and put contents of this repo inside.

### Git mode

Run inside `Packages` dir
```sh
git clone https://github.com/kodx/TangoDark.git
```

### Activating the theme for Sublime Text 3

Open your user settings file `preferences.sublime-settings` and add or replace your current theme settings with the code below:

```json
{
    "theme": "TangoDark.sublime-theme",
    "color_scheme": "Packages/TangoDark/TangoDark.tmTheme",
}
```

For bigger UI font(14pt) use:
```json
{
    "color_scheme": "Packages/TangoDark/TangoDark-font14.tmTheme",
}
```

![TangoDark screenshot](doc/tangodark_screenshot.png)

_Note: File icons are supported only for **Beta BUILDS 3065+**._

## Sublime Text 3 - PlainTasks

TangoDark theme supplied with [PlainTasks](https://github.com/aziz/PlainTasks) color scheme:

![TangoDark PlainTasks screenshot](doc/tangodark_plaintasks_screenshot.png)

To activate open `PlainTasks.sublime-settings` and add or replace "color_scheme" option with:

```json
{
    "color_scheme": "Packages/TangoDark/TangoDark-PlainTasks.tmTheme",
}
```

## Emacs

Add to your Emacs config:

```lisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/TangoDark")
(load-theme 'tangodark t)
```

![TangoDark Emacs screenshot](doc/tangodark_emacs_screenshot.png)

## urxvt-unicode

Add to your `~/.Xresources` contents of `urxvt/Xresources`.

![TangoDark rxvt-unicode screenshot](doc/tangodark_urxvt_screenshot.png)

## konsole

Copy file `TangoDark.colorscheme` from `konsole` to `~/.local/share/konsole` directory and choose theme `TangoDark` in settings.

## License

TangoDark Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so.

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: Based on TangoDark Theme by Yegor Bayev (https://github.com/kodx/TangoDark)

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "TangoDark Theme" (or a close variant) in the main project title, repo name or a Package Control name.
