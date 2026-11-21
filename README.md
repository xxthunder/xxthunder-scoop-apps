# xxthunder-scoop-apps

A [scoop](https://scoop.sh) bucket for apps by xxthunder.

```powershell
scoop bucket add xxthunder-scoop-apps https://github.com/xxthunder/xxthunder-scoop-apps
scoop install xxthunder-scoop-apps/cmdpal-shortcuts
```

| App | What it is |
|-----|------------|
| `cmdpal-shortcuts` | [Shortcuts for Command Palette](https://github.com/xxthunder/CmdPal.Extension.Shortcuts): folders of your choice in the Command Palette main search. Installs the Store-signed package of the GitHub release; no admin rights, no Developer Mode, no Store. |

The manifests are written by the release tooling of each app's repository, not by hand:
`cmdpal-shortcuts.json` comes from `scripts/publish-store-bundle.ps1` and the template
`scoop/cmdpal-shortcuts.json` in CmdPal.Extension.Shortcuts. Change the template there.
