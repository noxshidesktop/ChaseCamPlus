# ChaseCamPlus

A smarter chase camera for Assetto Corsa, built on CSP's custom chaser camera system.

## What it does

ChaseCamPlus gives you two camera modes in one:

- **Drift mode** — the camera follows the direction the car is *travelling*, so slides and spins happen in front of a steadier camera. Presets range from smooth cinematic looks to aggressive low-angle drift cams.
- **Racing mode** — the camera stays behind the car's nose like a normal chase cam and leans gently into corners.

Both modes are tuned live from an in-game panel. Pick a preset from the dropdown, drag a slider, and the camera updates instantly.

## Features

- **Preset dropdown** with built-in looks (Cinematic, StreetDrift, Aggressive, Smooth, Touge) plus your own custom presets
- **Live sliders** for distance, height, pitch, look-ahead, turn speed, smoothing, and FOV
- **Custom Rotation** toggle for the low-angle look (roll + side swing)
- **Look-around support** — left / right / behind keys and joystick look work like stock cameras
- **Horizon lock** so bumps don't tilt the view
- **Per-mode saves** — drift and racing presets are stored separately

## Requirements

- Assetto Corsa
- Content Shaders Patch (CSP) 0.1.76 or newer
- Content Manager

## Installation

1. Copy the `ChaseCamPlus` folder into:
   - `assettocorsa/apps/lua/ChaseCamPlus/`
   - `assettocorsa/extension/lua/chaser-camera/ChaseCamPlus/`
2. In Content Manager, enable `ChaseCamPlus` under **Content → Miscellaneous → Lua Apps**
3. Go to **Settings → Custom Shaders Patch → Chaser Camera**, tick **Active**, and set **Script** to `ChaseCamPlus`
4. Start a session — the camera will use the last saved preset

## Usage

Open the `ChaseCamPlus` app from the in-game sidebar:

- **Racing Mode** tick switches between drift and racing camera behaviour
- **Preset** dropdown picks a starting point; click **Load** to apply it
- **Sliders** change the camera live while you drag
- **Save As New** stores the current values as a custom preset
- **Reset Everything** wipes custom presets and returns to defaults

## Author

Made by additions.

## License

MIT — see [LICENSE](LICENSE).
