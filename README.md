# Self-Hosted Homelab Infrastructure

A self-hosted, home server built on Ubuntu Server host. Designed to do whatever looked interesting at the time.

## Architecture & Hardware
* **Operating System:** Ubuntu Server (Laptop)
* **Container Management:** Docker & Portainer CE
* **Remote Access & Networking:** Tailscale VPN with MagicDNS
* **Power Management:** lid-sleep override

## Deployed Services
* **Pi-hole:** Local DNS with network-wide adblocking.
* **Vaultwarden:** Bitwarden-compatible password manager.
* **Jellyfin:** Self-hosted media platform for streaming personal music.
* **Uptime Kuma:** Real-time uptime monitoring for local services with webhook notifications.

## Security & Development
All credentials, API tokens, and local IP addresses are isolated using environment variables ('.env'). Refer to '.env.example' for required configuration variables before deployment
