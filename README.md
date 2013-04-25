Homework--3
===========
I have increased the speed of my "Perfect Number" Algorithm. 

What I did/how it improved
==========================

My algorithm runs in two parts (first one complies the code using "n" as an integer, you must then pass in a 
number using "perfect(900)"

I would run my timed test when passing in a number (I used 900 for all tests). My code with no changes ran 
at the following speed:         
625 loops, best of 3: 381 µs per loop

I then simply ran it in cython and it ran at the following speed:
625 loops, best of 3: 140 µs per loop

Next I used cpdef with cython and it ran at the following speed:
625 loops, best of 3: 141 µs per loop (seems like it should have been faster??)

I found that using xrange shoul be faster than using range so I implemented that and it 
ran at the following speed:
625 loops, best of 3: 134 µs per loop

Finally used long before my perfect variable and this gave me alot of progess, running at 
the following speed:
625 loops, best of 3: 58.5 µs per loop

Overall achievement 
===================
Overall I was able to increse the speed of my code by 6.513,this is an improvement and I was pretty happy with
it, however I know there is more I can do since we were able to hit MUCH higher numbers than that in class.



