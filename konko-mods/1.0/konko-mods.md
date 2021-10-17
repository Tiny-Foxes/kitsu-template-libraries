# Konko Mods
## Version 1.0
#### Created by Sudospective

---
**Requires Kitsu Standard Library v1.0**

A mod loader included with Kitsu Template. Allows support for easing mods rather than applying mods via approach rate.

---
## Usage
```lua
local Mods = import 'konko-mods'

Mods:Insert(0, 2, Tweens.inoutquad, {
	{100, 'drunk'},
	{-50, 'tiny'},
	{2, 'xmod'}
})
```

See `konko-mods.lua` for more details

---
##### [Return to Index](../index.md)