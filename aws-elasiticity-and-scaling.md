AWS elasticity and Scaling:-

Scaling:-

It is the ability of the system to scale based upon a system.

There are two types of scaling is there 

Vertical scaling
Horizontal scaling
Vertical scaling is resizing the instance to a larger size.
t2 micro to t2 medium or t2.large like that

here we really adding more CPU and more memory for the system to increase in demand.

There is issue we facing at this time is that the instance need to be rebooted when it resized. This may result in cost increment.

Horizontal scaling:-
This will sort out some of the issues which is facing by the vertical scaling
Here instead of increaseing the size we add more ad more instance of the same size to handle that request.
We can use a load balancer here for equakky distribut the load to all of our horizontally scaled instances.


We have to take care some things in horizontal scaling that are 

1)Sessions
Dont intrupt the session that the customers are in.
AWS suggest to use sticky sessions, all sessions are distributed across all instances - no sessoins state is stored.
Sticky sessions allow the application load balancer to lock the user with a specific instance for a duration by generating
a cookie for our backend instance.

This will work even we scale in or scale out.

Elasticity:-

Automation
+
Horizontal scalling

Elasticity uses automation along with Horizontal scaling with demand.
Using the elastisity we can increase or decrease systems with demand. 

autoscaling+Hosizonatal scaling to match the capacity.
It increases the instances when the demand increases and scale down when the demand decreases.



