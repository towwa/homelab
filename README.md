## homelab


To start the stack, first setup .env file and copy it into `traefik` and then install docker and docker-compose and run

.env file example:
```
MEDIA_PATH=/mnt/media
DOCKER_VOLUME_STORAGE=/mnt/media
OPENVPN_USER=abcd
OPENVPN_PASSWORD=abcd
MY_DOMAIN=yourdomain.com
DEFAULT_NETWORK=traefik_net
CF_API_EMAIL=email@gmail.com
CF_DNS_API_TOKEN=LG-abcd
```

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