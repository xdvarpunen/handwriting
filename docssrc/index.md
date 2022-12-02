# Home

This doc includes information related to handwriting as tool.

## Journey

I am building handwriting recognition from scratch. While working on it looking around and finding the answer what is the challenge in making working handwriting recognition.

### Implementations

First implementation is about having lines passing through circles in a defined size of a box. If all circles are passed then handwriting is recognized as that symbol. This worked with three different numbers (0,1,2), but after that recognition required order due to overlapping lines. 

Second implementation used used snap to grid functionality. Instead of having recognition areas that need to pass through the user is helped to always get certain locations set. This way order is simple to define and recognizing numbers from 0 to 9 was done. This implementation does not scale further due to lacking amount of points. [Handwriting recognition demo that supports through snap to grid functionality 0-9 number recognition.](https://xdvarpunen.github.io/handwriting-0-9-snap-to-grid/)

Third implementation is ongoing. More written here when get it done.