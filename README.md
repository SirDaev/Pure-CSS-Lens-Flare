# Pure CSS Lens Flare
This is a pure CSS3 lens flare effect. It spans the entire area of the browser, no matter the size.

![](http://davejudd.com/images/github/lens-flare/lens-flare-narrow.jpg) ![](http://davejudd.com/images/github/lens-flare/lens-flare-wide.jpg)

The circle effect is made with varying styles of radial gradients on DIVs with 50% border radii made to simulate circle shapes.

The circles use negative margins equal to their radius to put the center of the circle on the top corner of the DIV. This allows all the circles' center points to easily be placed along a straight line when each individual's top and left absolute positions are equal.

Since the positioning is based on percentages, the lens flare will always fill the screen from the top left corner to the bottom right corner.
