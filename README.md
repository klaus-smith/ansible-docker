# ansible-docker
ansible-playbook roles/rancher.yml -i environment/home/home -v -k -K -u root

# Improvements axes
Variablize network commands
Manage changes on containers (docker commit)
Implement "groups_vars > all > main.yml" and clean "defaults > main.yml"
Manage errors for existing routes after a retry
Set-up Rancher
