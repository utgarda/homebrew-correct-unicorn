# Homebrew Tap for correct-unicorn

Homebrew formulae for [correct-unicorn](https://github.com/utgarda/correct-unicorn) - a passphrase generator inspired by xkcd 936.

## Installation

```bash
brew tap utgarda/correct-unicorn
brew install correct-unicorn
```

## Usage

Generate a 4-word passphrase:
```bash
correct-unicorn
```

With custom options:
```bash
correct-unicorn -w 5 --capitalize -s "-"
```

## Documentation

See the [main repository](https://github.com/utgarda/correct-unicorn) for:
- Full documentation
- Configuration options
- Building from source

## Available Flags

- `-w, --words COUNT` - Number of words (default: 4)
- `-s, --separator SEP` - Word separator (default: space)
- `-c, --chars COUNT` - Minimum character count
- `--capitalize` - Capitalize first letter of each word
- `-p, --no-color` - Disable ANSI colors
- `--dict PATH` - Custom dictionary path

## Requirements

- macOS with Homebrew
- Built-in dictionary at `/usr/share/dict/words`

## License

MIT - See [LICENSE](https://github.com/utgarda/correct-unicorn/blob/master/LICENSE) in main repository
