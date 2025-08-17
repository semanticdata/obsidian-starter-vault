# 🔮 Obsidian Starter Vault

![code size](https://img.shields.io/github/languages/code-size/semanticdata/obsidian-test-vault) ![repo size](https://img.shields.io/github/repo-size/semanticdata/obsidian-test-vault) ![commit activity](https://img.shields.io/github/commit-activity/t/semanticdata/obsidian-test-vault) ![last commit](https://img.shields.io/github/last-commit/semanticdata/obsidian-test-vault)

An opinionated [Obsidian](https://obsidian.md/) starter vault. It holds a compilation of extensions and settings to help you learn and start exploring Obsidian.

## 🌟 Getting Started

1. Clone this repo or download the [latest release](https://github.com/semanticdata/obsidian-starter-vault/releases/latest).
2. Open the repo/folder in Obsidian.
3. Use it, customize it, and have fun!

## 🦋 Appearance

The starter uses the [Minimal Theme](https://github.com/kepano/obsidian-minimal) including extra configurations and settings via the [Minimal Theme Settings](https://github.com/kepano/obsidian-minimal) plugin.

### 👨🏼‍💻 CSS Snippets

You will find a small subset of useful CSS snippets included with the starter. Here's a quick breakdown of what each one does:

- Compact Tab Header - Arranges items in Tab header into groups.
- Default Style Settings - Adds the option to customize Obsidian further.
- Frontmatter Tweaks - Improves the legibility of Frontmatter elements.
- MySnippets Tweaks - Essential UI setting while using [MySnippets](https://github.com/chetachiezikeuzor/MySnippets-Plugin) Plugin.
- Normalize Links - Removes decoration from external links.
- Status bar Tweaks - Improves legibility of the Status bar.
- Table Tweaks - Improves legibility of Tables.
- Typography Fixes - Normalizes styling and typography.

## 🤝🏼 Community Plugins

This starter vault uses the following [community plugins](https://obsidian.md/plugins):

- [Advance Tables](https://github.com/tgrosinger/advanced-tables-obsidian) - Improved navigation, formatting, and manipulation to markdown tables.
- [Calendar](https://github.com/liamcain/obsidian-calendar-plugin) - Integrates Daily Notes. Let's you visit any Daily Notes with ease.
- [Doubleshift](https://github.com/Qwyntex/doubleshift) - Press <kbd>shift</kbd> or <kbd>ctrl</kbd> twice and activate custom actions.
- [Editor Shortcuts](https://github.com/timhor/obsidian-editor-shortcuts) - Adds Hotkeys commonly found in other common code editors.
- [Linter](https://github.com/platers/obsidian-linter) - Format and style notes. Akin to something like Prettier.
- [Minimal Settings](https://github.com/kepano/obsidian-minimal-settings) - Allows you to customize the minimal theme settings panel.
- [Mononote](https://github.com/czottmann/obsidian-mononote) - Ensures each note occupies only one tab.
- [MySnippets](https://github.com/chetachiezikeuzor/MySnippets-Plugin) - Adds a status bar menu allowing the user to quickly manage their snippets.
- [Natural Language Dates](https://github.com/argenos/nldates-obsidian) - Allows `@today` style shortcuts.
- [Omnisearch](https://github.com/scambier/obsidian-omnisearch) - Better search. Period.
- [Settings Search](https://github.com/javalent/settings-search) - Adds a search bar to Obsidian settings.
- [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) - Allows snippet, theme, and plugin CSS files define as a set of config options.

## 📂 File Structure

```plaintext
obsidian-starter-vault/
├── assets/
├── journals/
│   └── example-journal.md
├── templates
│   └── daily-journal.md
├── Welcome.md
├── Markdown Demo.md
├── CHANGELOG.md
└── README.md
```

## 🔁 Workflows

### Formatting Text

The _Markdown Linter_ plugin is configured to <ins>lint on save</ins> for a smoother typing experience. This means every time you press <kbd>Ctrl</kbd> + <kbd>S</kbd>, it will **format the note** as well as save it.

### Search

- You may open the _Command Palette_ by pressing `Ctrl` `Ctrl` in rapid succession.
- You may start _Omnisearch: Search Vault_ by pressing `Shift` `Shift` in rapid succession.
- Reassigned <kbd>Ctrl</kbd> + <kbd>F</kbd> to _Omnisearch: In File Search_.
- Reassigned <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>F</kbd> to _Omnisearch: Search Vault_.

### Keyboard Shortcuts

| Action                   | Keybinding                               |
| ------------------------ | ---------------------------------------- |
| Move line up             | <kbd>Alt</kbd> + <kbd>Up</kbd>           |
| Move line down           | <kbd>Alt</kbd> + <kbd>Down</kbd>         |
| Copy line above          | <kbd>Alt</kbd> + <kbd>Shift + Up</kbd>   |
| Copy line below          | <kbd>Alt</kbd> + <kbd>shift + Down</kbd> |
| Select word / selection  | <kbd>Ctrl</kbd> + <kbd>D</kbd>           |
| Select line (repeatable) | <kbd>Ctrl</kbd> + <kbd>L</kbd>           |
| Enter Current time       | <bbd>Alt</kbd> + <kbd>T</kbd>            |

### 🌄 Natural Language Dates

Autocomplete and link natural language expressions to daily notes.

Examples:

- `@today`
- `@tomorrow`
- `@next week`

## © License

Source code in this repository is available under the [MIT License](LICENSE).
