- When `awardBadge()` is invoked:
  - Assigns Discord role tied to tier
  - Fires embed to `#shrine-echoes` with badge metadata
  - Logs badge drop to `badgeLog.json`

- Tiers:
  - `bronze` → Role: Initiate, Badge: Ember Sigil
  - `silver` → Role: Echo, Badge: Mirror Fragment
  - `gold` → Role: Beacon, Badge: Eternal Flame
