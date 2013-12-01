Html Video Background
=====================

Used this in the prototype for Toptal project. Playing Video in a supported browser is very easy. 
Infact, all functions, events are provided. Trying to work with QT on mobile. Next version then.

================================================

#Code

<video id="video1" autoplay loop muted>
 <source src="surf.mp4" type="video/mp4">
</video>

Just that much. on page load, it does autoplay, repeat forever with loop, and no sound with muted.

#CSS
The fontbox is the issue bc it need to see thru, so set it with rbga(0,0,0,0.6). 
body set overflow:hidden prevent browser showing scrollbars.

##this version
added FullAndControl.html, with very simple Javascript to display video in full screen with control box. 
Gave up on Css3 to do samething without JS. bugger!
