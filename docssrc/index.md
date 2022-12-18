# Home

This doc includes information related to handwriting as tool.

## Journey

I am building handwriting recognition from scratch. While working on it looking around and finding the answer what is the challenge in making working handwriting recognition.

### Implementations

First implementation is about having lines passing through circles in a defined size of a box. If all circles are passed then handwriting is recognized as that symbol. This worked with three different numbers (0,1,2), but after that recognition required order due to overlapping lines. On first implementation I am using just HTML file.

Second implementation uses snap to grid functionality. Instead of having recognition areas that need to pass through the user is helped to always get certain locations set. This way order is simple to define and recognizing numbers from 0 to 9 was done. This implementation does not scale further due to lacking amount of points. [Handwriting recognition demo that supports through snap to grid functionality 0-9 number recognition.](https://xdvarpunen.github.io/handwriting-0-9-snap-to-grid/) On second implementation I am still using just HTML file.

Third implementation is handwriting on canvas. No restricting areas beside canvas. Line strokes are recognized to be certain type. Intersecting lines are grouped together. Stroke groups are recognized as letters. There was trouble with differentiating line corner and line curve. Third implementation recognized roughly 5 or more letters. [Demo incoming](https://github.com/xdvarpunen/handwriting-canvas). On third implementation I moved to TypeScript due to size of the application.

The third implementation gave idea to create [tool](https://github.com/xdvarpunen/stroke-order) that could facilitate creating rules and features for the handwriting recognition. Tool is built using Python and Tkinter.

Fourth implementation is ongoing. In this implementation line curve and line corner is solved. More written here when get it done.

