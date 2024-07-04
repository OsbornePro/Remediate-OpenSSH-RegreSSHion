# Remediate-OpenSSH-RegreSSHion
Repository containing scripts to identify and remediate the new OpenSSH RegreSSHion vulnerability

## File List
1. **check_ssh_regression_exploit.sh** - Bash script to test whether the ssh version in use is exploitable
2. **check_ssh_regression_exploit.yml** - Ansible Playbook to test whether the ssh version in use is exploitable
3. **remediate_regresshion.yml** - Ansible Playbook to update ssh binary on Debian and Fedora based systems
4. **remediate_regresshion_exploit.sh** - Bash script to update ssh binary on Debian and Fedora based systems
