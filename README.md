# Mac Window Layout Tiles

Keyboard friendly window layouts for MacOS.

``Layouts.alfredworkflow` provides a simple [Aldred](https://www.alfredapp.com/) worklow for positioning and sizing windows with keyboard shortcuts.

![Screen Shot 2020-06-12 at 1.29.34 PM](/Users/jknight/Screenshots/Screen Shot 2020-06-12 at 1.29.34 PM.png)

Based on http://projects.jga.me/layouts/ by Greg Allen ([@jgaui](http://twitter.com/jgaui)) [jga.me](http://jga.me) 

There are other apps that do similar things ([Moom](https://manytricks.com/moom/) , https://setapp.com/apps/mosaic) but this is free, keyboard shortcut only, and integrates with Alfred with simple clean code.

### Install

- Download `Layouts.alfredworkflow`
- Double click to open in Alfred and add as a workflow.
- Right click->enabled
- Done

### Keyboard Shortcuts

<img src="/Users/jknight/Code/layouts/layouts.png" alt="image-20200612140112726" style="zoom:50%;" />

### Configure

Configuration is via the Alfred workflow. There are no external files or dependencies. 

You can change the key mappings and window sizings and placements to define any keyboard shortcut for any size+position.

The x1,x2,y1,y2 convention from the original Layouts workflow is tricky to get right. Notes from the original layout convention have been added as a note in the workflow.

<img src="/Users/jknight/Code/layouts/configure.png" alt="Screen Shot 2020-06-12 at 1.33.55 PM" style="zoom:50%;" />

### TODO

- Currently works well to size windows but doesn't offer any way to navigate between windows - stil need to alt+tab (https://manytricks.com/witch/) to switch between windows. Would be nice to have tmux-like short cuts to move between windows (see https://i3wm.org/)  

