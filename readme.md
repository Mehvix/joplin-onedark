# joplin-one-dark

---

Last tested with [Joplin 1.6.7](https://github.com/laurent22/joplin/releases/tag/v1.6.7)

Joplin uses [CodeMirror](https://codemirror.net/), so tags prefaced by `.cm` should be compatible with any other application built with CodeMirror.

## Installing

-   Go to `Tool > Options` (`Ctrl` + `,`)
-   Select `Apperance` tab
-   Go to Advanced Settings
-   Under `Custom stylesheet for rendered Markdown`, click `Edit` and copy in the contents of [userstyle.css](userstyle.css)
-   Do the same for `Custom stylesheet for Joplin-wide app styles` with the contents of [userchrome.css](userchrome.css)
-   Restart (Either with killing Joplin in task manager or through the taskbar process list, then re-opening)

### Using stow on Linux

```cmd
$ stow -t ~/.config/joplin-desktop/ css/
```
