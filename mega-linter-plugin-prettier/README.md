# [Prettier](https://prettier.io) Markdown Plugin for [MegaLinter](https://megalinter.io)

This plugin automatically formats Markdown files (`*.md`, `*.mdx`) with [Prettier](https://prettier.io).

## Example Usaage

```yaml
# file: .mega-linter.yml
ENABLE_LINTERS:
  - MARKDOWN_PRETTIER
PLUGINS:
  - https://raw.githubusercontent.com/liblaf/megalinter-plugins/refs/heads/main/mega-linter-plugin-prettier/markdown.megalinter-descriptor.yml
```
