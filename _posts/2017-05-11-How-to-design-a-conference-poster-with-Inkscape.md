## Useful links

[Scientific Poster
Design](http://hsp.berkeley.edu/sites/default/files/ScientificPosters.pdf)

[Designing conference posters](http://colinpurrington.com/tips/poster-design)

[COLORBREWER](http://colorbrewer2.org/#type=sequential&scheme=Blues&n=3)

[Making a Math Conference Poster with Inkscape](http://blog.felixbreuer.net/2010/10/24/poster.html)

**Be carefull with layers and how objects use them**, if you export to `.pdf` and can not see everything that you have in your `.svg`, there is something wrong with the layers and you have to "remix" them until it works

## Inkscape

1. Inkscape does not work on Mac with an external screen

2. Inkscape: tools on the left edge, colors and opacity at the bottom edge, tool properties at the right edge, menus at the top

3. At the top left menu, under ```view``` select ```grid``` and then at the right bottom click on the snap to grid button and all the objects you create after that will snap to the `grid`, you can do it similar with `guidelines`

3. you set up a guideline layer by pulling from the `rullers` at the edge of Inkscape and you can double click on them to change their properties, lock the layer when set-up

4. make a square that fits inside your poster and inside define a color gradient that will help to guide your reader from start to finish, grading icon is located at the bottom left of Inkscape

4. create layers and `lock` them(example: guideline layer) by clicking on the lock icon in the layer list and change their opacity aka transperancy option in the same toolbox

   - you need to imagine layers as physical layers and think which part of the object should be on top or below of the other 

5. group drawed objects together, so you can move them with CTRL+G or on the right bottom menu, you have group and ungroup.

5. save as .pdf, small logos can be raster as it will not be seen their are foggy



## Keyboard shortcut

- `CTRL+left click` is for even scaling

- `SHIFT+leftclick` if for around center scaling

- `ALT+leftclick` is for moving accross object parts


## Tools location

- in the bottom left corner you have color transparancy or opacity and color palett

- on the right edge you have layers, alligment, stroke and fill buttons for objects and text button

## Tool features

- alligment allows you to order a group ob objects to the left of the first selected object(you hold shift and click the objects), you still have to choose if you will allign the objects by first chosen, last chosen etc. in the menu.

- you can make rounder corners to squares with the button below the top arrow on the left or by double clicking on the square and manually setting the top left properties of ```Rx    ``` and ```Ry   ```
- to remove the fill and change the edge line of an object (example: square), use the fill and stroke setting on the right side of the window

## Random tips

- you can make hinges by rounding the end edges of a square and layering them in the proper physical order

- if you can not move an imported picture it mean that the layer is locked

- on Mac Windows key equals CTRL, be carefull with resize and copy paste

- if you want to have an even circle you need to hold CTRL while you are drawing the circle

   - you also have "cake" setting on top left where you can make "Pacman" like design and such, for example: you can draw an even circle, then make a cake out of it and remove the fill and put arrows at the end of the stroke to have a bended arrow
   
- double click the color in the bottom left to access the color settings   
   
- **HEX COLORS** Since you want to assign a specific hex color, enter it into the RGBA box (don't include the #). Note that this is RGBA, not RGB--the extra two characters on the end represent opacity (ff being solid; 00 being fully transparent). So to assign #666666, you would want to enter #666666ff

- you grab and move objects by clicking on the "solid part of the graphical object

- to copy an object, you need to use `CTRL+D` that will duplicate it exactly how it is assembled through the layers, do not forget to group the object before

## Add plots from Matlab

- look which font is MATLAB using and export everything in `.eps` format in the simplest form, with no text and you latter add text  inside Inkscape
