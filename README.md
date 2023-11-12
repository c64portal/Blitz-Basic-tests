# Blitz Basic Tests

Tests, PoCs and Snippets of Blitz Basic Amiga Code.
Feel free to use it as long as you credit me in any way.

__NOTICE:__
In the code repository you will find .bb2 files and ascii.bb2 files
first one is a tokenized Blitz Basic file, and second is an ascii version to be easily viewed in PC/Mac/Linux and online repository web view. 

# 1. HAM Anim Player

This is simple anim player (Proof of Concept) that plays 11 frames long HAM rendered raytrace animation like in old 90's Amiga demos.
The trick is to have a huge bitmap consisting of all animation frams from top to bottom. The program uses Amiga IFF file (obviously) but in the repo there's also png file for preview and to show how it works.
The code is rather simple, but I'll add some comments to it later so Blitz Basic beginers could get the idea.
The animation was rendered in Blender 2.79 with Cycles renderer. Composition of all frames to one file was done in Photoshop. Conversion to HAM mode was done with a tool called ham_converter 1.3.0 taken from website: http://mrsebe.bplaced.net/blog/wordpress/?page_id=374

here's a link to a YT video showing it in action:
https://www.youtube.com/watch?v=jZGufMhhJ-Y

# 2. Block Rotate Anim

This is a part of my 2017 Amiga demo called Allien Apparat. Again this is an animation but with two additional effects. 
One of them utilizes a Amiga Copper that creates a mirror effect. Second is a trick with colors that tries to mimic a fake lightsourcing by changing palette. It's also needed because without it you will notice that the box rotates only for 90 degrees. 

No comments in th code yet, but wlll add some soon to explain some details
The video of the whole demo can be seen here:
https://www.youtube.com/watch?v=KUqtLdrIIn4&t=30s

Source code to other demoparts from this demo will be released here ASAP.


# 3. Up Scroll and tiles

This is POC (proof-of-concept) code that is based on a discussion on EAB (English Amiga Board) forum. I cant find the link ATM.
The upscroll partially works. Partially because it starts to break after few screens scrolled. It's due to some miscalculations but I dont have the time to fix it now. The idea is there and after some fixes it should work.
The gfx is done by me for this test purpose. Some of the tiles were later used for my C64 pic called: "Planet, Rock, Lobster", here: https://csdb.dk/release/?id=219613
You can use the tiles if you want If you reuse the tiles please credit me and let me know. TIA.
The code is for AGA, as it was planned for a shooter game that I planned but stopped developing. I will restart the development of this game maybe some day. ;)


