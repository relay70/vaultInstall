# vaultInstall
### Description

Ansible script to install HashiCorp Vault.
- Sets up yum repo
- Installs vault
- Enables Service
- Unseals database
- Writes Keys and Tokes to file calle "KEYS"

See: https://www.relay70.com/hashicorp-vault-with-admin-account/

for the manual steps and explanations.

### Command
ansible-playbook -i < HOST >, main.yml -u < AnsibleUser > --ask-pass

