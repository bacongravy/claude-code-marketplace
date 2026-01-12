# Claude Code Marketplace

A Claude Code plugin marketplace that indexes plugins from external repositories.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [iterm](https://github.com/bacongravy/claude-code-iterm) | iTerm2 terminal automation - manage panes, tabs, windows, profiles, and layouts |

## Installation

### Add the Marketplace

```
/plugin marketplace add https://github.com/bacongravy/claude-code-marketplace
```

### Install a Plugin

```
/plugin install <plugin-name>@bacongravy
```

## Contributing

To add a plugin to this marketplace:

1. Host your plugin in its own repository
2. Add an entry to `marketplace.json` referencing your repository
3. Submit a pull request

## License

MIT
