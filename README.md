# ansible-role-remote-access
Ansible role which configures remote ssh access to use public private key connection only and disables password login. You can apply this role to a machine just after installing sshd for remote ansible management.
Ensures sudo is installed and remote_access_user is part of the sudoers list.
