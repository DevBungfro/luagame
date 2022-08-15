## Luagame methods

### luagame.init()

!!! Tip
    Store the `luagame` module in `ReplicatedStorage` so the client can access it.

```lua
luagame.init();
```
This will call all necessary functions in luagame.

!!! Warning
    Call this method before anything else, not doing so will result in unexpected behaviour.

### luagame.main_gui

```lua
luagame.main_gui -> GuiObject
```

This is the main gui used for displaying surfaces. This is not a function.

## KeyCodes

!!! Note 
    Luagame has every KeyCode that you can think of, there is no limitation on what keycode you want to use.

### K_[KeyCode](https://create.roblox.com/docs/reference/engine/enums/KeyCode)

```lua
luagame.K_KeyCode -> Enum.Keycode
-- https://create.roblox.com/docs/reference/engine/enums/KeyCode
```

| Name             | Value | Summary                                                               |
|------------------|-------|-----------------------------------------------------------------------|
| Unknown          | 0     | Blank value that represents no key being pressed.                     |
| Backspace        | 8     | The Backspace key.                                                    |
| Tab              | 9     | The Tab key.                                                          |
| Clear            | 12    | Only present on certain keyboards.                                    |
| Return           | 13    | Better known as enter.                                                |
| Pause            | 19    | Only present on certain keyboards.                                    |
| Escape           | 27    | The Escape key.                                                       |
| Space            | 32    | The Space key.                                                        |
| QuotedDouble     | 34    | The " key.                                                            |
| Hash             | 35    | The # key.                                                            |
| Dollar           | 36    | The $ key.                                                            |
| Percent          | 37    | The % key.                                                            |
| Ampersand        | 38    | The &amp; key.                                                        |
| Quote            | 39    | The ' key.                                                            |
| LeftParenthesis  | 40    | The ( key.                                                            |
| RightParenthesis | 41    | The ) key.                                                            |
| Asterisk         | 42    | The * key.                                                            |
| Plus             | 43    | The + key.                                                            |
| Comma            | 44    | The , key.                                                            |
| Minus            | 45    | The - key.                                                            |
| Period           | 46    | The . key.                                                            |
| Slash            | 47    | The `` key.                                                           |
| Zero             | 48    | The 0 key.                                                            |
| One              | 49    | The 1 key.                                                            |
| Two              | 50    | The 2 key.                                                            |
| Three            | 51    | The 3 key.                                                            |
| Four             | 52    | The 4 key.                                                            |
| Five             | 53    | The 5 key.                                                            |
| Six              | 54    | The 6 key.                                                            |
| Seven            | 55    | The 7 key.                                                            |
| Eight            | 56    | The 8 key.                                                            |
| Nine             | 57    | The 9 key.                                                            |
| Colon            | 58    | The : key.                                                            |
| Semicolon        | 59    | The ; key.                                                            |
| LessThan         | 60    | The &lt; key.                                                         |
| Equals           | 61    | The = key.                                                            |
| GreaterThan      | 62    | The &gt; key.                                                         |
| Question         | 63    | The ? key.                                                            |
| At               | 64    | The @ key.                                                            |
| LeftBracket      | 91    | The [ key.                                                            |
| BackSlash        | 92    | The \ key.                                                            |
| RightBracket     | 93    | The ] key.                                                            |
| Caret            | 94    | The ^ key.                                                            |
| Underscore       | 95    | The _ key.                                                            |
| Backquote        | 96    | The ` key.                                                            |
| A                | 97    | The A key.                                                            |
| B                | 98    | The B key.                                                            |
| C                | 99    | The C key.                                                            |
| D                | 100   | The D key.                                                            |
| E                | 101   | The E key.                                                            |
| F                | 102   | The F key.                                                            |
| G                | 103   | The G key.                                                            |
| H                | 104   | The H key.                                                            |
| I                | 105   | The I key.                                                            |
| J                | 106   | The J key.                                                            |
| K                | 107   | The K key.                                                            |
| L                | 108   | The L key.                                                            |
| M                | 109   | The M key.                                                            |
| N                | 110   | The N key.                                                            |
| O                | 111   | The O key.                                                            |
| P                | 112   | The P key.                                                            |
| Q                | 113   | The Q key.                                                            |
| R                | 114   | The R key.                                                            |
| S                | 115   | The S key.                                                            |
| T                | 116   | The T key.                                                            |
| U                | 117   | The U key.                                                            |
| V                | 118   | The V key.                                                            |
| W                | 119   | The W key.                                                            |
| X                | 120   | The X key.                                                            |
| Y                | 121   | The Y key.                                                            |
| Z                | 122   | The Z key.                                                            |
| LeftCurly        | 123   | The { key.                                                            |
| Pipe             | 124   | The | key.                                                            |
| RightCurly       | 125   | The } key.                                                            |
| Tilde            | 126   | The ~ key.                                                            |
| Delete           | 127   | The Del key.                                                          |
| KeypadZero       | 256   | The 0 key on the keypad cluster.                                      |
| KeypadOne        | 257   | The 1 key on the keypad cluster.                                      |
| KeypadTwo        | 258   | The 2 key on the keypad cluster.                                      |
| KeypadThree      | 259   | The 3 key on the keypad cluster.                                      |
| KeypadFour       | 260   | The 4 key on the keypad cluster.                                      |
| KeypadFive       | 261   | The 5 key on the keypad cluster.                                      |
| KeypadSix        | 262   | The 6 key on the keypad cluster.                                      |
| KeypadSeven      | 263   | The 7 key on the keypad cluster.                                      |
| KeypadEight      | 264   | The 8 key on the keypad cluster.                                      |
| KeypadNine       | 265   | The 9 key on the keypad cluster.                                      |
| KeypadPeriod     | 266   | The . key on the keypad cluster.                                      |
| KeypadDivide     | 267   | The `` key on the keypad cluster.                                     |
| KeypadMultiply   | 268   | The * key on the keypad cluster.                                      |
| KeypadMinus      | 269   | The - key on the keypad cluster.                                      |
| KeypadPlus       | 270   | The + key on the keypad cluster.                                      |
| KeypadEnter      | 271   | The Enter key on the keypad cluster.                                  |
| KeypadEquals     | 272   | The = key on the keypad cluster.                                      |
| Up               | 273   | The ↑ arrow key.                                                      |
| Down             | 274   | The ↓ arrow key.                                                      |
| Right            | 275   | The → arrow key.                                                      |
| Left             | 276   | The ← arrow key.                                                      |
| Insert           | 277   | The Insert key.                                                       |
| Home             | 278   | The Home key.                                                         |
| End              | 279   | The End key.                                                          |
| PageUp           | 280   | The PgUp key.                                                         |
| PageDown         | 281   | The PgDown key.                                                       |
| LeftShift        | 304   | The left side Shift key.                                              |
| RightShift       | 303   | The right side Shift key.                                             |
| LeftMeta         | 310   | The left side Meta key.                                               |
| RightMeta        | 309   | The right side Meta key.                                              |
| LeftAlt          | 308   | The left side Alt key.                                                |
| RightAlt         | 307   | The right side Alt key.                                               |
| LeftControl      | 306   | The left side Ctrl key.                                               |
| RightControl     | 305   | The right side Ctrl key.                                              |
| CapsLock         | 301   | The Caps Lock key.                                                    |
| NumLock          | 300   | The Num Lock key on the keypad cluster.                               |
| ScrollLock       | 302   | The Scr Lock key.                                                     |
| LeftSuper        | 311   | The left side Super key. Better known as the Windows key or Cmd key.  |
| RightSuper       | 312   | The right side Super key. Better known as the Windows key or Cmd key. |
| Mode             | 313   | Only present on certain keyboards.                                    |
| Compose          | 314   | Only present on certain keyboards.                                    |
| Help             | 315   | Only present on certain keyboards.                                    |
| Print            | 316   | Only present on certain keyboards.                                    |
| SysReq           | 317   | Only present on certain keyboards.                                    |
| Break            | 318   | Only present on certain keyboards.                                    |
| Menu             | 319   | The Menu key.                                                         |
| Power            | 320   | Only present on certain keyboards.                                    |
| Euro             | 321   | The € key. Only present on certain keyboards.                         |
| Undo             | 322   | Only present on certain keyboards.                                    |
| F1               | 282   | The F1 key.                                                           |
| F2               | 283   | The F2 key.                                                           |
| F3               | 284   | The F3 key.                                                           |
| F4               | 285   | The F4 key.                                                           |
| F5               | 286   | The F5 key.                                                           |
| F6               | 287   | The F6 key.                                                           |
| F7               | 288   | The F7 key.                                                           |
| F8               | 289   | The F8 key.                                                           |
| F9               | 290   | The F9 key.                                                           |
| F10              | 291   | The F10 key.                                                          |
| F11              | 292   | The F11 key.                                                          |
| F12              | 293   | The F12 key.                                                          |
| F13              | 294   | The F13 key. Only present on certain keyboards.                       |
| F14              | 295   | The F14 key. Only present on certain keyboards.                       |
| F15              | 296   | The F15 key. Only present on certain keyboards.                       |
| World0           | 160   | Generally not used.                                                   |
| World1           | 161   | Generally not used.                                                   |
| World2           | 162   | Generally not used.                                                   |
| World3           | 163   | Generally not used.                                                   |
| World4           | 164   | Generally not used.                                                   |
| World5           | 165   | Generally not used.                                                   |
| World6           | 166   | Generally not used.                                                   |
| World7           | 167   | Generally not used.                                                   |
| World8           | 168   | Generally not used.                                                   |
| World9           | 169   | Generally not used.                                                   |
| World10          | 170   | Generally not used.                                                   |
| World11          | 171   | Generally not used.                                                   |
| World12          | 172   | Generally not used.                                                   |
| World13          | 173   | Generally not used.                                                   |
| World14          | 174   | Generally not used.                                                   |
| World15          | 175   | Generally not used.                                                   |
| World16          | 176   | Generally not used.                                                   |
| World17          | 177   | Generally not used.                                                   |
| World18          | 178   | Generally not used.                                                   |
| World19          | 179   | Generally not used.                                                   |
| World20          | 180   | Generally not used.                                                   |
| World21          | 181   | Generally not used.                                                   |
| World22          | 182   | Generally not used.                                                   |
| World23          | 183   | Generally not used.                                                   |
| World24          | 184   | Generally not used.                                                   |
| World25          | 185   | Generally not used.                                                   |
| World26          | 186   | Generally not used.                                                   |
| World27          | 187   | Generally not used.                                                   |
| World28          | 188   | Generally not used.                                                   |
| World29          | 189   | Generally not used.                                                   |
| World30          | 190   | Generally not used.                                                   |
| World31          | 191   | Generally not used.                                                   |
| World32          | 192   | Generally not used.                                                   |
| World33          | 193   | Generally not used.                                                   |
| World34          | 194   | Generally not used.                                                   |
| World35          | 195   | Generally not used.                                                   |
| World36          | 196   | Generally not used.                                                   |
| World37          | 197   | Generally not used.                                                   |
| World38          | 198   | Generally not used.                                                   |
| World39          | 199   | Generally not used.                                                   |
| World40          | 200   | Generally not used.                                                   |
| World41          | 201   | Generally not used.                                                   |
| World42          | 202   | Generally not used.                                                   |
| World43          | 203   | Generally not used.                                                   |
| World44          | 204   | Generally not used.                                                   |
| World45          | 205   | Generally not used.                                                   |
| World46          | 206   | Generally not used.                                                   |
| World47          | 207   | Generally not used.                                                   |
| World48          | 208   | Generally not used.                                                   |
| World49          | 209   | Generally not used.                                                   |
| World50          | 210   | Generally not used.                                                   |
| World51          | 211   | Generally not used.                                                   |
| World52          | 212   | Generally not used.                                                   |
| World53          | 213   | Generally not used.                                                   |
| World54          | 214   | Generally not used.                                                   |
| World55          | 215   | Generally not used.                                                   |
| World56          | 216   | Generally not used.                                                   |
| World57          | 217   | Generally not used.                                                   |
| World58          | 218   | Generally not used.                                                   |
| World59          | 219   | Generally not used.                                                   |
| World60          | 220   | Generally not used.                                                   |
| World61          | 221   | Generally not used.                                                   |
| World62          | 222   | Generally not used.                                                   |
| World63          | 223   | Generally not used.                                                   |
| World64          | 224   | Generally not used.                                                   |
| World65          | 225   | Generally not used.                                                   |
| World66          | 226   | Generally not used.                                                   |
| World67          | 227   | Generally not used.                                                   |
| World68          | 228   | Generally not used.                                                   |
| World69          | 229   | Generally not used.                                                   |
| World70          | 230   | Generally not used.                                                   |
| World71          | 231   | Generally not used.                                                   |
| World72          | 232   | Generally not used.                                                   |
| World73          | 233   | Generally not used.                                                   |
| World74          | 234   | Generally not used.                                                   |
| World75          | 235   | Generally not used.                                                   |
| World76          | 236   | Generally not used.                                                   |
| World77          | 237   | Generally not used.                                                   |
| World78          | 238   | Generally not used.                                                   |
| World79          | 239   | Generally not used.                                                   |
| World80          | 240   | Generally not used.                                                   |
| World81          | 241   | Generally not used.                                                   |
| World82          | 242   | Generally not used.                                                   |
| World83          | 243   | Generally not used.                                                   |
| World84          | 244   | Generally not used.                                                   |
| World85          | 245   | Generally not used.                                                   |
| World86          | 246   | Generally not used.                                                   |
| World87          | 247   | Generally not used.                                                   |
| World88          | 248   | Generally not used.                                                   |
| World89          | 249   | Generally not used.                                                   |
| World90          | 250   | Generally not used.                                                   |
| World91          | 251   | Generally not used.                                                   |
| World92          | 252   | Generally not used.                                                   |
| World93          | 253   | Generally not used.                                                   |
| World94          | 254   | Generally not used.                                                   |
| World95          | 255   | Generally not used.                                                   |
| ButtonX          | 1000  | Gamepad X button.                                                     |
| ButtonY          | 1001  | Gamepad Y button.                                                     |
| ButtonA          | 1002  | Gamepad A button.                                                     |
| ButtonB          | 1003  | Gamepad B button.                                                     |
| ButtonR1         | 1004  | Gamepad R1 button.                                                    |
| ButtonL1         | 1005  | Gamepad L1 button.                                                    |
| ButtonR2         | 1006  | Gamepad R2 button.                                                    |
| ButtonL2         | 1007  | Gamepad L2 button.                                                    |
| ButtonR3         | 1008  | Gamepad R3 button.                                                    |
| ButtonL3         | 1009  | Gamepad L3 button.                                                    |
| ButtonStart      | 1010  | Gamepad Start button.                                                 |
| ButtonSelect     | 1011  | Gamepad Select button.                                                |
| DPadLeft         | 1012  | Left arrow on a gamepad D-pad.                                        |
| DPadRight        | 1013  | Right arrow on a gamepad D-pad.                                       |
| DPadUp           | 1014  | Up arrow on a gamepad D-pad.                                          |
| DPadDown         | 1015  | Down arrow on a gamepad D-pad.                                        |
| Thumbstick1      | 1016  | Gamepad primary thumbstick.                                           |
| Thumbstick2      | 1017  | Gamepad secondary thumbstick.                                         |
