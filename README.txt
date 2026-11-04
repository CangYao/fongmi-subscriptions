FongMi subscription configurations

Main subscription:
https://cangyao.github.io/fongmi-subscriptions/all.json

Latest availability audit: 2026-11-04.
Current main configuration: 130 site entries and 5 live playlists.
Removed 15 confirmed-broken site entries and 1 live playlist from the previous 145-site / 6-playlist configuration.
Removal evidence: unavailable configured Spider classes, NXDOMAIN verified through Google and Cloudflare DNS, or repeated playlist HTTP 404 responses.
See audit-summary.json for the exact removal list and checks performed.

Policy requested by the owner: only remove confirmed failures. Retain sources that require authorization, local helper services, network/proxy settings, or further Android testing.
Retained entries are not all playback-verified. CMS and live playback tests inspect a sample of HLS playlists, media fragments and AES keys; they do not establish full playback on an Android device.
67 dependency files were reachable and both configured JAR MD5 values matched. The JAR class inventory was inspected without executing third-party code.

The main configuration merges gaotianliuyun/gao 0825.json with the original 12-CMS / 1-live configuration.
Site entries include VOD, music, utilities, local-file and cloud-drive integrations.
Relative dependencies and the prior duplicate provider/key issues have been resolved.

Configuration selector:
https://cangyao.github.io/fongmi-subscriptions/index.json

The separate trial.json remains the original 12 CMS sites plus 3 live playlists and is outside this main-subscription audit. The Guovin trial playlist is a snapshot dated 2026-08-27.

Raw fallback:
https://raw.githubusercontent.com/CangYao/fongmi-subscriptions/main/all.json

Only public configuration addresses are stored here. Configurations are snapshots and are not automatically re-merged or retested.