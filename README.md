# dotfiles

<!-- markdownlint-disable MD034 -->

My dotfiles. [Thanks to holman for inspiration.](https://github.com/holman/dotfiles)

## Brewfile

Install Homebrew by following the instructions at https://brew.sh.

Create a Brewfile in your current directory with a list of your installed Homebrew packages with:

```shell
brew bundle dump
```

Install the packages listed in the Brewfile by running the following command in the directory containing the `Brewfile`:

```shell
brew bundle
```

## nono

Use `.nanorc` in your home directory for syntax highlighting in Nano. Copy the files in `/usr/local/share/nano` to the same location on your machine for specific syntax highlighting.
