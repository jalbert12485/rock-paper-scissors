# rock-paper-scissors

During a class activity we were tasked with coding a rock paper scissors game using prompts and alerts.  In the first .html we have precisely that.  

The second .html generalizes this to the case where you can have more than three objects.  For this case, we would need that every object either beats or loses to every distinct object.  Furthermore, each object will have to beat the same number of objects as every other object.  This is only possible for an odd number of objects and I accomplished this by having object listed in a way that each one will beat the one before it and woulds then alternate through the list winning and losing.  This table for 5 objects is given as

0 beats 4 loses to 3 beats 2 and loses to 1.
1 beats 0 loses to 4 beats 3 and loses to 2.
2 beats 1 loses to 0 beats 4 and loses to 3.
3 beats 2 loses to 1 beats 0 and loses to 4.
4 beats 3 loses to 2 beats 1 and loses to 0.