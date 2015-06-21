# OSX Provisioning

Shell scripts and Ansible playbooks for provisioning an OSX machine for PHP development.

## Requirements

* Ansible 1.7+

## Usage

``` bash
ansible-playbook -i hosts -l localhost
```
## Roles

### Homebrew

* Installs Homebrew
* Installs Hombrew Cask
* Taps the Homebrew services manager

### PHP

* Installs PHP
* Configures PHP
* Installs useful PHP modules
* Configures certain PHP modules (OpCache)
* Installs Composer
* Installs global composer packages
