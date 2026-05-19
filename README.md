# Mammotion Agora Card

A Lovelace card for displaying a live camera feed with movement controls for Mammotion mowers via the Agora SDK.

## Installation via HACS

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=mikey0000&repository=ha-mammotion-agora-card&category=plugin)

Or manually:

1. Open HACS → three-dot menu (⋮) → **Custom repositories**
2. Add `https://github.com/mikey0000/ha-mammotion-agora-card` with category **Dashboard**
3. Find **Mammotion Agora Card** and click **Download**

## Requirements

The **Mammotion** integration must be installed and the target mower must support camera streaming via Agora.

## Adding the card

In your Lovelace dashboard → **Edit** → **Add Card** → **Custom: Mammotion Agora Card**.

Or paste the YAML manually:

```yaml
type: custom:agora-client
entity: lawn_mower.my_luba2
```
