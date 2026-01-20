# IMGD5010_Assignment1_BYOB_Elizabeth
The explanation behind a theoretical binary interface capable of completing simple drawing tasks.

Imagine a 7x7 grid, where the bottom left position is (0,0), and the top right is (7,7). Such as the one below:
<img width="304" height="305" alt="Grid" src="https://github.com/user-attachments/assets/15f93ab3-d9de-47a0-a3fa-bee4d514da76" />

In this grid, simple shapes can be drawn by first establishing points and making a line between them.

A point is encoded with three bits for its x coordinate and three for its y coordinate. 

```
For example: A point at (5,2) is stored as:
101
010
```

After passing several of these points together, a line will connect each, following the order in which they were passed into the program. To close a shape, the first point must be passed in twice. 

```
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
```

This would then be rendered onto the grid like this:

<img width="304" height="305" alt="Square on Grid" src="https://github.com/user-attachments/assets/badfdc82-05a0-4960-8cb0-8a52f28a6d10" />

What other shapes could you make with this simple program? 

