# :city_sunset: Duotone Theme v2 Official

[![Version](https://vsmarketplacebadge.apphb.com/version/husseinkizz.duotone.svg?style=for-the-badge&colorA=4B1E97&colorB=280E54)](https://marketplace.visualstudio.com/items?itemName=husseinkizz.duotone)
[![Rating](https://vsmarketplacebadge.apphb.com/rating-star/husseinkizz.duotone.svg?style=for-the-badge&colorA=FFC600&colorB=FF9D00)](https://marketplace.visualstudio.com/items?itemName=husseinkizz.duotone)
[![Downloads](https://vsmarketplacebadge.apphb.com/downloads-short/husseinkizz.duotone.svg?style=for-the-badge&colorA=88FF00&colorB=00FF00CC)](https://marketplace.visualstudio.com/items?itemName=husseinkizz.duotone)

![Preview](https://raw.githubusercontent.com/Hussseinkizz/duotone/main/images/react.png)

**👋 Hey there, stop your search for a hot new theme and install this one!**

This is one of the best themes every night owl needs, very modern, cool to eyes, and not boring. Made to make your Vscode fun again, thanks to all those who gave feedback, ratings and appreciation for the first version, here I give you another one with improvements from the first one, give it a try!

## Installation

1. Install [Visual Studio Code](https://code.visualstudio.com/)
2. Launch Visual Studio Code
3. Choose **Extensions** from menu
4. Search for `Duotone Theme v2 Official`
5. Click **Install** to install the extension
6. Click **Reload** to reload VS Code
7. Press **Ctrl + K + T** to show installed themes.
8. Use arrow down/up keys to scroll through and select **Duotone Theme v2 Official**
9. Hit enter and that's it!
10. 🌟🌟🌟🌟🌟 Rate five-stars, just saying... 😃

11. **Optional:** Use the recommended settings below for best experience and swag!

## Recommended Settings

```js
{
  "workbench.colorTheme": "Duotone Theme v2 Official",
  "editor.fontFamily": "Fira Code iScript",
  "editor.fontSize": 16,
  "editor.fontLigatures": true,
  "editor.fontWeight": "500",
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "prettier.singleQuote": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "workbench.colorCustomizations": {},
  "window.zoomLevel": 2,
    "editor.cursorSmoothCaretAnimation": true,
    "editor.tabSize": 2,
    "editor.wordWrap": "bounded",
    "editor.cursorBlinking": "smooth",
    "editor.cursorStyle": "line-thin",
    "editor.suggest.shareSuggestSelections": true,
    "editor.minimap.enabled": false,
    "workbench.startupEditor": "newUntitledFile",
    "editor.renderWhitespace": "none",
    "files.autoSave": "onFocusChange",
    "workbench.tree.indent": 4,
    "typescript.updateImportsOnFileMove.enabled": "always",
    "vsicons.dontShowNewVersionMessage": true,
    "terminal.integrated.rendererType": "dom",
    "editor.quickSuggestions.comments": true,
    "editor.suggestSelection": "first",
    "breadcrumbs.enabled": false,
    "window.menuBarVisibility": "compact",
    "workbench.view.alwaysShowHeaderActions": true,
    "editor.linkedEditing": true,
    "editor.bracketPairColorization.enabled": true,
    "workbench.productIconTheme": "fluent-icons",
    "workbench.iconTheme": "helium-icon-theme",
    "prettier.bracketSameLine": true,
    "workbench.list.smoothScrolling": true,
    "terminal.integrated.cursorBlinking": true,
    "editor.smoothScrolling": true,
"editor.tokenColorCustomizations": {
    "textMateRules": [
        {
            "scope": [
                // the following elements will be in italic
                //   (=Fira Code iScript)
                "comment",
                "keyword.control.import.js", // import
                "keyword.control.export.js", // export
                "keyword.control.from.js", // from
                // "constant", // String, Number, Boolean…, this, super
                "storage.modifier", // static keyword
                "storage.type.class", // class keyword
                "storage.type.php", // typehints in methods keyword
                "keyword.other.new.php", // new
                "entity.other.attribute-name", // html attributes
                "fenced_code.block.language.markdown" // markdown language modifier
            ],
            "settings": {
                "fontStyle": "italic"
            }
        },
        {
            "scope": [
                // the following elements will be displayed in bold
                "entity.name.type.class" // class names
            ],
            "settings": {
                "fontStyle": "bold"
            }
        },
        {
            "scope": [
                // the following elements will be displayed in bold and italic
                "entity.name.section.markdown" // markdown headlines
            ],
            "settings": {
                "fontStyle": "italic bold"
            }
        },
        {
            "scope": [
                // the following elements will be excluded from italics
                //   (VSCode has some defaults for italics)
                "invalid",
                "keyword.operator",
                "constant.numeric.css",
                "keyword.other.unit.px.css",
                "constant.numeric.decimal.js",
                "constant.numeric.json",
                "comment.block",
                "entity.other.attribute-name.class.css"
            ],
            "settings": {
                "fontStyle": ""
            }
        }
    ]
}
}
```

## Bonus
- Am using a cool free and open source font called Fira Code iScript which comes with font ligatures and stylish itallics, and you can easily get it here [Fira Code iScript](https://github.com/Hussseinkizz/FiraCodeiScript)
- I also use other extensions to make my Vscode look more cool and more powerful, they include Hellium Icons, Fluent Icons and a lot more, find all my extensions list here [How I VSCode](https://howivscode.com/Hussseinkizz)
- I also chill to lofi beats when coding with this cool stream from [FreeCodeCamp Radio](https://coderadio.freecodecamp.org)

Feel Free To Connect With Me At Twitter:  [@HusseinKizz](https://twitter.com/HusseinKizz)


## Contributing

A little help won't hurt really, so feel free to give me a hand by doing the following:

1. Clone this repo and open in VS Code
2. Open run `View → Run`
3. Click `Launch Extension`. This will open up another VS Code Editor
4. Make changes to `duotone-theme-v2.json`. You will see changes reflected in the other editor that opened in step 3.
5. Then make a pull request and if you are making a pull request, please give me a screenshot of before/after!
6. That's it, and after successfully merging your changes to the main, you wil be credited on behalf of the community for making such a heartful contribution.


## Do you have any suggestions?

First, this theme is new so if something is off the grid, please open an issue. Because, there are many languages and parts of VS Code I don't know about, so let me know if anything goes wrong.

If you would like to change something personally, you can either open a PR and see if I'd like it added, or override the colours in your own settings.json file.

Start upon that here: https://code.visualstudio.com/docs/getstarted/theme-color-reference


Also file issues [here](https://github.com/Hussseinkizz/duotone/issues), or [submit PRs](https://github.com/Hussseinkizz/duotone/pulls) if you like.

## Credits
I really like thank all coders who installed, rated and recommended the previous version of Duotone Theme to their freinds and co-workers, those keep me pushing on to do this, else making a nice looking Vscode theme isn't easy!

Regards, [Hussein Kizz](https://mailto:hssnkizz@gmail.com)
