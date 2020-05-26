# Mowgli Theme for VSCode

[![Package version](https://vsmarketplacebadge.apphb.com/version/wapenshaw.mowgli.svg?style=for-the-badge&colorA=3e4246&colorB=47658e&label=VERSION)](https://marketplace.visualstudio.com/items?itemName=wapenshaw.mowgli) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/wapenshaw.mowgli.svg?style=for-the-badge&colorA=3e4246&colorB=47658e&label=INSTALLS)](https://marketplace.visualstudio.com/items?itemName=wapenshaw.mowgli) [![Downloads](https://vsmarketplacebadge.apphb.com/downloads-short/wapenshaw.mowgli.svg?style=for-the-badge&colorA=3e4246&colorB=47658e&label=DOWNLOADS)](https://marketplace.visualstudio.com/items?itemName=wapenshaw.mowgli) [![Rate!](https://vsmarketplacebadge.apphb.com/rating-star/wapenshaw.mowgli.svg?style=for-the-badge&colorA=3e4246&colorB=47658e&label=RATING)](https://marketplace.visualstudio.com/items?itemName=wapenshaw.mowgli&ssr=false#review-details)

### Install @ [VisualStudio Marketplace](https://marketplace.visualstudio.com/items?itemName=wapenshaw.mowgli)

ATTENTION! : Make sure you disable semantic highlighting in VSCode versions above 1.4.3. Add this to your settings.json file.

```javascript
"editor.semanticHighlighting.enabled": false,
```

### Javascript

![Javascript](./images/display/javascript.png 'Sample in JS')

### CSS

![CSS](./images/display/css.png 'CSS Sample')

### HTML

![HTML](./images/display/html.png 'HTML Sample')

### Terminal

![Terminal](./images/display/terminal.png 'Terminal Colors')

### Symbols

![Symbols](./images/display/symbols.png 'Symbols in Outline')

### Everything else

![Complete Viewport](./images/display/complete.png 'Complete Viewport')

Recommended Editor Settings :

```javascript
	// Workbench Settings
	"workbench.sideBar.location": "right",
	"workbench.editor.highlightModifiedTabs": true,
	//Editor -- Download link for the Ligalex Font below
	"editor.fontFamily": "Ligalex Mono",
	"editor.fontLigatures": true,
	"editor.fontSize": 16,
	"editor.fontWeight": 300,
	// Minimap
	"editor.minimap.enabled": true,
	"editor.minimap.renderCharacters": false,
	"editor.minimap.maxColumn": 100,
	"editor.renderWhitespace": "selection",
	"editor.minimap.showSlider": "always",
	"editor.minimap.size": "fit",
```

If you prefer italics for strings and keywords, add this to your settings.json

```json
"editor.tokenColorCustomizations": {
	"[Mowgli]": {
		"textMateRules": [
			{
				"name": "Keywords",
				"scope": "storage.type",
				"settings": {
					"fontStyle": "italic"
				}
			},
			{
				"name": "Parameters",
				"scope": "variable.parameter",
				"settings": {
					"fontStyle": "italic"
				}
			},
			{
				"name": "Strings",
				"scope": "string.template, string.quoted.single",
				"settings": {
					"fontStyle": "italic"
				}
			}
		]
	}
	},
```

Its based of of my Favourite VSCode theme [Jungle Night](https://github.com/tweakimp/jungle-night), I added custom coloring to the Syntax.

Languages supported :

1. Javascript, JSX, TypeScript
2. CSS/SCSS
3. HTML
4. Python
5. PHP
6. Markdown
7. Others are supported but require some further tweaks, coming soon™

I'd also recommend the following extenions which make the experience better.

1. [Bracket Pair Colorizer 2](https://github.com/CoenraadS/Bracket-Pair-Colorizer-2)
2. [Ligalex Mono aka IBM Plex Mono with Ligatures](https://github.com/ToxicFrog/Ligaturizer/releases)
3. Other recommended Fonts : [Cascadia Code Font](https://github.com/microsoft/cascadia-code) || [Fira Code Font](https://github.com/tonsky/FiraCode)
4. Icons in the screenshot are from the Monokai Pro icon set.
