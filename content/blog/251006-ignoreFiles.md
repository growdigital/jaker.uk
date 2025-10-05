---
title: Geek noodling to remove folders from menu
tags:
  - admin
  - tech
  - website
draft: false
date: 2025-10-05T11:55:43+01:00
modified: 2025-10-05T11:59:00+01:00
---
I have an `assets/templates/` folder, where I edit the Obsidian template for the [Unique Note Creator](https://help.obsidian.md/plugins/unique-note) plugin. However, the assets folder and the README file were appearing in the automagically created menus. 

I had to add:
```
ignoreFiles:
  - 'README'
  - 'assets/'
```

to the `hugo.yaml` config file.