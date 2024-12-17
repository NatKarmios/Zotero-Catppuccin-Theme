## Introduction

This repository contains Zotero userChrome.css files using the [Catppuccin](https://github.com/catppuccin/catppuccin) palettes.

It has only been tested on Zotero 7 on Linux Mint 22 but should work for previous versions.

## Installation

In Zotero 7, you need to change the "toolkit.legacyUserProfileCustomizations.stylesheets" flag to `true` for this (and any other) theme to work:

    Go to Edit → Settings
    Click on Advanced
    Scroll down, find and click on "Config Editor".
    search for the flag "toolkit.legacyUserProfileCustomizations.stylesheets" and set it to True.
    Close Zotero

Then, copy the theme into your Zotero user profile folder:

    Go to your user Profile folder
        Windows users: C:\Users\User_name\AppData\Roaming\Zotero\Zotero\Profiles\user_profile.default\
        Linux (Flatpak) users: ~/.zotero/zotero/XXXXXXXX.default/
    Create a folder called "chrome"
    Place the userChrome.css file of your preferred flavour in there
    Start Zotero and enjoy
