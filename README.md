Html Video Background
================================================

It seems pretty easy to load and run video as background in muted. Actually, it seems like nice idea, took me like 10 mimutes to do it, but another 10 minutes to try to scale it to fit with background on resize ..er... fail -without JS-. next version will try to workout CSS3 to fill up the background then

================================================

#Code

<video autoplay loop muted>
 <source src="Waterfall.mp4" type="video/mp4">
</video>

Just that much. on page load, it does autoplay, repeat forever with loop, and no sound with muted.

#CSS
The fontbox is the issue bc it need to see thru, so set it with rbga(0,0,0,0.6). 
The width and height of the video r set to 100%, just that the browser auto play it in its own propotion. Bugger! 

##next version
No glue, I did this on inspiration as someone seems showing interest on video background. Propably will come back for full screen playing one. Still not sure can do without JS.