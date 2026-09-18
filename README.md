# ha-ecovacs-t80s

Home Assistant Ecovacs override for the **DEEBOT T80S OMNI**.

## Version 2026.9.2-t80s.2

Based on Home Assistant Core **2026.9.2** and `deebot-client==18.5.1`.

T80S OMNI compatibility patches:

- `Clean` → `CleanV2`
- `CleanArea` → `CleanAreaV2`
- `GetMapSet` → `GetMapSetV2`
- clears cached `rzwv5p` capabilities when the integration is loaded

The additional `GetMapSetV2` patch is intended to restore room/segment discovery so Home Assistant can expose areas for room cleaning.
