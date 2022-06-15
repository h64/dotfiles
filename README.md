## Introduction

This repository contains a collection of handy scripts for me to set up a macOS computer from scratch. 

Inspiration taken from [driesvints](https://github.com/driesvints/dotfiles).

## Instructions

1. Update macOS through system preferences

1. [Generate a new public and private SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) by running:
    ```
    curl https://raw.githubusercontent.com/h64/dotfiles/HEAD/ssh.sh | sh -s "1981460+h64@users.noreply.github.com"
    ```

    Or if repo is already cloned down, run locally:

    ```
    ~/.dotfiles/ssh.sh "1981460+h64@users.noreply.github.com"
    ```

1. Clone this repo to `~/.dotfiles` with:
    ```
    git clone git@github.com:h64/dotfiles.git ~/.dotfiles
    ```

1. Run the installation with:
    ```
    ~/.dotfiles/fresh.sh
    ```

