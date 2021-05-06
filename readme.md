# Nuclear World Mod

Total Conversion Mod for OXCE.

#  Geoscape

## Adding New Terrains

- Edit the Ruleset `extraSprites.rul` on the `TEXTURE.dat` type.
    - The `width` and the `height` attributes must match the gif image
    - The height is default set to 96 so it supports 3 zoom levels, where the top one is the closest zoom

- Edit the Resource Globe pallete.gif specified on the `extraSprites.rul` ruleset
    - Each terrain is must have 32x32 pixels
    - There are 3 level of zoom so it is basically 32 pixels times 3 which give us 96 pixels of height
    - When adding a new terrain, increase the width by 32 pixels and add the new texture
    - When adding a new terrain, the id of the terrain will be the index starting from 0 of every 32 pixels
