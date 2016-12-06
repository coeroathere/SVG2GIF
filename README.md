# SVG2GIF
Convert GreenSock SVG Timeline Animations to GIF

## Notes

* SVG2GIF renders SVG animations animated inline with GreenSock TimelineMax.
* You must add a class name to the SVG tag you want to convert.
* If you don't already, you should create a main timeline and add all and any of your timelines to it
* Ensure that ```repeat:0``` on your timelines so that it plays only once
* In the ```vars``` for the main parent timeline add in ```SVG2GIF:true``` - this notifies SVG2GIF that this is the timeline you wish to render.

### SVG2GIF uses the following libraries
* [HTML2Canvas](https://github.com/niklasvh/html2canvas)
* [Gif.js](https://jnordberg.github.io/gif.js/)
* GreenSock's [Draggable](http://greensock.com/draggable)