# dotfiles-server

For more info info about dotfiles check this: https://www.atlassian.com/git/tutorials/dotfiles

## Initial setup

1. Install git `sudo dnf install git`
2. Generate ssh key `ssh-keygen -t ed25519 -C "zoocity14@gmail.com"` and add public key to github
3. Clone the bare repo: `git clone --bare github.com/abc-valera/dotfiles $HOME/.dotfiles`
4. Remove bash config `rm .bashrc`
5. Checkout the repo: `/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME checkout`
6. Install Fish shell `sudo dnf install fish`
7. Install Starship prompt
8. Make fish the default shell `chsh -s /usr/bin/fish`

## Software

1. Podman `sudo dnf install podman`
