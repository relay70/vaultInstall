# vaultInstall
### Description

Ansible script to install HashiCorp Vault.
- Sets up yum repo
- Installs vault
- Enables Service
- Unseals database
- Writes Keys and Tokes to file calle "KEYS"

### Command
ansible-playbook -i < HOST >, main.yml -u < AnsibleUser > --ask-pass

