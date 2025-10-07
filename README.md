# macos-dev-playbook
Automated macOS development environment setup via Ansible

This playbook automates most of the steps to configure a new mac for development use.

# Installation

1. Install xcode command line tools  
`xcode-select --install`
2. Install Ansible  
 i. Run the following command to add Python 3 to your $PATH:  
 `export PATH="$HOME/Library/Python/3.9/bin:/opt/homebrew/bin:$PATH"`  
 ii. Upgrade Pip: `sudo pip3 install --upgrade pip`  
 iii. Install Ansible: `pip3 install ansible`
3. Clone this repository
`git clone`
4. Run `ansible-playbook main.yaml --ask-become-pass` inside the repository directory. Enter your macOS account password when propted for the 'BECOME' password.
