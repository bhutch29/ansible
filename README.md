echo "<password>" > .password
ansible-galaxy role install artis3n.tailscale
ansible-playbook server.yml -k

