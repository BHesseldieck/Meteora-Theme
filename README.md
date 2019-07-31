# NOT YET OFFICIALLY PUBLISHED ON VS CODE MARKETPLACE

# [Meteora]()

Meteor.js inspired theme [themes]() for VS Code!

[GitHub repository](https://github.com/BHesseldieck/Meteora-Theme)


![screenshot]()


# CHANGELOG

[CHANGELOG.MD](https://github.com/BHesseldieck/Meteora-Theme/blob/master/CHANGELOG.md)

# ScreenShot

![Screenshot]()

## Tweaks &  theming

If you want to play around with new colors, use the setting
`workbench.colorCustomizations` to customize the currently selected theme. For
example, you can add this snippet in your "settings.json" file:

```json
"workbench.colorCustomizations":{
    "tab.activeBackground": "#282c34",
    "activityBar.background": "#282c34",
    "sideBar.background": "#282c34"
}
```

or use the setting `editor.tokenColorCustomizations`

```json
"editor.tokenColorCustomizations":{
    "[Meteora]": {
      "textMateRules": [
        {
          "scope":["source.python"],
          "settings": {
            "foreground": "#e06c75"
          }
        }
      ]
    }
}
```

Please check the official documentation,
[Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference) and
[Theme Color](https://code.visualstudio.com/docs/getstarted/themes), for more helpful information.


![setting.json]()
