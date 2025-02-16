# home-server
Documentation for home-server. Every service listed is self-hosted + open-source.

## Specs
* CPU: AMD A10-9700E (Radeon R7, 10 Compute Cores: 4C+6G)
* RAM: 7.2GB
* Swap: 976MB
* OS: Debian 12 (Bookworm)
* Storage: 1TB 7200rpm SATA HDD


## Software Used
* [OS: Debian Linux](https://github.com/debian)
* [Glance (dashboard)](https://github.com/glanceapp/glance): RSS feed, stock prices, basic server info, aggregated reddit feed, etc.
* [Portainer](https://github.com/portainer/portainer): tracks status of installed docker containers
* [Nextcloud](https://github.com/nextcloud/docker): self-hosted, open-source Google Drive alternative
* [Mealie](https://github.com/mealie-recipes/mealie): scrapes websites for recipie information, saves recipies
* [Minecraft-Server](https://github.com/itzg/docker-minecraft-server): hosts minecraft server
* [NGINX Proxy Manager](https://github.com/NginxProxyManager/nginx-proxy-manager): routes traffic and handles ssl
* [Tailscale VPN](https://github.com/tailscale/tailscale): used for remote access to server (easier installation than wireguard)
* [Watchtower](https://github.com/containrrr/watchtower): automatically updates docker containers
* [Hoarder](https://github.com/hoarder-app/hoarder): similar to Pintrest or Are.na; saves websites, images, videos, etc.
* [UFW (uncomplicated firewall)](https://help.ubuntu.com/community/UFW): basic Ubuntu/Debian firewall, restricts port access for security

## To-Do
* [Logseq](https://github.com/logseq/logseq): alternative to Obsidian, better UI than Joplin
* [Syncthing](https://github.com/syncthing/syncthing): self-hosted file sync tool (hoping to combine w/ Logseq)
* [Pi-Hole](https://github.com/pi-hole/pi-hole): network wide ad-blocker / dns sinkhole
* [Immich](https://github.com/immich-app/immich): self-hosted, open-source alternative to Google Photos
* [Vaultwarden](https://github.com/dani-garcia/vaultwarden): self-hosted alternative to Bitwarden (password manager)
