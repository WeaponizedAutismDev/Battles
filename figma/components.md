# Components Catalog (Figma)

- HUD/Bar.Health
  - Props: max, value, armorSegments[]
  - Variants: size [sm,md,lg], state [normal,warning,critical]
  - Auto-layout: horizontal, 320×24 default, armor overlay

- HUD/Dial.Energy
  - Props: value (0–100)
  - Variants: size [sm,md], ringStyle [solid,segmented]

- HUD/Dial.Heat
  - Props: value (0–100)
  - Variants: dangerThreshold [85]

- HUD/Weapon.Meter
  - Props: slot (w1|w2), charge (0–1), cooldown (ticks)
  - Variants: type [beam,projectile,melee]

- Overlay/Toast
  - Variants: [CRIT, OVERHEAT, SHIELD BREAK]
  - Motion: {core.motion.fast} with overshoot

- Camera/Mode.Button
  - Variants: [Auto, TopDown, KiterOrbit]
  - Icon: 20×20

- Panel/Card.MatchTile
  - Content: matchId, builds, odds, liveBadge
  - Variants: [Live, Scheduled]

- Table/Leaderboard.Row
  - Columns: rank, name, wins, ko%, dpm, dsWins, mmr
  - Sort icons optional

- Controls/Prediction
  - Inputs: stake slider (1–1000), pick [A|B]
  - Buttons: Place, Cancel, Confirm

- MiniMap/Tile
  - Layers: bounds, hazards, positions, vectors

- Chart/Lines
  - Types: Damage, Heat, Energy

- Tag/Chip
  - Variants: [Part, Archetype, Rarity]

- Button/Primary, Button/Ghost, IconButton
  - Sizes: sm, md
  - Radius: {semantic.component.button.radius}

- Layout shells
  - Header, Right Rail, Bottom Bar, Canvas Container