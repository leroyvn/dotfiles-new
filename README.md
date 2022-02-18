# Dotfiles

New dotfiles, powered by chezmoi and Oy My Posh.

## Requirements

Framework requirements (the basic engine powering this system)

- zsh
- [prezto](https://github.com/sorin-ionescu/prezto)
- [chezmoi](https://github.com/twpayne/chezmoi/)
- [oh-my-posh](https://github.com/jandedobbeleer/oh-my-posh)

Workflow requirements (tools I depend on for my usual workflow)

- [pipx](https://github.com/pypa/pipx/)
- [pyenv](https://github.com/pyenv/pyenv)
- Conda, usually through [miniforge](https://github.com/conda-forge/miniforge) (installing [mamba](https://github.com/mamba-org/mamba) is highly recommended)
- [PDM](https://github.com/pdm-project/pdm/)

## Extra setup instructions

- Prevent Conda from activating the `base` environment automatically:
  ```
  conda config --set auto_activate_base false
  ```
- Setting your own `resolv.conf` in WSL 2: https://github.com/microsoft/WSL/issues/5420
