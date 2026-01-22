# Feedback on the Assignment
> This is feedback provided by Caleb Prouty's attempt with my interface, as well as my reaction. 

The interface makes sense. It is simplistic and able to tackle a few fun drawing exercises. 
Here is my attempt at a smiley face:
6,1 -> 4,1 -> 6,1 | 6,3 -> 4,3 -> 6,3 | 3,0 -> 2,1 -> 2,3 -> 3,4 -> 3,0 |
110
001 

010
001

110
001

110
011

100
011

110
011

011
000

010
001

010
011

011
100

011
000

There wasn’t much clarity on when a shape ended or the path the lines would follow. The program has a simplistic order of three bits.

Elizabeth’s reflection on this attempt: 

This interface could be expanded to accommodate four bits, allowing for a larger grid. Alternatively, you could have a two-bit data point to specify the quadrant a shape would fall in, a four-quadrant (7x7) zone. 
More clarity is required for the way the interface handles multiple sets of bits. Perhaps each shape could start with a few bits to tell the interface how many points will appear in the shape (allowing the inference to terminate while shapes are open, without retracing the lines) and/or how many shapes will appear in total.
