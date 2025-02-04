# lumin/version-bumper

[![version](https://img.shields.io/github/v/release/lumin-org/version-bumper?style=plastic&logo=github&logoColor=FFFFFF&label=version)](https://github.com/lumin-org/version-bumper/releases/latest)
[![test](https://img.shields.io/github/actions/workflow/status/lumin-org/version-bumper/test.yml?style=plastic&logo=github&logoColor=FFFFFF&label=test)](https://github.com/lumin-org/version-bumper/blob/main/.github/workflows/test.yml)
[![discord](https://img.shields.io/discord/1105688855375511642?logo=discord&logoColor=white&label=chat&color=4d3dff&style=plastic)](https://lumin-org.github.io/to/discord)

A github action that bumps the version of TOML or JSON files

## Prerequisites

In order to use **lumin/version-bumper** you must be using one of the following server types:

* [`macOS`](https://en.wikipedia.org/wiki/macOS)
* [`Linux`](https://en.wikipedia.org/wiki/Linux)
* [`Windows`](https://en.wikipedia.org/wiki/Windows)

## Usage

Use the latest version, with the latest git tag and some TOML + JSON files

```yaml
steps:
- uses: lumin-org/version-bumper@v0.1.0
  with:
    file-paths: |
      pesde.toml
      wally.toml
      package.json
```

## License

This project is licensed under the [MIT](https://github.com/lumin-org/version-bumper/blob/main/LICENSE) license
