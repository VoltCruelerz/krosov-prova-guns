# Krosov & Prova Guns

## Changes

- Krosov Siege Frigates can now use their bombardment missiles as short-range improvised ship-to-ship weapons.
  - Range: 2000
  - DPS: 6.2 (50 penetration)
- Prova Scout Frigates now come equipped with a simple point defense autocannon for shooting down incoming missiles.

## Installation

1. Extract this to wherever you want.
2. Copy it to `%APPDATA%/Local/sins2/mods/`, so that this file's path is `%APPDATA%/Local/sins2/mods/krosov-prova-guns/README.md`
3. Add/Update `enabled_mods.json`
    1. If you don't already have one, add an `enabled_mods.json` file to your `mods` directory. It should look like the below:
    2. If you do already have one, just add in the element to `mod_keys`.

### Example enabled_mods.json

```json
{
    "mod_keys": [
        {
            "name": "krosov-prova-guns",
            "version": 0
        }
    ]
}
```
