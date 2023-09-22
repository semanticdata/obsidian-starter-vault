
<p align="right">
	<img src="https://img.shields.io/github/languages/code-size/semanticdata/obsidian-test-vault" />
	<img src="https://img.shields.io/github/repo-size/semanticdata/obsidian-test-vault" />
	<img src="https://img.shields.io/github/commit-activity/t/semanticdata/obsidian-test-vault" />
	<img src="https://img.shields.io/github/last-commit/semanticdata/obsidian-test-vault" />
</p>

# Obsidian Starter Vault

An opinionated Obsidian starter.

## Getting Started

1. Clone or download this repo.
2. Open the repo in Obsidian.
3. Use it and customize it.
4. Have fun!

## Appearance

* [Obsidian Minimal](https://github.com/kepano/obsidian-minimal) Theme

### Snippets

* Typography Fixes - Normalizes styling and typography.
* Normalize Links - Removes decoration from external links.
* MySnippets Tweaks - Essential UI adjustment while using [MySnippets](https://github.com/chetachiezikeuzor/MySnippets-Plugin) Plugin.

## Extensions

* [Advance Tables](https://github.com/tgrosinger/advanced-tables-obsidian) - Improved navigation, formatting, and manipulation to markdown tables.
* [Calendar](https://github.com/liamcain/obsidian-calendar-plugin) - Integrates Daily Notes. Let's you visit any Daily Notes with ease.
* [Doubleshift](https://github.com/Qwyntex/doubleshift) - Press `shift` or `ctrl` twice and activate custom actions.
* [Editor Shortcuts](https://github.com/timhor/obsidian-editor-shortcuts) - Adds Hotkeys commonly found in other common code editors.
* [Home Tab](https://github.com/olrenso/obsidian-home-tab) - Integrates recent notes and Omnisearch.
* [Linter](https://github.com/platers/obsidian-linter) - Format and style notes. Akin to something like Prettier.
* [Minimal Settings](https://github.com/kepano/obsidian-minimal-settings) - Allows you to customize the minimal theme settings panel.
* [Mononote](https://github.com/czottmann/obsidian-mononote) - Ensures each note occupies only one tab.
* [MySnippets](https://github.com/chetachiezikeuzor/MySnippets-Plugin) - Adds a status bar menu allowing the user to quickly manage their snippets.
* [Natural Language Dates](https://github.com/argenos/nldates-obsidian) - Allows `@today` style shortcuts.
* [Omnisearch](https://github.com/scambier/obsidian-omnisearch) - Better search. Period.
* [Settings Search](https://github.com/javalent/settings-search) - Adds a search bar to Obsidian settings.
* [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) - Allows snippet, theme, and plugin CSS files define as a set of config options.
* [YAOS - Yet Another Obsidian Synchronizer](https://github.com/mahyarmirrashed/yaos) - Sync your vault to GitHub.

## File Structure

```
root
├── assets/
├── journals/
│   └── first-journal.md
├── templates
│   └── daily-journal.md
└── README.md
```

## Workflows

### Formatting Text

The _Markdown Linter_ plugin is configured to `lint on save` for a smoother typing experience.

### Hotkeys

#### Search

- You may open the _Command Palette_ by pressing `Ctrl` `Ctrl` in rapid succession.
- You may start _Omnisearch: Search Vault_ by pressing `Shift` `Shift` in rapid succession.
- Reassigned `Ctrl + F` to _Omnisearch: In File Search_.
- Reassigned `Ctrl + Shift + F` to _Omnisearch: Search Vault_.

#### Editor Shortcuts

| Action                   | Keybinding           |
| ------------------------ | -------------------- |
| Move line up             | `Alt + Up`           |
| Move line down           | `Alt + Down`         |
| Copy line above          | `Alt + Shift + Up`   |
| Copy line below          | `Alt + shift + Down` |
| Select word / selection  | `Ctrl + D`           |
| Select line (repeatable) | `Ctrl + L`           | 

### Natural Language Dates

Autocomplete and link natural language expressions to daily notes.

Examples:
- `@today`
- `@tomorrow`
- `@next week`

### Tables

Start a Markdown table by typing `|` followed by a `<space>` and `Tab`.

## License

Source code is available under [MIT](LICENSE).
