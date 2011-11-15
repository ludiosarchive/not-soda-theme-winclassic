# (Not) Soda Theme with Windows Classic scrollbars

This is a copy of https://github.com/buymeasoda/soda-theme/ , modified to have Windows Classic scrollbars instead of the OS X-style pucks.

## Installation
=======

Repo warning: I rebase my changes on top of soda-theme and use `git push --force`.

If you are a git user, the best way to install the theme and keep up to date is to clone the repo directly into your `Packages` directory in the Sublime Text 2 application settings area.

Go to your Sublime Text 2 `Packages` directory and clone the theme repository using the command below:

    git clone https://github.com/ludios/not-soda-theme-winclassic/ "Theme - Soda"

## Activating the theme

To configure Sublime Text 2 to use the theme:

* For Sublime Text 2 (Build 2174) and later - Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`. For earlier builds - Open your User Global Settings Preferences file `Sublime Text 2 -> Preferences -> Global Settings - User`
* Add (or update) your theme entry to be `"theme": "Soda Light.sublime-theme"` or `"theme": "Soda Dark.sublime-theme"`

### Example User Settings

    {
        "theme": "Soda Light.sublime-theme"
    }

## Bonus Options

### Syntax Highlighting Colour Schemes

The Soda Light screenshot uses a modified version of Espresso Tutti Colori and the Soda Dark screenshot uses a modified version of Monokai.

If you'd like to use the syntax highlighting schemes shown in the screenshots: 

* Download [colour-schemes.zip](http://buymeasoda.github.com/soda-theme/extras/colour-schemes.zip)
* Unzip and place the extracted `tmtheme` files in the Sublime Text 2 `Packages/User` folder
* Enable the colour scheme via `Preferences -> Color Scheme -> User`

## Release Notes

Soda theme is designed to work with the latest [development build](http://www.sublimetext.com/dev) of Sublime Text 2. ST2 dev builds move quickly and changes can occur with the theme API between releases, so there may be occassions where the theme doesn't quite work with a brand new dev release.

## Legals

The theme contains some icons from the excellent [Pictos](http://pictos.drewwilson.com/) series by Drew Wilson which the author of Soda Theme has a license for. Any use of these icons, other than for the purpose of the theme itself, would need to comply with Drew's [icon licensing agreement](http://stockart.drewwilson.com/license/).
