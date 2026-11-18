# World map – StoryMapJS Zoomify tiles

Source: [World Map Parchment wallpaper (2560x1440)](https://www.flickr.com/photos/76491533@N00/5338919427) by Guy Sie, [CC BY-SA 2.0](https://creativecommons.org/licenses/by-sa/2.0/). This tile set was generated from the supplied 2048 × 1152 copy by downsampling and splitting it into JPEG tiles; no geographical content was changed. Reuse of the adapted tiles is under CC BY-SA 2.0. The historical map may contain outdated political boundaries.

## Hosting and StoryMapJS

Upload the contents of this folder (including `TileGroup0` as a folder, with the JPEG files inside it) to the root of a public GitHub repository, e.g. `world-map`. Enable GitHub Pages in Settings > Pages > Deploy from a branch > main > /(root). Copy the resulting site URL, for example `https://YOUR-USERNAME.github.io/world-map/` (replace with your actual address). Test that `ImageProperties.xml` and `TileGroup0/0-0-0.jpg` can be opened under that URL.

In StoryMapJS Options, choose Gigapixel and enter the published root URL as the Zoomify URL. Set width to 2048, height to 1152, and Treat As to Cartography. Place each slide's markers on the image manually. Save and preview. Do not use the GitHub repository URL or the XML file URL as the Zoomify base URL.

Knight Lab guidance: https://github.com/NUKnightLab/StoryMapJS/blob/master/GITHUB_HOSTING/GITHUB_HOSTING.md
