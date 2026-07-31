### Instructions to create this repo (for myself)

1. Add in .bashrc: `alias dotfiles='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'`
2. Initialize new folder: `git init --bare $HOME/.dotfiles`
3. Disable auto-adding new files: `dotfiles config --local status.showUntrackedFiles no`

Done!
Now, you can use standard git commands under the `dotfiles` alias: `add`, `commit`, `push`, etc.
