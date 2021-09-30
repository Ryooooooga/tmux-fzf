# tmux-fzf

Simple tmux session manager

## Usage

```sh
tmux-fzf [cmd] ...

commands:
    switch  sw                  switch sessions (default)
    kill  k                     kill sessions
    help  h  --help  -h         display help message
    version  --version  -v  -V  display tmux version
```

## Requirements

- [tmux](https://github.com/tmux/tmux)
- [fzf](https://github.com/junegunn/fzf)

## Installation

### Zinit

```zsh
# .zshrc
zinit wait lucid light-mode for 'Ryooooooga/tmux-fzf'
```
