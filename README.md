# Change Arc Browser Icon

![arc](https://gist.github.com/assets/7717888/fdfbbb6f-ba07-46b9-bdbf-6ef43009479b)

A collection of commands that change the Arc Browser icon on macOS.

## Commands
| Arc Theme        | Command                                                                    |
|------------------|----------------------------------------------------------------------------|
| **Candy Arc**    | `defaults write company.thebrowser.Browser currentAppIconName candy`       |
| **Hologram**     | `defaults write company.thebrowser.Browser currentAppIconName hologram`    |
| **Neon**         | `defaults write company.thebrowser.Browser currentAppIconName neon`        |
| **Fluted Glass** | `defaults write company.thebrowser.Browser currentAppIconName flutedGlass` |
| **Schoolbook**   | `defaults write company.thebrowser.Browser currentAppIconName schoolbook`  |
| **Colorful**     | `defaults write company.thebrowser.Browser currentAppIconName colorful`    |

## Steps
1. Copy one of the above commands
3. Open `Terminal` on macOS
4. Paste and run the command
5. Open Arc Settings (⌘,), then click the Icon tab
6. Click the new icon's radio button (it will already be selected, but clicking it will trigger the actual icon change)
8. The icon should be updated!

## Custom Icons
See (https://gist.github.com/gabe565/9654eea08a9f6c7c1f593049e5bed243?permalink_comment_id=5080589#gistcomment-5080589).
