<p align="center">
  <img alt="style-it-themes-logo" src="https://raw.githack.com/style-it-themes/style-it-themes-logos/master/style-it-themes-logo-full.svg" width="580">
</p>
<br>
<h1 align="center"><strong>DD-WRT Trac Inspired Themes</strong></h1>
<p align="center">
  <a href="./LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg?longCache=true&style=for-the-badge" alt="LICENCE">
  </a>
</p>
<p align="center">
  <a href="https://discord.gg/EpdGSfH">
    <img src="https://img.shields.io/badge/style--it--themes-discord%20channel-blue.svg?style=for-the-badge" alt="Style-It Themes (sit) Discord Channel">
  </a>
  <a href="https://github.com/style-it-themes/dd-wrt-trac-inspired-themes/releases">
    <img src="https://img.shields.io/github/tag/style-it-themes/dd-wrt-trac-inspired-themes.svg?label=Current%20Version&style=for-the-badge" alt="Current version">
  </a>
  <a href="https://david-dm.org/Style-it-Themes/dd-wrt-trac-inspired-themes?type=dev">
    <img src="https://img.shields.io/david/dev/style-it-themes/dd-wrt-trac-inspired-themes.svg?label=devDependencies&style=for-the-badge" alt="devDependencies">
  </a>
</p>

# TOC
  * [About](#about)
  * [Features](#features)
  * [Installing](#installing)
    * [Requirements](#requirements)
    * [Install This Style](#install-this-style)
    * [Additional Userstyles](#additional-userstyles)
  * [I Found a Bug](#i-found-a-bug)
  * [Engaging with the Project](#engaging-with-the-project)
    * [Contribution Guidelines](#contribution-guidelines)
    * [Development Scripts](#development-scripts)
  * [Screens](#screens)
  * [Thanks](#thanks)

## About

The *DD-WRT Trac Inspired Themes* style is designed the DD-WRT SVN Trac website.

The default Style is retina burning and lets just say plain looking.

It's made for my personal use only, and shared because... Why not.

This style leverages the _awesome_ v2 [stylus lang color generator](https://github.com/vednoc/stylus-color-generator) by @vednoc

## Features

The *DD-WRT Trac Inspired Themes* style has optional and built in redesigns that fix,
modernize or allow consistence styling through all accessible areas.
if you wish to view complete list click below.

<details>
  <summary>Click to Expand</summary>
 
 ### Preset styles

 * Custom colors (within reason and sane choices users can make up own color schemes)
 * Dracula
 * Duo Cocoa
 * Material
 * Material Darker
 * Solarized Dark
 * Twilight
 * The Matrix
 * Ubuntu

 ### Color Adjustments

 * Optionally darken/lighten to some extent the background, foreground and accent colors. 

 ### Redesigned Inputs

 * Redesigned input styling for checkboxes, radio, dropdown and other interactable elements.
 
 You can optionally choose the checkbox size, however not all sizes will look or align well.

 ### Icon Replacements
  
The code change, issue new/close icons have been replaced with a better Unicode CSS counterparts
 
</details> 

## Installing

### Requirements

* Stylus - install the addon for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) or [Opera](https://addons.opera.com/en-gb/extensions/details/stylus/).

### Install This Style

[![CLICK TO INSTALL WITH - STYLUS](https://img.shields.io/badge/Install_directly_with-Stylus-21d1d0.svg?longCache=true&style=for-the-badge)](https://github.com/style-it-themes/dd-wrt-trac-inspired-themes/raw/main/dd-wrt-trac-inspired-themes.user.styl)  
*Click to install directly from this repository*.

### Limitations of this Project

Some areas like admin areas are likely showing old styles and broken,
if you want these fixed, there are two options:
 
1) [Report issues](#i-found-a-bug) via GitHub with inspected stylesheets and show me what they are. 
 
2) Give me moderator/higher access so I can do this work myself. This wont happen (I don't really want it) anyway so GOTO 1)
 
**Main navigation and sub-navigation alignments:**
 
The main navigations originally was to be centred, but because the width varies from logged in/out this wasn't possible at this time.
The sub navigation just above and because the base CSS is done just cant get be placed any better at this time.

### Additional Userstyles

Style-It Themes (and I) recommends the additional styles below which can be used together without issues.
These add unapparelled consistent experience and extend customizations options for other areas of your browsing life.
  
Save your retinas from the burn!

* [DD-WRT Inspired Themes](https://github.com/style-it-themes/dd-wrt-inspired-themes)
* [DD-WRT Forum Inspired Themes](https://github.com/style-it-themes/dd-wrt-forum-inspired-themes)
* [Stylus Wardrobe](https://github.com/style-it-themes/stylus-wardrobe)
* [Overlay Scrollbars](https://github.com/StylishThemes/Overlay-Scrollbars)

## I Found a Bug

At the first instance of finding a bug, have a look if there is already an open issue, if so add the required information as described in the [issue template](.github/ISSUE_TEMPLATE.md).

If your issue is new, please [open an issue](https://github.com/style-it-themes/dd-wrt-trac-inspired-themes/issues/new/choose) and report your problem.

You will need to be familiar with browser development tools.

[Firefox development tools](https://developer.mozilla.org/en-US/docs/Tools)
[Chrome development tools](https://developers.google.com/web/tools/chrome-devtools)

## Engaging with the Project

There are many ways to engage with the project, all contributions types are most welcome and encouraged, e.g. ask for your fav color schemes, fix some typo(s), add documentation, prettify any included portions, provide feedback or ask a question, even help out with support/questions from other users, to name just a few ways you can engage with this project.

Open a pull request or [ticket](https://github.com/style-it-themes/dd-wrt-trac-inspired-themes/issues/new/choose) to start the ball rolling.

For Git related contributions you will need:

1. [Fork](https://github.com/style-it-themes/dd-wrt-trac-inspired-themes/fork) the project.
2. Install dev-dependencies `npm i --only-dev`
3. Edit the desired files according to current requirement below, commit changes, run fix script `npm run fix` and push changes.
4. Open a pull request

## Contribution Guidelines

After any changes and before opening a PR please run both development scripts below.
Then push your changes and open a PR.

If your contribution includes dependencies updates, ensure this is done as a separate commit.

Thank you in advance for any contributions.

### Development Scripts

* `npm run authors`: Regenerate the AUTHORS file based on Git history
* `npm run fix`: Runs editorconfig via ECLint with `--fix` on the styl file.

For dependencies updates;

* `npm run update`: Update development dependencies.

### For internal use Only

Releases are for internal use only, so remember to not include version bumps with your contributions 

* `npm run major`: Creates a semantic major release.
* `npm run minor`: Creates a semantic minor release.
* `npm run patch`: Creates a semantic patch release.

> Note: Dependencies updates can be submitted as part of any contribution that is a separate commit
>       from main contribution, or as a standalone contribution.

## Screens

# COMING SOON

More screenshots available in [screens directory](/screens) for your perusal.

## Thanks

@vednoc kudos and thanks, for showing me another way to save retinas from the burn.

[Openstyles](https://github.com/openstyles/stylus) for developing Stylus. The best userstyle extension on all the web.

[:arrow_up: UP :arrow_up:](#readme)
