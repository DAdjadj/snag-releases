# Snag

A free Safari extension for Mac that copies the current tab's link with ⌘⇧C or its toolbar button,
then shows a short "URL copied" note at the top of the page, so you know it reached the clipboard
without pasting to check.

This repository only holds the downloads. Get the latest version from
[Releases](https://github.com/DAdjadj/snag-releases/releases/latest).

## Install

1. Download `Snag.zip` from the latest release and unzip it.
2. Move **Snag** to your Applications folder and open it once.
3. In Safari, open Settings > Extensions and turn on **Snag**.

Requires macOS 26 or later. Snag keeps itself up to date: after a copy it checks at most once a day,
and when a new version is out the note offers an Update button.

## Privacy

Snag only reads the address of the tab you copy, when you copy it, and sends nothing anywhere: no
accounts, no analytics, no servers. The only network request it makes is the update check, which asks
GitHub for the latest version number and contains nothing about you.
