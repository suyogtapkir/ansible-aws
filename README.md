Pre-requisite
ansible-galaxy collection install amazon.aws:==3.3.1 --force

Command:
ansible-playbook playbook.yml -i localhost --ask-vault-pass
