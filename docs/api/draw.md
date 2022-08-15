
## Draw methods

### draw.rect()
```lua
draw.rect(surface : GuiObject, w : number, h : number, right : number, top : number, anchor_point?: Vector2) -> any
```

This wil put a rectangle (or square) on the screen.

### draw.circle()

```lua
draw.circle(surface : GuiObject, w : number, h : number, right : number, top : number, anchor_point?: Vector2) -> any
```

This wil put a circle on the screen.

### draw.circle()

```lua
draw.text(RenderedText : GuiObject, right : number, top : number, w: number, h: number, parent : Instance) -> GuiObject
```

This wil put the rendered text on the screen, the `RenderedText` param takes a GuiObject given by the [Font](/api/font) method.

## Instance methods

These methods return a custom object. This object can be used to change the color, border radius, and much more.

### Rect:SetColor()

```lua
local rect = draw.rect(surface : GuiObject, w : number, h : number, right : number, top : number, anchor_point?: Vector2)
rect:SetColor(color : Color3)
```

This method takes [Color3](https://create.roblox.com/docs/reference/engine/datatypes/Color3) as `color`.

### Rect:SetCornerRadius()

```lua
local rect = draw.rect(surface : GuiObject, w : number, h : number, right : number, top : number, anchor_point?: Vector2)
rect:SetCornerRadius(size : number)
```

This method takes a [number](https://developer.roblox.com/en-us/articles/Numbers) as `size`

### Rect:Move()

```lua
local rect = draw.rect(surface : GuiObject, w : number, h : number, right : number, top : number, anchor_point?: Vector2)
rect:Move(position : Udim2)
```

This method takes [Udim2](https://create.roblox.com/docs/reference/engine/datatypes/UDim2) as `position`.