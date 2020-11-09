# Poorman's guide to calculating the cycloid disk shapes

[//]: # (This is a comment)

* There are some good references
  * [video on cycloids](https://www.youtube.com/watch?v=SWIx3GgqrAg)
  * [cycloid disk design in fusion](https://www.youtube.com/watch?v=jQ6LQBFZXmU)

* Compute the formulas using [the calculator](http://www.otvinta.com/cycloid.html), you will need the following parameters:
  * outer diameter
  * pin diameter
  * pin number
  * excentricity
* Graph the firmulas and save as svg using an online [graphing calulator](http://fooplot.com/)
  * use the parametric plot option
  * paste the formulas for x and y from the previous steps (change `u` to `s` where appropriate)
  * set s from 0 to 1 (plus 1 step),  set the step to 0.001 (or less)
  * in the display section untick grid, axes, tick marks and numbers

* If your CAD is unhappy with svgs [convert to dxf](https://cloudconvert.com/svg-to-dxf)
> after all Alibre is unable to assimilate splines generated with external applications, bummer