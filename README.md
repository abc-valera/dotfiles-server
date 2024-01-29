# dotfiles-server

For more info info about dotfiles check this: https://www.atlassian.com/git/tutorials/dotfiles

## Initial setup

1. Update the server `sudo dnf update`
2. Install git `sudo dnf install git`
3. Clone the bare repo: `git clone --bare git@github.com:abc-valera/dotfiles-server.git $HOME/.dotfiles`
4. Remove bash config `rm .bashrc`
5. Checkout the repo: `/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME checkout`
6. Install Fish shell `sudo dnf install fish`
7. Install Starship prompt `curl -sS https://starship.rs/install.sh | sh -s -- -f`

## Software

1. Docker https://developer.fedoraproject.org/tools/docker/docker-installation.html
2. Caddy `sudo dnf install caddy`
3. Listmonk email server https://listmonk.app/
