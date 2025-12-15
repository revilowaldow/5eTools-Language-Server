# 5eTools Language Server

Available for:
- [VSCode](https://marketplace.visualstudio.com/items?itemName=revilowaldow.5etools-language-server)
- [VSCodium](https://open-vsx.org/extension/revilowaldow/5etools-language-server)

## Key Features

- Schema validation is completed for JSON files, giving:
  - Instantaneous error feedback
  - Automated completion of valid 5etools key names and values
- Syntax highlighting is provided:
  - For JSON
  - For 5etools tag syntax `{@item Bag of Holding|DMG}`
  - Including reserved source IDs and tag keywords
  - In non-json .5e files, nested-tag bracket-pair colours are supported
- JSON snippet templates are included:
  - For generic concepts like entries, images, lists and tables
  - For data structures like items, feats, races/species, classes, `_meta` and more
  - For basic and complex tags, including wrapping existing selected text with reference tags

## Demonstration

![Example video](https://raw.githubusercontent.com/revilowaldow/5eTools-Language-Server/main/images/Demo.webp)

## Credits

This extension is built with code (MIT licensed) taken from extensions previously written by [GoR](https://github.com/Git-GoR/5e-homebrew-snippets) & [Tree](https://github.com/Jklein64/5e-syntax). It supersedes those extensions.

Enhancements have been made:

- GoR
  - Provided fewer snippets, many are now incompatible with the site due to changes in data structures
- Tree
  - Provided syntax highlighting, but no longer covers all valid tag keywords and sources
  - A number of errors were present in escaping nested tag structures
- Both
  - Duplicated tags so would bloat snippet picker suggestions with copies
  - Do not provide suggestions, validation or error checking

Nonetheless their contribution is gratefully recognised.
