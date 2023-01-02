# joplin-onedark

Working with [Joplin](https://github.com/laurent22/joplin/) [2.9.17](https://github.com/laurent22/joplin/releases/tag/v2.9.17)

Joplin uses [CodeMirror](https://codemirror.net/), so tags prefaced by `.cm` should be compatible with any other application built with CodeMirror.

## Installing

1. Go to `Tool > Options` (`Ctrl` + `,`)
2. Select `Apperance` tab
3. Go to Advanced Settings
4. Under `Custom stylesheet for rendered Markdown`, click `Edit` and copy in the contents of [userstyle.css](css/userstyle.css)
5. Do the same for `Custom stylesheet for Joplin-wide app styles` with the contents of [userchrome.css](css/userchrome.css)
6. Restart (Either with killing Joplin in task manager or through the taskbar process list, then re-opening)

### Copying (Linux)

```sh
$ cp css/* ~/.config/joplin-desktop
```

This should be done after every `git pull` update

### Using GNU stow (Linux)

Automatically syncs repo changes, requires [stow](https://www.gnu.org/software/stow/)

```sh
$ rm ~/.config/joplin-desktop/userchrome.css ~/.config/joplin-desktop/userstyle.css  # delete existing theme files
$ stow -t ~/.config/joplin-desktop/ css/   # within project directory
```


## Note Tabs

If using the [Joplin Note Tabs](https://github.com/benji300/joplin-note-tabs) addon, go to `Tools > Options > Note Tabs`

| Setting            | Value     |
| ------------------ | --------- |
| Background         | `#21252b` |
| Hover Background   | `#282c34` |
| Active Background  | `#1d1f23` |
| Infobar Background | `#636d83` |
| Foreground         | `#abb2bf` |
| Active Foreground  | `#e2ebfd` |
| Divider            | `#636d83` |

