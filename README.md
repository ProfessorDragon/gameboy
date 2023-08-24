# gameboy

Modified version of [IodineGBA](https://github.com/taisel/IodineGBA).

### Controls
- Start - Enter
- Select - Shift
- D Pad - Arrows/WASD
- A - `X`/`K`/Space
- B - `Z`/`L`
- L - `Q`/`I`
- R - `E`/`O`
- Raise volume - `=`
- Lower volume - `-`
- Reset volume - `0`
- Increase speed - `]`
- Decrease speed - `[`
- Reset speed - `\`

### Url Parameters

`name` - Name of rom file.

`src` - Source of rom file.

The name and src parameters are joined together to locate the rom. The actual file will be taken from `src + "Binaries/" + name + ".gba"`.

`noconf` - Specify whether to skip the 'click to start game' message. Most browsers require the user to interact with the page before audio can be played, hence why there is a confirmation by default.
