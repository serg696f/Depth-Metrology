# Depth-Metrology

This repo holds chart design files and papers for the work in Depth Metrology TS 8527

## This is an Endoscope 3D chart - simplest version

This 3D chart is based on a 'Cut Siemens Start' as described in the paper ["Introducing the cut-out star target to evaluate the resolution performance of 3D structured-light systems"](https://github.com/serg696f/Depth-Metrology/blob/main/Papers/Evaluation%20methodology%20for%20structured%20light%203D%20based%20depth%20maps.pdf) by Tom Osborne, Vikas Ramachandra, Kalin Atanassov, Sergio Goma.

The chart uses the Cut Siemens Start and adds a cone in the back to provide a measurment of the accuray of depth - the height of the cone is equal to the radius of the Siemens Star, therfore, each point in the openings will be at a depth eqal to the distance to the centre of the star.

Here is how a model of the chart looks like (the Siemens star is 3.5mm diameter, the height of the cone is 1.75mm - this chart was designed to be used for measuring an endoscope). To manufacture, the cone is a rolled piece of sheet metal while the target on top is a stainlss steel stencil - all 0.1mm thinkness):

### [View Endoscope 3D chart](https://3dviewer.net/#model=https://github.com/serg696f/Depth-Metrology/blob/main/3d-chart-endoscope.stl)

---

## This is the 3D-Chart-Print

This chart is a variation of the simple chart - optimized for 3D printing

3d-chart-print is a two part chart:
- top is a stencil 0.1mm that is laser cut
- bottom is a 3D printed part

the radius of the cone is 1.75mm, making the diameter of the projected chart 3.5mm - same idea a before, any point inside the chart can be on the top surface, which is the reference distance while any point at the same radius in the opened area is at a depth equal with its radius (provided the chart is flat to the camera).

The flatness of the chart is ensured by adjusting the chart until the outer ring has all points at the same depth.

### [View 3D-Chart-Print](https://3dviewer.net/#model=https://github.com/serg696f/Depth-Metrology/blob/main/3d-chart-print.stp)

---

## This is the 3D-Chart-Print-Complex

This chart is designed to project two surfaces - depth patterns - one in increasing depth, one in decreasing depth. At any radius, the openings compared to the closed areas are at 2*R depth (provided the chart is flat to the camera).

The flatness of the chart is ensured by adjusting the chart until the outer ring has all points at the same depth.

### [View 3D-Chart-Print-Complex](https://3dviewer.net/#model=https://github.com/serg696f/Depth-Metrology/blob/main/3d-chart-print-complex.stp)

---

## This is the Depth3D-Sergio-Chart

This chart is designed to project two surfaces and be 3D printed - depth patterns - one in increasing depth, one in decreasing depth. At any radius, the openings compared to the closed areas are at 2*R depth (provided the chart is flat to the camera).

The flatness of the chart is ensured by adjusting the chart until the suqare at the front is at the same depth.

### [View Depth3D-Sergio-Chart](https://3dviewer.net/#model=https://github.com/serg696f/Depth-Metrology/blob/main/Depth3D-Sergio-chart.stl)

---
