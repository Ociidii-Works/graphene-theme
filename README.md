# Petroleum Theme

A very dark theme for Sublime Text 3 based on [Soda](http://buymeasoda.github.com/soda-theme/).

This is especially suited for nocturnal or photophobe developers.

## Design

 [![thumb]][full]
 
 The font used is Anomymous Pro

## Installation

Petroleum theme is designed to work with the latest verion of Sublime Text, [Sublime Text 3](http://www.sublimetext.com/3dev).

### Using Sublime Package Control

The Petroleum Theme package is listed as `Theme - Petroleum` in the packages list.

### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/ociidii-works/theme_petroleum/ "Theme - Petroleum"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Petroleum`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions below for your specific version.

### Sublime Text 2

We lack the time and man-power to officially support Sublime Text 2 at the same time as Sublime Text 3. Sorry. :(

### Sublime Text 3

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Petroleum.sublime-theme"`

**Example Sublime Text 3 User Settings**

    {
        "theme": "Petroleum.sublime-theme"
    }

## Additional Features

### Alternate Tab Styles

Petroleum Theme suppports the same alternate UI styles proposed by Soda Theme.

To avoid switching back and forth between repos, here's a quote from Soda Theme:

> By default, a square tab style is used. If you'd prefer to use the original curved tab style, add the following custom setting to your `Settings - User` file:

>    "soda_classic_tabs": true

> ![Soda Tab Styles](http://buymeasoda.github.com/soda-theme/images/features/multiple-tab-styles.png)

> ### Sidebar Folder Icons

> Soda Theme has folder icons by default with Sublime Text 3.

> If you'd like to use folder icons in the Sublime Text 2 sidebar instead of the regular arrows, add the following custom setting to your `Settings - User` file:

>     "soda_folder_icons": true

> ![Soda Folder Icons](http://buymeasoda.github.com/soda-theme/images/features/sidebar-folder-icons.png)

> ### Retina Resolution UI

> Soda Theme has been designed to take advantage of retina resolution (high-dpi) displays. Both Soda Light and Soda Dark support retina displays.

> ![Soda Retina](http://buymeasoda.github.com/soda-theme/images/features/soda-retina.png)

### Theme Customisation

Sublime Text provides an elegant way to tweak existing themes without having to duplicate or maintain a separate copy of the original theme. If there are aspects of Petroleum Theme that you would like to adjust, take a look at the [theme customisation](https://github.com/buymeasoda/soda-theme/wiki/Theme-customisation) wiki page.

## Bonus Options

### Syntax Highlighting Colour Schemes

We recommend using [Pastel-Paws](https://github.com/Ociidii-Works/pastel_paws) (Petroleum variant) as a color scheme since they are meant to be used together.

If you'd like to use the syntax highlighting schemes shown in the screenshots:

* Download Pastel Paws through Package Control
* Enable the colour scheme via `Preferences -> Color Scheme -> User`

## Development

Please note, Sublime Text dev builds move quickly and changes can occur with the theme API between releases, so there may be occasions where the theme doesn't quite work with a brand new dev release.

## License

Petroleum is licensed under the [Creative Commons Attribution-ShareAlike 4.0 License](http://creativecommons.org/licenses/by-sa/4.0/). You are free to share and remix the theme, however please abide by the license terms when doing so.

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: Based on Petroleum Theme by David "Xenhat" Turenne

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "Petroleum Theme" (or a close variant) in the main project title, repo name or Package Control name.

[thumb]: https://raw.githubusercontent.com/Ociidii-Works/theme_petroleum/master/preview/graphene_thumb.png
[full]: https://raw.githubusercontent.com/Ociidii-Works/theme_petroleum/master/preview/graphene_full.png
