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

Ensures that Homebrew is installed.

### NPM (todo)

Installs NPM and any Node.js packages required
.
### Nginx (todo)

Installs and configures Nginx

### PHP (todo)

Installs and configures PHP using Homebrew

### RVM (todo)
	
Installs RVM, Bundler, and any defined ruby versions. 