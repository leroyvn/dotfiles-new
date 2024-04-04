# Dotfiles

New dotfiles, powered by chezmoi.

## Requirements

Framework requirements (the basic engine powering this system)

- zsh
- [prezto](https://github.com/sorin-ionescu/prezto)
- [chezmoi](https://github.com/twpayne/chezmoi/)

Workflow requirements (tools I depend on for my usual workflow)

- [pipx](https://github.com/pypa/pipx/)
- Conda, usually through [miniforge](https://github.com/conda-forge/miniforge)

New machine setup instructions

- Refer to [chezmoi docs](https://www.chezmoi.io/quick-start/#set-up-a-new-machine-with-a-single-command)

## Extra setup instructions

- Install one of the powerlevel10k recommended fonts (my favourite is Hack [Nerd Font](https://www.nerdfonts.com/font-downloads))
- Upon checkout, if not already using it, the [powerlevel10k](https://github.com/romkatv/powerlevel10k) theme wizard should pop up.
- Install [Rye](https://rye-up.com/).
- Prevent Conda from activating the `base` environment automatically:

  ```bash
  conda config --set auto_activate_base false
  ```

- Setting your own `resolv.conf` in WSL 2: https://github.com/microsoft/WSL/issues/5420
- When using WSL, [SidebarDiagnostics](https://github.com/ArcadeRenegade/SidebarDiagnostics) can be useful to monitor real resource usage
