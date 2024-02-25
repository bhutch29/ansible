echo "<password>" > .password
ansible-galaxy role install artis3n.tailscale
ansible-playbook server.yml -k

Tailscale:
Followed https://tailscale.com/blog/docker-tailscale-guide
Auth Key expires in 90 days
`tailscale_authkey` is used by artis3n.tailscale role

