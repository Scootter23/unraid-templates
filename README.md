# Unraid Templates
- [Cloudflare-Tunnel](#cloudflare-tunnel)
  * [Create a Tunnel](#create-a-tunnel)
  * [Create the Unraid Container](#create-the-unraid-container)
----
# Cloudflare-Tunnel
![Cloudflare-Tunnel](https://raw.githubusercontent.com/Scootter23/unraid-templates/main/templates/img/cloudflare-zero-trust.png)

Cloudflare Tunnel is a Cloudflare Zero Trust connection that can connect HTTP web servers, SSH servers, remote desktops, and other protocols safely to Cloudflare. This way, your origins can serve traffic through Cloudflare without being vulnerable to attacks that bypass Cloudflare.

**Application Name:** Cloudflare-Tunnel

**Application Site:** https://github.com/Scootter23/unraid-templates/tree/main/templates

**Docker Hub:** https://hub.docker.com/r/cloudflare/cloudflared

**Github:** https://github.com/cloudflare/cloudflared

## Create a Tunnel
1. Log in to the Zero Trust dashboard at https://one.dash.cloudflare.com/
2. **Edit** Archivebox Docker Click at **Advanced View** put ```server 0.0.0.0:8000``` in **Post Arguments**.
## Create the Unraid Container
1. 
2.

**[`^back to top^`](#unraid-templates)**

----
