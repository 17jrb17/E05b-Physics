I completed the assignment by using the gravity constant which caused the balls to accelerate downward, then had them bounce both off the walls and off eachother using laws of physics via velocity and difference in velocity

You will then need to accelerate the balls according to the GRAVITY constant. You can call b.accelerate(x,y) on line 67. In the case of applying gravity, x will be 0 and y will be GRAVITY.

*main2.py*, is a little more complicated. You will need to apply all the lessons you learned in main1.py, but now we want the balls to bounce off the walls. First apply the GRAVITY constant from main1.py and accelerate the balls. Then, lines 39, 45, 51, and 57 will ask you to bounce (reverse the velocity) of the ball when it hits a wall. Think about what we discussed in class. I am applying some friction so they don't bounce forever. *I added a margin to the wall to handle fast-moving balls. SCREENWIDTH - MARGIN would represent the right side of the window, for example.*

*main3.py* is an opportunity for you to implement elastic collisions using the conservation of momentum. Assuming the animals are the same mass, they will just trade velocities. Insert your collision code at line 53. *For extra credit,* give each animal a random mass and use that to calculate the new velocities (remember that m1v1 = m2v2).

