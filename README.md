# Duck HuntAR

Thanks to [AR.js by Jerome Etienne](https://github.com/jeromeetienne/AR.js/blob/master/README.md)

Built using three.js libs from Jerome Etienne, but also the only AR.js example I've seen
using (albiet inconsistent) touch interaction with a three.js raycaster.

Retro Nintendo ducks fly out of a marker discovered by your webcam. On click/touch, they're hit.

If the webcam will loses the marker, ducks fly out of the last detected point. It was either
this or hide the ducks entirely when the marker disappears. Please comment if you have suggestions.

It seems like head-shots work consistently, where body shots only hit slow ducks. Fast ducks
require leading. It would be fun to dig into this and work it out, but I'm fairly satisfied
with this little toy for now.

[Give it a play!](https://jmidtlyng.github.io/duckHuntar/)

Make your own touch game using these patterns. And remember to set a small threshold
on Raycaster or you'll deal with a lot of bizarre intersections!

_As if it's not obvious_, I'm a rookie, but this AR stuff is a kick. Please message
me if you have any suggestions to improve this or introduce other AR projects.
