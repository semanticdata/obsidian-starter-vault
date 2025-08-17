# 🔮 Obsidian Starter Vault

![code size](https://img.shields.io/github/languages/code-size/semanticdata/obsidian-starter-vault) ![repo size](https://img.shields.io/github/repo-size/semanticdata/obsidian-starter-vault) ![commit activity](https://img.shields.io/github/commit-activity/t/semanticdata/obsidian-starter-vault) ![last commit](https://img.shields.io/github/last-commit/semanticdata/obsidian-starter-vault)

An opinionated [Obsidian](https://obsidian.md/) starter vault. It holds a compilation of extensions and settings to help you learn and start exploring Obsidian.

## 🌟 Getting Started

1. Clone this repo or download the [latest release](https://github.com/semanticdata/obsidian-starter-vault/releases/latest).
2. Open the repo/folder in Obsidian.
3. Use it, customize it, and have fun!

## 🦋 Appearance

The starter uses the [Minimal Theme](https://github.com/kepano/obsidian-minimal) including extra configurations and settings via the [Minimal Theme Settings](https://github.com/kepano/obsidian-minimal) plugin.

### 👨🏼‍💻 CSS Snippets

You will find a comprehensive collection of useful CSS snippets included with the starter. Here's a breakdown of what each one does:

#### Editor Snippets

- External Links - Removes decoration from external links for cleaner appearance.
- Frontmatter - Improves the legibility and styling of frontmatter elements.
- Internal Links - Enhances the appearance of internal note links.
- Tables - Improves legibility and formatting of markdown tables.

#### Plugin Snippets

- Calendar - Styling enhancements for the Calendar plugin interface.
- MySnippets - Essential UI settings while using the [MySnippets](https://github.com/chetachiezikeuzor/MySnippets-Plugin) plugin.
- Task Wrapper Tweaks - Improves task list formatting and appearance.

#### Print Snippets

- Dark PDF Export - Optimizes dark theme for PDF exports.

#### UI Snippets

- Compact Tab Header - Arranges items in tab header into organized groups.
- Default Style Settings - Adds options to customize Obsidian appearance further.
- Hover Preview Tweaks - Enhances the hover preview functionality.
- List Items (Compact) - Creates more compact list item spacing.
- New Empty Tab Tweaks - Improves the new tab experience.
- Statusbar Tweaks - Improves legibility and appearance of the status bar.

## 🤝🏼 Community Plugins

This starter vault uses the following [community plugins](https://obsidian.md/plugins):

- [Advanced Tables](https://github.com/tgrosinger/advanced-tables-obsidian) - Improved navigation, formatting, and manipulation to markdown tables.
- [Doubleshift](https://github.com/Qwyntex/doubleshift) - Press <kbd>shift</kbd> or <kbd>ctrl</kbd> twice and activate custom actions.
- [Editor Shortcuts](https://github.com/timhor/obsidian-editor-shortcuts) - Adds Hotkeys commonly found in other common code editors.
- [Homepage](https://github.com/mirnovov/obsidian-homepage) - Set any note, canvas, or workspace as your homepage.
- [Linter](https://github.com/platers/obsidian-linter) - Format and style notes. Akin to something like Prettier.
- [Minimal Settings](https://github.com/kepano/obsidian-minimal-settings) - Allows you to customize the minimal theme settings panel.
- [Mononote](https://github.com/czottmann/obsidian-mononote) - Ensures each note occupies only one tab.
- [MySnippets](https://github.com/chetachiezikeuzor/MySnippets-Plugin) - Adds a status bar menu allowing the user to quickly manage their snippets.
- [Natural Language Dates](https://github.com/argenos/nldates-obsidian) - Allows `@today` style shortcuts.
- [Omnisearch](https://github.com/scambier/obsidian-omnisearch) - Better search. Period.
- [Plugin Update Tracker](https://github.com/swar8080/obsidian-plugin-update-tracker) - Keep track of plugin updates and see what's new.
- [Settings Search](https://github.com/javalent/settings-search) - Adds a search bar to Obsidian settings.
- [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) - Allows snippet, theme, and plugin CSS files define as a set of config options.
- [Tag Wrangler](https://github.com/pjeby/tag-wrangler) - Rename, merge, toggle, and search tags from the tag pane.

## 📂 File Structure

```plaintext
obsidian-starter-vault/
├── .obsidian/                    # Obsidian configuration folder
│   ├── plugins/                  # Community plugins
│   ├── snippets/                 # CSS customizations
│   └── themes/                   # Minimal theme files
├── assets/                       # Images and media files
│   └── cookie-enjoyer.png
├── journals/                     # Example journal entries
│   └── example-journal.md
├── templates/                    # Note templates
│   └── daily-journal.md          # Daily note template
├── CHANGELOG.md                  # Version history and updates
├── Markdown Demo.md              # Markdown formatting examples
└── Welcome.md                    # Getting started guide
```

### Folder Purposes

- `.obsidian/`: Contains all Obsidian-specific configurations, plugins, and customizations
- `assets/`: Store images, attachments, and media files referenced in your notes
- `journals/`: Daily notes and journal entries (can be customized via templates)
- `templates/`: Reusable note templates for consistent formatting and structure

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
| Enter Current time       | <kbd>Alt</kbd> + <kbd>T</kbd>            |

### 🌄 Natural Language Dates

Autocomplete and link natural language expressions to daily notes.

Examples:

- `@today`
- `@tomorrow`
- `@next week`

## 🛠️ Troubleshooting

### Common Issues

**Plugins not loading properly:**

- Ensure you have opened the folder as a vault in Obsidian
- Go to Settings → Community plugins and enable them manually if needed
- Try restarting Obsidian

**Theme not appearing correctly:**

- Check that the Minimal theme is selected in Settings → Appearance → Themes
- Ensure the Minimal Theme Settings plugin is enabled
- Try toggling dark/light mode

**CSS snippets not working:**

- Verify snippets are enabled in Settings → Appearance → CSS snippets
- Check that snippet files are in the `.obsidian/snippets/` folder
- Restart Obsidian after adding new snippets

### Getting Help

If you encounter issues not covered here, please:

1. Check the [Obsidian documentation](https://help.obsidian.md/)
2. Visit the [Obsidian community forum](https://forum.obsidian.md/)
3. Create an issue in this repository's [Issues section](https://github.com/semanticdata/obsidian-starter-vault/issues)

## ❓ Frequently Asked Questions

### How do I customize the vault?

You can customize this vault by:

- Adding your own notes and organizing them as needed
- Installing additional community plugins from the Community Plugins tab
- Creating custom CSS snippets for further appearance tweaks
- Modifying the templates in the `templates/` folder
- Adjusting plugin settings to match your workflow

### Can I use this vault as a template for new vaults?

Yes! This vault is designed to be a starting point. You can:

- Clone or download this repository
- Remove the example content (journals, demo files)
- Add your own notes and structure
- Share your customized version with others

### How do I update the plugins?

With the Plugin Update Tracker installed, you'll see notifications when updates are available. You can also manually check for updates in Settings → Community plugins.

## © License

Source code in this repository is available under the [MIT License](LICENSE).
