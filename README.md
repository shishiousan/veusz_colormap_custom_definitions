# Veusz Custom Colormaps

This repository contains custom colormap definitions for use with
[Veusz](https://veusz.github.io/), a scientific plotting software.
You can use awesome colormaps proposed by [Fabio Crameri](https://www.fabiocrameri.ch/colourmaps/)
in Veusz.
I hope this will help you to create high-quality scientific plots :)

## How to use?

### Load a colormap individually

1. Browse the `definitions` folder in this repository and download
   `.vsz` file you wish to use.
2. Open Veusz.
3. Go to `Edit` → `Custom Definitions` → `Colormaps`.
4. Load the downloaded `.vsz` file.
5. The new colormap will now be available for use in your plots.

### Load all available colormaps at once

If you want to load all available colormaps in Veusz at once, you can use
the provided `crameri_colormap_definitions.vsz` file in the `definitions` folder.

### Set as a default definition in Veusz

We can set the defalt custom definition in Veusz as follows:

1. Open Veusz
1. Go to `Edit` → `Preferences` → `New documents`.
1. Set `Custom Definitions` as you like.
   You can choose the `crameri_colormap_definitions.vsz` file or
   the individual `.vsz` files from the `definitions` folder.
