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
$ rm ~/.config/joplin-desktop/userchrome.css ~/.config/joplin-desktop/userstyle.css  # delete exising theme files
$ stow -t ~/.config/joplin-desktop/ css/   # within project directory
```


### Note Tabs Settings

If using the [Joplin Note Tabs](https://github.com/benji300/joplin-note-tabs) addon, go to `Tools > Options > Note Tabs`

* Background color: `#21252b`
* Hover Background color: `#282c34`
* Active background color: `#1d1f23`
* Infobar background color: `#636d83`
* Foreground color: `#abb2bf`
* Active foreground color: `#e2ebfd`
* Divider color:: `#636d83`

