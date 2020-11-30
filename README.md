# @atom-ide-community/semantic-release-npm-config

## Plugins

This shareable configuration use the following plugins:
- [`@semantic-release/commit-analyzer`](https://github.com/semantic-release/commit-analyzer)
- [`@semantic-release/release-notes-generator`](https://github.com/semantic-release/release-notes-generator)
- [`@semantic-release/changelog`](https://github.com/semantic-release/changelog)
- [`@semantic-release/npm`](https://github.com/semantic-release/npm)
- [`@semantic-release/github`](https://github.com/semantic-release/github)
- [`@semantic-release/git`](https://github.com/semantic-release/git)

## Install

```bash
$ npm install --save-dev semantic-release @atom-ide-community/semantic-release-npm-config
```

## Usage

The shareable config can be configured in the [**semantic-release** configuration file](https://github.com/semantic-release/semantic-release/blob/master/docs/usage/configuration.md#configuration):

```json
{
  "extends": "@atom-ide-community/semantic-release-npm-config"
}
```

## Configuration

See each [plugin](#plugins) documentation for required installation and configuration steps.

### Overwritten options

This following options are set by this shareable config:

| Option                                                       | Value                                             |
|--------------------------------------------------------------|---------------------------------------------------|
| [`message`](https://github.com/semantic-release/git#message) | chore(release): \${nextRelease.version} [skip ci] |

Other options use their default values. See each [plugin](#plugins) documentation for available options.
