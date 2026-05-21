# TYPO3 FlexForm Snippets Extension

FlexForm Snippets for [TYPO3 FlexForms](https://docs.typo3.org/m/typo3/reference-tca/main/en-us/ColumnsConfig/Type/Flex/Index.html) in VSCode and VSCodium.<br>
If you want to contribute your own snippets, [create a Pull Request via GitHub](https://github.com/pagea-dev/typo3flexform-snippets/pulls)<br>
If you have problems or ideas, [open an Issue via GitHub](https://github.com/pagea-dev/typo3flexform-snippets/issues)<br>
You can find the source code on [GitHub](https://github.com/pagea-dev/typo3flexform-snippets)

Download for VSCode [from the Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=pagea-dev.typo3flexform-snippets)<br>
Download for VSCodium [from Open-VSX.org](https://open-vsx.org/extension/pagea-dev/typo3flexform-snippets)

## Features

All snippets use the modern TYPO3 13+ FlexForm syntax (without `TCEforms` wrapper).

| Prefix | Description |
|---|---|
| `flx` | FlexForm base structure (`<T3DataStructure>`) |
| `flxinput` | Text input field |
| `flxinputint` | Number input field |
| `flxtextarea` | Textarea field |
| `flxrte` | Rich Text Editor field |
| `flxcheckbox` | Checkbox field |
| `flxcolor` | Color picker field |
| `flxselectsingle` | Single select field (static items) |
| `flxselectmulti` | Multi-select side-by-side field (static items) |
| `flxselectside` | Multi-select side-by-side field (DB relation) |
| `flxfalimage` | FAL image field |
| `flxgroup` | Group field (DB relation) |
| `flxtypolink` | Link field |
| `flxsection` | Repeatable section container |
| `flxdisplaycond` | Display condition |

## Requirements

- TYPO3 13 or higher
- VSCode `^1.90.0` or VSCodium equivalent

## Installation

### Via Open VSX (VSCodium)

Search for `TYPO3 FlexForm Snippets` in the Extensions tab.

### Via Marketplace (VSCode)

Search for `TYPO3 FlexForm Snippets` in the Extensions tab or install via:

```
ext install pagea-dev.typo3flexform-snippets
```

### Manual (.vsix)

Download the latest `.vsix` from the [Releases](https://github.com/pagea-dev/typo3flexform-snippets/releases) page and install via:

```
Extensions → ··· → Install from VSIX...
```

## Contributing

Pull requests are welcome. For larger changes please open an issue first.

1. Fork the repository
2. Create your branch: `git checkout -b feat/my-snippet`
3. Commit your changes: `git commit -m 'feat: add flxinput snippet'`
4. Push and open a Pull Request

## License

[MIT](LICENSE)

## Acknowledgements

Inspired by the original (but outdated) [vscode-typo3-flx-snippets](https://github.com/bhavin-nitsan/vscode-typo3-flx-snippets/) extension by bhavin-nitsan