# Learn-Ansible-Vault
An encrypted yml file using ansible vault
# How to use ansible vault
- To create an encrypted file, use the ansible-vault create command and pass the filename.

$ ansible-vault create filename.yaml

- You’ll be prompted to create a password and then confirm it by re-typing it. 

- Once your password is confirmed, a new file will be created and will open an editing window. By default, the editor for Ansible Vault is vi. You can add data, save and exit. 

# Uses of ansible vault

Ansible Vault is a feature of Ansible that allows you to keep sensitive data, such as passwords or keys in encrypted files, rather than as plaintext in playbooks or roles. 
  
Ansible Vault can encrypt any structured data file used by Ansible. Ansible Vault can also encrypt arbitrary files, even binary files. If a vault-encrypted file is given as the src argument to the copy, template, unarchive, script, or assemble modules, the file will be placed at the destination on the target host decrypted (assuming a valid vault password is supplied when running the play).  
