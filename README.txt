FongMi subscription configurations

Main subscription:
https://cangyao.github.io/fongmi-subscriptions/all.json

The main configuration merges these two inputs:
https://raw.githubusercontent.com/gaotianliuyun/gao/master/0825.json
The previous all.json configuration in this repository (12 CMS sites and 1 live playlist).

Result: 145 unique site configurations, 6 live playlists, 0 parse entries.
Site configurations include VOD, music, utilities, local files and cloud-drive integrations; they are not all independent movie providers.

Changes:
- Deduplicated Liangzi and Feifan CMS provider variants, retaining the existing direct JSON API entries.
- Preserved different Spider/JS implementations as alternatives.
- Resolved all upstream relative configuration paths against gaotianliuyun/gao.
- Corrected three missing Wogg category/filter paths to the existing json/wogg.json.
- Renamed a duplicate TGYunPan key so that both distinct site configurations remain accessible.
- Replaced two GitHub proxy-wrapper live URLs with verified original GitHub URLs.
- Verified declared MD5 hashes for the PG and XBPQ JARs and availability of three JS drivers. JARs and scripts were not executed.

Some upstream sites require cloud-drive authorization, local helper services or network/proxy settings on the Android device. Importing a configuration does not supply these prerequisites. Full Android playback has not been tested.

Configuration selector:
https://cangyao.github.io/fongmi-subscriptions/index.json

The separate trial.json remains the previous 12 CMS sites plus 3 live playlists. The Guovin trial playlist is a snapshot last updated 2026-08-27.

Raw fallback:
https://raw.githubusercontent.com/CangYao/fongmi-subscriptions/main/all.json

Only public configuration addresses are stored here. These configurations are snapshots and are not automatically re-merged with upstream changes.