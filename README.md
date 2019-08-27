# MH Simplify Coordinates

**Algorithm based on Ramer–Douglas–Peucker Algorithm it simplify coordinates by kilometers**

> The starting curve is an ordered set of points or lines and the
> distance dimension  _ε_ > 0.
> 
> The algorithm Recursion  divides the line. Initially it is given all
> the points between the first and last point. It automatically marks
> the first and last point to be kept. It then finds the point that is
> furthest from the line segment with the first and last points as end
> points; this point is obviously furthest on the curve from the
> approximating line segment between the end points. If the point is
> closer than  _ε_  to the line segment, then any points not currently
> marked to be kept can be discarded without the simplified curve being
> worse than  _ε_.
> 
> If the point furthest from the line segment is greater than  _ε_  from
> the approximation then that point must be kept. The algorithm
> recursively calls itself with the first point and the furthest point
> and then with the furthest point and the last point, which includes
> the furthest point being marked as kept.
> 
> When the recursion is completed a new output curve can be generated
> consisting of all and only those points that have been marked as kept.

![enter image description here](https://upload.wikimedia.org/wikipedia/commons/thumb/3/30/Douglas-Peucker_animated.gif/330px-Douglas-Peucker_animated.gif)
# Implementation
	npm install mh-simplify-coordinates
	
    MHSimplify(coord,k)

# Result

simplify coordinates 


	
## Demo

https://mh-location.firebaseapp.com/

