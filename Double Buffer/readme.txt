This is the readme for the BetterExample file. Please not it is in C++
as are all examples in the book for GameProgrammingPatterns

First Part:

So the first section of the code, is setting up a basic graphics system.
GameProgrammingPatterns calls this the Framebuffer

SECOND PART:

The next part is the code drawing a basic image using the Graphics System using
a series of draw commands. The problem is that these draw commands have gaps in
between them. In other words, a little time gap where one part hasn't loaded yet.
THis will be fixed with Double Buffer for the next part, we will see what a 
single buffer looks like

THIRD PART:

This is an example of a single buffer and this would lead to gaps in 
the drawing of the entire image. The image would sort of flicker.

FOURTH PART:

This is the fix, this is how the Class Scene should be setup to support 
Double Buffer. Now there are two buffers that take turns.