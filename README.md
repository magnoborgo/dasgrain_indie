# dasgrain_indie
Companion node to run Dasgrain inside Nuke Indie or Non commercial

How to use (Youtube video):<br>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=MvZW1XmKHEA" target="_blank"><img src="http://img.youtube.com/vi/MvZW1XmKHEA/mqdefault.jpg"
alt="Click to Watch the video" width="240" height="135" border="10" /></a><br>

Tested to work with DasGrain 1.8

## Instalation

Just drop the files on your .nuke Toolset folder.

VORONOI scatter:
If you are on Nuke Indie - you dont need to run "step 1B" you can use the original dasgrain voronoi scatter.

I've included a sample Voronoi map and the Voronoi map generator (regular Nuke only).<br>
** YOU NEED A SEQUENCE OF ANIMATED VORONOI MAPS ** otherwise your resampled grain will be static.

NEW (Jan 2023): Naive Voronoi Toolset added, just plug it into the Voronoi Map input (or prerender a sequence from it)
Its a bruteforce approach using only Nuke expression nodes, somewhat slow but works!
also added the "voronoi_naive_generator.nk" that can be used to create new Voronois toolsets.


## Thanks

Thanks and kudos to Fabian Holtz (the creator of Dasgrain), <br>
this is just some code adaptation to make it run within the limitations of Indie/Non-commercial.
<br>
http://www.nukepedia.com/gizmos/other/dasgrain


