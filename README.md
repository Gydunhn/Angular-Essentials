# Angular Essentials - Extension Pack for Visual Studio Code

This extension pack for Visual Studio Code adds extensions that are convenient and useful for any development (regardless of language). I reserve the right to update the content of the extension pack at my own discretion.

This **CORE** version of the extension pack is for a series of very specific projects in which I am currently involved; projects with multiple repositories that share the same stack of technologies transversally on PLV.

## Reasons

The AFP PlanVital core Extensions was made to automate and standardize the setup phase of the development environment for Visual Studio Code, to have the same set of extensions, use the same id settings and file format everyone works on together.

See the [CHANGELOG](CHANGELOG.md) for the latest changes

## **settings.json**

It is imperative that the settings be added to settings.json, inside the ".vscode" folder, and that this file be inside Git version control for this extension pack to work correctly.

``` json
{
	/**
     * PlanVital's Essential Angular Settings
     */
	"extensions.ignoreRecommendations": true,
	"editor.tabCompletion": "on",
	"editor.showDeprecated": true,
	"editor.rulers": [
		80
	],
	"editor.guides.bracketPairs": "active",
	"editor.bracketPairColorization.independentColorPoolPerBracketType": true,
	"editor.formatOnSave": true,
	"[markdown]": {
		"editor.defaultFormatter": "yzhang.markdown-all-in-one"
	},
	"[json]": {
		"editor.defaultFormatter": "vscode.json-language-features"
	},
	"[jsonc]": {
		"editor.defaultFormatter": "vscode.json-language-features"
	},
	"[xml]": {
		"editor.defaultFormatter": "DotJoshJohnson.xml"
	},
	"[javascript]": {
		"editor.defaultFormatter": "vscode.typescript-language-features"
	},
	"[javascriptreact]": {
		"editor.defaultFormatter": "vscode.typescript-language-features"
	},
	"[typescript]": {
		"editor.defaultFormatter": "vscode.typescript-language-features"
	},
	"[typescriptreact]": {
		"editor.defaultFormatter": "vscode.typescript-language-features"
	},
	"[css]": {
		"editor.defaultFormatter": "vscode.css-language-features"
	},
	"[less]": {
		"editor.defaultFormatter": "vscode.css-language-features"
	},
	"[scss]": {
		"editor.defaultFormatter": "vscode.css-language-features"
	},
	"[html]": {
		"editor.defaultFormatter": "vscode.html-language-features"
	},
	"javascript.format.enable": true,
	"javascript.format.semicolons": "insert",
	"javascript.preferences.quoteStyle": "single",
	"typescript.format.enable": true,
	"typescript.format.semicolons": "insert",
	"typescript.preferences.quoteStyle": "single",
	"css.hover.documentation": true,
	"css.lint.important": "warning",
	"css.lint.importStatement": "warning",
	"less.hover.documentation": true,
	"less.lint.important": "warning",
	"less.lint.importStatement": "warning",
	"scss.hover.documentation": true,
	"scss.lint.important": "warning",
	"scss.lint.importStatement": "warning",
	"html.hover.documentation": true,
	"markdownlint.config": {
		"default": true,
		"MD001": false,
		"MD010": false,
		"MD024": false,
		"MD025": false
	},
	"todo-tree.tree.showCountsInTree": true,
	"todo-tree.general.statusBar": "top three",
	"todo-tree.general.showIconsInsteadOfTagsInStatusBar": true,
	"todo-tree.general.tags": [
		"TODO",
		"FIXME",
		"FIXIT",
		"FIX",
		"BUG",
		"HACK",
		"UNDONE",
	],
	"todo-tree.general.tagGroups": {
		"FIXME": [
			"FIXME",
			"FIXIT",
			"FIX",
			"BUG",
		]
	},
	"todo-tree.highlights.customHighlight": {
		"TODO": {
			"gutterIcon": true,
			"icon": "tasklist",
			"iconColour": "#FF9E29",
			"type": "tag",
			"background": "#CF7200",
			"foreground": "#FFFFFF",
			"fontWeight": "bold"
		},
		"FIXME": {
			"gutterIcon": true,
			"icon": "tools",
			"iconColour": "#00BD00",
			"type": "tag",
			"background": "#008000",
			"foreground": "#ffffff",
			"fontWeight": "bold"
		},
		"UNDONE": {
			"gutterIcon": true,
			"icon": "history",
			"iconColour": "#FFFF00",
			"type": "tag",
			"background": "#FFFF00",
			"foreground": "#141D1E",
			"fontWeight": "bold"
		},
		"HACK": {
			"gutterIcon": true,
			"icon": "code",
			"iconColour": "#FF30C8",
			"type": "tag",
			"background": "#141D1E",
			"foreground": "#fa64d2",
			"fontWeight": "bold"
		}
	},
	"better-comments.multilineComments": true,
	"better-comments.tags": [
		{
			"tag": "!",
			"color": "#FF2D00",
			"strikethrough": false,
			"underline": false,
			"backgroundColor": "transparent",
			"bold": true,
			"italic": false
		},
		{
			"tag": "?",
			"color": "#3498DB",
			"strikethrough": false,
			"underline": false,
			"backgroundColor": "transparent",
			"bold": false,
			"italic": false
		},
		{
			"tag": "//",
			"color": "#474747",
			"strikethrough": true,
			"underline": false,
			"backgroundColor": "transparent",
			"bold": false,
			"italic": false
		},
		{
			"tag": "todo",
			"color": "#FF8C00",
			"strikethrough": false,
			"underline": false,
			"backgroundColor": "transparent",
			"bold": false,
			"italic": false
		},
		{
			"tag": "fixme",
			"color": "#008000",
			"strikethrough": false,
			"underline": false,
			"backgroundColor": "transparent",
			"bold": false,
			"italic": false
		},
		{
			"tag": "fixit",
			"color": "#008000",
			"strikethrough": false,
			"underline": false,
			"backgroundColor": "transparent",
			"bold": false,
			"italic": false
		},
		{
			"tag": "fix",
			"color": "#008000",
			"strikethrough": false,
			"underline": false,
			"backgroundColor": "transparent",
			"bold": false,
			"italic": false
		},
		{
			"tag": "bug",
			"color": "#008000",
			"strikethrough": false,
			"underline": false,
			"backgroundColor": "transparent",
			"bold": false,
			"italic": false
		},
		{
			"tag": "*",
			"color": "#98C379",
			"strikethrough": false,
			"underline": false,
			"backgroundColor": "transparent",
			"bold": true,
			"italic": false
		}
	],
	"gitlens.statusBar.enabled": true,
	"gitlens.statusBar.command": "gitlens.openCommitOnRemote",
	"gitlens.blame.avatars": true,
	"gitlens.hovers.avatars": true,
	"gitlens.hovers.avatarSize": 64,
	"gitlens.hovers.changesDiff": "hunk"
	/**
     * PlanVital's Essential Angular Settings
     */
}
```

## Included

This extension pack includes the following extensions:

* the following extensions are included in this package:
  * Markdown All in One
  * markdownlint
  * Markdown Emoji
  * XML Tools
  * Format in context menus
  * Todo Tree
  * Better Comments
  * ESLint
  * Angular Language Service
  * Debugger for Firefox
  * GitLens — Git supercharged
