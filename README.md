# Unraid Templates
- [Cloudflare-Tunnel](#cloudflare-tunnel)
  * [First installation](#first-installation)
  * [Configuration](#configuration)
----
# Cloudflare-Tunnel
![Cloudflare-Tunnel](https://raw.githubusercontent.com/Scootter23/unraid-templates/main/templates/img/cloudflare-zerotrust.png)

Cloudflare Tunnel provides you with a secure way to connect your resources to Cloudflare without a publicly routable IP address. With Tunnel, you do not send traffic to an external IP — instead, a lightweight daemon in your infrastructure (cloudflared) creates outbound-only connections to Cloudflare’s global network. Cloudflare Tunnel can connect HTTP web servers, SSH servers, remote desktops, and other protocols safely to Cloudflare. This way, your origins can serve traffic through Cloudflare without being vulnerable to attacks that bypass Cloudflare.

**Application Name:** Cloudflare-Tunnel

**Application Site:** https://github.com/Scootter23/unraid-templates/tree/main/templates

**Docker Hub:** https://hub.docker.com/r/cloudflare/cloudflared

**Github:** https://github.com/cloudflare/cloudflared
## First installation 
1. **Run** the Archivebox Docker and **Console** to it.
```su - archivebox```
```cd /data```
```archivebox init```
```archivebox manage createsuperuser```
2. **Edit** Archivebox Docker Click at **Advanced View** put ```server 0.0.0.0:8000``` in **Post Arguments**.
## Configuration
To edit configuration open cf folder and Edit ArchiveBox.conf (https://github.com/pirate/ArchiveBox/wiki/Configuration)

**[`^back to top^`](#unraid-templates)**

----
