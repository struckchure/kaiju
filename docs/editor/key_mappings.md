---
title: Kaiju Editor | Key Mappings
---

## Key Mappings

| Shortcut       | Description                                |
|----------------|--------------------------------------------|
| `Alt + LMB`    | Rotate viewport                            |
| `MMB`	         | Pan viewport                               |
| `Space + LMB`  | Pan viewport                               |
| `Alt + RMB`    | Zoom viewport                              |
| `Scroll`       | Zoom viewport                              |
| `F`            | Focus the selection                        |
| `G`            | Grab/move selection                        |
| `R`            | Rotate selection                           |
| `S`            | Scale selection                            |
| `X`            | Locks transform mod to X axis              |
| `Y`            | Locks transform mod to Y axis              |
| `Z`            | Locks transform mod to Z axis              |
| `C`            | Toggle content panel                       |
| `H`            | Toggle hierarchy panel                     |
| `D`            | Toggle details panel                       |
| `Ctrl + S`     | Save the current stage                     |
| `Ctrl + T`     | Create template from selected              |
| `Ctrl + P`     | Parent selection [1](#note_1)              |
| `F5`           | Build and run a debug build [2](#note_2)   |
| `Ctrl + F5`    | Build and run a release build [3](#note_3) |

## Notes
<a id="note_1"></a>
[1] Parenting selection will parent all selected entities to the last selected entity. If there is only 1 entity selected when parenting, then it will be removed from it's parent and moved to the root.

<a id="note_2"></a>
[2] If a stage is currently open, that stage will be automatically loaded into by the debug instance that runs.

<a id="note_3"></a>
[3] This will start from the main entry point of the game, it will not load the current stage.
