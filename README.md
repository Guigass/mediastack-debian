# mediastack-debian
Bazarr - Deluge - Jackett - Plex - Portainer - Radarr - Sonarr

Run the command below on a clean, minimal installation of Debian Stretch.

PLEX:
```
bash <(wget --no-check-certificate -qO- https://raw.githubusercontent.com/Guigass/mediastack-debian/master/mediastack-plex)
```

Jellyfin:
```
bash <(wget --no-check-certificate -qO- https://raw.githubusercontent.com/Guigass/mediastack-debian/master/mediastack-jellyfin)
```

It will install Bazarr / Deluge / Jackett / (Plex or Jellyfin) / Portainer / Radarr / Sonarr, in a containerized environment.

After the installation, this is how you can access all the web apps:
```
Name: bazarr
Usage: subtitles downloader
URL: http://<your_ip_here>:6767
```
```
Name: deluge
Usage: download manager
URL: http://<your_ip_here>:8112
Pass: deluge
```
```
Name: jackett
Usage: api torrent tracker
URL: http://<your_ip_here>:9117
```
```
Name: portainer
Usage: docker container management
URL: http://<your_ip_here>:9000
```
```
Name: radarr
Usage: download movies
URL: http://<your_ip_here>:7878
```
```
Name: sonarr
Usage: download tv shows
URL: http://<your_ip_here>:8989
```
