Info
----
Set alpha transparency of any background for any image within ImpactJS on the client side.

Usage
-----

- Copy transparent-image.js into your lib/game folder
- In your game's module, add an entry to the require section for the module 'game.transparent-image'
- Append #alpha:<hexcolor> to the path in any ig.Image or ig.AnimationSheet.
- 
- For example, rather than
loading 'media/player.png' you can change it to 'media/player.png#alpha:ff00ff' if the background colour is #ff00ff.

For more info [see this forum post](http://impactjs.com/forums/code/set-background-color-to-transparent-tilesets-images-etc)

Note: This is based off the image blender code by Ptg:

[Image Blender](http://impactjs.com/forums/code/image-blender-tint-blend-your-images-client-side-using-any-color)