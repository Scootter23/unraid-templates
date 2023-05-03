# Unraid Templates
- [Cloudflare-Tunnel](#archivebox)
  * [First installation](#first-installation)
  * [Configuration](#configuration)
----
# ArchiveBox
![Cloudflare-Tunnel](https://raw.githubusercontent.com/Scootter23/unraid-templates/main/templates/img/cloudflare-zerotrust.png)

ArchiveBox is a powerful self-hosted internet archiving solution written in Python 3. You feed it URLs of pages you want to archive, and it saves them to disk in a varitety of formats depending on the configuration and the content it detects. 

**Application Name:** ArchiveBox

**Application Site:** https://archivebox.io/

**Docker Hub:** https://hub.docker.com/r/nikisweeting/archivebox

**Github:** https://github.com/pirate/ArchiveBox
## First installation 
1. **Run** the Archivebox Docker and **Console** to it.
```su - archivebox```
```cd /data```
```archivebox init```
```archivebox manage createsuperuser```
2. **Edit** Archivebox Docker Click at **Advanced View** put ```server 0.0.0.0:8000``` in **Post Arguments**.
## Configuration
To edit configuration open Archivebox folder and Edit ArchiveBox.conf (https://github.com/pirate/ArchiveBox/wiki/Configuration)

**[`^back to top^`](#unraid-templates)**

----
