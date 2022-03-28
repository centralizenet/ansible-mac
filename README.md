<img src="https://raw.githubusercontent.com/geerlingguy/mac-dev-playbook/master/files/Mac-Dev-Playbook-Logo.png" width="250" height="156" alt="Mac Dev Playbook Logo" />

# Centralize Mac Ansible Playbook

## Fork this!
Fork this repo to your personal user and keep it for setting up all your Macs in the future. There's lots to customize!

## Install Instructions
* Run the bootstrap script to install xcode tools and ansible
  `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/centralizenet/ansible-mac/main/bootstrap.sh)"`
* Download the repo
* Change the config to your needs (particularly adjusting the dotfiles link)
* Install ansible requirements `ansible-galaxy install -r requirements.yml`

## Run Ansible
`ansible-playbook main.yml --ask-become-pass`
