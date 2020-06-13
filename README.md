# macOS Development Ansible Playbook

[![Build Status](https://travis-ci.com/davideimola/mac-dev-setup.svg?branch=master)](https://travis-ci.com/davideimola/mac-dev-setup)

This playbook installs and configures most of the software I use on my Mac for development. I still have some manual installation apps, but at least something is automated.

This is a work in progress, because I'll be evolving this set of playbooks over time in order to document my current Mac's setup.

## Installation

1. Ensure Apple's command line tools are installed.
2. Install Ansible.
3. Clone this repository.
4. Run `$ ansible-galaxy install -r requirements.yml` inside the project directory to install required Ansible roles.
5. Run `$ ansible-playbook main.yml -i inventory -K` inside the project directory. Enter your account password when prompted.

## Included Applications/Configuration (Default)

Applications (installed with Homebrew Cask)

   - [Alfred](https://www.alfredapp.com/)
   - [Commander One](https://mac.eltima.com/file-manager.html)
   - [Dash](https://kapeli.com/dash)
   - [Docker](https://www.docker.com/)
   - [Firefox Developer Edition](https://www.mozilla.org/it/firefox/developer/)
   - [iTerm](https://iterm2.com/)
   - [PyCharm](https://www.jetbrains.com/pycharm/)
   - [SmartGit](https://www.syntevo.com/smartgit/)
   - [Spotify](https://www.spotify.com/it/)
   - [Vagrant](https://www.vagrantup.com/)
   - [VirtualBox](https://www.virtualbox.org/)
   - [Visual Studio Code](https://code.visualstudio.com/)

Homebrew packages

   - fzf
   - git
   - kubectx
   - minikube
   - node
   - nvm
   - openssl
   - wget