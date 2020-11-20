                                  

# This is a private project and not endorsed by Scandit.
[![Screenshot](http://scandit3d.kuendig.io/screenshot-thumb.png)](http://scandit3d.kuendig.io/screenshot.png)

## How to use
Try it out at http://scandit3d.kuendig.io/. 
* Click once in the main area to start it (click a second time to go into fullscreen). 
* Once the game runs, you can add barcodes via the barcode generator. Selecting a new symbology or pressing enter automatically regenerates the barcode

## Bugs & Improvements
- [ ] Graphics
  - [x] Full screen
  - [ ] 🐞no message on lauch ("click to start")
  - [ ] start screen / animation
  - [ ] blood animation / overlay 
  - [x] take screenshots (ctrl/cmd+c)
  - [x] Add screensaver mode (autostart with rotating barcodes)
- [ ] Sound effects 
  - [ ] 🐞 gun sound doesn't play (commented out)
  - [ ] Background Music
- [ ] 3D Maze
  - [ ] better textures (not from Win95)
  - [x] default enable lightening (only on space currently)
  - [x] automatically loop barcodes (press 1-9 to set scans per symbology, 0 to disable)
- [ ] Status bar
  - [x] 🐞aspect ratio of status bar (Doom used [non-square pixels](https://doom.fandom.com/wiki/Aspect_ratio))
  - [x] 🐞using AmazDooMLeft for whole logo (instead of just left side)
- [ ] Source Quality
  - [ ] code cleanup
  - [ ] use npm / web bundler to build


## References
* The **barcode scanner** is obviously the amazing [Scandit Barcode Scanner for the Web](https://www.npmjs.com/package/scandit-sdk).

* The **barcode generator** used is [bwip-js](https://github.com/metafloor/bwip-js) which is a translation to native JavaScript of [Barcode Writer in Pure PostScript](https://github.com/bwipp/postscriptbarcode).

* The **3D maze** is based on the WebGL-port of the 3D Maze screensaver from Windows 95 available at [ibid-11962/Windows-95-3D-Maze-Screensaver](https://github.com/ibid-11962/Windows-95-3D-Maze-Screensaver). The matrix libraries it uses are from [esangel/WebGL](https://github.com/esangel/WebGL/tree/master/Common) and the maze generator can be found at [dstromberg2/maze-generator](https://github.com/dstromberg2/maze-generator) ([Tutorial](https://www.dstromberg.com/2013/07/tutorial-random-maze-generation-algorithm-in-javascript/)).

* The **status bar** uses the UI elements from [NES.css](https://github.com/nostalgic-css/NES.css) and the font is [Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P?selection.family=Press+Start+2P). The background is a modified version of `STBAR` from the [DOOM1.WAD](https://doomwiki.org/wiki/DOOM1.WAD).

* The **Scandit3D logo** uses the [AmazDooM font](https://www.dafont.com/amazdoom.font).

* The **gun sound** is `SPISTOL` from the [DOOM1.WAD](https://doomwiki.org/wiki/DOOM1.WAD).



