# Dotfiles Direct

This repository containes dotfiles to be managed directly in the `$HOME` directory. This
method avoids the use of a tool like stow, as described in this [blog post](https://drewdevault.com/2019/12/30/dotfiles.html) by Drew Devault.

## Cloning

- Clone repo to a subdirectory of the home directory, such as `~/dotfiles-direct`
- Copy the `.git/` directory from the repo to the home directory
- `git status` will show the missing files
- `git reset --hard` will add the missing files to the home directory
- `rm ~/<dotfiles directory>`
