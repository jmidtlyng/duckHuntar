# Duck HuntAR

Really fun project all thanks to [AR.js by Jerome Etienne](https://github.com/jeromeetienne/AR.js/blob/master/README.md)

Built using three.js libs from Jerome Etienne, but also the only AR.js example I've seen
using (albiet inconsistent) touch interaction with a three.js raycaster.

Retro Nintendo ducks fly out of a marker discovered by your webcam. On click/touch, they're hit.

Sometimes the webcam will lose the marker. Currently testing fixes, but my interim resolution is
to jiggle the webcam a bit to blur things. Somehow this helps pick up the marker.

It seems like head-shots work consistently, where body shots only hit slow ducks. Fast ducks
require leading. It would be fun to dig into this and work it out, but I'm fairly satisfied
with this little toy for now.

[Give it a play!](https://jmidtlyng.github.io/duckHuntar/)

Make your own touch game using these patterns. And remember to set a small threshold
on Raycaster or you'll deal with a lot of bizarre intersections!

_As if it's not obvious_, I'm a rookie, but this AR stuff is a kick. Please message
me if you have any suggestions to improve this or introduce other AR projects.
