Explain:
- alias → friendly name
- ansible_host → actual IP

Important:
- Ansible uses the alias but connects using the IP.

Even if we don’t define any groups, Ansible creates two default groups:
- all → contains all hosts
- ungrouped → hosts not in any custom group
