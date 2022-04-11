# UpClean

An update and cleanup script for macOS.

- [Usage](#usage)
- [Configuration](#configuration)

![Screenshot](./screenshot.png)

## Usage

```
$ upclean --help

UpClean 2.0 🧼 upclean.app

An update and cleanup script for macOS.

Usage:
  upclean [options]

Options:
      --skip-clean               Skip cleaning
      --skip-composer            Skip updating Composer
      --skip-composer-packages   Skip updating Composer packages
      --skip-dns                 Skip flushing DNS cache
      --skip-docker              Skip cleaning Docker
      --skip-homebrew            Skip updating Homebrew
      --skip-mas                 Skip updating Mac App Store applications
      --skip-memory              Skip clearing inactive memory
      --skip-update              Skip updating
  -h, --help                     Display this help message
```

## Configuration

You can configure the [runtime options](#usage) by adding them to the `.upcleanrc` file in your home directory:

```bash
# File: ~/.upcleanrc
--skip-dns
--skip-memory
```

Passing options directly will override any configuration options that you may have set.