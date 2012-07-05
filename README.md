Info
----
Set alpha transparency to background for any image within ImpactJS on the client side.

Usage
-----

- Copy transparent-image.js into your lib/game folder
- In your game's module, add an entry to the require section for the module 'game.transparent-image'
- Append #alpha:<hexcolor> to the path in any ig.Image or ig.AnimationSheet.
- 
- For example, rather than
loading 'media/player.png' you can change it to 'media/player.png#alpha:FF0000' if the background colour is #FF0000.

For more info [see this forum post](http://www.impactjs.com/forums)