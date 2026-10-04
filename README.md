# div16

A Minecraft coordinate calculator by **senzdev**.

Choose a calculator, enter X and Z, optionally Y, then select Calculate.

| Mode | Calculation | Closest result |
| --- | --- | --- |
| 16-block alignment | Each supplied axis ÷ 16 | Nearest multiple of 16 |
| Overworld to Nether | X and Z ÷ 8; Y unchanged | Nearest whole-block X/Z coordinates |
| Nether to Overworld | X and Z × 8; Y unchanged | Nearest whole-block X/Z coordinates |

Every mode also shows exact, unrounded results. Ties choose the coordinate closer to zero. In Nether conversion modes, Y is preserved even when it contains decimals. Choose a suitable portal height for your destination.

- Positive, negative, and decimal coordinates
- Optional Y coordinate
- Copy nearest coordinates to the clipboard
- Responsive Minecraft-inspired interface
- Clear preserves the selected calculator
- Changing inputs or mode clears old results
- Runs entirely in your browser without external dependencies

Open `index.html` locally to use the calculator offline.

Verified with 14 alignment cases, 18 Nether conversion cases, invalid input checks, browser interactions, and mobile/desktop layout checks.
