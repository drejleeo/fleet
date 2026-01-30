# 🌊 Fleet

## 💻 Homelab using FOSS & Self-hosting

This project represents a fleet of ships (services) each responsible for its own cargo (containers).
Think of it as a homelab, but we use the words proposed by the chosen technology, so it becomes a journey.
Plus we navigate ⎈


### ⛴️ Ships

 - [x] Blinko - https://blinko.space/
 - [x] Glance - https://github.com/glanceapp/glance
 - [x] Immich - https://immich.app/
 - [x] Portainer - https://www.portainer.io/
 - [x] qBittorrent - https://www.qbittorrent.org
 - [x] Vaultwarden - https://github.com/dani-garcia/vaultwarden


### 💡 Projects that sparked my interest & future candidates for this fleet

Top priorities:
 - [ ] Twingate - https://www.twingate.com/
 - [ ] Metube - https://github.com/alexta69/metube

Next in line:
 - [ ] Affine.pro - https://affine.pro/
 - [ ] Audiobookshelf - https://www.audiobookshelf.org/
 - [ ] Booklore - https://github.com/adityachandelgit/BookLore
 - [ ] Caddy - https://caddyserver.com/
 - [ ] Code Server - https://coder.com/
 - [ ] Docmost - https://github.com/Docmost/docmost
 - [ ] Grafana - https://grafana.com/
 - [ ] Invidious - https://invidious.io/
 - [ ] Kasm - https://kasmweb.com/
 - [ ] N8n - https://n8n.io/
 - [ ] Openreader - https://www.openread.academy/
 - [ ] Plex - https://www.plex.tv/
 - [ ] Prometheus - https://prometheus.io/
 - [ ] Rancher - https://www.rancher.com/
 - [ ] Sshwifty - https://github.com/nirui/sshwifty
 - [ ] Stremio - https://github.com/Stremio/server-docker
 - [ ] Tailscale - https://tailscale.com/
 - [ ] Tautulli - https://tautulli.com/
 - [ ] Umbrel - https://apps.umbrel.com/
 - [ ] Watchtower - https://containrrr.dev/watchtower/


## Important
 - Make sure to enable Websockets for the containers that need them.


## TODOs
 - Add `container_name` properties to all containers.
 - Ensure `fleet` network is used on all stacks in the end.


## Ambition
 - [ ] Implement a way to spin-up all containers stacks at once.
 - [ ] Implement feature toggle to allow only the desired stacks.
 - [ ] Create a system for easy secrets management, while using best practices.


## Useful links
 - [Docker, Tailscale and Caddy with HTTPS. A love story!](https://www.reddit.com/r/Tailscale/comments/104y6nq/docker_tailscale_and_caddy_with_https_a_love_story/)
 - [Tailscale, Synology, HTTPS to docker services](https://caddy.community/t/taiscale-synology-https-to-docker-services/18834/1)
 - [Setting up Caddy, tailscale for reverse proxy on Synology NAS](https://caddy.community/t/setting-up-caddy-tailscale-for-reverse-proxy-on-synology-nas/23418)

## Troubleshooting
 - [Server getting OOMKilled](https://github.com/immich-app/immich/discussions/16119)
