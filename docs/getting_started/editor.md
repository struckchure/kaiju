---
title: Getting Started | Kaiju Editor
---

# Getting started
The best way to get started with the engine is to get the editor up and running and create a project. I'd highly recommend watching through the Sudoku port series I've created on YouTube to learn the basics on how to use the engine/editor.

## Installing the editor
Kaiju is a portable program and doesn't require installation at this time. You can either [download a prebuilt version](https://github.com/KaijuEngine/kaiju/tags) or [build from source](../engine/build_from_source.md).

## Launching the editor
When you launch the editor, you will be presented with the project select window. In this window, you can either select an existing project from the list of previously opened projects, or create a new project.

### Selecting a project folder
If you clicked on the "Select project folder" button, an overlay will pop up, allowing you to browse your file system and select a folder. Navigate into the folder you wish to select, and then click on the "Select" button in the top right.

If the folder is empty, a new project will be created inside of that folder. if there are content inside of the folder, Then the engine will try to determine if it is a kaiju engine project. If it is, it will be opened. If it's not, you will be presented with a warning that the selected folder is not a kaiju project.

You will then be loaded into the main editor window.

### Selecting an existing project
Back on the project select window, there is a list of existing projects if you have previously opened any. By clicking on any of the labels with the project name you're interested in, it will immediately be opened. If that project no longer exists, you will get a warning, and the project will be removed from the list.

You will then be loaded into the main editor window.

The primary editor window gives you access to all other editor windows. The main window is also the primary viewport for your game stage (level/map/scene).
