# Unraid templates

Public Unraid application templates and artwork for projects maintained by `yelpspoon`.

## Media utilities

- Media Utilities template: [`templates/media-utilities.xml`](templates/media-utilities.xml)
- Media Tagger template: [`templates/media-tagger.xml`](templates/media-tagger.xml)
- Container repository: [`yelpspoon/media-utilities`](https://hub.docker.com/r/yelpspoon/media-utilities)

Media Utilities provides FLAC-to-MP3 conversion and authorized YouTube audio processing. Media Tagger runs the native Puddletag editor through a browser-accessible Linux desktop.

## Retro Games

- Application template: [`templates/retro-games.xml`](templates/retro-games.xml)
- Database helper: [`templates/retro-games-db.xml`](templates/retro-games-db.xml)
- Container repository: [`yelpspoon/retro-games`](https://hub.docker.com/r/yelpspoon/retro-games)

Retro Games provides a browser-hosted SNES and Nintendo 64 library using RomM and EmulatorJS. The application reads the ROM sources without modifying them and keeps its database, artwork, saves, and configuration under Unraid appdata.

## IPTV

- Template: [`templates/tv-guide-search.xml`](templates/tv-guide-search.xml)
- Icon: [`images/tv-guide-search.png`](images/tv-guide-search.png)
- Container: [`yelpspoon/tv-guide-search`](https://hub.docker.com/r/yelpspoon/tv-guide-search)

The IPTV template installs a unified home screen, TVheadend, XMLTV guide generation, UK and US iptv-org playlists, and the guide-search API as one Unraid container.
