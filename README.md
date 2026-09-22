# Worms

A Worms-style artillery duel in pygame: two worms, destructible terrain, a wind value that
drifts between rounds, and grenade and missile pickups.

```
python main.py
```

Your worm moves with `A`/`D`, weapons are selected with the mouse, and the shot is fired
from the same controls once a weapon is chosen.

Everything lives in `main.py` (about 400 lines) plus the game art — terrain, explosions,
the weapon sprites and the wind indicator. It started as a game-programming assignment and
stayed around because it was fun to keep tweaking.
