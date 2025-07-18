## homelab

To start the stack install docker and docker-compose and run
```
docker compose up -d
```

My personal homelab for learning. My stack runs on a proxmox Ubuntu 22.04 VM. So far I have and planned
- proxmox 
- *arr stack with jellyfin
- minecraft game server
- metrics and homepage dashboard
- reverse proxy / routing
  - traefik / caddy-docker / nginx proxy manager?
- [ ] authelia - 2fa server?
- [ ] ldap server for jellyfin
 

Future things to explore are
- [ ] k3s and kubernetes
- [ ] ansible
- [ ] proxmox HA mode / k3s high availability