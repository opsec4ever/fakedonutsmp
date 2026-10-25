# Schem World

A browser-based 3D Minecraft schematic viewer.

## Run it

Open [the GitHub Pages site](https://opsec4ever.github.io/fakedonutsmp/) after enabling GitHub Pages for the `main` branch and `/(root)` in repository Settings → Pages. You can also open `index.html` through a local web server.

## Features

- Upload Sponge `.schem` files and supported legacy NBT schematic files.
- Instanced 3D blocks for better performance on larger builds.
- First-person controls and a simple blocky player model.
- Demo structure for testing without a schematic.
- Attempts to load block textures from the Minecraft asset mirror for version 26.3, with fallback materials when a texture is unavailable.

## Controls

- Click **Explore world** and click the 3D view to capture the mouse.
- **WASD** to move, **mouse** to look, **Space** to jump, **Shift** to move faster.
- **Esc** releases the mouse. **Tab** toggles the controls panel.

## Notes

This is an early browser viewer, not a complete Minecraft client. Texture availability depends on the asset mirror and version path; some blocks may use fallback colors. Complex block states, block-entity data, and every schematic variant are not yet supported. The player model is a basic blocky model rather than a Mojang-authenticated player skin.
