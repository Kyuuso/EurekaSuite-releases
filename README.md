# Eureka Suite releases

Public downloads for Eureka Suite, a Dalamud plugin for the Eureka zones of Final Fantasy XIV (Anemos, Pagos, Pyros and Hydatos). This repository holds the plugin feed and the release ZIPs only; the plugin source is not published here.

## Install

In game, open `/xlsettings`, go to **Experimental**, and add this URL under **Custom Plugin Repositories**:

```
https://raw.githubusercontent.com/Kyuuso/EurekaSuite-releases/main/pluginmaster.json
```

Save, then install **Eureka Suite** from `/xlplugins`. Testing builds appear when **Get plugin testing builds** is enabled for the plugin.

Eureka Suite is also listed in `https://raw.githubusercontent.com/Kyuuso/dalamud-plugins/main/pluginmaster.json`, which points at the same downloads. Add only one of the two feeds; with both, Dalamud lists the plugin twice. Existing installations from that feed keep receiving updates.

## Contents

| Path | Purpose |
| --- | --- |
| `pluginmaster.json` | Feed read by Dalamud |
| `EurekaSuite.json` | Manifest of the current stable release |
| `icon.png` | Plugin icon |
| Releases | `EurekaSuite-vX.Y.Z.zip` for stable versions, `EurekaSuite-vX.Y.Z-preview.zip` for testing builds |

## Third-party components

See [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).
