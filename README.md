### Usage
Set the coordinate on any or all of these three players on the scoreboard `teleport_at` either with the command `scoreboard players set AT#* teleport_at $` or the execute command `execute store result score AT#* teleport_at [...]`.
- **AT#X** - X coordinate
- **AT#Y** - Y coordinate
- **AT#Z** - Z coordinate
Any unspecified coordinate will default to the current coordinate of the command sender.

When you want to teleport the player, execute the function `function teleport:to` or `execute as @p teleport:to`.
The coordinates will be reset after a successful teleport.

### Teleport everyone
`function teleport:all/to`

### How it works

It summons an ender pearl at the current position of the command sender then moves it to the coordinates, then teleport the command sender.

### Credits

No need for credit me if you use this, I don't care.
Include this anywhere you want, I just got tired of typing the same thing everytime I needed to.
