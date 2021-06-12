# combined-corner-and-edge-detection
Implementation of the paper "A COMBINED CORNER AND EDGE DETECTOR"

The Moravec
operator suffers from a number of problems; these are
listed below, together with appropriate corrective
measures:

1. The response is anisotropic because only a
discrete set of shifts at every 45 degrees is
considered - all possible small shifts can be covered by
performing an analytic expansion about the shift origin.

2. The response is noisy because the window is
binary and rectangular - use a smooth circular
window, for example a Gaussian.

3. The operator responds too readily to edges
because only the minimum of E is taken into
account - reformulate the corner measure to make use of
the variation of E with the direction of shift.



![alt text](demo.gif)
