# PortaNote - Portable Note

I take a lot of notes... Like a lot, sometimes while I'm sitting in front of the PC or my phone, or even when I just randomly get a stupid idea about something. For me it's very disorganized, notes are all over the place, so that's why I created this static page prototype for what could be a note taking app. 

I created this site for practicing HTML and CSS flex-box and grid and a potential future app

![PortaNote](/porta.png)

[Nice overview of how to use 2x grid technique created by IBM (not the same as css grid).](https://carbondesignsystem.com/guidelines/2x-grid/overview/)

## New page - Notes

Added a concept for a page for viewing all notes. The whole page was created utilizing grid and with responsiveness in mind. 

Grid seems to be more intuitive for me when trying to setup a general layout for website, like: headers, body, footer, etc. 

Also tried to implement *2x grid technique*. The default font is 16px, so I made all containers be a `log2X` where X is the box size in pixels.

![Notes page on desktop](/images/site/note.png)
![Notes page on mobile](/images/site/note_m.png.png)

### My thoughts

I think this did not turn out really well, I would like to make folders for notes, with max-depth, as it would help with organization. With that it would be possible to make some cool transition animations. Like maybe when collapsing a folder it would smoothly fall out and push other folders downwards. 