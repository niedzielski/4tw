
    7---8---9
    | X |   |   4
    4---5---6  the
    |   |   |  win
    1---2---3
A utility for positioning X windows in quarters, halves, or full screen. This is a supplement for users not wanting to install a tiling window manager.

## Usage
- `4tw n` - Position active window in top half of screen.
- `4tw se` - Position active window in lower right hand quarter of screen.
- `4tw o` - Toggle active window maximize state.
- `4tw` - Toggle show desktop.

## Tips
- It's highly recommended that the script be hotkeyed for each parameter (NW, N, NE, ...). When the hotkey is invoked, the currently active window will be used.

## Requirements
- wmctrl
- xdotool
