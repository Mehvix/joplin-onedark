# joplin-onedark

Working with [Joplin 2.8.8](https://github.com/laurent22/joplin/releases/tag/v2.8.8)

Joplin uses [CodeMirror](https://codemirror.net/), so tags prefaced by `.cm` should be compatible with any other application built with CodeMirror.

## Installing

1. Go to `Tool > Options` (`Ctrl` + `,`)
2. Select `Apperance` tab
3. Go to Advanced Settings
4. Under `Custom stylesheet for rendered Markdown`, click `Edit` and copy in the contents of [userstyle.css](userstyle.css)
5. Do the same for `Custom stylesheet for Joplin-wide app styles` with the contents of [userchrome.css](userchrome.css)
6. Restart (Either with killing Joplin in task manager or through the taskbar process list, then re-opening)

### Using GNU stow

```cmd
$ stow -t ~/.config/joplin-desktop/ css/
```