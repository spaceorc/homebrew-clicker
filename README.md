# Homebrew Clicker

Homebrew tap for [clicker](https://github.com/spaceorc/clicker) - LLM-powered browser automation agent.

## Installation

```bash
brew tap spaceorc/clicker
brew install --HEAD clicker
```

## Usage

After installation, the `clicker` command will be available:

```bash
# Show help
clicker --help

# Run browser automation
clicker "https://example.com" "Click the 'More information' link"

# Run with visible browser
clicker "https://example.com" "Fill the form" --no-headless

# Resume last session
clicker --last-session
```

## Requirements

- Python 3.13+
- macOS (Homebrew)

## Updating

```bash
brew update
brew upgrade --fetch-HEAD clicker
```

## Uninstall

```bash
brew uninstall clicker
brew untap spaceorc/clicker
```

## Documentation

See [clicker documentation](https://github.com/spaceorc/clicker) for detailed usage instructions.
