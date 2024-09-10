# `sanitize-filename` terminal utility in bash

[![No Maintenance Intended]][no-maintenance]

[No Maintenance Intended]: https://img.shields.io/badge/No%20Maintenance%20Intended-%F0%9F%97%99-red
[no-maintenance]: https://unmaintained.tech/


<img alt="Default view" title="Default view" src="./img/Dialog.webp?raw=true" width=350 align="right">

<img alt="`NO_COLOR` support" title="`NO_COLOR` support" src="./img/Dialog-NO_COLOR-support-wow.webp?raw=true" width=350 align="right">

<img alt="Success notification allows for undo." title="Success notification allows for undo." src="./img/Undo_super_wow.webp?raw=true" width=350 align="right">

Convert spaces to underscores, trims punctuation parentheses etc and leading/ending whitespaces.

For GUI, it uses `zenity`.

## Use

* Use as `env NO_GUI=sth sanitize-filename [...]` to disable GUI.
* Use as `env verbose=true sanitize-filename [...]` to enable verbose debugging messages.
* Use as `env dry_run=true sanitize-filename [...]` to not actually perform any filesystem operations.

## Add to Thunar's context menu as an action

End result:

<img alt="Custom action in thunar's context menu when you right click a file." title="Custom action in thunar's context menu when you right click a file." src="./img/Thunar-Context-Menu-Action.webp" width=250>

1. Open the custom actions menu.
   <br />
   <img alt="" title="" src="./img/Thunar-Edit-Actions-Context-Menu.webp" width=256>
2. Create a new action and set these values.
   <br />
   <img alt="" title="" src="./img/Edit-Action-Tab-1.webp" width=256>
   <br/>
   <img alt="" title="" src="./img/Edit-Action-Tab-2.webp" width=256>
