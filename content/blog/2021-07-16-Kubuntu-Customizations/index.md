---
title: "Kubuntu Customizations"
date: 2021-07-16T16:45:33+02:00
slug: "kubuntu-customizations"
draft: true
---

This article is a collection of Kubuntu and KDE customizations I usually apply to get the best working experience.
These are **only based on my individual personal preference**.
This collection will grow over time and will be updated every time I see myself adjusting Kubuntu.


## Delay of Tooltips

I usually have my Task Bar pinned to the left of my screen.
Hence, I always use the `icons-only` mode.
When I have multiple windows of the same applications opened at the same time, they get grouped into one icon.

To select one specific window of the application, I hover over the application icon, wait for the previews (aka. toolbar) to open and click on the desired window.
That waiting time is way too long for me (~1s).
Usually, I shorten this waiting time to 200ms by applying
```bash
kwriteconfig5 --file ~/.config/plasmarc --group PlasmaToolTips --key Delay 200
```

If you want to make it even more instant, use `1` instead of `200`.
Note, that setting `0` turns off the tooltips altogether, so a positive value is required.

This tip was given on [reddit.com](https://www.reddit.com/r/kde/comments/66vu2u/how_to_set_faster_windows_preview_tooltips_in/dglpcwn/?utm_source=reddit&utm_medium=web2x&context=3) by the reddit user [Zren](https://www.reddit.com/user/Zren/).