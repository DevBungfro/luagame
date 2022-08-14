
!!! Note
    This documentation assumes that the `luagame` module is in `ReplicatedStorage`

``` lua
local luagame = require(game.ReplicatedStorage.luagame)
luagame.init() -- Initialize luagame
```

We just initialized luagame! Now let's draw our first rectangle.


``` lua
local rect = luagame.draw.rect(luagame.main_gui.BG, .1, .1, .5,.5, Vector2.new(.5,.5))
```

!!! Warning
    You must have basic knowledge of `Positioning` and `Scaling` guis.