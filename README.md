### Spritify Blender add-on

When an animation render is complete, all of the frames in the animation are
compiled into a single spritesheet usable for sprite-based video games.

There is a Spritify panel in Render Properties where you configure some of the
attributes of the sprite sheet as well as enable/disable the ability to
automatically generate a sprite sheet each time an animation render completes.

It can also generate an animated gif file, allowing you to easily showcase animations.

Originally developed for use in the [Ancient Beast](https://AncientBeast.com) game project.

### Requirements

This add-on requires that you have ImageMagick installed on your computer and the montage command is in your system path.
It also assumes that you're rendering a sequence of still frames. Video renders will not work.

### Installation

- User Preferences → Addons → Install Addon...
- Use the File Browser to find spritify.py on your hard drive
- Double-click or select the file and click Install Add on...
- Use the Addon browser to find and enable Spritify (from Render category)
