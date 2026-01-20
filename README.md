# IMGD5010_Assignment1_BYOB_Elizabeth
The explanation behind a simple (theoretical) binary interface capable of completing simple drawing tasks.

Imagine a 7x7 grid, where the bottom left position is (0,0), and the top right is (7,7). Such as the one below:
In this grid, simple shapes can be drawn by first establishing points and making a line between them.
A point is encoded with three bits for its x coordinate and three for its y coordinate. 

For example: A point at (5,2) is stored as: 
101
010

After passing several of these points together, a line will connect each, following the order in which they were passed into the program. To close a shape, the first point must be passed in twice

For example: Drawing a square requires five points in order, such as [(1,1), (1,3), (3,3), (3,1), (1,1)]
001
001

001
011

011
011

011
001

001
001

This would then be rendered onto the grid like this:
