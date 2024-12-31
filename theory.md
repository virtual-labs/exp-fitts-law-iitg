### Fitts’s Law - Modeling Target Movement Time in HCI

Fitts's law is a model of speed-accuracy tradeoffs used in human–computer interaction and ergonomics. It predicts time required to acquire a target on screen as a function of the distance to the target and the size of the target. Fitts's law is used to model the act of pointing, either by physically touching an object with a hand,finger or virtually or by pointing to an object on a computer monitor using a pointing device. It was proposed by Paul Fitts in 1954. (Reference: http://en.wikipedia.org/wiki/Fitts%27s_law)

Mathematically it can be written as

MT = a + b log 2 ( 2A / W )

MT : Movement time (average) taken to complete the movement or point the target.

a : Start / Stop time of the device (y intercept)

b : Inherent speed of the device (slope of line)

W : Width of the target measured along the axis of motion, which corresponds to accuracy

A : Distance from the starting point to the center of the target

The term log 2 ( 2A / W ) is called the index of difficulty (ID). It describes the difficulty of the motor tasks. 1/b is also called the index of performance (IP) and measures the information capacity of the human motor system.

Thus  MT= a+b ID = a + ID / IP


### Physical interpretation and application of Fitts’s Law

1. Big targets at close distance are acquired faster than small targets at long range.

2. Target acquiring difficulty increases by one unit for each doubling of distance and halving of width of target.

3. Fitts's Law can be used  to evaluate  alternative interaction methods in Graphical User Interface (GUI).

4. It can also be used to predict the performance of operators in user-adaptive systems.

      (Reference: http://www.cs.umd.edu/class/fall2002/cmsc838s/tichi/fitts.html)
      

### Use of Fitts’s Law to radial menus

Supposing a designer is confronted with choosing between a linear array type of menu and a round menu in which control buttons are placed radially. Fitts law helps the designer in finding out which would be functionally more efficient and error free given the use context.

Also the advantage of radial menus can be demonstrated with Fitts’s Law. Since menus pop up at the current cursor position and all items are at same distance from the centre, they can be approximately reached at the same speed in addition pointing is enhanced as the radial slices are of infinite size and thus can be more quickly and reliably selected. (Reference : http://www.betriebsraum.de/blog/2009/12/11/extremely-efficient-menu-selection-marking-menus-for-the-flash-platform/)

It should be noted that while Fitts’s law applies to the physical movement of the pointing devices, other human factors like search-time and decision-time for item selection, must also be taken into account when evaluating the overall performance of menu systems.

