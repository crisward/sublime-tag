# sublime-tag

Sublime syntax highlighting for Riot JS TAG files.
Witin sublime you can use HTML, but this doesn't work well with coffeescript.

With this plugin you can use

```
<yourtag>
  <script type="test/coffeescript">
    # your coffee script here
  </script>
</yourtag>
```
This will then have correct syntax highlighting.



## Installation

### Install via Package Control

1. You will need the [Package Control](https://packagecontrol.io/installation) Package Manager for Sublime
1. Open the command pallete with `⌘+shift+p`
1. Type `install` and select `Package Control: Install Package`
1. Wait a moment for the package list to appear, and type `tag` and select `TAG Syntax`
1. Open a .tag file and in the lower right hand corner of your Sublime window, open the syntax dropdown.
1. Select "Open all with current extension as..." and then choose 'Riot Tag'

### Install from source

To install this plugin from Github, follow these steps:

1. Open Sublime and open "Package Control" (cmd + shift + p).
1. Type "Add Repository"; select the result (hit enter).
1. At the bottom of your Sublime window you will see a text input that prompts you for the Github URL.
1. Copy and paste: "https://github.com/crisward/sublime-tag".
1. Give Sublime a few minutes to add the repo.
1. Open "Package Control" again (cmd + shift + p) and type "Install Package".
1. Type "sublime tag"; select the result (hit enter).
1. Give Sublime a few minutes to install the package.
1. Open a .tag file and in the lower right hand corner of your Sublime window, open the syntax dropdown.
1. Select "Open all with current extension as..." and then choose 'Riot Tag'

## Credit

Thanks to Kevin Wood <kevin@guidebook.com>, as I've used his sublime CJSX plugin repo
as a template to setup this repo.

