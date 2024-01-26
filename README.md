# dotfiles-server

For more info info about dotfiles check this: https://www.atlassian.com/git/tutorials/dotfiles

## Initial setup

1. Install git `sudo dnf install git`
2. Clone the bare repo: `git clone --bare git@github.com:abc-valera/dotfiles-server.git $HOME/.dotfiles`
3. Remove bash config `rm .bashrc`
4. Checkout the repo: `/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME checkout`
5. Install Fish shell `sudo dnf install fish`
6. Install Starship prompt `curl -sS https://starship.rs/install.sh | sh -s -- -f`

## Software

1. Podman `sudo dnf install podman`
2. Caddy `sudo dnf install caddy`
