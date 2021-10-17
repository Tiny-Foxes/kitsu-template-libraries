# Konko Node
## Version 1.0
#### Created by Sudospective

---
**Requires Kitsu Standard Library v1.0 or higher**

An included library for Kitsu Template that allows construction of Actors via objects and functions rather than tables and keys.

---
## Usage
```lua
local Node = import 'konko-node'

Node.new('Quad')
	:SetReady(function(self)
		self:FullScreen()
		self:diffuse(color('#000000'))
	end)
	:AddToTree('CoverBG', 1)
```

See `konko-node.lua` for more details

---
##### [Return to Index](../index.md)
