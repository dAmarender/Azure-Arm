# Ansible commands
# to find the host ip of the server
$ ansible --list-hosts all

# to target a specific servers
$ ansible --list-hosts webserver
$ ansible --list-hosts loadbalancers

# Ansible patterns
$ ansible --list-hosts "*"
# Ansible wildcards
$ ansible --list-hosts webserver*
$ ansible --list-hosts webserver:loadbalancers
# Ansible gate functionality
$ ansible --list-hosts \!control

# Ansible Array systax
$ ansible --list-hosts webserver[0]


