# wii_tanks_mods

Gecko code pack for Wii Play Tanks (Ocarina format).

## Example `GCT` / `INI` entries

> These are starter Gecko entries for Tanks gameplay tweaks. Keep one region per file and place the file in your loader's `codes/` directory.

```ini
[Gecko]
$Infinite Lives
04123456 00000063

$Rapid Fire
0412345A 00000001

$Max Score
0412345E 0001869F
```

## Usage

1. Create or edit the game `.ini` file in your loader's `codes/` folder.
2. Paste the code entries above.
3. Enable each code in your loader and launch the game.
