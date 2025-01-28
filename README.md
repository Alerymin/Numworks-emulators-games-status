# Numworks emulators games status
A list of games compatible with numworks emulators and their working status

## Content

CSV files containing info about games working status. One file per emulator:

```
Game name,Running status,Game save status,Savestate status,Gameplay rating,Notes
```

Running status:
- 0: Game refuses to start or stops shortly afer starting
- 1: Game is playable but stops before the end of the game
- 2: Game is fully working

Game save status:
- X: Game does not use save data
- 0: Save does not work or cannot be restored
- 1: Save works

Savestate status:
- 0: Savestate does not work or cannot be restored
- 1: Savestate works

Gameplay rating:
- 1: Hard to pres the buttons correctly
- 2: It's possible to adapt without too much effort
- 3: Game works with not effort

Notes:
  Adds precision on where the game has issues if needed
