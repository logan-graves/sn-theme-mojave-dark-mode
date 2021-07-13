**Forked so that I can create my own JSON endpoint as the original repo doesn't appear to have a proper one.**

Table of Contents
=================
  * [sn-theme-mojave-dark-mode](#sn-theme-mojave-dark-mode)
  * [Revision history](#revision-history)

# sn-theme-mojave-dark-mode

For Standard Notes (https://standardnotes.org/) color theme which roughly matches Mojave Dark Mode.

![Standard Notes Mojave Dark Mode](preview.png "Standard Notes Mojave Dark Mode")

Tested on macOS 10.14

**Installation instructions:** Go to `Extensions > Import extension` and paste whatever's in the "latest-url" field; at the moment it's https://listed.to/p/KXknJEbW6j. Hit enter/return (whatever your OS calls it) and review the info before clicking `Install`.

*This theme currently registers as a Component (rather than a theme); it has something to do with how the extension is written (Some css breaks when I tried switching it to `"content_type": "SN|Theme"`), and I don't care enough to find out why.*

https://docs.standardnotes.org/extensions/publishing

**sn-mojave-dark-mode.json**

```JSON
---
metatype: json
---

{
  "identifier": "io.github.matthew-cox.mojave-dark-mode",
  "name": "Mojave Dark Mode",
  "content_type": "SN|Component",
  "area": "themes",
  "description": "Mojave Dark Mode theme",
  "version": "v0.0.3",
  "url": "https://raw.githubusercontent.com/matthew-cox/sn-theme-mojave-dark-mode/master/dist/mojave-dark-mode.css",
  "download_url": "https://github.com/matthew-cox/sn-theme-mojave-dark-mode/archive/v0.0.3.zip",
  "latest_url": "https://listed.to/p/KXknJEbW6j",
  "marketing_url": "https://github.com/matthew-cox/sn-theme-mojave-dark-mode",
  "thumbnail_url": "https://github.com/matthew-cox/sn-theme-mojave-dark-mode/raw/master/preview.png"
}


```

# Revision history

* v0.0.3: Better colors for advanced markdown editor
* v0.0.2: Add `package.json`
* v0.0.1: Tolerable
