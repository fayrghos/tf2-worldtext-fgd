# Point Worldtext for TF2
This FGD adds full support for `point_worldtext` entities to Team Fortress 2, including all functional Keyvalues and Inputs. Additional info about this entity can be found in its [VDC Article](https://developer.valvesoftware.com/wiki/Point_worldtext).

Only works in [Hammer++](https://developer.valvesoftware.com/wiki/Hammer%2B%2B).

> [!TIP]
> Even though this is still fully functional, i highly recommend that you use the [BAMF](https://bamf.tf) FGD instead.

## About
Since Hammer++ introduced `editor_text` entities to display 3D text in the editor, we can make use of them to make a basic preview of worldtexts. Some features are not visible in the editor, but still functional in-game.

## Limitations
Only supports the preview of Entity Message, Text Size, Color (excluding Alpha) and Logic Inputs. Features like Font, Text Spacing, Orientation, Rainbow and Color Alpha can only be visualized in-game.

## Setup
Place the FGD file in your `...\Team Fortress 2\bin` folder, open Hammer++ and go to Tools > Options > Game Configurations > Game Data Files > Add (This requires a Hammer restart).