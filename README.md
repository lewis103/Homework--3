Homework--3
===========
I have increased the speed of my "Perfect Number" Algorithm. 

What I did/how it improved
==========================

My algorithm runs in two parts (first one complies the code using "n" as an integer, you must then pass in a 
number using "perfect(900)"

I would run my timed test when passing in a number (I used 900 for all test). My code with no changes ran 
at the following speed:         
625 loops, best of 3: 216 µs per loop

I then simply ran it in cython and it ran at the following speed:
625 loops, best of 3: 132 µs per loop

Next I used cpdef with cython and it ran at the following speed:
625 loops, best of 3: 133 µs per loop (seems like it should have been faster??)

Finally I found that using xrange shoul be faster than using range so I implemented that and it 
ran at the following speed:
625 loops, best of 3: 122 µs per loop

Overall achievement 
===================
Overall I was able to increse the speed of my code by 1.77, (almost twice as fast) this is an improvement, however
I am not too excited about it as we were able to hit MUCH higher numbers than that in class.



