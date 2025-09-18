# home-server
Documentation for my home-server. Every service listed is self-hosted + open-source.

## Specs
* CPU: AMD A10-9700E (Radeon R7, 10 Compute Cores: 4C+6G)
* RAM: 7.2GB
* Swap: 976MB
* OS: Debian 13 (Trixie)
* Storage: 1TB 7200rpm SATA HDD
* Backup Drive (via RSYNC): 1TB

## Software Used
* [OS: Debian Linux](https://github.com/debian)
* [Tailscale VPN](https://github.com/tailscale/tailscale): used for remote access to server (easier installation than basic wireguard)
* [UFW (uncomplicated firewall)](https://help.ubuntu.com/community/UFW): basic Ubuntu/Debian firewall, restricts port access for security
* [Watchtower](https://github.com/containrrr/watchtower): automatically updates docker containers
* [Portainer](https://github.com/portainer/portainer): tracks status of installed docker containers
* NGINX Proxy Manager
* [Glance (dashboard)](https://github.com/glanceapp/glance): RSS feed, stock prices, basic server info, aggregated reddit feed, etc.
* [Nextcloud](https://github.com/nextcloud/docker): self-hosted, open-source Google Drive alternative
* [Immich](https://github.com/immich-app/immich): self-hosted, open-source alternative to Google Photos
* [Vaultwarden](https://github.com/dani-garcia/vaultwarden): self-hosted alternative to Bitwarden (password manager)

## To-Do
* Authelia
* AdGuard Home
* Mullvad + Tailscale
* Jellyfin Metadata
* Self-Host Standard Notes
* Backup Music folder 
* Backup Calendar and Contacts
* BIOS Restart (after power-outage)

## Future:
* Off-Site Server
* Off-Site Backup
* UPS
