# Change Arc Browser Icon

![User Image](https://github.com/user-attachments/assets/04cac5b0-bfee-4404-8ac3-c40e5c958329)

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
2. Open `Terminal` on macOS
3. Paste and run the command
4. Open Arc Settings (⌘,), then click the Icon tab
5. Click the new icon's radio button (it will already be selected, but clicking it will trigger the actual icon change)
6. The icon should be updated!

## Custom Icons
1. Arc forces users with their predefined icons, making you unable to change and get custom icons for Arc.
2. Arc stores their icons in a .car file: /Applications/Arc.app/Contents/Resources/ARCClients_BaseAssets.bundle/Contents/Resources/Assets.car
3. With an app *https://github.com/NSAntoine/Samra*, editing the Assets.car catalog is made easy, and you can replace one of their icons with yours.
