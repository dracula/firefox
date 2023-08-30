### [Firefox](https://www.mozilla.org/en-US/firefox/new/)

#### Install using Firefox Addon

Install the theme directly from [Firefox Addons](https://addons.mozilla.org/en-US/firefox/addon/dracula-dark-colorscheme/).

#### Install using userChrome

[Edge-Frfox](https://github.com/bmFtZQ/edge-frfox) fork CSS Theme that aims to recreate the look and feel of the Chromium version of [Microsoft Edge](https://www.microsoft.com/edge).

##### **Installation**

1. Go to `about:support` and click the "Open Folder/Show in Finder" button for the root directory of your browser profile/s.
2. Download and copy the `userChrome/chrome` folder into the profile folder.git clone https://github.com/dracula/firefox.git

3. Go to `about:config` and change these preferences:

   For all operating systems:

   1. `toolkit.legacyUserProfileCustomizations.stylesheets` = `true`
   2. `svg.context-properties.content.enabled` = `true`
   3. `layout.css.color-mix.enabled` = `true`

   On macOS: 4. To use the Edge style context menu on macOS then set `widget.macos.native-context-menus` = `false`

   Recommended: 5. `browser.tabs.tabMinWidth` = `66` 6. `browser.tabs.tabClipWidth` = `86` 7. `browser.tabs.tabmanager.enabled` = `false`

##### **JSON Viewer**

1. Go to `about:config` page and set `devtools.jsonview.enabled` = `false`.
2. Install the JSON Lite extension from [here](https://addons.mozilla.org/en-US/firefox/addon/json-lite/).
3. Set the values as shown in the screenshot above, you can find the values to copy below.

```
Font: 13px JetBrains Mono,monospace
Text color: #f8f8f2
Background color: #282A36
Info color: #6272a4
Info hover color: #6272a4
Line numbers color: #6272a4
Line numbers background: #1D2128
String color: #f1fa8c
Number color: #bd93f9
Boolean color: #bd93f9
Null color: #bd93f9
Propertie name color: #8be9fd
Error color: #ed2655
```

##### **Tweaks**

Certain customizations like hiding the Firefox logo on the newtab page or switching to floating tabs can be done on the theme. More information on how to do this can be found in the original [repository](https://github.com/bmFtZQ/edge-frfox#tweaks).

You can also check out [Stylus](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) themes (e.g. [StackOverflow](https://draculatheme.com/stackoverflow) or [GitHub](https://draculatheme.com/github)).
