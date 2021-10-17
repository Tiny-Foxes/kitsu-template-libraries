# Kitsu Standard Library
## Version 1.1
#### Created by Sudospective

---
The inlcuded standard library for Kitsu template. Initializes a basis for most templating needs, such as variable shortcuts, input handling, and various useful functions (`ready`, `update`, etc.)

---
## Usage
```lua
local std = import 'stdlib'

local t = Def.ActorFrame {
	InitComand = function(self)
		self:x(std.SCX)
	end,
	Def.Quad {
		InitCommand = function(self)
			self:y(std.SCY)
		end,
		UpdateCommand = function(self)
			self:addrotationz(180 * std.DT)
		end,
	}
}

function input(event)
	if event.type = 'InputEventType_FirstPress' then
		t:diffuse(color('#00FF00'))
	else
		t:diffuse(color('#FFFFFF'))
	end
end

return t
```

See `stdlib.lua` for more details

---
##### [Return to Index](../index.md)
