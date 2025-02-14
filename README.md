# lumin/key-editor

[![version](https://img.shields.io/github/v/release/lumin-org/key-editor?style=plastic&logo=github&logoColor=FFFFFF&label=version)](https://github.com/lumin-org/key-editor/releases/latest)
[![test](https://img.shields.io/github/actions/workflow/status/lumin-org/key-editor/test.yml?style=plastic&logo=github&logoColor=FFFFFF&label=test)](https://github.com/lumin-org/key-editor/blob/main/.github/workflows/test.yml)
[![discord](https://img.shields.io/discord/1105688855375511642?logo=discord&logoColor=white&label=chat&color=4d3dff&style=plastic)](https://lumin-org.github.io/to/discord)

A github action that edits the specified key of TOML or JSON files

## Prerequisites

In order to use **lumin/key-editor** you must be using one of the following server types:

* [`macOS`](https://en.wikipedia.org/wiki/macOS)
* [`Linux`](https://en.wikipedia.org/wiki/Linux)
* [`Windows`](https://en.wikipedia.org/wiki/Windows)

## Usage

Use the latest version, and bump a version key on config files

```yaml
steps:
- uses: lumin-org/key-editor@v0.2.1
  with:
    content: 'v1.0.0'
    key: version
    paths: |
      pesde.toml
      wally.toml
      package.json
```

## License

This project is licensed under the [MIT](https://github.com/lumin-org/key-editor/blob/main/LICENSE) license
