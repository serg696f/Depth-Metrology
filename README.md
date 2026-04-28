# Depth-Metrology

This repo holds chart design files and papers for the work in Depth Metrology TS 8527

## This is an Endoscope 3D chart - simplest version

This 3D chart is based on a 'Cut Siemens Start' as described in the paper ["Introducing the cut-out star target to evaluate the resolution performance of 3D structured-light systems"](https://github.com/serg696f/Depth-Metrology/blob/main/Papers/Evaluation%20methodology%20for%20structured%20light%203D%20based%20depth%20maps.pdf) by Tom Osborne, Vikas Ramachandra, Kalin Atanassov, Sergio Goma.

The chart uses the Cut Siemens Start and adds a cone in the back to provide a measurment of the accuray of depth - the height of the cone is equal to the radius of the Siemens Star, therfore, each point in the openings will be at a depth eqal to the distance to the centre of the star.

Here is how a model of the chart looks like (the Siemens start is 3.5mm diameter, the height of the cone is 1.75mm - this chart was designed to be used for measuring an endoscope):

```stl
solid ASCII
  facet normal -5.574642e-16 -1.000000e+00 1.022306e-31
    outer loop
      vertex   3.209238e-16 0.000000e+00 1.750000e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -5.574642e-17 1.650000e+00
    endloop
  endfacet
  facet normal 0.000000e+00 -1.000000e+00 -3.378571e-17
    outer loop
      vertex   1.000000e-01 -5.574642e-17 1.650000e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.506731e-15 -7.071068e-01 -7.071068e-01
    outer loop
      vertex   0.000000e+00 -1.237437e+00 1.237437e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.166726e+00 1.166726e+00
    endloop
  endfacet
  facet normal 0.000000e+00 -7.071068e-01 -7.071068e-01
    outer loop
      vertex   1.000000e-01 -1.166726e+00 1.166726e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.348128e-15 -7.071068e-01 7.071068e-01
    outer loop
      vertex   0.000000e+00 1.237437e+00 1.237437e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.166726e+00 1.166726e+00
    endloop
  endfacet
  facet normal 0.000000e+00 -7.071068e-01 7.071068e-01
    outer loop
      vertex   1.000000e-01 1.166726e+00 1.166726e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 3.172066e-16 3.378215e-16 -1.000000e+00
    outer loop
      vertex   0.000000e+00 -1.750000e+00 -5.911877e-16
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.650000e+00 -5.256849e-16
    endloop
  endfacet
  facet normal 0.000000e+00 3.185969e-16 -1.000000e+00
    outer loop
      vertex   1.000000e-01 -1.650000e+00 -5.256849e-16
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal -3.172066e-16 -6.911667e-16 1.000000e+00
    outer loop
      vertex   0.000000e+00 1.750000e+00 1.209542e-15
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.650000e+00 1.172146e-15
    endloop
  endfacet
  facet normal 0.000000e+00 -7.103914e-16 1.000000e+00
    outer loop
      vertex   1.000000e-01 1.650000e+00 1.172146e-15
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 3.806479e-15 7.071068e-01 -7.071068e-01
    outer loop
      vertex   0.000000e+00 -1.237437e+00 -1.237437e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.166726e+00 -1.166726e+00
    endloop
  endfacet
  facet normal 0.000000e+00 7.071068e-01 -7.071068e-01
    outer loop
      vertex   1.000000e-01 -1.166726e+00 -1.166726e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal -2.616954e-15 7.071068e-01 7.071068e-01
    outer loop
      vertex   0.000000e+00 1.237437e+00 -1.237437e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.166726e+00 -1.166726e+00
    endloop
  endfacet
  facet normal 0.000000e+00 7.071068e-01 7.071068e-01
    outer loop
      vertex   1.000000e-01 1.166726e+00 -1.166726e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.853671e-17 -1.685630e-17
    outer loop
      vertex   1.000000e-01 -1.524401e+00 -6.314277e-01
      vertex   1.000000e-01 -1.498436e+00 -6.907886e-01
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.784522e-17 -1.835625e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.498436e+00 -6.907886e-01
      vertex   1.000000e-01 -1.470161e+00 -7.490843e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -3.709538e-17 -1.982789e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.470161e+00 -7.490843e-01
      vertex   1.000000e-01 -1.439618e+00 -8.062250e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -3.628834e-17 -2.126897e-17
    outer loop
      vertex   1.000000e-01 -1.439618e+00 -8.062250e-01
      vertex   1.000000e-01 -1.406856e+00 -8.621226e-01
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.542535e-17 -2.267724e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.406856e+00 -8.621226e-01
      vertex   1.000000e-01 -1.371925e+00 -9.166909e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -3.450773e-17 -2.405055e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.371925e+00 -9.166909e-01
      vertex   1.000000e-01 -1.334878e+00 -9.698457e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -3.353691e-17 -2.538678e-17
    outer loop
      vertex   1.000000e-01 -1.334878e+00 -9.698457e-01
      vertex   1.000000e-01 -1.295773e+00 -1.021505e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.251437e-17 -2.668386e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.295773e+00 -1.021505e+00
      vertex   1.000000e-01 -1.254670e+00 -1.071589e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.144170e-17 -2.793979e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.254670e+00 -1.071589e+00
      vertex   1.000000e-01 -1.211632e+00 -1.120021e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.032055e-17 -2.915265e-17
    outer loop
      vertex   1.000000e-01 -1.211632e+00 -1.120021e+00
      vertex   1.000000e-01 -1.166726e+00 -1.166726e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.533036e-17 -3.916877e-17
    outer loop
      vertex   1.000000e-01 -6.314277e-01 -1.524401e+00
      vertex   1.000000e-01 -5.710931e-01 -1.548016e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.378078e-17 -3.974044e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -5.710931e-01 -1.548016e+00
      vertex   1.000000e-01 -5.098780e-01 -1.569243e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.220996e-17 -4.025083e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -5.098780e-01 -1.569243e+00
      vertex   1.000000e-01 -4.478767e-01 -1.588051e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.062030e-17 -4.069916e-17
    outer loop
      vertex   1.000000e-01 -4.478767e-01 -1.588051e+00
      vertex   1.000000e-01 -3.851849e-01 -1.604410e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -9.014274e-18 -4.108474e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -3.851849e-01 -1.604410e+00
      vertex   1.000000e-01 -3.218990e-01 -1.618296e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -7.394345e-18 -4.140696e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -3.218990e-01 -1.618296e+00
      vertex   1.000000e-01 -2.581169e-01 -1.629686e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -5.763015e-18 -4.166534e-17
    outer loop
      vertex   1.000000e-01 -2.581169e-01 -1.629686e+00
      vertex   1.000000e-01 -1.939367e-01 -1.638563e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -4.122798e-18 -4.185947e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.939367e-01 -1.638563e+00
      vertex   1.000000e-01 -1.294575e-01 -1.644914e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.476224e-18 -4.198906e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.294575e-01 -1.644914e+00
      vertex   1.000000e-01 -6.477870e-02 -1.648728e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -8.258326e-19 -4.205390e-17
    outer loop
      vertex   1.000000e-01 -6.477870e-02 -1.648728e+00
      vertex   1.000000e-01 1.844151e-15 -1.650000e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.685630e-17 -3.853671e-17
    outer loop
      vertex   1.000000e-01 6.314277e-01 -1.524401e+00
      vertex   1.000000e-01 6.907886e-01 -1.498436e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.835625e-17 -3.784522e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 6.907886e-01 -1.498436e+00
      vertex   1.000000e-01 7.490843e-01 -1.470161e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.982789e-17 -3.709538e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 7.490843e-01 -1.470161e+00
      vertex   1.000000e-01 8.062250e-01 -1.439618e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.126897e-17 -3.628834e-17
    outer loop
      vertex   1.000000e-01 8.062250e-01 -1.439618e+00
      vertex   1.000000e-01 8.621226e-01 -1.406856e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.267724e-17 -3.542535e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 8.621226e-01 -1.406856e+00
      vertex   1.000000e-01 9.166909e-01 -1.371925e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.405055e-17 -3.450773e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 9.166909e-01 -1.371925e+00
      vertex   1.000000e-01 9.698457e-01 -1.334878e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.538678e-17 -3.353691e-17
    outer loop
      vertex   1.000000e-01 9.698457e-01 -1.334878e+00
      vertex   1.000000e-01 1.021505e+00 -1.295773e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.668386e-17 -3.251437e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.021505e+00 -1.295773e+00
      vertex   1.000000e-01 1.071589e+00 -1.254670e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.793979e-17 -3.144170e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.071589e+00 -1.254670e+00
      vertex   1.000000e-01 1.120021e+00 -1.211632e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.915265e-17 -3.032055e-17
    outer loop
      vertex   1.000000e-01 1.120021e+00 -1.211632e+00
      vertex   1.000000e-01 1.166726e+00 -1.166726e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.916877e-17 1.533036e-17
    outer loop
      vertex   1.000000e-01 -1.524401e+00 6.314277e-01
      vertex   1.000000e-01 -1.548016e+00 5.710931e-01
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.974044e-17 1.378078e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.548016e+00 5.710931e-01
      vertex   1.000000e-01 -1.569243e+00 5.098780e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -4.025083e-17 1.220996e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.569243e+00 5.098780e-01
      vertex   1.000000e-01 -1.588051e+00 4.478767e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -4.069916e-17 1.062030e-17
    outer loop
      vertex   1.000000e-01 -1.588051e+00 4.478767e-01
      vertex   1.000000e-01 -1.604410e+00 3.851849e-01
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -4.108474e-17 9.014274e-18
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.604410e+00 3.851849e-01
      vertex   1.000000e-01 -1.618296e+00 3.218990e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -4.140696e-17 7.394345e-18
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.618296e+00 3.218990e-01
      vertex   1.000000e-01 -1.629686e+00 2.581169e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -4.166534e-17 5.763015e-18
    outer loop
      vertex   1.000000e-01 -1.629686e+00 2.581169e-01
      vertex   1.000000e-01 -1.638563e+00 1.939367e-01
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -4.185947e-17 4.122798e-18
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.638563e+00 1.939367e-01
      vertex   1.000000e-01 -1.644914e+00 1.294575e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -4.198906e-17 2.476224e-18
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.644914e+00 1.294575e-01
      vertex   1.000000e-01 -1.648728e+00 6.477870e-02
    endloop
  endfacet
  facet normal 1.000000e+00 -4.205390e-17 8.258326e-19
    outer loop
      vertex   1.000000e-01 -1.648728e+00 6.477870e-02
      vertex   1.000000e-01 -1.650000e+00 -5.256849e-16
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.916877e-17 -1.533036e-17
    outer loop
      vertex   1.000000e-01 1.524401e+00 -6.314277e-01
      vertex   1.000000e-01 1.548016e+00 -5.710931e-01
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.974044e-17 -1.378078e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.548016e+00 -5.710931e-01
      vertex   1.000000e-01 1.569243e+00 -5.098780e-01
    endloop
  endfacet
  facet normal 1.000000e+00 4.025083e-17 -1.220996e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.569243e+00 -5.098780e-01
      vertex   1.000000e-01 1.588051e+00 -4.478767e-01
    endloop
  endfacet
  facet normal 1.000000e+00 4.069916e-17 -1.062030e-17
    outer loop
      vertex   1.000000e-01 1.588051e+00 -4.478767e-01
      vertex   1.000000e-01 1.604410e+00 -3.851849e-01
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 4.108474e-17 -9.014274e-18
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.604410e+00 -3.851849e-01
      vertex   1.000000e-01 1.618296e+00 -3.218990e-01
    endloop
  endfacet
  facet normal 1.000000e+00 4.140696e-17 -7.394345e-18
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.618296e+00 -3.218990e-01
      vertex   1.000000e-01 1.629686e+00 -2.581169e-01
    endloop
  endfacet
  facet normal 1.000000e+00 4.166534e-17 -5.763015e-18
    outer loop
      vertex   1.000000e-01 1.629686e+00 -2.581169e-01
      vertex   1.000000e-01 1.638563e+00 -1.939367e-01
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 4.185947e-17 -4.122798e-18
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.638563e+00 -1.939367e-01
      vertex   1.000000e-01 1.644914e+00 -1.294575e-01
    endloop
  endfacet
  facet normal 1.000000e+00 4.198906e-17 -2.476224e-18
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.644914e+00 -1.294575e-01
      vertex   1.000000e-01 1.648728e+00 -6.477870e-02
    endloop
  endfacet
  facet normal 1.000000e+00 4.205390e-17 -8.258326e-19
    outer loop
      vertex   1.000000e-01 1.648728e+00 -6.477870e-02
      vertex   1.000000e-01 1.650000e+00 1.172146e-15
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.685630e-17 3.853671e-17
    outer loop
      vertex   1.000000e-01 -6.314277e-01 1.524401e+00
      vertex   1.000000e-01 -6.907886e-01 1.498436e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.835625e-17 3.784522e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -6.907886e-01 1.498436e+00
      vertex   1.000000e-01 -7.490843e-01 1.470161e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.982789e-17 3.709538e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -7.490843e-01 1.470161e+00
      vertex   1.000000e-01 -8.062250e-01 1.439618e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.126897e-17 3.628834e-17
    outer loop
      vertex   1.000000e-01 -8.062250e-01 1.439618e+00
      vertex   1.000000e-01 -8.621226e-01 1.406856e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.267724e-17 3.542535e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -8.621226e-01 1.406856e+00
      vertex   1.000000e-01 -9.166909e-01 1.371925e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.405055e-17 3.450773e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -9.166909e-01 1.371925e+00
      vertex   1.000000e-01 -9.698457e-01 1.334878e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.538678e-17 3.353691e-17
    outer loop
      vertex   1.000000e-01 -9.698457e-01 1.334878e+00
      vertex   1.000000e-01 -1.021505e+00 1.295773e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.668386e-17 3.251437e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.021505e+00 1.295773e+00
      vertex   1.000000e-01 -1.071589e+00 1.254670e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.793979e-17 3.144170e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.071589e+00 1.254670e+00
      vertex   1.000000e-01 -1.120021e+00 1.211632e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.915265e-17 3.032055e-17
    outer loop
      vertex   1.000000e-01 -1.120021e+00 1.211632e+00
      vertex   1.000000e-01 -1.166726e+00 1.166726e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.853671e-17 1.685630e-17
    outer loop
      vertex   1.000000e-01 1.524401e+00 6.314277e-01
      vertex   1.000000e-01 1.498436e+00 6.907886e-01
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.784522e-17 1.835625e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.498436e+00 6.907886e-01
      vertex   1.000000e-01 1.470161e+00 7.490843e-01
    endloop
  endfacet
  facet normal 1.000000e+00 3.709538e-17 1.982789e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.470161e+00 7.490843e-01
      vertex   1.000000e-01 1.439618e+00 8.062250e-01
    endloop
  endfacet
  facet normal 1.000000e+00 3.628834e-17 2.126897e-17
    outer loop
      vertex   1.000000e-01 1.439618e+00 8.062250e-01
      vertex   1.000000e-01 1.406856e+00 8.621226e-01
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.542535e-17 2.267724e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.406856e+00 8.621226e-01
      vertex   1.000000e-01 1.371925e+00 9.166909e-01
    endloop
  endfacet
  facet normal 1.000000e+00 3.450773e-17 2.405055e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.371925e+00 9.166909e-01
      vertex   1.000000e-01 1.334878e+00 9.698457e-01
    endloop
  endfacet
  facet normal 1.000000e+00 3.353691e-17 2.538678e-17
    outer loop
      vertex   1.000000e-01 1.334878e+00 9.698457e-01
      vertex   1.000000e-01 1.295773e+00 1.021505e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.251437e-17 2.668386e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.295773e+00 1.021505e+00
      vertex   1.000000e-01 1.254670e+00 1.071589e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.144170e-17 2.793979e-17
    outer loop
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.254670e+00 1.071589e+00
      vertex   1.000000e-01 1.211632e+00 1.120021e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.032055e-17 2.915265e-17
    outer loop
      vertex   1.000000e-01 1.211632e+00 1.120021e+00
      vertex   1.000000e-01 1.166726e+00 1.166726e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal -7.930164e-16 1.000000e+00 1.069606e-15
    outer loop
      vertex   0.000000e+00 1.871810e-15 -1.750000e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.844151e-15 -1.650000e+00
    endloop
  endfacet
  facet normal 0.000000e+00 1.000000e+00 1.117667e-15
    outer loop
      vertex   1.000000e-01 1.844151e-15 -1.650000e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -3.800502e-32 -4.278985e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   3.209238e-16 0.000000e+00 1.750000e+00
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 7.886603e-18 -4.016098e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   3.209238e-16 0.000000e+00 1.750000e+00
      vertex   3.209238e-16 -6.870468e-02 1.748651e+00
    endloop
  endfacet
  facet normal -1.000000e+00 2.115260e-17 -3.586823e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   3.209238e-16 -6.870468e-02 1.748651e+00
      vertex   3.209238e-16 -1.373034e-01 1.744605e+00
    endloop
  endfacet
  facet normal -1.000000e+00 0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   0.000000e+00 1.750000e+00 1.209542e-15
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -1.461363e-14 4.384088e-15
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   0.000000e+00 1.750000e+00 1.209542e-15
      vertex   3.209238e-16 1.748651e+00 6.870468e-02
    endloop
  endfacet
  facet normal -1.000000e+00 -3.586823e-16 -2.115260e-17
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   3.209238e-16 1.748651e+00 6.870468e-02
      vertex   3.209238e-16 1.744605e+00 1.373034e-01
    endloop
  endfacet
  facet normal -1.000000e+00 0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   0.000000e+00 1.871810e-15 -1.750000e+00
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 4.384088e-15 1.461363e-14
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   0.000000e+00 1.871810e-15 -1.750000e+00
      vertex   3.209238e-16 6.870468e-02 -1.748651e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -2.115260e-17 3.586823e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 6.870468e-02 -1.748651e+00
      vertex   3.209238e-16 1.373034e-01 -1.744605e+00
    endloop
  endfacet
  facet normal -1.000000e+00 0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   0.000000e+00 -1.750000e+00 -5.911877e-16
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 1.461363e-14 -4.384088e-15
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   0.000000e+00 -1.750000e+00 -5.911877e-16
      vertex   3.209238e-16 -1.748651e+00 -6.870468e-02
    endloop
  endfacet
  facet normal -1.000000e+00 3.586823e-16 2.115260e-17
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 -1.748651e+00 -6.870468e-02
      vertex   3.209238e-16 -1.744605e+00 -1.373034e-01
    endloop
  endfacet
  facet normal -1.000000e+00 -3.302940e-15 -3.302940e-15
    outer loop
      vertex   3.209238e-16 -1.285064e+00 1.187901e+00
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   0.000000e+00 -1.237437e+00 1.237437e+00
    endloop
  endfacet
  facet normal -1.000000e+00 0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 -1.237437e+00 1.237437e+00
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   0.000000e+00 -6.696960e-01 1.616789e+00
    endloop
  endfacet
  facet normal -1.000000e+00 0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 -1.237437e+00 1.237437e+00
      vertex   0.000000e+00 -6.696960e-01 1.616789e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 1.347912e-16 -1.197785e-16
    outer loop
      vertex   3.209238e-16 -1.285064e+00 1.187901e+00
      vertex   3.209238e-16 -1.330710e+00 1.136534e+00
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 1.402482e-16 -1.150987e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   3.209238e-16 -1.330710e+00 1.136534e+00
      vertex   3.209238e-16 -1.374305e+00 1.083414e+00
    endloop
  endfacet
  facet normal -1.000000e+00 1.460057e-16 -1.105234e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   3.209238e-16 -1.374305e+00 1.083414e+00
      vertex   3.209238e-16 -1.415780e+00 1.028624e+00
    endloop
  endfacet
  facet normal -1.000000e+00 1.521174e-16 -1.060199e-16
    outer loop
      vertex   3.209238e-16 -1.415780e+00 1.028624e+00
      vertex   3.209238e-16 -1.455072e+00 9.722479e-01
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 1.586450e-16 -1.015553e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   3.209238e-16 -1.455072e+00 9.722479e-01
      vertex   3.209238e-16 -1.492120e+00 9.143725e-01
    endloop
  endfacet
  facet normal -1.000000e+00 1.656610e-16 -9.709560e-17
    outer loop
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   3.209238e-16 -1.492120e+00 9.143725e-01
      vertex   3.209238e-16 -1.526868e+00 8.550872e-01
    endloop
  endfacet
  facet normal -1.000000e+00 1.732517e-16 -9.260496e-17
    outer loop
      vertex   3.209238e-16 -1.526868e+00 8.550872e-01
      vertex   3.209238e-16 -1.559261e+00 7.944834e-01
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 1.815207e-16 -8.804387e-17
    outer loop
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   3.209238e-16 -1.559261e+00 7.944834e-01
      vertex   3.209238e-16 -1.589251e+00 7.326545e-01
    endloop
  endfacet
  facet normal -1.000000e+00 5.540890e-15 2.673749e-15
    outer loop
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   3.209238e-16 -1.589251e+00 7.326545e-01
      vertex   0.000000e+00 -1.616789e+00 6.696960e-01
    endloop
  endfacet
  facet normal -1.000000e+00 -0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   0.000000e+00 -1.750000e+00 -5.911877e-16
      vertex   0.000000e+00 -1.616789e+00 6.696960e-01
    endloop
  endfacet
  facet normal -1.000000e+00 -0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 -1.616789e+00 6.696960e-01
      vertex   0.000000e+00 -1.750000e+00 -5.911877e-16
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 3.247888e-16 3.198891e-17
    outer loop
      vertex   3.209238e-16 -1.744605e+00 -1.373034e-01
      vertex   3.209238e-16 -1.737870e+00 -2.056904e-01
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 2.972971e-16 4.112118e-17
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 -1.737870e+00 -2.056904e-01
      vertex   3.209238e-16 -1.728455e+00 -2.737603e-01
    endloop
  endfacet
  facet normal -1.000000e+00 2.745047e-16 4.902032e-17
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 -1.728455e+00 -2.737603e-01
      vertex   3.209238e-16 -1.716374e+00 -3.414081e-01
    endloop
  endfacet
  facet normal -1.000000e+00 2.552615e-16 5.600613e-17
    outer loop
      vertex   3.209238e-16 -1.716374e+00 -3.414081e-01
      vertex   3.209238e-16 -1.701647e+00 -4.085294e-01
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 2.387623e-16 6.230418e-17
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 -1.701647e+00 -4.085294e-01
      vertex   3.209238e-16 -1.684297e+00 -4.750208e-01
    endloop
  endfacet
  facet normal -1.000000e+00 2.244263e-16 6.807899e-17
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 -1.684297e+00 -4.750208e-01
      vertex   3.209238e-16 -1.664349e+00 -5.407797e-01
    endloop
  endfacet
  facet normal -1.000000e+00 2.118240e-16 7.345416e-17
    outer loop
      vertex   3.209238e-16 -1.664349e+00 -5.407797e-01
      vertex   3.209238e-16 -1.641835e+00 -6.057048e-01
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -5.738519e-15 2.769115e-15
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 -1.641835e+00 -6.057048e-01
      vertex   0.000000e+00 -1.616789e+00 -6.696960e-01
    endloop
  endfacet
  facet normal -1.000000e+00 0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   0.000000e+00 -1.616789e+00 -6.696960e-01
      vertex   0.000000e+00 -1.237437e+00 -1.237437e+00
    endloop
  endfacet
  facet normal -1.000000e+00 0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 -1.237437e+00 -1.237437e+00
      vertex   0.000000e+00 -1.616789e+00 -6.696960e-01
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 3.302940e-15 -3.302940e-15
    outer loop
      vertex   0.000000e+00 -1.237437e+00 -1.237437e+00
      vertex   3.209238e-16 -1.187901e+00 -1.285064e+00
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 1.197785e-16 1.347912e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 -1.187901e+00 -1.285064e+00
      vertex   3.209238e-16 -1.136534e+00 -1.330710e+00
    endloop
  endfacet
  facet normal -1.000000e+00 1.150987e-16 1.402482e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 -1.136534e+00 -1.330710e+00
      vertex   3.209238e-16 -1.083414e+00 -1.374305e+00
    endloop
  endfacet
  facet normal -1.000000e+00 1.105234e-16 1.460057e-16
    outer loop
      vertex   3.209238e-16 -1.083414e+00 -1.374305e+00
      vertex   3.209238e-16 -1.028624e+00 -1.415780e+00
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 1.060199e-16 1.521174e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 -1.028624e+00 -1.415780e+00
      vertex   3.209238e-16 -9.722479e-01 -1.455072e+00
    endloop
  endfacet
  facet normal -1.000000e+00 1.015553e-16 1.586450e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 -9.722479e-01 -1.455072e+00
      vertex   3.209238e-16 -9.143725e-01 -1.492120e+00
    endloop
  endfacet
  facet normal -1.000000e+00 9.709560e-17 1.656610e-16
    outer loop
      vertex   3.209238e-16 -9.143725e-01 -1.492120e+00
      vertex   3.209238e-16 -8.550872e-01 -1.526868e+00
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 9.260496e-17 1.732517e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 -8.550872e-01 -1.526868e+00
      vertex   3.209238e-16 -7.944834e-01 -1.559261e+00
    endloop
  endfacet
  facet normal -1.000000e+00 8.804387e-17 1.815207e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 -7.944834e-01 -1.559261e+00
      vertex   3.209238e-16 -7.326545e-01 -1.589251e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -2.673749e-15 5.540890e-15
    outer loop
      vertex   3.209238e-16 -7.326545e-01 -1.589251e+00
      vertex   0.000000e+00 -6.696960e-01 -1.616789e+00
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   0.000000e+00 -6.696960e-01 -1.616789e+00
      vertex   0.000000e+00 1.871810e-15 -1.750000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 -6.696960e-01 -1.616789e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   0.000000e+00 1.871810e-15 -1.750000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -3.198891e-17 3.247888e-16
    outer loop
      vertex   3.209238e-16 1.373034e-01 -1.744605e+00
      vertex   3.209238e-16 2.056904e-01 -1.737870e+00
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -4.112118e-17 2.972971e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 2.056904e-01 -1.737870e+00
      vertex   3.209238e-16 2.737603e-01 -1.728455e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -4.902032e-17 2.745047e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 2.737603e-01 -1.728455e+00
      vertex   3.209238e-16 3.414081e-01 -1.716374e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -5.600613e-17 2.552615e-16
    outer loop
      vertex   3.209238e-16 3.414081e-01 -1.716374e+00
      vertex   3.209238e-16 4.085294e-01 -1.701647e+00
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -6.230418e-17 2.387623e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 4.085294e-01 -1.701647e+00
      vertex   3.209238e-16 4.750208e-01 -1.684297e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -6.807899e-17 2.244263e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 4.750208e-01 -1.684297e+00
      vertex   3.209238e-16 5.407797e-01 -1.664349e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -7.345416e-17 2.118240e-16
    outer loop
      vertex   3.209238e-16 5.407797e-01 -1.664349e+00
      vertex   3.209238e-16 6.057048e-01 -1.641835e+00
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -2.769115e-15 -5.738519e-15
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 6.057048e-01 -1.641835e+00
      vertex   0.000000e+00 6.696960e-01 -1.616789e+00
    endloop
  endfacet
  facet normal -1.000000e+00 0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   0.000000e+00 6.696960e-01 -1.616789e+00
      vertex   0.000000e+00 1.237437e+00 -1.237437e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 1.237437e+00 -1.237437e+00
      vertex   0.000000e+00 6.696960e-01 -1.616789e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 3.302940e-15 3.302940e-15
    outer loop
      vertex   0.000000e+00 1.237437e+00 -1.237437e+00
      vertex   3.209238e-16 1.285064e+00 -1.187901e+00
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -1.347912e-16 1.197785e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 1.285064e+00 -1.187901e+00
      vertex   3.209238e-16 1.330710e+00 -1.136534e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -1.402482e-16 1.150987e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 1.330710e+00 -1.136534e+00
      vertex   3.209238e-16 1.374305e+00 -1.083414e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -1.460057e-16 1.105234e-16
    outer loop
      vertex   3.209238e-16 1.374305e+00 -1.083414e+00
      vertex   3.209238e-16 1.415780e+00 -1.028624e+00
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -1.521174e-16 1.060199e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 1.415780e+00 -1.028624e+00
      vertex   3.209238e-16 1.455072e+00 -9.722479e-01
    endloop
  endfacet
  facet normal -1.000000e+00 -1.586450e-16 1.015553e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 1.455072e+00 -9.722479e-01
      vertex   3.209238e-16 1.492120e+00 -9.143725e-01
    endloop
  endfacet
  facet normal -1.000000e+00 -1.656610e-16 9.709560e-17
    outer loop
      vertex   3.209238e-16 1.492120e+00 -9.143725e-01
      vertex   3.209238e-16 1.526868e+00 -8.550872e-01
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -1.732517e-16 9.260496e-17
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 1.526868e+00 -8.550872e-01
      vertex   3.209238e-16 1.559261e+00 -7.944834e-01
    endloop
  endfacet
  facet normal -1.000000e+00 -1.815207e-16 8.804387e-17
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   3.209238e-16 1.559261e+00 -7.944834e-01
      vertex   3.209238e-16 1.589251e+00 -7.326545e-01
    endloop
  endfacet
  facet normal -1.000000e+00 -5.540890e-15 -2.673749e-15
    outer loop
      vertex   3.209238e-16 1.589251e+00 -7.326545e-01
      vertex   0.000000e+00 1.616789e+00 -6.696960e-01
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
      vertex   0.000000e+00 1.616789e+00 -6.696960e-01
      vertex   0.000000e+00 1.750000e+00 1.209542e-15
    endloop
  endfacet
  facet normal -1.000000e+00 0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 1.616789e+00 -6.696960e-01
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   0.000000e+00 1.750000e+00 1.209542e-15
    endloop
  endfacet
  facet normal -1.000000e+00 -3.247888e-16 -3.198891e-17
    outer loop
      vertex   3.209238e-16 1.744605e+00 1.373034e-01
      vertex   3.209238e-16 1.737870e+00 2.056904e-01
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -2.972971e-16 -4.112118e-17
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   3.209238e-16 1.737870e+00 2.056904e-01
      vertex   3.209238e-16 1.728455e+00 2.737603e-01
    endloop
  endfacet
  facet normal -1.000000e+00 -2.745047e-16 -4.902032e-17
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   3.209238e-16 1.728455e+00 2.737603e-01
      vertex   3.209238e-16 1.716374e+00 3.414081e-01
    endloop
  endfacet
  facet normal -1.000000e+00 -2.552615e-16 -5.600613e-17
    outer loop
      vertex   3.209238e-16 1.716374e+00 3.414081e-01
      vertex   3.209238e-16 1.701647e+00 4.085294e-01
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -2.387623e-16 -6.230418e-17
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   3.209238e-16 1.701647e+00 4.085294e-01
      vertex   3.209238e-16 1.684297e+00 4.750208e-01
    endloop
  endfacet
  facet normal -1.000000e+00 -2.244263e-16 -6.807899e-17
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   3.209238e-16 1.684297e+00 4.750208e-01
      vertex   3.209238e-16 1.664349e+00 5.407797e-01
    endloop
  endfacet
  facet normal -1.000000e+00 -2.118240e-16 -7.345416e-17
    outer loop
      vertex   3.209238e-16 1.664349e+00 5.407797e-01
      vertex   3.209238e-16 1.641835e+00 6.057048e-01
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 5.738519e-15 -2.769115e-15
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   3.209238e-16 1.641835e+00 6.057048e-01
      vertex   0.000000e+00 1.616789e+00 6.696960e-01
    endloop
  endfacet
  facet normal -1.000000e+00 0.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   0.000000e+00 1.616789e+00 6.696960e-01
      vertex   0.000000e+00 1.237437e+00 1.237437e+00
    endloop
  endfacet
  facet normal -1.000000e+00 0.000000e+00 -0.000000e+00
    outer loop
      vertex   0.000000e+00 1.237437e+00 1.237437e+00
      vertex   0.000000e+00 1.616789e+00 6.696960e-01
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -3.302940e-15 3.302940e-15
    outer loop
      vertex   0.000000e+00 1.237437e+00 1.237437e+00
      vertex   3.209238e-16 1.187901e+00 1.285064e+00
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -1.197785e-16 -1.347912e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   3.209238e-16 1.187901e+00 1.285064e+00
      vertex   3.209238e-16 1.136534e+00 1.330710e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -1.150987e-16 -1.402482e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   3.209238e-16 1.136534e+00 1.330710e+00
      vertex   3.209238e-16 1.083414e+00 1.374305e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -1.105234e-16 -1.460057e-16
    outer loop
      vertex   3.209238e-16 1.083414e+00 1.374305e+00
      vertex   3.209238e-16 1.028624e+00 1.415780e+00
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -1.060199e-16 -1.521174e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   3.209238e-16 1.028624e+00 1.415780e+00
      vertex   3.209238e-16 9.722479e-01 1.455072e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -1.015553e-16 -1.586450e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   3.209238e-16 9.722479e-01 1.455072e+00
      vertex   3.209238e-16 9.143725e-01 1.492120e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -9.709560e-17 -1.656610e-16
    outer loop
      vertex   3.209238e-16 9.143725e-01 1.492120e+00
      vertex   3.209238e-16 8.550872e-01 1.526868e+00
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -9.260496e-17 -1.732517e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   3.209238e-16 8.550872e-01 1.526868e+00
      vertex   3.209238e-16 7.944834e-01 1.559261e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -8.804387e-17 -1.815207e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   3.209238e-16 7.944834e-01 1.559261e+00
      vertex   3.209238e-16 7.326545e-01 1.589251e+00
    endloop
  endfacet
  facet normal -1.000000e+00 2.673749e-15 -5.540890e-15
    outer loop
      vertex   3.209238e-16 7.326545e-01 1.589251e+00
      vertex   0.000000e+00 6.696960e-01 1.616789e+00
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -3.393317e-16 7.032071e-16
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   0.000000e+00 6.696960e-01 1.616789e+00
      vertex   3.209238e-16 0.000000e+00 1.750000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 -4.427307e-16 1.833851e-16
    outer loop
      vertex   0.000000e+00 6.696960e-01 1.616789e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   3.209238e-16 0.000000e+00 1.750000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 3.198891e-17 -3.247888e-16
    outer loop
      vertex   3.209238e-16 -1.373034e-01 1.744605e+00
      vertex   3.209238e-16 -2.056904e-01 1.737870e+00
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 4.112118e-17 -2.972971e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   3.209238e-16 -2.056904e-01 1.737870e+00
      vertex   3.209238e-16 -2.737603e-01 1.728455e+00
    endloop
  endfacet
  facet normal -1.000000e+00 4.902032e-17 -2.745047e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   3.209238e-16 -2.737603e-01 1.728455e+00
      vertex   3.209238e-16 -3.414081e-01 1.716374e+00
    endloop
  endfacet
  facet normal -1.000000e+00 5.600613e-17 -2.552615e-16
    outer loop
      vertex   3.209238e-16 -3.414081e-01 1.716374e+00
      vertex   3.209238e-16 -4.085294e-01 1.701647e+00
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 6.230418e-17 -2.387623e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   3.209238e-16 -4.085294e-01 1.701647e+00
      vertex   3.209238e-16 -4.750208e-01 1.684297e+00
    endloop
  endfacet
  facet normal -1.000000e+00 6.807899e-17 -2.244263e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   3.209238e-16 -4.750208e-01 1.684297e+00
      vertex   3.209238e-16 -5.407797e-01 1.664349e+00
    endloop
  endfacet
  facet normal -1.000000e+00 7.345416e-17 -2.118240e-16
    outer loop
      vertex   3.209238e-16 -5.407797e-01 1.664349e+00
      vertex   3.209238e-16 -6.057048e-01 1.641835e+00
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal -1.000000e+00 2.769115e-15 5.738519e-15
    outer loop
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
      vertex   3.209238e-16 -6.057048e-01 1.641835e+00
      vertex   0.000000e+00 -6.696960e-01 1.616789e+00
    endloop
  endfacet
  facet normal -8.961086e-15 9.238795e-01 3.826834e-01
    outer loop
      vertex   0.000000e+00 -6.696960e-01 1.616789e+00
      vertex   1.000000e-01 -6.314277e-01 1.524401e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal -0.000000e+00 9.238795e-01 3.826834e-01
    outer loop
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -6.314277e-01 1.524401e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -4.823549e-15 -4.906539e-16
    outer loop
      vertex   1.000000e-01 -5.574642e-17 1.650000e+00
      vertex   1.000000e-01 2.879647e-02 1.649749e+00
      vertex   1.000000e-01 0.000000e+00 1.791421e+00
    endloop
  endfacet
  facet normal 1.000000e+00 4.281872e-18 4.906539e-16
    outer loop
      vertex   1.000000e-01 0.000000e+00 1.791421e+00
      vertex   1.000000e-01 2.879647e-02 1.649749e+00
      vertex   1.000000e-01 3.126461e-02 1.791149e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -0.000000e+00 0.000000e+00
    outer loop
      vertex   1.000000e-01 0.000000e+00 1.791421e+00
      vertex   1.000000e-01 3.126461e-02 1.791149e+00
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -8.534915e-16 2.972477e-15
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 3.126461e-02 1.791149e+00
      vertex   1.000000e-01 1.031614e-01 1.788449e+00
    endloop
  endfacet
  facet normal 1.000000e+00 6.014994e-18 7.725649e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.031614e-01 1.788449e+00
      vertex   1.000000e-01 1.748919e-01 1.782864e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -4.818900e-15 4.205390e-17
    outer loop
      vertex   1.000000e-01 -5.574642e-17 1.650000e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 2.879647e-02 1.649749e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.015932e-15 -7.724853e-17
    outer loop
      vertex   1.000000e-01 2.879647e-02 1.649749e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 9.753610e-02 1.647115e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.361214e-18 4.192853e-17
    outer loop
      vertex   1.000000e-01 9.753610e-02 1.647115e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.661062e-01 1.641618e+00
    endloop
  endfacet
  facet normal 1.000000e+00 5.105954e-18 4.175199e-17
    outer loop
      vertex   1.000000e-01 1.661062e-01 1.641618e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 2.343876e-01 1.633267e+00
    endloop
  endfacet
  facet normal 1.000000e+00 6.841819e-18 4.150288e-17
    outer loop
      vertex   1.000000e-01 2.343876e-01 1.633267e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 3.022616e-01 1.622078e+00
    endloop
  endfacet
  facet normal 1.000000e+00 8.565792e-18 4.118163e-17
    outer loop
      vertex   1.000000e-01 3.022616e-01 1.622078e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 3.696102e-01 1.608070e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.027488e-17 4.078880e-17
    outer loop
      vertex   1.000000e-01 3.696102e-01 1.608070e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 4.363164e-01 1.591266e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.196610e-17 4.032508e-17
    outer loop
      vertex   1.000000e-01 4.363164e-01 1.591266e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 5.022642e-01 1.571697e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.363653e-17 3.979126e-17
    outer loop
      vertex   1.000000e-01 5.022642e-01 1.571697e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 5.673390e-01 1.549396e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.528325e-17 3.918829e-17
    outer loop
      vertex   1.000000e-01 5.673390e-01 1.549396e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 6.314277e-01 1.524401e+00
    endloop
  endfacet
  facet normal 1.000000e+00 8.279059e-18 6.991591e-17
    outer loop
      vertex   1.000000e-01 1.748919e-01 1.782864e+00
      vertex   1.000000e-01 2.463402e-01 1.774403e+00
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.019396e-17 6.396835e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 2.463402e-01 1.774403e+00
      vertex   1.000000e-01 3.173912e-01 1.763081e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.185743e-17 5.904148e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 3.173912e-01 1.763081e+00
      vertex   1.000000e-01 3.879302e-01 1.748914e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.333578e-17 5.488433e-17
    outer loop
      vertex   1.000000e-01 3.879302e-01 1.748914e+00
      vertex   1.000000e-01 4.578435e-01 1.731927e+00
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.467581e-17 5.132145e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 4.578435e-01 1.731927e+00
      vertex   1.000000e-01 5.270183e-01 1.712145e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.591169e-17 4.822650e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 5.270183e-01 1.712145e+00
      vertex   1.000000e-01 5.953430e-01 1.689603e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.706918e-17 4.550609e-17
    outer loop
      vertex   1.000000e-01 5.953430e-01 1.689603e+00
      vertex   1.000000e-01 6.627074e-01 1.664335e+00
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.816827e-17 4.308963e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 6.627074e-01 1.664335e+00
      vertex   1.000000e-01 7.290029e-01 1.636382e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.922493e-17 4.092277e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 7.290029e-01 1.636382e+00
      vertex   1.000000e-01 7.941225e-01 1.605790e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.025231e-17 3.896284e-17
    outer loop
      vertex   1.000000e-01 7.941225e-01 1.605790e+00
      vertex   1.000000e-01 8.579611e-01 1.572607e+00
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.126156e-17 3.717587e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 8.579611e-01 1.572607e+00
      vertex   1.000000e-01 9.204159e-01 1.536888e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.226242e-17 3.553437e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 9.204159e-01 1.536888e+00
      vertex   1.000000e-01 9.813860e-01 1.498690e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.326371e-17 3.401578e-17
    outer loop
      vertex   1.000000e-01 9.813860e-01 1.498690e+00
      vertex   1.000000e-01 1.040773e+00 1.458075e+00
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.427365e-17 3.260136e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.040773e+00 1.458075e+00
      vertex   1.000000e-01 1.098481e+00 1.415107e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.530015e-17 3.127527e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.098481e+00 1.415107e+00
      vertex   1.000000e-01 1.154418e+00 1.369858e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.635111e-17 3.002396e-17
    outer loop
      vertex   1.000000e-01 1.154418e+00 1.369858e+00
      vertex   1.000000e-01 1.208492e+00 1.322398e+00
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.743461e-17 2.883566e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.208492e+00 1.322398e+00
      vertex   1.000000e-01 1.260618e+00 1.272806e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.855917e-17 2.769993e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.260618e+00 1.272806e+00
      vertex   1.000000e-01 1.310709e+00 1.221160e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.973397e-17 2.660740e-17
    outer loop
      vertex   1.000000e-01 1.310709e+00 1.221160e+00
      vertex   1.000000e-01 1.358687e+00 1.167545e+00
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.096917e-17 2.554939e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.358687e+00 1.167545e+00
      vertex   1.000000e-01 1.404473e+00 1.112046e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.227619e-17 2.451775e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.404473e+00 1.112046e+00
      vertex   1.000000e-01 1.447993e+00 1.054754e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.366810e-17 2.350456e-17
    outer loop
      vertex   1.000000e-01 1.447993e+00 1.054754e+00
      vertex   1.000000e-01 1.489178e+00 9.957603e-01
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.516015e-17 2.250193e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.489178e+00 9.957603e-01
      vertex   1.000000e-01 1.527961e+00 9.351605e-01
    endloop
  endfacet
  facet normal 1.000000e+00 3.677031e-17 2.150174e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.527961e+00 9.351605e-01
      vertex   1.000000e-01 1.564279e+00 8.730523e-01
    endloop
  endfacet
  facet normal 1.000000e+00 3.852014e-17 2.049534e-17
    outer loop
      vertex   1.000000e-01 1.564279e+00 8.730523e-01
      vertex   1.000000e-01 1.598075e+00 8.095359e-01
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 4.043581e-17 1.947326e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.598075e+00 8.095359e-01
      vertex   1.000000e-01 1.629292e+00 7.447136e-01
    endloop
  endfacet
  facet normal 1.000000e+00 4.254959e-17 1.842472e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.629292e+00 7.447136e-01
      vertex   1.000000e-01 1.657881e+00 6.786902e-01
    endloop
  endfacet
  facet normal 1.000000e+00 4.490180e-17 1.733713e-17
    outer loop
      vertex   1.000000e-01 1.657881e+00 6.786902e-01
      vertex   1.000000e-01 1.683796e+00 6.115720e-01
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 4.754368e-17 1.619528e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.683796e+00 6.115720e-01
      vertex   1.000000e-01 1.706996e+00 5.434674e-01
    endloop
  endfacet
  facet normal 1.000000e+00 5.054139e-17 1.498027e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.706996e+00 5.434674e-01
      vertex   1.000000e-01 1.727441e+00 4.744861e-01
    endloop
  endfacet
  facet normal 1.000000e+00 5.398212e-17 1.366793e-17
    outer loop
      vertex   1.000000e-01 1.727441e+00 4.744861e-01
      vertex   1.000000e-01 1.745101e+00 4.047395e-01
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 5.798312e-17 1.222641e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.745101e+00 4.047395e-01
      vertex   1.000000e-01 1.759945e+00 3.343400e-01
    endloop
  endfacet
  facet normal 1.000000e+00 6.270615e-17 1.061245e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.759945e+00 3.343400e-01
      vertex   1.000000e-01 1.771951e+00 2.634013e-01
    endloop
  endfacet
  facet normal 1.000000e+00 6.838087e-17 8.765235e-18
    outer loop
      vertex   1.000000e-01 1.771951e+00 2.634013e-01
      vertex   1.000000e-01 1.781099e+00 1.920377e-01
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 7.534479e-17 6.596062e-18
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.781099e+00 1.920377e-01
      vertex   1.000000e-01 1.787373e+00 1.203643e-01
    endloop
  endfacet
  facet normal 1.000000e+00 8.411518e-17 3.969601e-18
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.787373e+00 1.203643e-01
      vertex   1.000000e-01 1.790765e+00 4.849677e-02
    endloop
  endfacet
  facet normal 1.000000e+00 9.552736e-17 6.679864e-19
    outer loop
      vertex   1.000000e-01 1.790765e+00 4.849677e-02
      vertex   1.000000e-01 1.791268e+00 -2.344898e-02
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 9.790573e-17 0.000000e+00
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 1.791268e+00 -2.344898e-02
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 8.773243e-17 -2.911367e-18
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.791268e+00 -2.344898e-02
      vertex   1.000000e-01 1.788882e+00 -9.535691e-02
    endloop
  endfacet
  facet normal 1.000000e+00 7.815958e-17 -5.742318e-18
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.788882e+00 -9.535691e-02
      vertex   1.000000e-01 1.783610e+00 -1.671110e-01
    endloop
  endfacet
  facet normal 1.000000e+00 7.063772e-17 -8.052154e-18
    outer loop
      vertex   1.000000e-01 1.783610e+00 -1.671110e-01
      vertex   1.000000e-01 1.775461e+00 -2.385956e-01
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 6.455962e-17 -9.999535e-18
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.775461e+00 -2.385956e-01
      vertex   1.000000e-01 1.764449e+00 -3.096953e-01
    endloop
  endfacet
  facet normal 1.000000e+00 5.953572e-17 -1.168667e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.764449e+00 -3.096953e-01
      vertex   1.000000e-01 1.750590e+00 -3.802955e-01
    endloop
  endfacet
  facet normal 1.000000e+00 5.530452e-17 -1.318259e-17
    outer loop
      vertex   1.000000e-01 1.750590e+00 -3.802955e-01
      vertex   1.000000e-01 1.733908e+00 -4.502822e-01
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 5.168391e-17 -1.453580e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.733908e+00 -4.502822e-01
      vertex   1.000000e-01 1.714429e+00 -5.195427e-01
    endloop
  endfacet
  facet normal 1.000000e+00 4.854314e-17 -1.578163e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.714429e+00 -5.195427e-01
      vertex   1.000000e-01 1.692184e+00 -5.879651e-01
    endloop
  endfacet
  facet normal 1.000000e+00 4.578579e-17 -1.694658e-17
    outer loop
      vertex   1.000000e-01 1.692184e+00 -5.879651e-01
      vertex   1.000000e-01 1.667210e+00 -6.554391e-01
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 4.333920e-17 -1.805118e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.667210e+00 -6.554391e-01
      vertex   1.000000e-01 1.639547e+00 -7.218559e-01
    endloop
  endfacet
  facet normal 1.000000e+00 4.114747e-17 -1.911177e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.639547e+00 -7.218559e-01
      vertex   1.000000e-01 1.609239e+00 -7.871083e-01
    endloop
  endfacet
  facet normal 1.000000e+00 3.916684e-17 -2.014176e-17
    outer loop
      vertex   1.000000e-01 1.609239e+00 -7.871083e-01
      vertex   1.000000e-01 1.576336e+00 -8.510912e-01
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.736251e-17 -2.115249e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.576336e+00 -8.510912e-01
      vertex   1.000000e-01 1.540890e+00 -9.137012e-01
    endloop
  endfacet
  facet normal 1.000000e+00 3.570637e-17 -2.215382e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.540890e+00 -9.137012e-01
      vertex   1.000000e-01 1.502958e+00 -9.748374e-01
    endloop
  endfacet
  facet normal 1.000000e+00 3.417540e-17 -2.315466e-17
    outer loop
      vertex   1.000000e-01 1.502958e+00 -9.748374e-01
      vertex   1.000000e-01 1.462602e+00 -1.034401e+00
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.275048e-17 -2.416327e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.462602e+00 -1.034401e+00
      vertex   1.000000e-01 1.419887e+00 -1.092296e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.141548e-17 -2.518760e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.419887e+00 -1.092296e+00
      vertex   1.000000e-01 1.374882e+00 -1.148430e+00
    endloop
  endfacet
  facet normal 1.000000e+00 3.015665e-17 -2.623551e-17
    outer loop
      vertex   1.000000e-01 1.374882e+00 -1.148430e+00
      vertex   1.000000e-01 1.327658e+00 -1.202711e+00
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.896203e-17 -2.731508e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.327658e+00 -1.202711e+00
      vertex   1.000000e-01 1.278294e+00 -1.255052e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.782106e-17 -2.843474e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.278294e+00 -1.255052e+00
      vertex   1.000000e-01 1.226867e+00 -1.305368e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.672426e-17 -2.960361e-17
    outer loop
      vertex   1.000000e-01 1.226867e+00 -1.305368e+00
      vertex   1.000000e-01 1.173462e+00 -1.353580e+00
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.566290e-17 -3.083172e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.173462e+00 -1.353580e+00
      vertex   1.000000e-01 1.118164e+00 -1.399607e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.462878e-17 -3.213034e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.118164e+00 -1.399607e+00
      vertex   1.000000e-01 1.061062e+00 -1.443377e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.361397e-17 -3.351234e-17
    outer loop
      vertex   1.000000e-01 1.061062e+00 -1.443377e+00
      vertex   1.000000e-01 1.002249e+00 -1.484819e+00
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.261058e-17 -3.499269e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.002249e+00 -1.484819e+00
      vertex   1.000000e-01 9.418186e-01 -1.523866e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.161053e-17 -3.658905e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 9.418186e-01 -1.523866e+00
      vertex   1.000000e-01 8.798694e-01 -1.560455e+00
    endloop
  endfacet
  facet normal 1.000000e+00 2.060525e-17 -3.832253e-17
    outer loop
      vertex   1.000000e-01 8.798694e-01 -1.560455e+00
      vertex   1.000000e-01 8.165011e-01 -1.594527e+00
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.958537e-17 -4.021875e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 8.165011e-01 -1.594527e+00
      vertex   1.000000e-01 7.518157e-01 -1.626027e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.854028e-17 -4.230922e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 7.518157e-01 -1.626027e+00
      vertex   1.000000e-01 6.859176e-01 -1.654904e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.745761e-17 -4.463327e-17
    outer loop
      vertex   1.000000e-01 6.859176e-01 -1.654904e+00
      vertex   1.000000e-01 6.189131e-01 -1.681112e+00
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.632249e-17 -4.724078e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 6.189131e-01 -1.681112e+00
      vertex   1.000000e-01 5.509104e-01 -1.704608e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.511649e-17 -5.019606e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 5.509104e-01 -1.704608e+00
      vertex   1.000000e-01 4.820190e-01 -1.725355e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.381610e-17 -5.358362e-17
    outer loop
      vertex   1.000000e-01 4.820190e-01 -1.725355e+00
      vertex   1.000000e-01 4.123501e-01 -1.743318e+00
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.239047e-17 -5.751688e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 4.123501e-01 -1.743318e+00
      vertex   1.000000e-01 3.420160e-01 -1.758470e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.079780e-17 -6.215183e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 3.420160e-01 -1.758470e+00
      vertex   1.000000e-01 2.711304e-01 -1.770785e+00
    endloop
  endfacet
  facet normal 1.000000e+00 8.979600e-18 -6.770920e-17
    outer loop
      vertex   1.000000e-01 2.711304e-01 -1.770785e+00
      vertex   1.000000e-01 1.998073e-01 -1.780244e+00
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 6.850902e-18 -7.451208e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.998073e-01 -1.780244e+00
      vertex   1.000000e-01 1.281620e-01 -1.786831e+00
    endloop
  endfacet
  facet normal 1.000000e+00 4.282753e-18 -8.305316e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 1.281620e-01 -1.786831e+00
      vertex   1.000000e-01 5.630997e-02 -1.790536e+00
    endloop
  endfacet
  facet normal 1.000000e+00 1.068891e-18 -9.412305e-17
    outer loop
      vertex   1.000000e-01 5.630997e-02 -1.790536e+00
      vertex   1.000000e-01 -1.563290e-02 -1.791353e+00
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -8.696822e-33 -9.791751e-17
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.563290e-02 -1.791353e+00
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.562788e-18 -8.893292e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.563290e-02 -1.791353e+00
      vertex   1.000000e-01 -8.755056e-02 -1.789281e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -5.463586e-18 -7.908652e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -8.755056e-02 -1.789281e+00
      vertex   1.000000e-01 -1.593270e-01 -1.784322e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -7.821023e-18 -7.137636e-17
    outer loop
      vertex   1.000000e-01 -1.593270e-01 -1.784322e+00
      vertex   1.000000e-01 -2.308464e-01 -1.776485e+00
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -9.802070e-18 -6.516322e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -2.308464e-01 -1.776485e+00
      vertex   1.000000e-01 -3.019935e-01 -1.765783e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.151367e-17 -6.003923e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -3.019935e-01 -1.765783e+00
      vertex   1.000000e-01 -3.726535e-01 -1.752233e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.302772e-17 -5.573186e-17
    outer loop
      vertex   1.000000e-01 -3.726535e-01 -1.752233e+00
      vertex   1.000000e-01 -4.427124e-01 -1.735856e+00
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.439454e-17 -5.205201e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -4.427124e-01 -1.735856e+00
      vertex   1.000000e-01 -5.120571e-01 -1.716679e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.565062e-17 -4.886428e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -5.120571e-01 -1.716679e+00
      vertex   1.000000e-01 -5.805760e-01 -1.694734e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.682327e-17 -4.606916e-17
    outer loop
      vertex   1.000000e-01 -5.805760e-01 -1.694734e+00
      vertex   1.000000e-01 -6.481583e-01 -1.670054e+00
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.793357e-17 -4.359176e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -6.481583e-01 -1.670054e+00
      vertex   1.000000e-01 -7.146952e-01 -1.642681e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.899825e-17 -4.137465e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -7.146952e-01 -1.642681e+00
      vertex   1.000000e-01 -7.800792e-01 -1.612658e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.003099e-17 -3.937291e-17
    outer loop
      vertex   1.000000e-01 -7.800792e-01 -1.612658e+00
      vertex   1.000000e-01 -8.442050e-01 -1.580034e+00
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.104331e-17 -3.755089e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -8.442050e-01 -1.580034e+00
      vertex   1.000000e-01 -9.069691e-01 -1.544862e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.204522e-17 -3.587985e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -9.069691e-01 -1.544862e+00
      vertex   1.000000e-01 -9.682702e-01 -1.507197e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.304570e-17 -3.433627e-17
    outer loop
      vertex   1.000000e-01 -9.682702e-01 -1.507197e+00
      vertex   1.000000e-01 -1.028010e+00 -1.467102e+00
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.405308e-17 -3.290065e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.028010e+00 -1.467102e+00
      vertex   1.000000e-01 -1.086091e+00 -1.424639e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.507532e-17 -3.155659e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.086091e+00 -1.424639e+00
      vertex   1.000000e-01 -1.142420e+00 -1.379879e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.612029e-17 -3.029009e-17
    outer loop
      vertex   1.000000e-01 -1.142420e+00 -1.379879e+00
      vertex   1.000000e-01 -1.196906e+00 -1.332894e+00
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.719601e-17 -2.908903e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.196906e+00 -1.332894e+00
      vertex   1.000000e-01 -1.249462e+00 -1.283758e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.831089e-17 -2.794271e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.249462e+00 -1.283758e+00
      vertex   1.000000e-01 -1.300003e+00 -1.232551e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.947395e-17 -2.684155e-17
    outer loop
      vertex   1.000000e-01 -1.300003e+00 -1.232551e+00
      vertex   1.000000e-01 -1.348446e+00 -1.179357e+00
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.069511e-17 -2.577674e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.348446e+00 -1.179357e+00
      vertex   1.000000e-01 -1.394715e+00 -1.124260e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.198547e-17 -2.474005e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.394715e+00 -1.124260e+00
      vertex   1.000000e-01 -1.438734e+00 -1.067350e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.335773e-17 -2.372352e-17
    outer loop
      vertex   1.000000e-01 -1.438734e+00 -1.067350e+00
      vertex   1.000000e-01 -1.480432e+00 -1.008718e+00
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.482660e-17 -2.271928e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.480432e+00 -1.008718e+00
      vertex   1.000000e-01 -1.519742e+00 -9.484587e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -3.640940e-17 -2.171927e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.519742e+00 -9.484587e-01
      vertex   1.000000e-01 -1.556601e+00 -8.866698e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -3.812684e-17 -2.071499e-17
    outer loop
      vertex   1.000000e-01 -1.556601e+00 -8.866698e-01
      vertex   1.000000e-01 -1.590949e+00 -8.234507e-01
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -4.000397e-17 -1.969718e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.590949e+00 -8.234507e-01
      vertex   1.000000e-01 -1.622731e+00 -7.589034e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -4.207159e-17 -1.865539e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.622731e+00 -7.589034e-01
      vertex   1.000000e-01 -1.651895e+00 -6.931319e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -4.436807e-17 -1.757747e-17
    outer loop
      vertex   1.000000e-01 -1.651895e+00 -6.931319e-01
      vertex   1.000000e-01 -1.678395e+00 -6.262424e-01
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -4.694197e-17 -1.644887e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.678395e+00 -6.262424e-01
      vertex   1.000000e-01 -1.702188e+00 -5.583428e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -4.985581e-17 -1.525160e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.702188e+00 -5.583428e-01
      vertex   1.000000e-01 -1.723235e+00 -4.895426e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -5.319152e-17 -1.396280e-17
    outer loop
      vertex   1.000000e-01 -1.723235e+00 -4.895426e-01
      vertex   1.000000e-01 -1.741502e+00 -4.199528e-01
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -5.705885e-17 -1.255256e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.741502e+00 -4.199528e-01
      vertex   1.000000e-01 -1.756961e+00 -3.496855e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -6.160829e-17 -1.098051e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.756961e+00 -3.496855e-01
      vertex   1.000000e-01 -1.769585e+00 -2.788543e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -6.705208e-17 -9.190342e-18
    outer loop
      vertex   1.000000e-01 -1.769585e+00 -2.788543e-01
      vertex   1.000000e-01 -1.779355e+00 -2.075732e-01
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -7.369962e-17 -7.100627e-18
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.779355e+00 -2.075732e-01
      vertex   1.000000e-01 -1.786255e+00 -1.359573e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -8.202047e-17 -4.588418e-18
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.786255e+00 -1.359573e-01
      vertex   1.000000e-01 -1.790273e+00 -6.412210e-02
    endloop
  endfacet
  facet normal 1.000000e+00 -9.276352e-17 -1.458284e-18
    outer loop
      vertex   1.000000e-01 -1.790273e+00 -6.412210e-02
      vertex   1.000000e-01 -1.791404e+00 7.816525e-03
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -9.792458e-17 -1.739490e-32
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -1.791404e+00 7.816525e-03
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -9.017040e-17 2.204726e-18
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.791404e+00 7.816525e-03
      vertex   1.000000e-01 -1.789646e+00 7.974254e-02
    endloop
  endfacet
  facet normal 1.000000e+00 -8.003828e-17 5.178541e-18
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.789646e+00 7.974254e-02
      vertex   1.000000e-01 -1.785000e+00 1.515399e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -7.213245e-17 7.585506e-18
    outer loop
      vertex   1.000000e-01 -1.785000e+00 1.515399e-01
      vertex   1.000000e-01 -1.777476e+00 2.230929e-01
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -6.577954e-17 9.601458e-18
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.777476e+00 2.230929e-01
      vertex   1.000000e-01 -1.767084e+00 2.942860e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -6.055230e-17 1.133837e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.767084e+00 2.942860e-01
      vertex   1.000000e-01 -1.753842e+00 3.650044e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -5.616656e-17 1.287114e-17
    outer loop
      vertex   1.000000e-01 -1.753842e+00 3.650044e-01
      vertex   1.000000e-01 -1.737771e+00 4.351341e-01
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -5.242587e-17 1.425198e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.737771e+00 4.351341e-01
      vertex   1.000000e-01 -1.718897e+00 5.045619e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -4.919003e-17 1.551863e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.718897e+00 5.045619e-01
      vertex   1.000000e-01 -1.697251e+00 5.731758e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -4.635625e-17 1.669924e-17
    outer loop
      vertex   1.000000e-01 -1.697251e+00 5.731758e-01
      vertex   1.000000e-01 -1.672866e+00 6.408652e-01
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -4.384739e-17 1.781544e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.672866e+00 6.408652e-01
      vertex   1.000000e-01 -1.645784e+00 7.075209e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -4.160436e-17 1.888436e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.645784e+00 7.075209e-01
      vertex   1.000000e-01 -1.616047e+00 7.730353e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -3.958109e-17 1.991998e-17
    outer loop
      vertex   1.000000e-01 -1.616047e+00 7.730353e-01
      vertex   1.000000e-01 -1.583703e+00 8.373028e-01
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.774105e-17 2.093401e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.583703e+00 8.373028e-01
      vertex   1.000000e-01 -1.548804e+00 9.002198e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -3.605483e-17 2.193660e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.548804e+00 9.002198e-01
      vertex   1.000000e-01 -1.511408e+00 9.616847e-01
    endloop
  endfacet
  facet normal 1.000000e+00 -3.449841e-17 2.293683e-17
    outer loop
      vertex   1.000000e-01 -1.511408e+00 9.616847e-01
      vertex   1.000000e-01 -1.471573e+00 1.021598e+00
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.305191e-17 2.394307e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.471573e+00 1.021598e+00
      vertex   1.000000e-01 -1.429365e+00 1.079864e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.169862e-17 2.496331e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.429365e+00 1.079864e+00
      vertex   1.000000e-01 -1.384851e+00 1.136388e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -3.042431e-17 2.600542e-17
    outer loop
      vertex   1.000000e-01 -1.384851e+00 1.136388e+00
      vertex   1.000000e-01 -1.338103e+00 1.191079e+00
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.921667e-17 2.707741e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.338103e+00 1.191079e+00
      vertex   1.000000e-01 -1.289197e+00 1.243849e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.806489e-17 2.818761e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.289197e+00 1.243849e+00
      vertex   1.000000e-01 -1.238212e+00 1.294612e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.695926e-17 2.934498e-17
    outer loop
      vertex   1.000000e-01 -1.238212e+00 1.294612e+00
      vertex   1.000000e-01 -1.185229e+00 1.343288e+00
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.589091e-17 3.055931e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.185229e+00 1.343288e+00
      vertex   1.000000e-01 -1.130335e+00 1.389796e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.485155e-17 3.184157e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.130335e+00 1.389796e+00
      vertex   1.000000e-01 -1.073617e+00 1.434063e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.383322e-17 3.320426e-17
    outer loop
      vertex   1.000000e-01 -1.073617e+00 1.434063e+00
      vertex   1.000000e-01 -1.015168e+00 1.476017e+00
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.282802e-17 3.466185e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.015168e+00 1.476017e+00
      vertex   1.000000e-01 -9.550808e-01 1.515589e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.182795e-17 3.623134e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -9.550808e-01 1.515589e+00
      vertex   1.000000e-01 -8.934533e-01 1.552718e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -2.082457e-17 3.793302e-17
    outer loop
      vertex   1.000000e-01 -8.934533e-01 1.552718e+00
      vertex   1.000000e-01 -8.303847e-01 1.587341e+00
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.980871e-17 3.979143e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -8.303847e-01 1.587341e+00
      vertex   1.000000e-01 -7.659766e-01 1.619404e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.877008e-17 4.183666e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -7.659766e-01 1.619404e+00
      vertex   1.000000e-01 -7.003331e-01 1.648855e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.769674e-17 4.410613e-17
    outer loop
      vertex   1.000000e-01 -7.003331e-01 1.648855e+00
      vertex   1.000000e-01 -6.335598e-01 1.675647e+00
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.657444e-17 4.664716e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -6.335598e-01 1.675647e+00
      vertex   1.000000e-01 -5.657647e-01 1.699736e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.538564e-17 4.952050e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -5.657647e-01 1.699736e+00
      vertex   1.000000e-01 -4.970570e-01 1.721082e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.410808e-17 5.280566e-17
    outer loop
      vertex   1.000000e-01 -4.970570e-01 1.721082e+00
      vertex   1.000000e-01 -4.275475e-01 1.739653e+00
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.271277e-17 5.660882e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -4.275475e-01 1.739653e+00
      vertex   1.000000e-01 -3.573484e-01 1.755418e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -1.116067e-17 6.107522e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -3.573484e-01 1.755418e+00
      vertex   1.000000e-01 -2.865728e-01 1.768351e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -9.397588e-18 6.640901e-17
    outer loop
      vertex   1.000000e-01 -2.865728e-01 1.768351e+00
      vertex   1.000000e-01 -2.153351e-01 1.778432e+00
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -7.345433e-18 7.290665e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -2.153351e-01 1.778432e+00
      vertex   1.000000e-01 -1.437500e-01 1.785645e+00
    endloop
  endfacet
  facet normal 1.000000e+00 -4.886913e-18 8.101590e-17
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -1.437500e-01 1.785645e+00
      vertex   1.000000e-01 -7.193300e-02 1.789977e+00
    endloop
  endfacet
  facet normal 1.000000e+00 9.007984e-16 3.178188e-15
    outer loop
      vertex   1.000000e-01 -7.193300e-02 1.789977e+00
      vertex   1.000000e-01 0.000000e+00 1.791421e+00
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 1.000000e+00 0.000000e+00 0.000000e+00
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   1.000000e-01 0.000000e+00 1.791421e+00
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 4.758099e-15 3.826834e-01 9.238795e-01
    outer loop
      vertex   0.000000e+00 -1.616789e+00 6.696960e-01
      vertex   1.000000e-01 -1.524401e+00 6.314277e-01
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal -0.000000e+00 3.826834e-01 9.238795e-01
    outer loop
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.524401e+00 6.314277e-01
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 1.308477e-15 -3.826834e-01 9.238795e-01
    outer loop
      vertex   0.000000e+00 -1.616789e+00 -6.696960e-01
      vertex   1.000000e-01 -1.524401e+00 -6.314277e-01
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 0.000000e+00 -3.826834e-01 9.238795e-01
    outer loop
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -1.524401e+00 -6.314277e-01
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal -5.392512e-15 -9.238795e-01 3.826834e-01
    outer loop
      vertex   0.000000e+00 -6.696960e-01 -1.616789e+00
      vertex   1.000000e-01 -6.314277e-01 -1.524401e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 0.000000e+00 -9.238795e-01 3.826834e-01
    outer loop
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 -6.314277e-01 -1.524401e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal -5.590766e-15 -9.238795e-01 -3.826834e-01
    outer loop
      vertex   0.000000e+00 6.696960e-01 -1.616789e+00
      vertex   1.000000e-01 6.314277e-01 -1.524401e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 0.000000e+00 -9.238795e-01 -3.826834e-01
    outer loop
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 6.314277e-01 -1.524401e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal -4.401241e-15 -3.826834e-01 -9.238795e-01
    outer loop
      vertex   0.000000e+00 1.616789e+00 -6.696960e-01
      vertex   1.000000e-01 1.524401e+00 -6.314277e-01
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 0.000000e+00 -3.826834e-01 -9.238795e-01
    outer loop
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.524401e+00 -6.314277e-01
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 9.119689e-16 3.826834e-01 -9.238795e-01
    outer loop
      vertex   0.000000e+00 1.616789e+00 6.696960e-01
      vertex   1.000000e-01 1.524401e+00 6.314277e-01
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 0.000000e+00 3.826834e-01 -9.238795e-01
    outer loop
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 1.524401e+00 6.314277e-01
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 5.233909e-15 9.238795e-01 -3.826834e-01
    outer loop
      vertex   0.000000e+00 6.696960e-01 1.616789e+00
      vertex   1.000000e-01 6.314277e-01 1.524401e+00
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 0.000000e+00 9.238795e-01 -3.826834e-01
    outer loop
      vertex   0.000000e+00 0.000000e+00 0.000000e+00
      vertex   1.000000e-01 6.314277e-01 1.524401e+00
      vertex   1.000000e-01 0.000000e+00 0.000000e+00
    endloop
  endfacet
  facet normal 0.000000e+00 1.000000e+00 0.000000e+00
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 0.000000e+00 1.000000e+00 0.000000e+00
    outer loop
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -0.000000e+00 -8.881784e-17 -1.000000e+00
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -0.000000e+00 -8.881784e-17 -1.000000e+00
    outer loop
      vertex   1.000000e-01 2.500000e+00 -2.500000e+00
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   0.000000e+00 2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal -0.000000e+00 -1.000000e+00 -1.776357e-16
    outer loop
      vertex   1.000000e-01 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
    endloop
  endfacet
  facet normal 0.000000e+00 -1.000000e+00 -1.776357e-16
    outer loop
      vertex   0.000000e+00 -2.500000e+00 -2.500000e+00
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 0.000000e+00 8.881784e-17 1.000000e+00
    outer loop
      vertex   1.000000e-01 2.500000e+00 2.500000e+00
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 0.000000e+00 8.881784e-17 1.000000e+00
    outer loop
      vertex   1.000000e-01 -2.500000e+00 2.500000e+00
      vertex   0.000000e+00 2.500000e+00 2.500000e+00
      vertex   0.000000e+00 -2.500000e+00 2.500000e+00
    endloop
  endfacet
  facet normal 7.070353e-01 -1.422071e-02 7.070353e-01
    outer loop
      vertex   1.820711e+00 0.000000e+00 7.071068e-02
      vertex   1.000000e-01 0.000000e+00 1.791421e+00
      vertex   9.603553e-01 -3.743821e-02 9.303130e-01
    endloop
  endfacet
  facet normal 7.070359e-01 -1.420092e-02 7.070350e-01
    outer loop
      vertex   9.603553e-01 -3.743821e-02 9.303130e-01
      vertex   1.000000e-01 0.000000e+00 1.791421e+00
      vertex   1.000000e-01 -7.193300e-02 1.789977e+00
    endloop
  endfacet
  facet normal 7.070350e-01 -4.257991e-02 7.058955e-01
    outer loop
      vertex   9.603553e-01 -3.743821e-02 9.303130e-01
      vertex   1.000000e-01 -7.193300e-02 1.789977e+00
      vertex   1.000000e-01 -1.437500e-01 1.785645e+00
    endloop
  endfacet
  facet normal 7.070369e-01 -4.263903e-02 7.058900e-01
    outer loop
      vertex   9.603553e-01 -3.743821e-02 9.303130e-01
      vertex   1.000000e-01 -1.437500e-01 1.785645e+00
      vertex   9.603553e-01 -7.481586e-02 9.280552e-01
    endloop
  endfacet
  facet normal 7.070346e-01 -7.089025e-02 7.036168e-01
    outer loop
      vertex   9.603553e-01 -7.481586e-02 9.280552e-01
      vertex   1.000000e-01 -1.437500e-01 1.785645e+00
      vertex   1.000000e-01 -2.153351e-01 1.778432e+00
    endloop
  endfacet
  facet normal 7.070378e-01 -7.098833e-02 7.036038e-01
    outer loop
      vertex   9.603553e-01 -7.481586e-02 9.280552e-01
      vertex   1.000000e-01 -2.153351e-01 1.778432e+00
      vertex   9.603553e-01 -1.120725e-01 9.242963e-01
    endloop
  endfacet
  facet normal 7.070342e-01 -9.908627e-02 7.002032e-01
    outer loop
      vertex   9.603553e-01 -1.120725e-01 9.242963e-01
      vertex   1.000000e-01 -2.153351e-01 1.778432e+00
      vertex   1.000000e-01 -2.865728e-01 1.768351e+00
    endloop
  endfacet
  facet normal 7.070411e-01 -9.930073e-02 7.001659e-01
    outer loop
      vertex   9.603553e-01 -1.120725e-01 9.242963e-01
      vertex   1.000000e-01 -2.865728e-01 1.768351e+00
      vertex   9.603553e-01 -1.493535e-01 9.190090e-01
    endloop
  endfacet
  facet normal 7.070321e-01 -1.271228e-01 6.956619e-01
    outer loop
      vertex   9.603553e-01 -1.493535e-01 9.190090e-01
      vertex   1.000000e-01 -2.865728e-01 1.768351e+00
      vertex   1.000000e-01 -3.573484e-01 1.755418e+00
    endloop
  endfacet
  facet normal 7.070433e-01 -1.274710e-01 6.955868e-01
    outer loop
      vertex   9.603553e-01 -1.493535e-01 9.190090e-01
      vertex   1.000000e-01 -3.573484e-01 1.755418e+00
      vertex   9.603553e-01 -1.862371e-01 9.122498e-01
    endloop
  endfacet
  facet normal 7.070312e-01 -1.549542e-01 6.899971e-01
    outer loop
      vertex   9.603553e-01 -1.862371e-01 9.122498e-01
      vertex   1.000000e-01 -3.573484e-01 1.755418e+00
      vertex   1.000000e-01 -4.275475e-01 1.739653e+00
    endloop
  endfacet
  facet normal 7.070449e-01 -1.553757e-01 6.898884e-01
    outer loop
      vertex   9.603553e-01 -1.862371e-01 9.122498e-01
      vertex   1.000000e-01 -4.275475e-01 1.739653e+00
      vertex   9.603553e-01 -2.228187e-01 9.040109e-01
    endloop
  endfacet
  facet normal 7.070304e-01 -1.825357e-01 6.832194e-01
    outer loop
      vertex   9.603553e-01 -2.228187e-01 9.040109e-01
      vertex   1.000000e-01 -4.275475e-01 1.739653e+00
      vertex   1.000000e-01 -4.970570e-01 1.721082e+00
    endloop
  endfacet
  facet normal 7.070465e-01 -1.830283e-01 6.830710e-01
    outer loop
      vertex   9.603553e-01 -2.228187e-01 9.040109e-01
      vertex   1.000000e-01 -4.970570e-01 1.721082e+00
      vertex   9.603553e-01 -2.590388e-01 8.943058e-01
    endloop
  endfacet
  facet normal 7.070296e-01 -2.098228e-01 6.753396e-01
    outer loop
      vertex   9.603553e-01 -2.590388e-01 8.943058e-01
      vertex   1.000000e-01 -4.970570e-01 1.721082e+00
      vertex   1.000000e-01 -5.657647e-01 1.699736e+00
    endloop
  endfacet
  facet normal 7.070481e-01 -2.103839e-01 6.751457e-01
    outer loop
      vertex   9.603553e-01 -2.590388e-01 8.943058e-01
      vertex   1.000000e-01 -5.657647e-01 1.699736e+00
      vertex   9.603553e-01 -2.948388e-01 8.831500e-01
    endloop
  endfacet
  facet normal 7.070288e-01 -2.367715e-01 6.663705e-01
    outer loop
      vertex   9.603553e-01 -2.948388e-01 8.831500e-01
      vertex   1.000000e-01 -5.657647e-01 1.699736e+00
      vertex   1.000000e-01 -6.335598e-01 1.675647e+00
    endloop
  endfacet
  facet normal 7.070496e-01 -2.373981e-01 6.661253e-01
    outer loop
      vertex   9.603553e-01 -2.948388e-01 8.831500e-01
      vertex   1.000000e-01 -6.335598e-01 1.675647e+00
      vertex   9.603553e-01 -3.301606e-01 8.705618e-01
    endloop
  endfacet
  facet normal 7.070279e-01 -2.633384e-01 6.563264e-01
    outer loop
      vertex   9.603553e-01 -3.301606e-01 8.705618e-01
      vertex   1.000000e-01 -6.335598e-01 1.675647e+00
      vertex   1.000000e-01 -7.003331e-01 1.648855e+00
    endloop
  endfacet
  facet normal 7.070512e-01 -2.640272e-01 6.560246e-01
    outer loop
      vertex   9.603553e-01 -3.301606e-01 8.705618e-01
      vertex   1.000000e-01 -7.003331e-01 1.648855e+00
      vertex   9.603553e-01 -3.649468e-01 8.565616e-01
    endloop
  endfacet
  facet normal 7.070271e-01 -2.894806e-01 6.452237e-01
    outer loop
      vertex   9.603553e-01 -3.649468e-01 8.565616e-01
      vertex   1.000000e-01 -7.003331e-01 1.648855e+00
      vertex   1.000000e-01 -7.659766e-01 1.619404e+00
    endloop
  endfacet
  facet normal 7.070528e-01 -2.902278e-01 6.448598e-01
    outer loop
      vertex   9.603553e-01 -3.649468e-01 8.565616e-01
      vertex   1.000000e-01 -7.659766e-01 1.619404e+00
      vertex   9.603553e-01 -3.991411e-01 8.411720e-01
    endloop
  endfacet
  facet normal 7.070263e-01 -3.151559e-01 6.330802e-01
    outer loop
      vertex   9.603553e-01 -3.991411e-01 8.411720e-01
      vertex   1.000000e-01 -7.659766e-01 1.619404e+00
      vertex   1.000000e-01 -8.303847e-01 1.587341e+00
    endloop
  endfacet
  facet normal 7.070543e-01 -3.159577e-01 6.326491e-01
    outer loop
      vertex   9.603553e-01 -3.991411e-01 8.411720e-01
      vertex   1.000000e-01 -8.303847e-01 1.587341e+00
      vertex   9.603553e-01 -4.326880e-01 8.244180e-01
    endloop
  endfacet
  facet normal 7.070255e-01 -3.403229e-01 6.199155e-01
    outer loop
      vertex   9.603553e-01 -4.326880e-01 8.244180e-01
      vertex   1.000000e-01 -8.303847e-01 1.587341e+00
      vertex   1.000000e-01 -8.934533e-01 1.552718e+00
    endloop
  endfacet
  facet normal 7.070559e-01 -3.411749e-01 6.194124e-01
    outer loop
      vertex   9.603553e-01 -4.326880e-01 8.244180e-01
      vertex   1.000000e-01 -8.934533e-01 1.552718e+00
      vertex   9.603553e-01 -4.655330e-01 8.063268e-01
    endloop
  endfacet
  facet normal 7.070247e-01 -3.649410e-01 6.057509e-01
    outer loop
      vertex   9.603553e-01 -4.655330e-01 8.063268e-01
      vertex   1.000000e-01 -8.934533e-01 1.552718e+00
      vertex   1.000000e-01 -9.550808e-01 1.515589e+00
    endloop
  endfacet
  facet normal 7.070574e-01 -3.658386e-01 6.051710e-01
    outer loop
      vertex   9.603553e-01 -4.655330e-01 8.063268e-01
      vertex   1.000000e-01 -9.550808e-01 1.515589e+00
      vertex   9.603553e-01 -4.976230e-01 7.869278e-01
    endloop
  endfacet
  facet normal 7.070239e-01 -3.889706e-01 5.906091e-01
    outer loop
      vertex   9.603553e-01 -4.976230e-01 7.869278e-01
      vertex   1.000000e-01 -9.550808e-01 1.515589e+00
      vertex   1.000000e-01 -1.015168e+00 1.476017e+00
    endloop
  endfacet
  facet normal 7.070589e-01 -3.899089e-01 5.899481e-01
    outer loop
      vertex   9.603553e-01 -4.976230e-01 7.869278e-01
      vertex   1.000000e-01 -1.015168e+00 1.476017e+00
      vertex   9.603553e-01 -5.289058e-01 7.662523e-01
    endloop
  endfacet
  facet normal 7.070231e-01 -4.123727e-01 5.745146e-01
    outer loop
      vertex   9.603553e-01 -5.289058e-01 7.662523e-01
      vertex   1.000000e-01 -1.015168e+00 1.476017e+00
      vertex   1.000000e-01 -1.073617e+00 1.434063e+00
    endloop
  endfacet
  facet normal 7.070604e-01 -4.133466e-01 5.737684e-01
    outer loop
      vertex   9.603553e-01 -5.289058e-01 7.662523e-01
      vertex   1.000000e-01 -1.073617e+00 1.434063e+00
      vertex   9.603553e-01 -5.593307e-01 7.443340e-01
    endloop
  endfacet
  facet normal 7.070223e-01 -4.351098e-01 5.574934e-01
    outer loop
      vertex   9.603553e-01 -5.593307e-01 7.443340e-01
      vertex   1.000000e-01 -1.073617e+00 1.434063e+00
      vertex   1.000000e-01 -1.130335e+00 1.389796e+00
    endloop
  endfacet
  facet normal 7.070620e-01 -4.361137e-01 5.566581e-01
    outer loop
      vertex   9.603553e-01 -5.593307e-01 7.443340e-01
      vertex   1.000000e-01 -1.130335e+00 1.389796e+00
      vertex   9.603553e-01 -5.888484e-01 7.212084e-01
    endloop
  endfacet
  facet normal 7.070216e-01 -4.571450e-01 5.395729e-01
    outer loop
      vertex   9.603553e-01 -5.888484e-01 7.212084e-01
      vertex   1.000000e-01 -1.130335e+00 1.389796e+00
      vertex   1.000000e-01 -1.185229e+00 1.343288e+00
    endloop
  endfacet
  facet normal 7.070634e-01 -4.581734e-01 5.386449e-01
    outer loop
      vertex   9.603553e-01 -5.888484e-01 7.212084e-01
      vertex   1.000000e-01 -1.185229e+00 1.343288e+00
      vertex   9.603553e-01 -6.174110e-01 6.969129e-01
    endloop
  endfacet
  facet normal 7.070208e-01 -4.784430e-01 5.207821e-01
    outer loop
      vertex   9.603553e-01 -6.174110e-01 6.969129e-01
      vertex   1.000000e-01 -1.185229e+00 1.343288e+00
      vertex   1.000000e-01 -1.238212e+00 1.294612e+00
    endloop
  endfacet
  facet normal 7.070649e-01 -4.794899e-01 5.197582e-01
    outer loop
      vertex   9.603553e-01 -6.174110e-01 6.969129e-01
      vertex   1.000000e-01 -1.238212e+00 1.294612e+00
      vertex   9.603553e-01 -6.449721e-01 6.714871e-01
    endloop
  endfacet
  facet normal 7.070200e-01 -4.989692e-01 5.011511e-01
    outer loop
      vertex   9.603553e-01 -6.449721e-01 6.714871e-01
      vertex   1.000000e-01 -1.238212e+00 1.294612e+00
      vertex   1.000000e-01 -1.289197e+00 1.243849e+00
    endloop
  endfacet
  facet normal 7.070664e-01 -5.000285e-01 5.000285e-01
    outer loop
      vertex   9.603553e-01 -6.449721e-01 6.714871e-01
      vertex   1.000000e-01 -1.289197e+00 1.243849e+00
      vertex   9.603553e-01 -6.714871e-01 6.449721e-01
    endloop
  endfacet
  facet normal 7.070192e-01 -5.186906e-01 4.807118e-01
    outer loop
      vertex   9.603553e-01 -6.714871e-01 6.449721e-01
      vertex   1.000000e-01 -1.289197e+00 1.243849e+00
      vertex   1.000000e-01 -1.338103e+00 1.191079e+00
    endloop
  endfacet
  facet normal 7.070679e-01 -5.197561e-01 4.794879e-01
    outer loop
      vertex   9.603553e-01 -6.714871e-01 6.449721e-01
      vertex   1.000000e-01 -1.338103e+00 1.191079e+00
      vertex   9.603553e-01 -6.969129e-01 6.174110e-01
    endloop
  endfacet
  facet normal 7.070185e-01 -5.375755e-01 4.594970e-01
    outer loop
      vertex   9.603553e-01 -6.969129e-01 6.174110e-01
      vertex   1.000000e-01 -1.338103e+00 1.191079e+00
      vertex   1.000000e-01 -1.384851e+00 1.136388e+00
    endloop
  endfacet
  facet normal 7.070693e-01 -5.386405e-01 4.581696e-01
    outer loop
      vertex   9.603553e-01 -6.969129e-01 6.174110e-01
      vertex   1.000000e-01 -1.384851e+00 1.136388e+00
      vertex   9.603553e-01 -7.212084e-01 5.888484e-01
    endloop
  endfacet
  facet normal 7.070177e-01 -5.555932e-01 4.375410e-01
    outer loop
      vertex   9.603553e-01 -7.212084e-01 5.888484e-01
      vertex   1.000000e-01 -1.384851e+00 1.136388e+00
      vertex   1.000000e-01 -1.429365e+00 1.079864e+00
    endloop
  endfacet
  facet normal 7.070708e-01 -5.566511e-01 4.361083e-01
    outer loop
      vertex   9.603553e-01 -7.212084e-01 5.888484e-01
      vertex   1.000000e-01 -1.429365e+00 1.079864e+00
      vertex   9.603553e-01 -7.443340e-01 5.593307e-01
    endloop
  endfacet
  facet normal 7.070170e-01 -5.727148e-01 4.148792e-01
    outer loop
      vertex   9.603553e-01 -7.443340e-01 5.593307e-01
      vertex   1.000000e-01 -1.429365e+00 1.079864e+00
      vertex   1.000000e-01 -1.471573e+00 1.021598e+00
    endloop
  endfacet
  facet normal 7.070722e-01 -5.737588e-01 4.133397e-01
    outer loop
      vertex   9.603553e-01 -7.443340e-01 5.593307e-01
      vertex   1.000000e-01 -1.471573e+00 1.021598e+00
      vertex   9.603553e-01 -7.662523e-01 5.289058e-01
    endloop
  endfacet
  facet normal 7.070162e-01 -5.889127e-01 3.915481e-01
    outer loop
      vertex   9.603553e-01 -7.662523e-01 5.289058e-01
      vertex   1.000000e-01 -1.471573e+00 1.021598e+00
      vertex   1.000000e-01 -1.511408e+00 9.616847e-01
    endloop
  endfacet
  facet normal 7.070737e-01 -5.899358e-01 3.899007e-01
    outer loop
      vertex   9.603553e-01 -7.662523e-01 5.289058e-01
      vertex   1.000000e-01 -1.511408e+00 9.616847e-01
      vertex   9.603553e-01 -7.869278e-01 4.976230e-01
    endloop
  endfacet
  facet normal 7.070155e-01 -6.041606e-01 3.675854e-01
    outer loop
      vertex   9.603553e-01 -7.869278e-01 4.976230e-01
      vertex   1.000000e-01 -1.511408e+00 9.616847e-01
      vertex   1.000000e-01 -1.548804e+00 9.002198e-01
    endloop
  endfacet
  facet normal 7.070751e-01 -6.051559e-01 3.658295e-01
    outer loop
      vertex   9.603553e-01 -7.869278e-01 4.976230e-01
      vertex   1.000000e-01 -1.548804e+00 9.002198e-01
      vertex   9.603553e-01 -8.063268e-01 4.655330e-01
    endloop
  endfacet
  facet normal 7.070147e-01 -6.184341e-01 3.430298e-01
    outer loop
      vertex   9.603553e-01 -8.063268e-01 4.655330e-01
      vertex   1.000000e-01 -1.548804e+00 9.002198e-01
      vertex   1.000000e-01 -1.583703e+00 8.373028e-01
    endloop
  endfacet
  facet normal 7.070765e-01 -6.193943e-01 3.411649e-01
    outer loop
      vertex   9.603553e-01 -8.063268e-01 4.655330e-01
      vertex   1.000000e-01 -1.583703e+00 8.373028e-01
      vertex   9.603553e-01 -8.244180e-01 4.326880e-01
    endloop
  endfacet
  facet normal 7.070140e-01 -6.317101e-01 3.179208e-01
    outer loop
      vertex   9.603553e-01 -8.244180e-01 4.326880e-01
      vertex   1.000000e-01 -1.583703e+00 8.373028e-01
      vertex   1.000000e-01 -1.616047e+00 7.730353e-01
    endloop
  endfacet
  facet normal 7.070779e-01 -6.326280e-01 3.159471e-01
    outer loop
      vertex   9.603553e-01 -8.244180e-01 4.326880e-01
      vertex   1.000000e-01 -1.616047e+00 7.730353e-01
      vertex   9.603553e-01 -8.411720e-01 3.991411e-01
    endloop
  endfacet
  facet normal 7.070133e-01 -6.439671e-01 2.922989e-01
    outer loop
      vertex   9.603553e-01 -8.411720e-01 3.991411e-01
      vertex   1.000000e-01 -1.616047e+00 7.730353e-01
      vertex   1.000000e-01 -1.645784e+00 7.075209e-01
    endloop
  endfacet
  facet normal 7.070793e-01 -6.448356e-01 2.902170e-01
    outer loop
      vertex   9.603553e-01 -8.411720e-01 3.991411e-01
      vertex   1.000000e-01 -1.645784e+00 7.075209e-01
      vertex   9.603553e-01 -8.565616e-01 3.649468e-01
    endloop
  endfacet
  facet normal 7.070126e-01 -6.551854e-01 2.662055e-01
    outer loop
      vertex   9.603553e-01 -8.565616e-01 3.649468e-01
      vertex   1.000000e-01 -1.645784e+00 7.075209e-01
      vertex   1.000000e-01 -1.672866e+00 6.408652e-01
    endloop
  endfacet
  facet normal 7.070807e-01 -6.559972e-01 2.640162e-01
    outer loop
      vertex   9.603553e-01 -8.565616e-01 3.649468e-01
      vertex   1.000000e-01 -1.672866e+00 6.408652e-01
      vertex   9.603553e-01 -8.705618e-01 3.301606e-01
    endloop
  endfacet
  facet normal 7.070118e-01 -6.653469e-01 2.396826e-01
    outer loop
      vertex   9.603553e-01 -8.705618e-01 3.301606e-01
      vertex   1.000000e-01 -1.672866e+00 6.408652e-01
      vertex   1.000000e-01 -1.697251e+00 5.731758e-01
    endloop
  endfacet
  facet normal 7.070821e-01 -6.660948e-01 2.373872e-01
    outer loop
      vertex   9.603553e-01 -8.705618e-01 3.301606e-01
      vertex   1.000000e-01 -1.697251e+00 5.731758e-01
      vertex   9.603553e-01 -8.831500e-01 2.948388e-01
    endloop
  endfacet
  facet normal 7.070111e-01 -6.744352e-01 2.127731e-01
    outer loop
      vertex   9.603553e-01 -8.831500e-01 2.948388e-01
      vertex   1.000000e-01 -1.697251e+00 5.731758e-01
      vertex   1.000000e-01 -1.718897e+00 5.045619e-01
    endloop
  endfacet
  facet normal 7.070834e-01 -6.751119e-01 2.103734e-01
    outer loop
      vertex   9.603553e-01 -8.831500e-01 2.948388e-01
      vertex   1.000000e-01 -1.718897e+00 5.045619e-01
      vertex   9.603553e-01 -8.943058e-01 2.590388e-01
    endloop
  endfacet
  facet normal 7.070104e-01 -6.824357e-01 1.855203e-01
    outer loop
      vertex   9.603553e-01 -8.943058e-01 2.590388e-01
      vertex   1.000000e-01 -1.718897e+00 5.045619e-01
      vertex   1.000000e-01 -1.737771e+00 4.351341e-01
    endloop
  endfacet
  facet normal 7.070848e-01 -6.830339e-01 1.830184e-01
    outer loop
      vertex   9.603553e-01 -8.943058e-01 2.590388e-01
      vertex   1.000000e-01 -1.737771e+00 4.351341e-01
      vertex   9.603553e-01 -9.040109e-01 2.228187e-01
    endloop
  endfacet
  facet normal 7.070097e-01 -6.893354e-01 1.579682e-01
    outer loop
      vertex   9.603553e-01 -9.040109e-01 2.228187e-01
      vertex   1.000000e-01 -1.737771e+00 4.351341e-01
      vertex   1.000000e-01 -1.753842e+00 3.650044e-01
    endloop
  endfacet
  facet normal 7.070862e-01 -6.898481e-01 1.553667e-01
    outer loop
      vertex   9.603553e-01 -9.040109e-01 2.228187e-01
      vertex   1.000000e-01 -1.753842e+00 3.650044e-01
      vertex   9.603553e-01 -9.122498e-01 1.862371e-01
    endloop
  endfacet
  facet normal 7.070090e-01 -6.951232e-01 1.301612e-01
    outer loop
      vertex   9.603553e-01 -9.122498e-01 1.862371e-01
      vertex   1.000000e-01 -1.753842e+00 3.650044e-01
      vertex   1.000000e-01 -1.767084e+00 2.942860e-01
    endloop
  endfacet
  facet normal 7.070875e-01 -6.955433e-01 1.274630e-01
    outer loop
      vertex   9.603553e-01 -9.122498e-01 1.862371e-01
      vertex   1.000000e-01 -1.767084e+00 2.942860e-01
      vertex   9.603553e-01 -9.190090e-01 1.493535e-01
    endloop
  endfacet
  facet normal 7.070083e-01 -6.997898e-01 1.021443e-01
    outer loop
      vertex   9.603553e-01 -9.190090e-01 1.493535e-01
      vertex   1.000000e-01 -1.767084e+00 2.942860e-01
      vertex   1.000000e-01 -1.777476e+00 2.230929e-01
    endloop
  endfacet
  facet normal 7.070888e-01 -7.001103e-01 9.935277e-02
    outer loop
      vertex   9.603553e-01 -9.190090e-01 1.493535e-01
      vertex   1.000000e-01 -1.777476e+00 2.230929e-01
      vertex   9.603553e-01 -9.242775e-01 1.122276e-01
    endloop
  endfacet
  facet normal 7.070076e-01 -7.033276e-01 7.396249e-02
    outer loop
      vertex   9.603553e-01 -9.242775e-01 1.122276e-01
      vertex   1.000000e-01 -1.777476e+00 2.230929e-01
      vertex   1.000000e-01 -1.785000e+00 1.515399e-01
    endloop
  endfacet
  facet normal 7.070901e-01 -7.035417e-01 7.108146e-02
    outer loop
      vertex   9.603553e-01 -9.242775e-01 1.122276e-01
      vertex   1.000000e-01 -1.785000e+00 1.515399e-01
      vertex   9.603553e-01 -9.280469e-01 7.491969e-02
    endloop
  endfacet
  facet normal 7.070069e-01 -7.057310e-01 4.566136e-02
    outer loop
      vertex   9.603553e-01 -9.280469e-01 7.491969e-02
      vertex   1.000000e-01 -1.785000e+00 1.515399e-01
      vertex   1.000000e-01 -1.789646e+00 7.974254e-02
    endloop
  endfacet
  facet normal 7.070915e-01 -7.058320e-01 4.269497e-02
    outer loop
      vertex   9.603553e-01 -9.280469e-01 7.491969e-02
      vertex   1.000000e-01 -1.789646e+00 7.974254e-02
      vertex   9.603553e-01 -9.303109e-01 3.749025e-02
    endloop
  endfacet
  facet normal 7.070063e-01 -7.069960e-01 1.728652e-02
    outer loop
      vertex   9.603553e-01 -9.303109e-01 3.749025e-02
      vertex   1.000000e-01 -1.789646e+00 7.974254e-02
      vertex   1.000000e-01 -1.791404e+00 7.816525e-03
    endloop
  endfacet
  facet normal 7.070928e-01 -7.069774e-01 1.423933e-02
    outer loop
      vertex   9.603553e-01 -9.303109e-01 3.749025e-02
      vertex   1.000000e-01 -1.791404e+00 7.816525e-03
      vertex   9.603553e-01 -9.310660e-01 5.701135e-17
    endloop
  endfacet
  facet normal 7.070056e-01 -7.071206e-01 -1.111625e-02
    outer loop
      vertex   9.603553e-01 -9.310660e-01 5.701135e-17
      vertex   1.000000e-01 -1.791404e+00 7.816525e-03
      vertex   1.000000e-01 -1.790273e+00 -6.412210e-02
    endloop
  endfacet
  facet normal 7.070941e-01 -7.069761e-01 -1.423930e-02
    outer loop
      vertex   9.603553e-01 -9.310660e-01 5.701135e-17
      vertex   1.000000e-01 -1.790273e+00 -6.412210e-02
      vertex   9.603553e-01 -9.303109e-01 -3.749025e-02
    endloop
  endfacet
  facet normal 7.070049e-01 -7.061046e-01 -3.950115e-02
    outer loop
      vertex   9.603553e-01 -9.303109e-01 -3.749025e-02
      vertex   1.000000e-01 -1.790273e+00 -6.412210e-02
      vertex   1.000000e-01 -1.786255e+00 -1.359573e-01
    endloop
  endfacet
  facet normal 7.070953e-01 -7.058281e-01 -4.269474e-02
    outer loop
      vertex   9.603553e-01 -9.303109e-01 -3.749025e-02
      vertex   1.000000e-01 -1.786255e+00 -1.359573e-01
      vertex   9.603553e-01 -9.280469e-01 -7.491969e-02
    endloop
  endfacet
  facet normal 7.070042e-01 -7.039497e-01 -6.782239e-02
    outer loop
      vertex   9.603553e-01 -9.280469e-01 -7.491969e-02
      vertex   1.000000e-01 -1.786255e+00 -1.359573e-01
      vertex   1.000000e-01 -1.779355e+00 -2.075732e-01
    endloop
  endfacet
  facet normal 7.070966e-01 -7.035353e-01 -7.108081e-02
    outer loop
      vertex   9.603553e-01 -9.280469e-01 -7.491969e-02
      vertex   1.000000e-01 -1.779355e+00 -2.075732e-01
      vertex   9.603553e-01 -9.242775e-01 -1.122276e-01
    endloop
  endfacet
  facet normal 7.070036e-01 -7.006592e-01 -9.603428e-02
    outer loop
      vertex   9.603553e-01 -9.242775e-01 -1.122276e-01
      vertex   1.000000e-01 -1.779355e+00 -2.075732e-01
      vertex   1.000000e-01 -1.769585e+00 -2.788543e-01
    endloop
  endfacet
  facet normal 7.070979e-01 -7.001013e-01 -9.935150e-02
    outer loop
      vertex   9.603553e-01 -9.242775e-01 -1.122276e-01
      vertex   1.000000e-01 -1.769585e+00 -2.788543e-01
      vertex   9.603553e-01 -9.190090e-01 -1.493535e-01
    endloop
  endfacet
  facet normal 7.070029e-01 -6.962386e-01 -1.240913e-01
    outer loop
      vertex   9.603553e-01 -9.190090e-01 -1.493535e-01
      vertex   1.000000e-01 -1.769585e+00 -2.788543e-01
      vertex   1.000000e-01 -1.756961e+00 -3.496855e-01
    endloop
  endfacet
  facet normal 7.070991e-01 -6.955318e-01 -1.274609e-01
    outer loop
      vertex   9.603553e-01 -9.190090e-01 -1.493535e-01
      vertex   1.000000e-01 -1.756961e+00 -3.496855e-01
      vertex   9.603553e-01 -9.122498e-01 -1.862371e-01
    endloop
  endfacet
  facet normal 7.070023e-01 -6.906949e-01 -1.519482e-01
    outer loop
      vertex   9.603553e-01 -9.122498e-01 -1.862371e-01
      vertex   1.000000e-01 -1.756961e+00 -3.496855e-01
      vertex   1.000000e-01 -1.741502e+00 -4.199528e-01
    endloop
  endfacet
  facet normal 7.071004e-01 -6.898342e-01 -1.553635e-01
    outer loop
      vertex   9.603553e-01 -9.122498e-01 -1.862371e-01
      vertex   1.000000e-01 -1.741502e+00 -4.199528e-01
      vertex   9.603553e-01 -9.040109e-01 -2.228187e-01
    endloop
  endfacet
  facet normal 7.070016e-01 -6.840372e-01 -1.795601e-01
    outer loop
      vertex   9.603553e-01 -9.040109e-01 -2.228187e-01
      vertex   1.000000e-01 -1.741502e+00 -4.199528e-01
      vertex   1.000000e-01 -1.723235e+00 -4.895426e-01
    endloop
  endfacet
  facet normal 7.071016e-01 -6.830177e-01 -1.830140e-01
    outer loop
      vertex   9.603553e-01 -9.040109e-01 -2.228187e-01
      vertex   1.000000e-01 -1.723235e+00 -4.895426e-01
      vertex   9.603553e-01 -8.943058e-01 -2.590388e-01
    endloop
  endfacet
  facet normal 7.070010e-01 -6.762760e-01 -2.068824e-01
    outer loop
      vertex   9.603553e-01 -8.943058e-01 -2.590388e-01
      vertex   1.000000e-01 -1.723235e+00 -4.895426e-01
      vertex   1.000000e-01 -1.702188e+00 -5.583428e-01
    endloop
  endfacet
  facet normal 7.071029e-01 -6.750933e-01 -2.103676e-01
    outer loop
      vertex   9.603553e-01 -8.943058e-01 -2.590388e-01
      vertex   1.000000e-01 -1.702188e+00 -5.583428e-01
      vertex   9.603553e-01 -8.831500e-01 -2.948388e-01
    endloop
  endfacet
  facet normal 7.070004e-01 -6.674240e-01 -2.338711e-01
    outer loop
      vertex   9.603553e-01 -8.831500e-01 -2.948388e-01
      vertex   1.000000e-01 -1.702188e+00 -5.583428e-01
      vertex   1.000000e-01 -1.678395e+00 -6.262424e-01
    endloop
  endfacet
  facet normal 7.071041e-01 -6.660740e-01 -2.373798e-01
    outer loop
      vertex   9.603553e-01 -8.831500e-01 -2.948388e-01
      vertex   1.000000e-01 -1.678395e+00 -6.262424e-01
      vertex   9.603553e-01 -8.705618e-01 -3.301606e-01
    endloop
  endfacet
  facet normal 7.069997e-01 -6.574954e-01 -2.604825e-01
    outer loop
      vertex   9.603553e-01 -8.705618e-01 -3.301606e-01
      vertex   1.000000e-01 -1.678395e+00 -6.262424e-01
      vertex   1.000000e-01 -1.651895e+00 -6.931319e-01
    endloop
  endfacet
  facet normal 7.071053e-01 -6.559744e-01 -2.640070e-01
    outer loop
      vertex   9.603553e-01 -8.705618e-01 -3.301606e-01
      vertex   1.000000e-01 -1.651895e+00 -6.931319e-01
      vertex   9.603553e-01 -8.565616e-01 -3.649468e-01
    endloop
  endfacet
  facet normal 7.069991e-01 -6.465063e-01 -2.866739e-01
    outer loop
      vertex   9.603553e-01 -8.565616e-01 -3.649468e-01
      vertex   1.000000e-01 -1.651895e+00 -6.931319e-01
      vertex   1.000000e-01 -1.622731e+00 -7.589034e-01
    endloop
  endfacet
  facet normal 7.071065e-01 -6.448108e-01 -2.902058e-01
    outer loop
      vertex   9.603553e-01 -8.565616e-01 -3.649468e-01
      vertex   1.000000e-01 -1.622731e+00 -7.589034e-01
      vertex   9.603553e-01 -8.411720e-01 -3.991411e-01
    endloop
  endfacet
  facet normal 7.069985e-01 -6.344743e-01 -3.124029e-01
    outer loop
      vertex   9.603553e-01 -8.411720e-01 -3.991411e-01
      vertex   1.000000e-01 -1.622731e+00 -7.589034e-01
      vertex   1.000000e-01 -1.590949e+00 -8.234507e-01
    endloop
  endfacet
  facet normal 7.071077e-01 -6.326014e-01 -3.159338e-01
    outer loop
      vertex   9.603553e-01 -8.411720e-01 -3.991411e-01
      vertex   1.000000e-01 -1.590949e+00 -8.234507e-01
      vertex   9.603553e-01 -8.244180e-01 -4.326880e-01
    endloop
  endfacet
  facet normal 7.069979e-01 -6.214188e-01 -3.376280e-01
    outer loop
      vertex   9.603553e-01 -8.244180e-01 -4.326880e-01
      vertex   1.000000e-01 -1.590949e+00 -8.234507e-01
      vertex   1.000000e-01 -1.556601e+00 -8.866698e-01
    endloop
  endfacet
  facet normal 7.071089e-01 -6.193660e-01 -3.411493e-01
    outer loop
      vertex   9.603553e-01 -8.244180e-01 -4.326880e-01
      vertex   1.000000e-01 -1.556601e+00 -8.866698e-01
      vertex   9.603553e-01 -8.063268e-01 -4.655330e-01
    endloop
  endfacet
  facet normal 7.069972e-01 -6.073610e-01 -3.623086e-01
    outer loop
      vertex   9.603553e-01 -8.063268e-01 -4.655330e-01
      vertex   1.000000e-01 -1.556601e+00 -8.866698e-01
      vertex   1.000000e-01 -1.519742e+00 -9.484587e-01
    endloop
  endfacet
  facet normal 7.071101e-01 -6.051259e-01 -3.658114e-01
    outer loop
      vertex   9.603553e-01 -8.063268e-01 -4.655330e-01
      vertex   1.000000e-01 -1.519742e+00 -9.484587e-01
      vertex   9.603553e-01 -7.869278e-01 -4.976230e-01
    endloop
  endfacet
  facet normal 7.069966e-01 -5.923235e-01 -3.864047e-01
    outer loop
      vertex   9.603553e-01 -7.869278e-01 -4.976230e-01
      vertex   1.000000e-01 -1.519742e+00 -9.484587e-01
      vertex   1.000000e-01 -1.480432e+00 -1.008718e+00
    endloop
  endfacet
  facet normal 7.071112e-01 -5.899045e-01 -3.898800e-01
    outer loop
      vertex   9.603553e-01 -7.869278e-01 -4.976230e-01
      vertex   1.000000e-01 -1.480432e+00 -1.008718e+00
      vertex   9.603553e-01 -7.662523e-01 -5.289058e-01
    endloop
  endfacet
  facet normal 7.069960e-01 -5.763305e-01 -4.098777e-01
    outer loop
      vertex   9.603553e-01 -7.662523e-01 -5.289058e-01
      vertex   1.000000e-01 -1.480432e+00 -1.008718e+00
      vertex   1.000000e-01 -1.438734e+00 -1.067350e+00
    endloop
  endfacet
  facet normal 7.071124e-01 -5.737262e-01 -4.133162e-01
    outer loop
      vertex   9.603553e-01 -7.662523e-01 -5.289058e-01
      vertex   1.000000e-01 -1.438734e+00 -1.067350e+00
      vertex   9.603553e-01 -7.443340e-01 -5.593307e-01
    endloop
  endfacet
  facet normal 7.069954e-01 -5.594079e-01 -4.326896e-01
    outer loop
      vertex   9.603553e-01 -7.443340e-01 -5.593307e-01
      vertex   1.000000e-01 -1.438734e+00 -1.067350e+00
      vertex   1.000000e-01 -1.394715e+00 -1.124260e+00
    endloop
  endfacet
  facet normal 7.071135e-01 -5.566175e-01 -4.360819e-01
    outer loop
      vertex   9.603553e-01 -7.443340e-01 -5.593307e-01
      vertex   1.000000e-01 -1.394715e+00 -1.124260e+00
      vertex   9.603553e-01 -7.212084e-01 -5.888484e-01
    endloop
  endfacet
  facet normal 7.069948e-01 -5.415829e-01 -4.548035e-01
    outer loop
      vertex   9.603553e-01 -7.212084e-01 -5.888484e-01
      vertex   1.000000e-01 -1.394715e+00 -1.124260e+00
      vertex   1.000000e-01 -1.348446e+00 -1.179357e+00
    endloop
  endfacet
  facet normal 7.071147e-01 -5.386059e-01 -4.581403e-01
    outer loop
      vertex   9.603553e-01 -7.212084e-01 -5.888484e-01
      vertex   1.000000e-01 -1.348446e+00 -1.179357e+00
      vertex   9.603553e-01 -6.969129e-01 -6.174110e-01
    endloop
  endfacet
  facet normal 7.069942e-01 -5.228843e-01 -4.761839e-01
    outer loop
      vertex   9.603553e-01 -6.969129e-01 -6.174110e-01
      vertex   1.000000e-01 -1.348446e+00 -1.179357e+00
      vertex   1.000000e-01 -1.300003e+00 -1.232551e+00
    endloop
  endfacet
  facet normal 7.071158e-01 -5.197208e-01 -4.794554e-01
    outer loop
      vertex   9.603553e-01 -6.969129e-01 -6.174110e-01
      vertex   1.000000e-01 -1.300003e+00 -1.232551e+00
      vertex   9.603553e-01 -6.714871e-01 -6.449721e-01
    endloop
  endfacet
  facet normal 7.069937e-01 -5.033423e-01 -4.967963e-01
    outer loop
      vertex   9.603553e-01 -6.714871e-01 -6.449721e-01
      vertex   1.000000e-01 -1.300003e+00 -1.232551e+00
      vertex   1.000000e-01 -1.249462e+00 -1.283758e+00
    endloop
  endfacet
  facet normal 7.071169e-01 -4.999928e-01 -4.999928e-01
    outer loop
      vertex   9.603553e-01 -6.714871e-01 -6.449721e-01
      vertex   1.000000e-01 -1.249462e+00 -1.283758e+00
      vertex   9.603553e-01 -6.449721e-01 -6.714871e-01
    endloop
  endfacet
  facet normal 7.069931e-01 -4.829883e-01 -5.166073e-01
    outer loop
      vertex   9.603553e-01 -6.449721e-01 -6.714871e-01
      vertex   1.000000e-01 -1.249462e+00 -1.283758e+00
      vertex   1.000000e-01 -1.196906e+00 -1.332894e+00
    endloop
  endfacet
  facet normal 7.071180e-01 -4.794539e-01 -5.197192e-01
    outer loop
      vertex   9.603553e-01 -6.449721e-01 -6.714871e-01
      vertex   1.000000e-01 -1.196906e+00 -1.332894e+00
      vertex   9.603553e-01 -6.174110e-01 -6.969129e-01
    endloop
  endfacet
  facet normal 7.069925e-01 -4.618552e-01 -5.355851e-01
    outer loop
      vertex   9.603553e-01 -6.174110e-01 -6.969129e-01
      vertex   1.000000e-01 -1.196906e+00 -1.332894e+00
      vertex   1.000000e-01 -1.142420e+00 -1.379879e+00
    endloop
  endfacet
  facet normal 7.071191e-01 -4.581374e-01 -5.386025e-01
    outer loop
      vertex   9.603553e-01 -6.174110e-01 -6.969129e-01
      vertex   1.000000e-01 -1.142420e+00 -1.379879e+00
      vertex   9.603553e-01 -5.888484e-01 -7.212084e-01
    endloop
  endfacet
  facet normal 7.069919e-01 -4.399771e-01 -5.536990e-01
    outer loop
      vertex   9.603553e-01 -5.888484e-01 -7.212084e-01
      vertex   1.000000e-01 -1.142420e+00 -1.379879e+00
      vertex   1.000000e-01 -1.086091e+00 -1.424639e+00
    endloop
  endfacet
  facet normal 7.071202e-01 -4.360778e-01 -5.566122e-01
    outer loop
      vertex   9.603553e-01 -5.888484e-01 -7.212084e-01
      vertex   1.000000e-01 -1.086091e+00 -1.424639e+00
      vertex   9.603553e-01 -5.593307e-01 -7.443340e-01
    endloop
  endfacet
  facet normal 7.069914e-01 -4.173893e-01 -5.709198e-01
    outer loop
      vertex   9.603553e-01 -5.593307e-01 -7.443340e-01
      vertex   1.000000e-01 -1.086091e+00 -1.424639e+00
      vertex   1.000000e-01 -1.028010e+00 -1.467102e+00
    endloop
  endfacet
  facet normal 7.071213e-01 -4.133110e-01 -5.737190e-01
    outer loop
      vertex   9.603553e-01 -5.593307e-01 -7.443340e-01
      vertex   1.000000e-01 -1.028010e+00 -1.467102e+00
      vertex   9.603553e-01 -5.289058e-01 -7.662523e-01
    endloop
  endfacet
  facet normal 7.069908e-01 -3.941282e-01 -5.872197e-01
    outer loop
      vertex   9.603553e-01 -5.289058e-01 -7.662523e-01
      vertex   1.000000e-01 -1.028010e+00 -1.467102e+00
      vertex   1.000000e-01 -9.682702e-01 -1.507197e+00
    endloop
  endfacet
  facet normal 7.071224e-01 -3.898739e-01 -5.898952e-01
    outer loop
      vertex   9.603553e-01 -5.289058e-01 -7.662523e-01
      vertex   1.000000e-01 -9.682702e-01 -1.507197e+00
      vertex   9.603553e-01 -4.976230e-01 -7.869278e-01
    endloop
  endfacet
  facet normal 7.069903e-01 -3.702313e-01 -6.025725e-01
    outer loop
      vertex   9.603553e-01 -4.976230e-01 -7.869278e-01
      vertex   1.000000e-01 -9.682702e-01 -1.507197e+00
      vertex   1.000000e-01 -9.069691e-01 -1.544862e+00
    endloop
  endfacet
  facet normal 7.071234e-01 -3.658045e-01 -6.051145e-01
    outer loop
      vertex   9.603553e-01 -4.976230e-01 -7.869278e-01
      vertex   1.000000e-01 -9.069691e-01 -1.544862e+00
      vertex   9.603553e-01 -4.655330e-01 -8.063268e-01
    endloop
  endfacet
  facet normal 7.069897e-01 -3.457372e-01 -6.169533e-01
    outer loop
      vertex   9.603553e-01 -4.655330e-01 -8.063268e-01
      vertex   1.000000e-01 -9.069691e-01 -1.544862e+00
      vertex   1.000000e-01 -8.442050e-01 -1.580034e+00
    endloop
  endfacet
  facet normal 7.071245e-01 -3.411418e-01 -6.193523e-01
    outer loop
      vertex   9.603553e-01 -4.655330e-01 -8.063268e-01
      vertex   1.000000e-01 -8.442050e-01 -1.580034e+00
      vertex   9.603553e-01 -4.326880e-01 -8.244180e-01
    endloop
  endfacet
  facet normal 7.069892e-01 -3.206853e-01 -6.303390e-01
    outer loop
      vertex   9.603553e-01 -4.326880e-01 -8.244180e-01
      vertex   1.000000e-01 -8.442050e-01 -1.580034e+00
      vertex   1.000000e-01 -7.800792e-01 -1.612658e+00
    endloop
  endfacet
  facet normal 7.071255e-01 -3.159258e-01 -6.325854e-01
    outer loop
      vertex   9.603553e-01 -4.326880e-01 -8.244180e-01
      vertex   1.000000e-01 -7.800792e-01 -1.612658e+00
      vertex   9.603553e-01 -3.991411e-01 -8.411720e-01
    endloop
  endfacet
  facet normal 7.069886e-01 -2.951162e-01 -6.427080e-01
    outer loop
      vertex   9.603553e-01 -3.991411e-01 -8.411720e-01
      vertex   1.000000e-01 -7.800792e-01 -1.612658e+00
      vertex   1.000000e-01 -7.146952e-01 -1.642681e+00
    endloop
  endfacet
  facet normal 7.071266e-01 -2.901976e-01 -6.447925e-01
    outer loop
      vertex   9.603553e-01 -3.991411e-01 -8.411720e-01
      vertex   1.000000e-01 -7.146952e-01 -1.642681e+00
      vertex   9.603553e-01 -3.649468e-01 -8.565616e-01
    endloop
  endfacet
  facet normal 7.069881e-01 -2.690710e-01 -6.540403e-01
    outer loop
      vertex   9.603553e-01 -3.649468e-01 -8.565616e-01
      vertex   1.000000e-01 -7.146952e-01 -1.642681e+00
      vertex   1.000000e-01 -6.481583e-01 -1.670054e+00
    endloop
  endfacet
  facet normal 7.071276e-01 -2.639986e-01 -6.559537e-01
    outer loop
      vertex   9.603553e-01 -3.649468e-01 -8.565616e-01
      vertex   1.000000e-01 -6.481583e-01 -1.670054e+00
      vertex   9.603553e-01 -3.301606e-01 -8.705618e-01
    endloop
  endfacet
  facet normal 7.069875e-01 -2.425918e-01 -6.643176e-01
    outer loop
      vertex   9.603553e-01 -3.301606e-01 -8.705618e-01
      vertex   1.000000e-01 -6.481583e-01 -1.670054e+00
      vertex   1.000000e-01 -5.805760e-01 -1.694734e+00
    endloop
  endfacet
  facet normal 7.071286e-01 -2.373716e-01 -6.660509e-01
    outer loop
      vertex   9.603553e-01 -3.301606e-01 -8.705618e-01
      vertex   1.000000e-01 -5.805760e-01 -1.694734e+00
      vertex   9.603553e-01 -2.948388e-01 -8.831500e-01
    endloop
  endfacet
  facet normal 7.069870e-01 -2.157212e-01 -6.735234e-01
    outer loop
      vertex   9.603553e-01 -2.948388e-01 -8.831500e-01
      vertex   1.000000e-01 -5.805760e-01 -1.694734e+00
      vertex   1.000000e-01 -5.120571e-01 -1.716679e+00
    endloop
  endfacet
  facet normal 7.071296e-01 -2.103596e-01 -6.750678e-01
    outer loop
      vertex   9.603553e-01 -2.948388e-01 -8.831500e-01
      vertex   1.000000e-01 -5.120571e-01 -1.716679e+00
      vertex   9.603553e-01 -2.590388e-01 -8.943058e-01
    endloop
  endfacet
  facet normal 7.069865e-01 -1.885026e-01 -6.816428e-01
    outer loop
      vertex   9.603553e-01 -2.590388e-01 -8.943058e-01
      vertex   1.000000e-01 -5.120571e-01 -1.716679e+00
      vertex   1.000000e-01 -4.427124e-01 -1.735856e+00
    endloop
  endfacet
  facet normal 7.071306e-01 -1.830065e-01 -6.829897e-01
    outer loop
      vertex   9.603553e-01 -2.590388e-01 -8.943058e-01
      vertex   1.000000e-01 -4.427124e-01 -1.735856e+00
      vertex   9.603553e-01 -2.228187e-01 -9.040109e-01
    endloop
  endfacet
  facet normal 7.069860e-01 -1.609799e-01 -6.886627e-01
    outer loop
      vertex   9.603553e-01 -2.228187e-01 -9.040109e-01
      vertex   1.000000e-01 -4.427124e-01 -1.735856e+00
      vertex   1.000000e-01 -3.726535e-01 -1.752233e+00
    endloop
  endfacet
  facet normal 7.071316e-01 -1.553567e-01 -6.898037e-01
    outer loop
      vertex   9.603553e-01 -2.228187e-01 -9.040109e-01
      vertex   1.000000e-01 -3.726535e-01 -1.752233e+00
      vertex   9.603553e-01 -1.862371e-01 -9.122498e-01
    endloop
  endfacet
  facet normal 7.069855e-01 -1.331975e-01 -6.945718e-01
    outer loop
      vertex   9.603553e-01 -1.862371e-01 -9.122498e-01
      vertex   1.000000e-01 -3.726535e-01 -1.752233e+00
      vertex   1.000000e-01 -3.019935e-01 -1.765783e+00
    endloop
  endfacet
  facet normal 7.071326e-01 -1.274549e-01 -6.954989e-01
    outer loop
      vertex   9.603553e-01 -1.862371e-01 -9.122498e-01
      vertex   1.000000e-01 -3.019935e-01 -1.765783e+00
      vertex   9.603553e-01 -1.493535e-01 -9.190090e-01
    endloop
  endfacet
  facet normal 7.069850e-01 -1.052002e-01 -6.993606e-01
    outer loop
      vertex   9.603553e-01 -1.493535e-01 -9.190090e-01
      vertex   1.000000e-01 -3.019935e-01 -1.765783e+00
      vertex   1.000000e-01 -2.308464e-01 -1.776485e+00
    endloop
  endfacet
  facet normal 7.071336e-01 -9.934649e-02 -7.000660e-01
    outer loop
      vertex   9.603553e-01 -1.493535e-01 -9.190090e-01
      vertex   1.000000e-01 -2.308464e-01 -1.776485e+00
      vertex   9.603553e-01 -1.122276e-01 -9.242775e-01
    endloop
  endfacet
  facet normal 7.069845e-01 -7.703315e-02 -7.030212e-01
    outer loop
      vertex   9.603553e-01 -1.122276e-01 -9.242775e-01
      vertex   1.000000e-01 -2.308464e-01 -1.776485e+00
      vertex   1.000000e-01 -1.593270e-01 -1.784322e+00
    endloop
  endfacet
  facet normal 7.071345e-01 -7.107700e-02 -7.034976e-01
    outer loop
      vertex   9.603553e-01 -1.122276e-01 -9.242775e-01
      vertex   1.000000e-01 -1.593270e-01 -1.784322e+00
      vertex   9.603553e-01 -7.491969e-02 -9.280469e-01
    endloop
  endfacet
  facet normal 7.069840e-01 -4.874183e-02 -7.055480e-01
    outer loop
      vertex   9.603553e-01 -7.491969e-02 -9.280469e-01
      vertex   1.000000e-01 -1.593270e-01 -1.784322e+00
      vertex   1.000000e-01 -8.755056e-02 -1.789281e+00
    endloop
  endfacet
  facet normal 7.071355e-01 -4.269231e-02 -7.057881e-01
    outer loop
      vertex   9.603553e-01 -7.491969e-02 -9.280469e-01
      vertex   1.000000e-01 -8.755056e-02 -1.789281e+00
      vertex   9.603553e-01 -3.749025e-02 -9.303109e-01
    endloop
  endfacet
  facet normal 7.069835e-01 -2.037186e-02 -7.069366e-01
    outer loop
      vertex   9.603553e-01 -3.749025e-02 -9.303109e-01
      vertex   1.000000e-01 -8.755056e-02 -1.789281e+00
      vertex   1.000000e-01 -1.563290e-02 -1.791353e+00
    endloop
  endfacet
  facet normal 7.071364e-01 -1.423845e-02 -7.069338e-01
    outer loop
      vertex   9.603553e-01 -3.749025e-02 -9.303109e-01
      vertex   1.000000e-01 -1.563290e-02 -1.791353e+00
      vertex   9.603553e-01 -1.140227e-16 -9.310660e-01
    endloop
  endfacet
  facet normal 7.069830e-01 8.031016e-03 -7.071850e-01
    outer loop
      vertex   9.603553e-01 -1.140227e-16 -9.310660e-01
      vertex   1.000000e-01 -1.563290e-02 -1.791353e+00
      vertex   1.000000e-01 5.630997e-02 -1.790536e+00
    endloop
  endfacet
  facet normal 7.071374e-01 1.423843e-02 -7.069328e-01
    outer loop
      vertex   9.603553e-01 -1.140227e-16 -9.310660e-01
      vertex   1.000000e-01 5.630997e-02 -1.790536e+00
      vertex   9.603553e-01 3.749025e-02 -9.303109e-01
    endloop
  endfacet
  facet normal 7.069825e-01 3.642098e-02 -7.062926e-01
    outer loop
      vertex   9.603553e-01 3.749025e-02 -9.303109e-01
      vertex   1.000000e-01 5.630997e-02 -1.790536e+00
      vertex   1.000000e-01 1.281620e-01 -1.786831e+00
    endloop
  endfacet
  facet normal 7.071383e-01 4.269214e-02 -7.057853e-01
    outer loop
      vertex   9.603553e-01 3.749025e-02 -9.303109e-01
      vertex   1.000000e-01 1.281620e-01 -1.786831e+00
      vertex   9.603553e-01 7.491969e-02 -9.280469e-01
    endloop
  endfacet
  facet normal 7.069820e-01 6.475223e-02 -7.042610e-01
    outer loop
      vertex   9.603553e-01 7.491969e-02 -9.280469e-01
      vertex   1.000000e-01 1.281620e-01 -1.786831e+00
      vertex   1.000000e-01 1.998073e-01 -1.780244e+00
    endloop
  endfacet
  facet normal 7.071392e-01 7.107653e-02 -7.034929e-01
    outer loop
      vertex   9.603553e-01 7.491969e-02 -9.280469e-01
      vertex   1.000000e-01 1.998073e-01 -1.780244e+00
      vertex   9.603553e-01 1.122276e-01 -9.242775e-01
    endloop
  endfacet
  facet normal 7.069815e-01 9.297907e-02 -7.010934e-01
    outer loop
      vertex   9.603553e-01 1.122276e-01 -9.242775e-01
      vertex   1.000000e-01 1.998073e-01 -1.780244e+00
      vertex   1.000000e-01 2.711304e-01 -1.770785e+00
    endloop
  endfacet
  facet normal 7.071401e-01 9.934557e-02 -7.000595e-01
    outer loop
      vertex   9.603553e-01 1.122276e-01 -9.242775e-01
      vertex   1.000000e-01 2.711304e-01 -1.770785e+00
      vertex   9.603553e-01 1.493535e-01 -9.190090e-01
    endloop
  endfacet
  facet normal 7.069811e-01 1.210560e-01 -6.967950e-01
    outer loop
      vertex   9.603553e-01 1.493535e-01 -9.190090e-01
      vertex   1.000000e-01 2.711304e-01 -1.770785e+00
      vertex   1.000000e-01 3.420160e-01 -1.758470e+00
    endloop
  endfacet
  facet normal 7.071410e-01 1.274534e-01 -6.954906e-01
    outer loop
      vertex   9.603553e-01 1.493535e-01 -9.190090e-01
      vertex   1.000000e-01 3.420160e-01 -1.758470e+00
      vertex   9.603553e-01 1.862371e-01 -9.122498e-01
    endloop
  endfacet
  facet normal 7.069806e-01 1.489376e-01 -6.913726e-01
    outer loop
      vertex   9.603553e-01 1.862371e-01 -9.122498e-01
      vertex   1.000000e-01 3.420160e-01 -1.758470e+00
      vertex   1.000000e-01 4.123501e-01 -1.743318e+00
    endloop
  endfacet
  facet normal 7.071419e-01 1.553544e-01 -6.897937e-01
    outer loop
      vertex   9.603553e-01 1.862371e-01 -9.122498e-01
      vertex   1.000000e-01 4.123501e-01 -1.743318e+00
      vertex   9.603553e-01 2.228187e-01 -9.040109e-01
    endloop
  endfacet
  facet normal 7.069801e-01 1.765791e-01 -6.848349e-01
    outer loop
      vertex   9.603553e-01 2.228187e-01 -9.040109e-01
      vertex   1.000000e-01 4.123501e-01 -1.743318e+00
      vertex   1.000000e-01 4.820190e-01 -1.725355e+00
    endloop
  endfacet
  facet normal 7.071428e-01 1.830034e-01 -6.829779e-01
    outer loop
      vertex   9.603553e-01 2.228187e-01 -9.040109e-01
      vertex   1.000000e-01 4.820190e-01 -1.725355e+00
      vertex   9.603553e-01 2.590388e-01 -8.943058e-01
    endloop
  endfacet
  facet normal 7.069797e-01 2.039358e-01 -6.771927e-01
    outer loop
      vertex   9.603553e-01 2.590388e-01 -8.943058e-01
      vertex   1.000000e-01 4.820190e-01 -1.725355e+00
      vertex   1.000000e-01 5.509104e-01 -1.704608e+00
    endloop
  endfacet
  facet normal 7.071437e-01 2.103555e-01 -6.750544e-01
    outer loop
      vertex   9.603553e-01 2.590388e-01 -8.943058e-01
      vertex   1.000000e-01 5.509104e-01 -1.704608e+00
      vertex   9.603553e-01 2.948388e-01 -8.831500e-01
    endloop
  endfacet
  facet normal 7.069792e-01 2.309636e-01 -6.684581e-01
    outer loop
      vertex   9.603553e-01 2.948388e-01 -8.831500e-01
      vertex   1.000000e-01 5.509104e-01 -1.704608e+00
      vertex   1.000000e-01 6.189131e-01 -1.681112e+00
    endloop
  endfacet
  facet normal 7.071445e-01 2.373663e-01 -6.660360e-01
    outer loop
      vertex   9.603553e-01 2.948388e-01 -8.831500e-01
      vertex   1.000000e-01 6.189131e-01 -1.681112e+00
      vertex   9.603553e-01 3.301606e-01 -8.705618e-01
    endloop
  endfacet
  facet normal 7.069788e-01 2.576188e-01 -6.586452e-01
    outer loop
      vertex   9.603553e-01 3.301606e-01 -8.705618e-01
      vertex   1.000000e-01 6.189131e-01 -1.681112e+00
      vertex   1.000000e-01 6.859176e-01 -1.654904e+00
    endloop
  endfacet
  facet normal 7.071454e-01 2.639920e-01 -6.559372e-01
    outer loop
      vertex   9.603553e-01 3.301606e-01 -8.705618e-01
      vertex   1.000000e-01 6.859176e-01 -1.654904e+00
      vertex   9.603553e-01 3.649468e-01 -8.565616e-01
    endloop
  endfacet
  facet normal 7.069783e-01 2.838586e-01 -6.477700e-01
    outer loop
      vertex   9.603553e-01 3.649468e-01 -8.565616e-01
      vertex   1.000000e-01 6.859176e-01 -1.654904e+00
      vertex   1.000000e-01 7.518157e-01 -1.626027e+00
    endloop
  endfacet
  facet normal 7.071462e-01 2.901895e-01 -6.447746e-01
    outer loop
      vertex   9.603553e-01 3.649468e-01 -8.565616e-01
      vertex   1.000000e-01 7.518157e-01 -1.626027e+00
      vertex   9.603553e-01 3.991411e-01 -8.411720e-01
    endloop
  endfacet
  facet normal 7.069779e-01 3.096405e-01 -6.358498e-01
    outer loop
      vertex   9.603553e-01 3.991411e-01 -8.411720e-01
      vertex   1.000000e-01 7.518157e-01 -1.626027e+00
      vertex   1.000000e-01 8.165011e-01 -1.594527e+00
    endloop
  endfacet
  facet normal 7.071470e-01 3.159162e-01 -6.325662e-01
    outer loop
      vertex   9.603553e-01 3.991411e-01 -8.411720e-01
      vertex   1.000000e-01 8.165011e-01 -1.594527e+00
      vertex   9.603553e-01 4.326880e-01 -8.244180e-01
    endloop
  endfacet
  facet normal 7.069775e-01 3.349230e-01 -6.229040e-01
    outer loop
      vertex   9.603553e-01 4.326880e-01 -8.244180e-01
      vertex   1.000000e-01 8.165011e-01 -1.594527e+00
      vertex   1.000000e-01 8.798694e-01 -1.560455e+00
    endloop
  endfacet
  facet normal 7.071479e-01 3.411305e-01 -6.193318e-01
    outer loop
      vertex   9.603553e-01 4.326880e-01 -8.244180e-01
      vertex   1.000000e-01 8.798694e-01 -1.560455e+00
      vertex   9.603553e-01 4.655330e-01 -8.063268e-01
    endloop
  endfacet
  facet normal 7.069771e-01 3.596653e-01 -6.089535e-01
    outer loop
      vertex   9.603553e-01 4.655330e-01 -8.063268e-01
      vertex   1.000000e-01 8.798694e-01 -1.560455e+00
      vertex   1.000000e-01 9.418186e-01 -1.523866e+00
    endloop
  endfacet
  facet normal 7.071487e-01 3.657914e-01 -6.050929e-01
    outer loop
      vertex   9.603553e-01 4.655330e-01 -8.063268e-01
      vertex   1.000000e-01 9.418186e-01 -1.523866e+00
      vertex   9.603553e-01 4.976230e-01 -7.869278e-01
    endloop
  endfacet
  facet normal 7.069766e-01 3.838274e-01 -5.940207e-01
    outer loop
      vertex   9.603553e-01 4.976230e-01 -7.869278e-01
      vertex   1.000000e-01 9.418186e-01 -1.523866e+00
      vertex   1.000000e-01 1.002249e+00 -1.484819e+00
    endloop
  endfacet
  facet normal 7.071495e-01 3.898589e-01 -5.898725e-01
    outer loop
      vertex   9.603553e-01 4.976230e-01 -7.869278e-01
      vertex   1.000000e-01 1.002249e+00 -1.484819e+00
      vertex   9.603553e-01 5.289058e-01 -7.662523e-01
    endloop
  endfacet
  facet normal 7.069762e-01 4.073705e-01 -5.781297e-01
    outer loop
      vertex   9.603553e-01 5.289058e-01 -7.662523e-01
      vertex   1.000000e-01 1.002249e+00 -1.484819e+00
      vertex   1.000000e-01 1.061062e+00 -1.443377e+00
    endloop
  endfacet
  facet normal 7.071503e-01 4.132941e-01 -5.736955e-01
    outer loop
      vertex   9.603553e-01 5.289058e-01 -7.662523e-01
      vertex   1.000000e-01 1.061062e+00 -1.443377e+00
      vertex   9.603553e-01 5.593307e-01 -7.443340e-01
    endloop
  endfacet
  facet normal 7.069758e-01 4.302565e-01 -5.613061e-01
    outer loop
      vertex   9.603553e-01 5.593307e-01 -7.443340e-01
      vertex   1.000000e-01 1.061062e+00 -1.443377e+00
      vertex   1.000000e-01 1.118164e+00 -1.399607e+00
    endloop
  endfacet
  facet normal 7.071511e-01 4.360588e-01 -5.565879e-01
    outer loop
      vertex   9.603553e-01 5.593307e-01 -7.443340e-01
      vertex   1.000000e-01 1.118164e+00 -1.399607e+00
      vertex   9.603553e-01 5.888484e-01 -7.212084e-01
    endloop
  endfacet
  facet normal 7.069754e-01 4.524485e-01 -5.435771e-01
    outer loop
      vertex   9.603553e-01 5.888484e-01 -7.212084e-01
      vertex   1.000000e-01 1.118164e+00 -1.399607e+00
      vertex   1.000000e-01 1.173462e+00 -1.353580e+00
    endloop
  endfacet
  facet normal 7.071519e-01 4.581162e-01 -5.385776e-01
    outer loop
      vertex   9.603553e-01 5.888484e-01 -7.212084e-01
      vertex   1.000000e-01 1.173462e+00 -1.353580e+00
      vertex   9.603553e-01 6.174110e-01 -6.969129e-01
    endloop
  endfacet
  facet normal 7.069750e-01 4.739108e-01 -5.249714e-01
    outer loop
      vertex   9.603553e-01 6.174110e-01 -6.969129e-01
      vertex   1.000000e-01 1.173462e+00 -1.353580e+00
      vertex   1.000000e-01 1.226867e+00 -1.305368e+00
    endloop
  endfacet
  facet normal 7.071526e-01 4.794304e-01 -5.196938e-01
    outer loop
      vertex   9.603553e-01 6.174110e-01 -6.969129e-01
      vertex   1.000000e-01 1.226867e+00 -1.305368e+00
      vertex   9.603553e-01 6.449721e-01 -6.714871e-01
    endloop
  endfacet
  facet normal 7.069746e-01 4.946086e-01 -5.055188e-01
    outer loop
      vertex   9.603553e-01 6.449721e-01 -6.714871e-01
      vertex   1.000000e-01 1.226867e+00 -1.305368e+00
      vertex   1.000000e-01 1.278294e+00 -1.255052e+00
    endloop
  endfacet
  facet normal 7.071534e-01 4.999670e-01 -4.999670e-01
    outer loop
      vertex   9.603553e-01 6.449721e-01 -6.714871e-01
      vertex   1.000000e-01 1.278294e+00 -1.255052e+00
      vertex   9.603553e-01 6.714871e-01 -6.449721e-01
    endloop
  endfacet
  facet normal 7.069742e-01 5.145087e-01 -4.852507e-01
    outer loop
      vertex   9.603553e-01 6.714871e-01 -6.449721e-01
      vertex   1.000000e-01 1.278294e+00 -1.255052e+00
      vertex   1.000000e-01 1.327658e+00 -1.202711e+00
    endloop
  endfacet
  facet normal 7.071541e-01 5.196927e-01 -4.794294e-01
    outer loop
      vertex   9.603553e-01 6.714871e-01 -6.449721e-01
      vertex   1.000000e-01 1.327658e+00 -1.202711e+00
      vertex   9.603553e-01 6.969129e-01 -6.174110e-01
    endloop
  endfacet
  facet normal 7.069738e-01 5.335789e-01 -4.642000e-01
    outer loop
      vertex   9.603553e-01 6.969129e-01 -6.174110e-01
      vertex   1.000000e-01 1.327658e+00 -1.202711e+00
      vertex   1.000000e-01 1.374882e+00 -1.148430e+00
    endloop
  endfacet
  facet normal 7.071549e-01 5.385753e-01 -4.581142e-01
    outer loop
      vertex   9.603553e-01 6.969129e-01 -6.174110e-01
      vertex   1.000000e-01 1.374882e+00 -1.148430e+00
      vertex   9.603553e-01 7.212084e-01 -5.888484e-01
    endloop
  endfacet
  facet normal 7.069734e-01 5.517884e-01 -4.424004e-01
    outer loop
      vertex   9.603553e-01 7.212084e-01 -5.888484e-01
      vertex   1.000000e-01 1.374882e+00 -1.148430e+00
      vertex   1.000000e-01 1.419887e+00 -1.092296e+00
    endloop
  endfacet
  facet normal 7.071556e-01 5.565843e-01 -4.360560e-01
    outer loop
      vertex   9.603553e-01 7.212084e-01 -5.888484e-01
      vertex   1.000000e-01 1.419887e+00 -1.092296e+00
      vertex   9.603553e-01 7.443340e-01 -5.593307e-01
    endloop
  endfacet
  facet normal 7.069731e-01 5.691079e-01 -4.198873e-01
    outer loop
      vertex   9.603553e-01 7.443340e-01 -5.593307e-01
      vertex   1.000000e-01 1.419887e+00 -1.092296e+00
      vertex   1.000000e-01 1.462602e+00 -1.034401e+00
    endloop
  endfacet
  facet normal 7.071563e-01 5.736906e-01 -4.132905e-01
    outer loop
      vertex   9.603553e-01 7.443340e-01 -5.593307e-01
      vertex   1.000000e-01 1.462602e+00 -1.034401e+00
      vertex   9.603553e-01 7.662523e-01 -5.289058e-01
    endloop
  endfacet
  facet normal 7.069727e-01 5.855094e-01 -3.966968e-01
    outer loop
      vertex   9.603553e-01 7.662523e-01 -5.289058e-01
      vertex   1.000000e-01 1.462602e+00 -1.034401e+00
      vertex   1.000000e-01 1.502958e+00 -9.748374e-01
    endloop
  endfacet
  facet normal 7.071570e-01 5.898662e-01 -3.898548e-01
    outer loop
      vertex   9.603553e-01 7.662523e-01 -5.289058e-01
      vertex   1.000000e-01 1.502958e+00 -9.748374e-01
      vertex   9.603553e-01 7.869278e-01 -4.976230e-01
    endloop
  endfacet
  facet normal 7.069723e-01 6.009665e-01 -3.728664e-01
    outer loop
      vertex   9.603553e-01 7.869278e-01 -4.976230e-01
      vertex   1.000000e-01 1.502958e+00 -9.748374e-01
      vertex   1.000000e-01 1.540890e+00 -9.137012e-01
    endloop
  endfacet
  facet normal 7.071577e-01 6.050851e-01 -3.657867e-01
    outer loop
      vertex   9.603553e-01 7.869278e-01 -4.976230e-01
      vertex   1.000000e-01 1.540890e+00 -9.137012e-01
      vertex   9.603553e-01 8.063268e-01 -4.655330e-01
    endloop
  endfacet
  facet normal 7.069719e-01 6.154543e-01 -3.484346e-01
    outer loop
      vertex   9.603553e-01 8.063268e-01 -4.655330e-01
      vertex   1.000000e-01 1.540890e+00 -9.137012e-01
      vertex   1.000000e-01 1.576336e+00 -8.510912e-01
    endloop
  endfacet
  facet normal 7.071584e-01 6.193225e-01 -3.411254e-01
    outer loop
      vertex   9.603553e-01 8.063268e-01 -4.655330e-01
      vertex   1.000000e-01 1.576336e+00 -8.510912e-01
      vertex   9.603553e-01 8.244180e-01 -4.326880e-01
    endloop
  endfacet
  facet normal 7.069716e-01 6.289494e-01 -3.234407e-01
    outer loop
      vertex   9.603553e-01 8.244180e-01 -4.326880e-01
      vertex   1.000000e-01 1.576336e+00 -8.510912e-01
      vertex   1.000000e-01 1.609239e+00 -7.871083e-01
    endloop
  endfacet
  facet normal 7.071591e-01 6.325554e-01 -3.159108e-01
    outer loop
      vertex   9.603553e-01 8.244180e-01 -4.326880e-01
      vertex   1.000000e-01 1.609239e+00 -7.871083e-01
      vertex   9.603553e-01 8.411720e-01 -3.991411e-01
    endloop
  endfacet
  facet normal 7.069712e-01 6.414299e-01 -2.979250e-01
    outer loop
      vertex   9.603553e-01 8.411720e-01 -3.991411e-01
      vertex   1.000000e-01 1.609239e+00 -7.871083e-01
      vertex   1.000000e-01 1.639547e+00 -7.218559e-01
    endloop
  endfacet
  facet normal 7.071598e-01 6.447622e-01 -2.901839e-01
    outer loop
      vertex   9.603553e-01 8.411720e-01 -3.991411e-01
      vertex   1.000000e-01 1.639547e+00 -7.218559e-01
      vertex   9.603553e-01 8.565616e-01 -3.649468e-01
    endloop
  endfacet
  facet normal 7.069709e-01 6.528759e-01 -2.719288e-01
    outer loop
      vertex   9.603553e-01 8.565616e-01 -3.649468e-01
      vertex   1.000000e-01 1.639547e+00 -7.218559e-01
      vertex   1.000000e-01 1.667210e+00 -6.554391e-01
    endloop
  endfacet
  facet normal 7.071605e-01 6.559232e-01 -2.639864e-01
    outer loop
      vertex   9.603553e-01 8.565616e-01 -3.649468e-01
      vertex   1.000000e-01 1.667210e+00 -6.554391e-01
      vertex   9.603553e-01 8.705618e-01 -3.301606e-01
    endloop
  endfacet
  facet normal 7.069705e-01 6.632687e-01 -2.454940e-01
    outer loop
      vertex   9.603553e-01 8.705618e-01 -3.301606e-01
      vertex   1.000000e-01 1.667210e+00 -6.554391e-01
      vertex   1.000000e-01 1.692184e+00 -5.879651e-01
    endloop
  endfacet
  facet normal 7.071611e-01 6.660203e-01 -2.373607e-01
    outer loop
      vertex   9.603553e-01 8.705618e-01 -3.301606e-01
      vertex   1.000000e-01 1.692184e+00 -5.879651e-01
      vertex   9.603553e-01 8.831500e-01 -2.948388e-01
    endloop
  endfacet
  facet normal 7.069702e-01 6.725917e-01 -2.186631e-01
    outer loop
      vertex   9.603553e-01 8.831500e-01 -2.948388e-01
      vertex   1.000000e-01 1.692184e+00 -5.879651e-01
      vertex   1.000000e-01 1.714429e+00 -5.195427e-01
    endloop
  endfacet
  facet normal 7.071618e-01 6.750371e-01 -2.103501e-01
    outer loop
      vertex   9.603553e-01 8.831500e-01 -2.948388e-01
      vertex   1.000000e-01 1.714429e+00 -5.195427e-01
      vertex   9.603553e-01 8.943058e-01 -2.590388e-01
    endloop
  endfacet
  facet normal 7.069699e-01 6.808298e-01 -1.914795e-01
    outer loop
      vertex   9.603553e-01 8.943058e-01 -2.590388e-01
      vertex   1.000000e-01 1.714429e+00 -5.195427e-01
      vertex   1.000000e-01 1.733908e+00 -4.502822e-01
    endloop
  endfacet
  facet normal 7.071624e-01 6.829590e-01 -1.829983e-01
    outer loop
      vertex   9.603553e-01 8.943058e-01 -2.590388e-01
      vertex   1.000000e-01 1.733908e+00 -4.502822e-01
      vertex   9.603553e-01 9.040109e-01 -2.228187e-01
    endloop
  endfacet
  facet normal 7.069695e-01 6.879697e-01 -1.639870e-01
    outer loop
      vertex   9.603553e-01 9.040109e-01 -2.228187e-01
      vertex   1.000000e-01 1.733908e+00 -4.502822e-01
      vertex   1.000000e-01 1.750590e+00 -3.802955e-01
    endloop
  endfacet
  facet normal 7.071631e-01 6.897731e-01 -1.553498e-01
    outer loop
      vertex   9.603553e-01 9.040109e-01 -2.228187e-01
      vertex   1.000000e-01 1.750590e+00 -3.802955e-01
      vertex   9.603553e-01 9.122498e-01 -1.862371e-01
    endloop
  endfacet
  facet normal 7.069692e-01 6.940000e-01 -1.362300e-01
    outer loop
      vertex   9.603553e-01 9.122498e-01 -1.862371e-01
      vertex   1.000000e-01 1.750590e+00 -3.802955e-01
      vertex   1.000000e-01 1.764449e+00 -3.096953e-01
    endloop
  endfacet
  facet normal 7.071637e-01 6.954683e-01 -1.274493e-01
    outer loop
      vertex   9.603553e-01 9.122498e-01 -1.862371e-01
      vertex   1.000000e-01 1.764449e+00 -3.096953e-01
      vertex   9.603553e-01 9.190090e-01 -1.493535e-01
    endloop
  endfacet
  facet normal 7.069689e-01 6.989108e-01 -1.082532e-01
    outer loop
      vertex   9.603553e-01 9.190090e-01 -1.493535e-01
      vertex   1.000000e-01 1.764449e+00 -3.096953e-01
      vertex   1.000000e-01 1.775461e+00 -2.385956e-01
    endloop
  endfacet
  facet normal 7.071643e-01 7.000356e-01 -9.934217e-02
    outer loop
      vertex   9.603553e-01 9.190090e-01 -1.493535e-01
      vertex   1.000000e-01 1.775461e+00 -2.385956e-01
      vertex   9.603553e-01 9.242775e-01 -1.122276e-01
    endloop
  endfacet
  facet normal 7.069686e-01 7.026942e-01 -8.010171e-02
    outer loop
      vertex   9.603553e-01 9.242775e-01 -1.122276e-01
      vertex   1.000000e-01 1.775461e+00 -2.385956e-01
      vertex   1.000000e-01 1.783610e+00 -1.671110e-01
    endloop
  endfacet
  facet normal 7.071649e-01 7.034673e-01 -7.107395e-02
    outer loop
      vertex   9.603553e-01 9.242775e-01 -1.122276e-01
      vertex   1.000000e-01 1.783610e+00 -1.671110e-01
      vertex   9.603553e-01 9.280469e-01 -7.491969e-02
    endloop
  endfacet
  facet normal 7.069683e-01 7.053442e-01 -5.182104e-02
    outer loop
      vertex   9.603553e-01 9.280469e-01 -7.491969e-02
      vertex   1.000000e-01 1.783610e+00 -1.671110e-01
      vertex   1.000000e-01 1.788882e+00 -9.535691e-02
    endloop
  endfacet
  facet normal 7.071655e-01 7.057581e-01 -4.269050e-02
    outer loop
      vertex   9.603553e-01 9.280469e-01 -7.491969e-02
      vertex   1.000000e-01 1.788882e+00 -9.535691e-02
      vertex   9.603553e-01 9.303109e-01 -3.749025e-02
    endloop
  endfacet
  facet normal 7.069680e-01 7.068565e-01 -2.345676e-02
    outer loop
      vertex   9.603553e-01 9.303109e-01 -3.749025e-02
      vertex   1.000000e-01 1.788882e+00 -9.535691e-02
      vertex   1.000000e-01 1.791268e+00 -2.344898e-02
    endloop
  endfacet
  facet normal 7.071661e-01 7.069041e-01 -1.423785e-02
    outer loop
      vertex   9.603553e-01 9.303109e-01 -3.749025e-02
      vertex   1.000000e-01 1.791268e+00 -2.344898e-02
      vertex   9.603553e-01 9.310660e-01 5.701135e-17
    endloop
  endfacet
  facet normal 7.069676e-01 7.072286e-01 4.945380e-03
    outer loop
      vertex   9.603553e-01 9.310660e-01 5.701135e-17
      vertex   1.000000e-01 1.791268e+00 -2.344898e-02
      vertex   1.000000e-01 1.790765e+00 4.849677e-02
    endloop
  endfacet
  facet normal 7.071666e-01 7.069035e-01 1.423784e-02
    outer loop
      vertex   9.603553e-01 9.310660e-01 5.701135e-17
      vertex   1.000000e-01 1.790765e+00 4.849677e-02
      vertex   9.603553e-01 9.303109e-01 3.749025e-02
    endloop
  endfacet
  facet normal 7.069674e-01 7.064599e-01 3.333957e-02
    outer loop
      vertex   9.603553e-01 9.303109e-01 3.749025e-02
      vertex   1.000000e-01 1.790765e+00 4.849677e-02
      vertex   1.000000e-01 1.787373e+00 1.203643e-01
    endloop
  endfacet
  facet normal 7.071672e-01 7.057564e-01 4.269040e-02
    outer loop
      vertex   9.603553e-01 9.303109e-01 3.749025e-02
      vertex   1.000000e-01 1.787373e+00 1.203643e-01
      vertex   9.603553e-01 9.280469e-01 7.491969e-02
    endloop
  endfacet
  facet normal 7.069671e-01 7.045517e-01 6.168000e-02
    outer loop
      vertex   9.603553e-01 9.280469e-01 7.491969e-02
      vertex   1.000000e-01 1.787373e+00 1.203643e-01
      vertex   1.000000e-01 1.781099e+00 1.920377e-01
    endloop
  endfacet
  facet normal 7.071678e-01 7.034645e-01 7.107366e-02
    outer loop
      vertex   9.603553e-01 9.280469e-01 7.491969e-02
      vertex   1.000000e-01 1.781099e+00 1.920377e-01
      vertex   9.603553e-01 9.242775e-01 1.122276e-01
    endloop
  endfacet
  facet normal 7.069668e-01 7.015071e-01 8.992097e-02
    outer loop
      vertex   9.603553e-01 9.242775e-01 1.122276e-01
      vertex   1.000000e-01 1.781099e+00 1.920377e-01
      vertex   1.000000e-01 1.771951e+00 2.634013e-01
    endloop
  endfacet
  facet normal 7.071678e-01 7.000358e-01 9.931556e-02
    outer loop
      vertex   9.603553e-01 9.242775e-01 1.122276e-01
      vertex   1.000000e-01 1.771951e+00 2.634013e-01
      vertex   9.603553e-01 9.190201e-01 1.492849e-01
    endloop
  endfacet
  facet normal 7.069667e-01 6.973307e-01 1.180169e-01
    outer loop
      vertex   9.603553e-01 9.190201e-01 1.492849e-01
      vertex   1.000000e-01 1.771951e+00 2.634013e-01
      vertex   1.000000e-01 1.759945e+00 3.343400e-01
    endloop
  endfacet
  facet normal 7.071690e-01 6.954679e-01 1.274224e-01
    outer loop
      vertex   9.603553e-01 9.190201e-01 1.492849e-01
      vertex   1.000000e-01 1.759945e+00 3.343400e-01
      vertex   9.603553e-01 9.122498e-01 1.862371e-01
    endloop
  endfacet
  facet normal 7.069662e-01 6.920299e-01 1.459225e-01
    outer loop
      vertex   9.603553e-01 9.122498e-01 1.862371e-01
      vertex   1.000000e-01 1.759945e+00 3.343400e-01
      vertex   1.000000e-01 1.745101e+00 4.047395e-01
    endloop
  endfacet
  facet normal 7.071694e-01 6.897669e-01 1.553484e-01
    outer loop
      vertex   9.603553e-01 9.122498e-01 1.862371e-01
      vertex   1.000000e-01 1.745101e+00 4.047395e-01
      vertex   9.603553e-01 9.040109e-01 2.228187e-01
    endloop
  endfacet
  facet normal 7.069659e-01 6.856127e-01 1.735928e-01
    outer loop
      vertex   9.603553e-01 9.040109e-01 2.228187e-01
      vertex   1.000000e-01 1.745101e+00 4.047395e-01
      vertex   1.000000e-01 1.727441e+00 4.744861e-01
    endloop
  endfacet
  facet normal 7.071699e-01 6.829517e-01 1.829964e-01
    outer loop
      vertex   9.603553e-01 9.040109e-01 2.228187e-01
      vertex   1.000000e-01 1.727441e+00 4.744861e-01
      vertex   9.603553e-01 8.943058e-01 2.590388e-01
    endloop
  endfacet
  facet normal 7.069657e-01 6.780895e-01 2.009830e-01
    outer loop
      vertex   9.603553e-01 8.943058e-01 2.590388e-01
      vertex   1.000000e-01 1.727441e+00 4.744861e-01
      vertex   1.000000e-01 1.706996e+00 5.434674e-01
    endloop
  endfacet
  facet normal 7.071704e-01 6.750288e-01 2.103475e-01
    outer loop
      vertex   9.603553e-01 8.943058e-01 2.590388e-01
      vertex   1.000000e-01 1.706996e+00 5.434674e-01
      vertex   9.603553e-01 8.831500e-01 2.948388e-01
    endloop
  endfacet
  facet normal 7.069654e-01 6.694726e-01 2.280491e-01
    outer loop
      vertex   9.603553e-01 8.831500e-01 2.948388e-01
      vertex   1.000000e-01 1.706996e+00 5.434674e-01
      vertex   1.000000e-01 1.683796e+00 6.115720e-01
    endloop
  endfacet
  facet normal 7.071709e-01 6.660111e-01 2.373574e-01
    outer loop
      vertex   9.603553e-01 8.831500e-01 2.948388e-01
      vertex   1.000000e-01 1.683796e+00 6.115720e-01
      vertex   9.603553e-01 8.705618e-01 3.301606e-01
    endloop
  endfacet
  facet normal 7.069651e-01 6.597757e-01 2.547474e-01
    outer loop
      vertex   9.603553e-01 8.705618e-01 3.301606e-01
      vertex   1.000000e-01 1.683796e+00 6.115720e-01
      vertex   1.000000e-01 1.657881e+00 6.786902e-01
    endloop
  endfacet
  facet normal 7.071714e-01 6.559131e-01 2.639823e-01
    outer loop
      vertex   9.603553e-01 8.705618e-01 3.301606e-01
      vertex   1.000000e-01 1.657881e+00 6.786902e-01
      vertex   9.603553e-01 8.565616e-01 3.649468e-01
    endloop
  endfacet
  facet normal 7.069649e-01 6.490147e-01 2.810348e-01
    outer loop
      vertex   9.603553e-01 8.565616e-01 3.649468e-01
      vertex   1.000000e-01 1.657881e+00 6.786902e-01
      vertex   1.000000e-01 1.629292e+00 7.447136e-01
    endloop
  endfacet
  facet normal 7.071719e-01 6.447512e-01 2.901790e-01
    outer loop
      vertex   9.603553e-01 8.565616e-01 3.649468e-01
      vertex   1.000000e-01 1.629292e+00 7.447136e-01
      vertex   9.603553e-01 8.411720e-01 3.991411e-01
    endloop
  endfacet
  facet normal 7.069646e-01 6.372068e-01 3.068689e-01
    outer loop
      vertex   9.603553e-01 8.411720e-01 3.991411e-01
      vertex   1.000000e-01 1.629292e+00 7.447136e-01
      vertex   1.000000e-01 1.598075e+00 8.095359e-01
    endloop
  endfacet
  facet normal 7.071724e-01 6.325435e-01 3.159049e-01
    outer loop
      vertex   9.603553e-01 8.411720e-01 3.991411e-01
      vertex   1.000000e-01 1.598075e+00 8.095359e-01
      vertex   9.603553e-01 8.244180e-01 4.326880e-01
    endloop
  endfacet
  facet normal 7.069644e-01 6.243710e-01 3.322080e-01
    outer loop
      vertex   9.603553e-01 8.244180e-01 4.326880e-01
      vertex   1.000000e-01 1.598075e+00 8.095359e-01
      vertex   1.000000e-01 1.564279e+00 8.730523e-01
    endloop
  endfacet
  facet normal 7.071728e-01 6.193099e-01 3.411185e-01
    outer loop
      vertex   9.603553e-01 8.244180e-01 4.326880e-01
      vertex   1.000000e-01 1.564279e+00 8.730523e-01
      vertex   9.603553e-01 8.063268e-01 4.655330e-01
    endloop
  endfacet
  facet normal 7.069642e-01 6.105281e-01 3.570113e-01
    outer loop
      vertex   9.603553e-01 8.063268e-01 4.655330e-01
      vertex   1.000000e-01 1.564279e+00 8.730523e-01
      vertex   1.000000e-01 1.527961e+00 9.351605e-01
    endloop
  endfacet
  facet normal 7.071733e-01 6.050718e-01 3.657787e-01
    outer loop
      vertex   9.603553e-01 8.063268e-01 4.655330e-01
      vertex   1.000000e-01 1.527961e+00 9.351605e-01
      vertex   9.603553e-01 7.869278e-01 4.976230e-01
    endloop
  endfacet
  facet normal 7.069639e-01 5.957005e-01 3.812387e-01
    outer loop
      vertex   9.603553e-01 7.869278e-01 4.976230e-01
      vertex   1.000000e-01 1.527961e+00 9.351605e-01
      vertex   1.000000e-01 1.489178e+00 9.957603e-01
    endloop
  endfacet
  facet normal 7.071737e-01 5.898523e-01 3.898456e-01
    outer loop
      vertex   9.603553e-01 7.869278e-01 4.976230e-01
      vertex   1.000000e-01 1.489178e+00 9.957603e-01
      vertex   9.603553e-01 7.662523e-01 5.289058e-01
    endloop
  endfacet
  facet normal 7.069637e-01 5.799119e-01 4.048512e-01
    outer loop
      vertex   9.603553e-01 7.662523e-01 5.289058e-01
      vertex   1.000000e-01 1.489178e+00 9.957603e-01
      vertex   1.000000e-01 1.447993e+00 1.054754e+00
    endloop
  endfacet
  facet normal 7.071742e-01 5.736761e-01 4.132801e-01
    outer loop
      vertex   9.603553e-01 7.662523e-01 5.289058e-01
      vertex   1.000000e-01 1.447993e+00 1.054754e+00
      vertex   9.603553e-01 7.443340e-01 5.593307e-01
    endloop
  endfacet
  facet normal 7.069635e-01 5.631879e-01 4.278107e-01
    outer loop
      vertex   9.603553e-01 7.443340e-01 5.593307e-01
      vertex   1.000000e-01 1.447993e+00 1.054754e+00
      vertex   1.000000e-01 1.404473e+00 1.112046e+00
    endloop
  endfacet
  facet normal 7.071746e-01 5.565694e-01 4.360443e-01
    outer loop
      vertex   9.603553e-01 7.443340e-01 5.593307e-01
      vertex   1.000000e-01 1.404473e+00 1.112046e+00
      vertex   9.603553e-01 7.212084e-01 5.888484e-01
    endloop
  endfacet
  facet normal 7.069633e-01 5.455555e-01 4.500802e-01
    outer loop
      vertex   9.603553e-01 7.212084e-01 5.888484e-01
      vertex   1.000000e-01 1.404473e+00 1.112046e+00
      vertex   1.000000e-01 1.358687e+00 1.167545e+00
    endloop
  endfacet
  facet normal 7.071750e-01 5.385600e-01 4.581011e-01
    outer loop
      vertex   9.603553e-01 7.212084e-01 5.888484e-01
      vertex   1.000000e-01 1.358687e+00 1.167545e+00
      vertex   9.603553e-01 6.969129e-01 6.174110e-01
    endloop
  endfacet
  facet normal 7.069630e-01 5.270431e-01 4.716236e-01
    outer loop
      vertex   9.603553e-01 6.969129e-01 6.174110e-01
      vertex   1.000000e-01 1.358687e+00 1.167545e+00
      vertex   1.000000e-01 1.310709e+00 1.221160e+00
    endloop
  endfacet
  facet normal 7.071754e-01 5.196770e-01 4.794150e-01
    outer loop
      vertex   9.603553e-01 6.969129e-01 6.174110e-01
      vertex   1.000000e-01 1.310709e+00 1.221160e+00
      vertex   9.603553e-01 6.714871e-01 6.449721e-01
    endloop
  endfacet
  facet normal 7.069628e-01 5.076805e-01 4.924064e-01
    outer loop
      vertex   9.603553e-01 6.714871e-01 6.449721e-01
      vertex   1.000000e-01 1.310709e+00 1.221160e+00
      vertex   1.000000e-01 1.260618e+00 1.272806e+00
    endloop
  endfacet
  facet normal 7.071758e-01 4.999512e-01 4.999512e-01
    outer loop
      vertex   9.603553e-01 6.714871e-01 6.449721e-01
      vertex   1.000000e-01 1.260618e+00 1.272806e+00
      vertex   9.603553e-01 6.449721e-01 6.714871e-01
    endloop
  endfacet
  facet normal 7.069626e-01 4.874991e-01 5.123949e-01
    outer loop
      vertex   9.603553e-01 6.449721e-01 6.714871e-01
      vertex   1.000000e-01 1.260618e+00 1.272806e+00
      vertex   1.000000e-01 1.208492e+00 1.322398e+00
    endloop
  endfacet
  facet normal 7.071762e-01 4.794144e-01 5.196764e-01
    outer loop
      vertex   9.603553e-01 6.449721e-01 6.714871e-01
      vertex   1.000000e-01 1.208492e+00 1.322398e+00
      vertex   9.603553e-01 6.174110e-01 6.969129e-01
    endloop
  endfacet
  facet normal 7.069624e-01 4.665312e-01 5.315569e-01
    outer loop
      vertex   9.603553e-01 6.174110e-01 6.969129e-01
      vertex   1.000000e-01 1.208492e+00 1.322398e+00
      vertex   1.000000e-01 1.154418e+00 1.369858e+00
    endloop
  endfacet
  facet normal 7.071766e-01 4.581001e-01 5.385587e-01
    outer loop
      vertex   9.603553e-01 6.174110e-01 6.969129e-01
      vertex   1.000000e-01 1.154418e+00 1.369858e+00
      vertex   9.603553e-01 5.888484e-01 7.212084e-01
    endloop
  endfacet
  facet normal 7.069622e-01 4.448109e-01 5.498615e-01
    outer loop
      vertex   9.603553e-01 5.888484e-01 7.212084e-01
      vertex   1.000000e-01 1.154418e+00 1.369858e+00
      vertex   1.000000e-01 1.098481e+00 1.415107e+00
    endloop
  endfacet
  facet normal 7.071770e-01 4.360428e-01 5.565675e-01
    outer loop
      vertex   9.603553e-01 5.888484e-01 7.212084e-01
      vertex   1.000000e-01 1.098481e+00 1.415107e+00
      vertex   9.603553e-01 5.593307e-01 7.443340e-01
    endloop
  endfacet
  facet normal 7.069620e-01 4.223730e-01 5.672792e-01
    outer loop
      vertex   9.603553e-01 5.593307e-01 7.443340e-01
      vertex   1.000000e-01 1.098481e+00 1.415107e+00
      vertex   1.000000e-01 1.040773e+00 1.458075e+00
    endloop
  endfacet
  facet normal 7.071773e-01 4.132782e-01 5.736735e-01
    outer loop
      vertex   9.603553e-01 5.593307e-01 7.443340e-01
      vertex   1.000000e-01 1.040773e+00 1.458075e+00
      vertex   9.603553e-01 5.289058e-01 7.662523e-01
    endloop
  endfacet
  facet normal 7.069618e-01 3.992539e-01 5.837819e-01
    outer loop
      vertex   9.603553e-01 5.289058e-01 7.662523e-01
      vertex   1.000000e-01 1.040773e+00 1.458075e+00
      vertex   1.000000e-01 9.813860e-01 1.498690e+00
    endloop
  endfacet
  facet normal 7.071777e-01 3.898434e-01 5.898490e-01
    outer loop
      vertex   9.603553e-01 5.289058e-01 7.662523e-01
      vertex   1.000000e-01 9.813860e-01 1.498690e+00
      vertex   9.603553e-01 4.976230e-01 7.869278e-01
    endloop
  endfacet
  facet normal 7.069617e-01 3.754907e-01 5.993429e-01
    outer loop
      vertex   9.603553e-01 4.976230e-01 7.869278e-01
      vertex   1.000000e-01 9.813860e-01 1.498690e+00
      vertex   1.000000e-01 9.204159e-01 1.536888e+00
    endloop
  endfacet
  facet normal 7.071780e-01 3.657762e-01 6.050677e-01
    outer loop
      vertex   9.603553e-01 4.976230e-01 7.869278e-01
      vertex   1.000000e-01 9.204159e-01 1.536888e+00
      vertex   9.603553e-01 4.655330e-01 8.063268e-01
    endloop
  endfacet
  facet normal 7.069615e-01 3.511219e-01 6.139372e-01
    outer loop
      vertex   9.603553e-01 4.655330e-01 8.063268e-01
      vertex   1.000000e-01 9.204159e-01 1.536888e+00
      vertex   1.000000e-01 8.579611e-01 1.572607e+00
    endloop
  endfacet
  facet normal 7.071784e-01 3.411158e-01 6.193051e-01
    outer loop
      vertex   9.603553e-01 4.655330e-01 8.063268e-01
      vertex   1.000000e-01 8.579611e-01 1.572607e+00
      vertex   9.603553e-01 4.326880e-01 8.244180e-01
    endloop
  endfacet
  facet normal 7.069613e-01 3.261866e-01 6.275412e-01
    outer loop
      vertex   9.603553e-01 4.326880e-01 8.244180e-01
      vertex   1.000000e-01 8.579611e-01 1.572607e+00
      vertex   1.000000e-01 7.941225e-01 1.605790e+00
    endloop
  endfacet
  facet normal 7.071787e-01 3.159021e-01 6.325379e-01
    outer loop
      vertex   9.603553e-01 4.326880e-01 8.244180e-01
      vertex   1.000000e-01 7.941225e-01 1.605790e+00
      vertex   9.603553e-01 3.991411e-01 8.411720e-01
    endloop
  endfacet
  facet normal 7.069611e-01 3.007253e-01 6.401330e-01
    outer loop
      vertex   9.603553e-01 3.991411e-01 8.411720e-01
      vertex   1.000000e-01 7.941225e-01 1.605790e+00
      vertex   1.000000e-01 7.290029e-01 1.636382e+00
    endloop
  endfacet
  facet normal 7.071790e-01 2.901760e-01 6.447447e-01
    outer loop
      vertex   9.603553e-01 3.991411e-01 8.411720e-01
      vertex   1.000000e-01 7.290029e-01 1.636382e+00
      vertex   9.603553e-01 3.649468e-01 8.565616e-01
    endloop
  endfacet
  facet normal 7.069610e-01 2.747788e-01 6.516923e-01
    outer loop
      vertex   9.603553e-01 3.649468e-01 8.565616e-01
      vertex   1.000000e-01 7.290029e-01 1.636382e+00
      vertex   1.000000e-01 6.627074e-01 1.664335e+00
    endloop
  endfacet
  facet normal 7.071793e-01 2.639793e-01 6.559057e-01
    outer loop
      vertex   9.603553e-01 3.649468e-01 8.565616e-01
      vertex   1.000000e-01 6.627074e-01 1.664335e+00
      vertex   9.603553e-01 3.301606e-01 8.705618e-01
    endloop
  endfacet
  facet normal 7.069608e-01 2.483891e-01 6.622003e-01
    outer loop
      vertex   9.603553e-01 3.301606e-01 8.705618e-01
      vertex   1.000000e-01 6.627074e-01 1.664335e+00
      vertex   1.000000e-01 5.953430e-01 1.689603e+00
    endloop
  endfacet
  facet normal 7.071796e-01 2.373545e-01 6.660029e-01
    outer loop
      vertex   9.603553e-01 3.301606e-01 8.705618e-01
      vertex   1.000000e-01 5.953430e-01 1.689603e+00
      vertex   9.603553e-01 2.948388e-01 8.831500e-01
    endloop
  endfacet
  facet normal 7.069607e-01 2.215987e-01 6.716402e-01
    outer loop
      vertex   9.603553e-01 2.948388e-01 8.831500e-01
      vertex   1.000000e-01 5.953430e-01 1.689603e+00
      vertex   1.000000e-01 5.270183e-01 1.712145e+00
    endloop
  endfacet
  facet normal 7.071799e-01 2.103447e-01 6.750198e-01
    outer loop
      vertex   9.603553e-01 2.948388e-01 8.831500e-01
      vertex   1.000000e-01 5.270183e-01 1.712145e+00
      vertex   9.603553e-01 2.590388e-01 8.943058e-01
    endloop
  endfacet
  facet normal 7.069605e-01 1.944509e-01 6.799968e-01
    outer loop
      vertex   9.603553e-01 2.590388e-01 8.943058e-01
      vertex   1.000000e-01 5.270183e-01 1.712145e+00
      vertex   1.000000e-01 4.578435e-01 1.731927e+00
    endloop
  endfacet
  facet normal 7.071802e-01 1.829937e-01 6.829418e-01
    outer loop
      vertex   9.603553e-01 2.590388e-01 8.943058e-01
      vertex   1.000000e-01 4.578435e-01 1.731927e+00
      vertex   9.603553e-01 2.228187e-01 9.040109e-01
    endloop
  endfacet
  facet normal 7.069604e-01 1.669894e-01 6.872566e-01
    outer loop
      vertex   9.603553e-01 2.228187e-01 9.040109e-01
      vertex   1.000000e-01 4.578435e-01 1.731927e+00
      vertex   1.000000e-01 3.879302e-01 1.748914e+00
    endloop
  endfacet
  facet normal 7.071805e-01 1.553459e-01 6.897561e-01
    outer loop
      vertex   9.603553e-01 2.228187e-01 9.040109e-01
      vertex   1.000000e-01 3.879302e-01 1.748914e+00
      vertex   9.603553e-01 1.862371e-01 9.122498e-01
    endloop
  endfacet
  facet normal 7.069602e-01 1.392586e-01 6.934077e-01
    outer loop
      vertex   9.603553e-01 1.862371e-01 9.122498e-01
      vertex   1.000000e-01 3.879302e-01 1.748914e+00
      vertex   1.000000e-01 3.173912e-01 1.763081e+00
    endloop
  endfacet
  facet normal 7.071807e-01 1.274462e-01 6.954516e-01
    outer loop
      vertex   9.603553e-01 1.862371e-01 9.122498e-01
      vertex   1.000000e-01 3.173912e-01 1.763081e+00
      vertex   9.603553e-01 1.493535e-01 9.190090e-01
    endloop
  endfacet
  facet normal 7.069601e-01 1.113031e-01 6.984404e-01
    outer loop
      vertex   9.603553e-01 1.493535e-01 9.190090e-01
      vertex   1.000000e-01 3.173912e-01 1.763081e+00
      vertex   1.000000e-01 2.463402e-01 1.774403e+00
    endloop
  endfacet
  facet normal 7.071810e-01 9.933982e-02 7.000190e-01
    outer loop
      vertex   9.603553e-01 1.493535e-01 9.190090e-01
      vertex   1.000000e-01 2.463402e-01 1.774403e+00
      vertex   9.603553e-01 1.122276e-01 9.242775e-01
    endloop
  endfacet
  facet normal 7.069600e-01 8.316803e-02 7.023465e-01
    outer loop
      vertex   9.603553e-01 1.122276e-01 9.242775e-01
      vertex   1.000000e-01 2.463402e-01 1.774403e+00
      vertex   1.000000e-01 1.748919e-01 1.782864e+00
    endloop
  endfacet
  facet normal 7.071812e-01 7.107231e-02 7.034511e-01
    outer loop
      vertex   9.603553e-01 1.122276e-01 9.242775e-01
      vertex   1.000000e-01 1.748919e-01 1.782864e+00
      vertex   9.603553e-01 7.491969e-02 9.280469e-01
    endloop
  endfacet
  facet normal 7.069598e-01 5.489884e-02 7.051198e-01
    outer loop
      vertex   9.603553e-01 7.491969e-02 9.280469e-01
      vertex   1.000000e-01 1.748919e-01 1.782864e+00
      vertex   1.000000e-01 1.031614e-01 1.788449e+00
    endloop
  endfacet
  facet normal 7.071815e-01 4.268953e-02 7.057421e-01
    outer loop
      vertex   9.603553e-01 7.491969e-02 9.280469e-01
      vertex   1.000000e-01 1.031614e-01 1.788449e+00
      vertex   9.603553e-01 3.749025e-02 9.303109e-01
    endloop
  endfacet
  facet normal 7.069597e-01 2.654108e-02 7.067556e-01
    outer loop
      vertex   9.603553e-01 3.749025e-02 9.303109e-01
      vertex   1.000000e-01 1.031614e-01 1.788449e+00
      vertex   1.000000e-01 3.126461e-02 1.791149e+00
    endloop
  endfacet
  facet normal 7.070838e-01 2.040851e-02 7.068352e-01
    outer loop
      vertex   9.603553e-01 3.749025e-02 9.303109e-01
      vertex   1.000000e-01 3.126461e-02 1.791149e+00
      vertex   1.820711e+00 1.234071e-03 7.069991e-02
    endloop
  endfacet
  facet normal 7.071656e-01 7.373618e-02 7.031926e-01
    outer loop
      vertex   1.820711e+00 1.345858e-02 6.941806e-02
      vertex   9.603553e-01 1.122276e-01 9.242775e-01
      vertex   1.820711e+00 1.234071e-03 7.069991e-02
    endloop
  endfacet
  facet normal 7.071298e-01 7.107748e-02 7.035023e-01
    outer loop
      vertex   1.820711e+00 1.234071e-03 7.069991e-02
      vertex   9.603553e-01 1.122276e-01 9.242775e-01
      vertex   9.603553e-01 7.491969e-02 9.280469e-01
    endloop
  endfacet
  facet normal 7.070560e-01 4.269711e-02 7.058674e-01
    outer loop
      vertex   1.820711e+00 1.234071e-03 7.069991e-02
      vertex   9.603553e-01 7.491969e-02 9.280469e-01
      vertex   9.603553e-01 3.749025e-02 9.303109e-01
    endloop
  endfacet
  facet normal 7.072145e-01 1.943811e-01 6.797526e-01
    outer loop
      vertex   1.820711e+00 2.527642e-02 6.603864e-02
      vertex   9.603553e-01 2.590388e-01 8.943058e-01
      vertex   1.820711e+00 1.345858e-02 6.941806e-02
    endloop
  endfacet
  facet normal 7.071010e-01 1.830142e-01 6.830183e-01
    outer loop
      vertex   1.820711e+00 1.345858e-02 6.941806e-02
      vertex   9.603553e-01 2.590388e-01 8.943058e-01
      vertex   9.603553e-01 2.228187e-01 9.040109e-01
    endloop
  endfacet
  facet normal 7.070423e-01 1.553763e-01 6.898909e-01
    outer loop
      vertex   1.820711e+00 1.345858e-02 6.941806e-02
      vertex   9.603553e-01 2.228187e-01 9.040109e-01
      vertex   9.603553e-01 1.862371e-01 9.122498e-01
    endloop
  endfacet
  facet normal 7.071994e-01 3.091642e-01 6.358353e-01
    outer loop
      vertex   1.820711e+00 3.633050e-02 6.066379e-02
      vertex   9.603553e-01 3.991411e-01 8.411720e-01
      vertex   1.820711e+00 2.527642e-02 6.603864e-02
    endloop
  endfacet
  facet normal 7.070770e-01 2.902179e-01 6.448377e-01
    outer loop
      vertex   1.820711e+00 2.527642e-02 6.603864e-02
      vertex   9.603553e-01 3.991411e-01 8.411720e-01
      vertex   9.603553e-01 3.649468e-01 8.565616e-01
    endloop
  endfacet
  facet normal 7.070334e-01 2.640338e-01 6.560411e-01
    outer loop
      vertex   1.820711e+00 2.527642e-02 6.603864e-02
      vertex   9.603553e-01 3.649468e-01 8.565616e-01
      vertex   9.603553e-01 3.301606e-01 8.705618e-01
    endloop
  endfacet
  facet normal 7.071561e-01 4.146267e-01 5.727259e-01
    outer loop
      vertex   1.820711e+00 4.628680e-02 5.345589e-02
      vertex   9.603553e-01 5.593307e-01 7.443340e-01
      vertex   1.820711e+00 3.633050e-02 6.066379e-02
    endloop
  endfacet
  facet normal 7.071333e-01 4.133040e-01 5.737092e-01
    outer loop
      vertex   1.820711e+00 3.633050e-02 6.066379e-02
      vertex   9.603553e-01 5.593307e-01 7.443340e-01
      vertex   9.603553e-01 5.289058e-01 7.662523e-01
    endloop
  endfacet
  facet normal 7.070579e-01 3.899095e-01 5.899490e-01
    outer loop
      vertex   1.820711e+00 3.633050e-02 6.066379e-02
      vertex   9.603553e-01 5.289058e-01 7.662523e-01
      vertex   9.603553e-01 4.976230e-01 7.869278e-01
    endloop
  endfacet
  facet normal 7.072122e-01 5.075015e-01 4.922328e-01
    outer loop
      vertex   1.820711e+00 5.484449e-02 4.463275e-02
      vertex   9.603553e-01 6.714871e-01 6.449721e-01
      vertex   1.820711e+00 4.628680e-02 5.345589e-02
    endloop
  endfacet
  facet normal 7.071040e-01 5.000020e-01 5.000020e-01
    outer loop
      vertex   1.820711e+00 4.628680e-02 5.345589e-02
      vertex   9.603553e-01 6.714871e-01 6.449721e-01
      vertex   9.603553e-01 6.449721e-01 6.714871e-01
    endloop
  endfacet
  facet normal 7.070436e-01 4.795044e-01 5.197739e-01
    outer loop
      vertex   1.820711e+00 4.628680e-02 5.345589e-02
      vertex   9.603553e-01 6.449721e-01 6.714871e-01
      vertex   9.603553e-01 6.174110e-01 6.969129e-01
    endloop
  endfacet
  facet normal 7.072043e-01 5.850810e-01 3.969161e-01
    outer loop
      vertex   1.820711e+00 6.174497e-02 3.446097e-02
      vertex   9.603553e-01 7.662523e-01 5.289058e-01
      vertex   1.820711e+00 5.484449e-02 4.463275e-02
    endloop
  endfacet
  facet normal 7.070794e-01 5.737530e-01 4.133355e-01
    outer loop
      vertex   1.820711e+00 5.484449e-02 4.463275e-02
      vertex   9.603553e-01 7.662523e-01 5.289058e-01
      vertex   9.603553e-01 7.443340e-01 5.593307e-01
    endloop
  endfacet
  facet normal 7.070342e-01 5.566799e-01 4.361309e-01
    outer loop
      vertex   1.820711e+00 5.484449e-02 4.463275e-02
      vertex   9.603553e-01 7.443340e-01 5.593307e-01
      vertex   9.603553e-01 7.212084e-01 5.888484e-01
    endloop
  endfacet
  facet normal 7.071458e-01 6.450291e-01 2.896245e-01
    outer loop
      vertex   1.820711e+00 6.677975e-02 2.324791e-02
      vertex   9.603553e-01 8.565616e-01 3.649468e-01
      vertex   1.820711e+00 6.174497e-02 3.446097e-02
    endloop
  endfacet
  facet normal 7.071370e-01 6.447830e-01 2.901933e-01
    outer loop
      vertex   1.820711e+00 6.174497e-02 3.446097e-02
      vertex   9.603553e-01 8.565616e-01 3.649468e-01
      vertex   9.603553e-01 8.411720e-01 3.991411e-01
    endloop
  endfacet
  facet normal 7.070598e-01 6.326443e-01 3.159552e-01
    outer loop
      vertex   1.820711e+00 6.174497e-02 3.446097e-02
      vertex   9.603553e-01 8.411720e-01 3.991411e-01
      vertex   9.603553e-01 8.244180e-01 4.326880e-01
    endloop
  endfacet
  facet normal 7.072091e-01 6.853770e-01 1.735331e-01
    outer loop
      vertex   1.820711e+00 6.979668e-02 1.133238e-02
      vertex   9.603553e-01 9.040109e-01 2.228187e-01
      vertex   1.820711e+00 6.677975e-02 2.324791e-02
    endloop
  endfacet
  facet normal 7.071070e-01 6.830125e-01 1.830126e-01
    outer loop
      vertex   1.820711e+00 6.677975e-02 2.324791e-02
      vertex   9.603553e-01 9.040109e-01 2.228187e-01
      vertex   9.603553e-01 8.943058e-01 2.590388e-01
    endloop
  endfacet
  facet normal 7.070449e-01 6.751486e-01 2.103848e-01
    outer loop
      vertex   1.820711e+00 6.677975e-02 2.324791e-02
      vertex   9.603553e-01 8.943058e-01 2.590388e-01
      vertex   9.603553e-01 8.831500e-01 2.948388e-01
    endloop
  endfacet
  facet normal 7.072083e-01 7.050738e-01 5.222418e-02
    outer loop
      vertex   1.820711e+00 7.070462e-02 -9.255742e-04
      vertex   9.603553e-01 9.280469e-01 7.491969e-02
      vertex   1.820711e+00 6.979668e-02 1.133238e-02
    endloop
  endfacet
  facet normal 7.070820e-01 7.035499e-01 7.108229e-02
    outer loop
      vertex   1.820711e+00 6.979668e-02 1.133238e-02
      vertex   9.603553e-01 9.280469e-01 7.491969e-02
      vertex   9.603553e-01 9.242775e-01 1.122276e-01
    endloop
  endfacet
  facet normal 7.070353e-01 7.001670e-01 9.933418e-02
    outer loop
      vertex   1.820711e+00 6.979668e-02 1.133238e-02
      vertex   9.603553e-01 9.242775e-01 1.122276e-01
      vertex   9.603553e-01 9.190201e-01 1.492849e-01
    endloop
  endfacet
  facet normal 7.071435e-01 7.035296e-01 -7.066944e-02
    outer loop
      vertex   1.820711e+00 6.947612e-02 -1.315556e-02
      vertex   9.603553e-01 9.280469e-01 -7.491969e-02
      vertex   1.820711e+00 7.070462e-02 -9.255742e-04
    endloop
  endfacet
  facet normal 7.070617e-01 7.058617e-01 -4.269677e-02
    outer loop
      vertex   1.820711e+00 7.070462e-02 -9.255742e-04
      vertex   9.603553e-01 9.280469e-01 -7.491969e-02
      vertex   9.603553e-01 9.303109e-01 -3.749025e-02
    endloop
  endfacet
  facet normal 7.070299e-01 7.070402e-01 -1.424059e-02
    outer loop
      vertex   1.820711e+00 7.070462e-02 -9.255742e-04
      vertex   9.603553e-01 9.303109e-01 -3.749025e-02
      vertex   9.603553e-01 9.310660e-01 5.701135e-17
    endloop
  endfacet
  facet normal 7.072052e-01 6.806033e-01 -1.914158e-01
    outer loop
      vertex   1.820711e+00 6.614830e-02 -2.498803e-02
      vertex   9.603553e-01 8.943058e-01 -2.590388e-01
      vertex   1.820711e+00 6.947612e-02 -1.315556e-02
    endloop
  endfacet
  facet normal 7.071101e-01 6.830094e-01 -1.830118e-01
    outer loop
      vertex   1.820711e+00 6.947612e-02 -1.315556e-02
      vertex   9.603553e-01 8.943058e-01 -2.590388e-01
      vertex   9.603553e-01 9.040109e-01 -2.228187e-01
    endloop
  endfacet
  facet normal 7.070464e-01 6.898869e-01 -1.553754e-01
    outer loop
      vertex   1.820711e+00 6.947612e-02 -1.315556e-02
      vertex   9.603553e-01 9.040109e-01 -2.228187e-01
      vertex   9.603553e-01 9.122498e-01 -1.862371e-01
    endloop
  endfacet
  facet normal 7.072116e-01 6.371672e-01 -3.063816e-01
    outer loop
      vertex   1.820711e+00 6.082173e-02 -3.606546e-02
      vertex   9.603553e-01 8.411720e-01 -3.991411e-01
      vertex   1.820711e+00 6.614830e-02 -2.498803e-02
    endloop
  endfacet
  facet normal 7.070845e-01 6.448309e-01 -2.902148e-01
    outer loop
      vertex   1.820711e+00 6.614830e-02 -2.498803e-02
      vertex   9.603553e-01 8.411720e-01 -3.991411e-01
      vertex   9.603553e-01 8.565616e-01 -3.649468e-01
    endloop
  endfacet
  facet normal 7.070359e-01 6.560388e-01 -2.640329e-01
    outer loop
      vertex   1.820711e+00 6.614830e-02 -2.498803e-02
      vertex   9.603553e-01 8.565616e-01 -3.649468e-01
      vertex   9.603553e-01 8.705618e-01 -3.301606e-01
    endloop
  endfacet
  facet normal 7.071540e-01 5.745313e-01 -4.121250e-01
    outer loop
      vertex   1.820711e+00 5.365734e-02 -4.605312e-02
      vertex   9.603553e-01 7.662523e-01 -5.289058e-01
      vertex   1.820711e+00 6.082173e-02 -3.606546e-02
    endloop
  endfacet
  facet normal 7.070638e-01 5.899441e-01 -3.899062e-01
    outer loop
      vertex   1.820711e+00 6.082173e-02 -3.606546e-02
      vertex   9.603553e-01 7.662523e-01 -5.289058e-01
      vertex   9.603553e-01 7.869278e-01 -4.976230e-01
    endloop
  endfacet
  facet normal 7.070302e-01 6.051942e-01 -3.658527e-01
    outer loop
      vertex   1.820711e+00 6.082173e-02 -3.606546e-02
      vertex   9.603553e-01 7.869278e-01 -4.976230e-01
      vertex   9.603553e-01 8.063268e-01 -4.655330e-01
    endloop
  endfacet
  facet normal 7.072004e-01 4.944507e-01 -5.053574e-01
    outer loop
      vertex   1.820711e+00 4.487163e-02 -5.464922e-02
      vertex   9.603553e-01 6.449721e-01 -6.714871e-01
      vertex   1.820711e+00 5.365734e-02 -4.605312e-02
    endloop
  endfacet
  facet normal 7.071133e-01 4.999954e-01 -4.999954e-01
    outer loop
      vertex   1.820711e+00 5.365734e-02 -4.605312e-02
      vertex   9.603553e-01 6.449721e-01 -6.714871e-01
      vertex   9.603553e-01 6.714871e-01 -6.449721e-01
    endloop
  endfacet
  facet normal 7.070479e-01 5.197708e-01 -4.795015e-01
    outer loop
      vertex   1.820711e+00 5.365734e-02 -4.605312e-02
      vertex   9.603553e-01 6.714871e-01 -6.449721e-01
      vertex   9.603553e-01 6.969129e-01 -6.174110e-01
    endloop
  endfacet
  facet normal 7.072141e-01 3.994596e-01 -5.833354e-01
    outer loop
      vertex   1.820711e+00 3.473006e-02 -6.159402e-02
      vertex   9.603553e-01 5.289058e-01 -7.662523e-01
      vertex   1.820711e+00 4.487163e-02 -5.464922e-02
    endloop
  endfacet
  facet normal 7.070872e-01 4.133310e-01 -5.737467e-01
    outer loop
      vertex   1.820711e+00 4.487163e-02 -5.464922e-02
      vertex   9.603553e-01 5.289058e-01 -7.662523e-01
      vertex   9.603553e-01 5.593307e-01 -7.443340e-01
    endloop
  endfacet
  facet normal 7.070368e-01 4.361292e-01 -5.566779e-01
    outer loop
      vertex   1.820711e+00 4.487163e-02 -5.464922e-02
      vertex   9.603553e-01 5.593307e-01 -7.443340e-01
      vertex   9.603553e-01 5.888484e-01 -7.212084e-01
    endloop
  endfacet
  facet normal 7.071637e-01 2.924288e-01 -6.437429e-01
    outer loop
      vertex   1.820711e+00 2.353907e-02 -6.667767e-02
      vertex   9.603553e-01 3.991411e-01 -8.411720e-01
      vertex   1.820711e+00 3.473006e-02 -6.159402e-02
    endloop
  endfacet
  facet normal 7.070659e-01 3.159525e-01 -6.326388e-01
    outer loop
      vertex   1.820711e+00 3.473006e-02 -6.159402e-02
      vertex   9.603553e-01 3.991411e-01 -8.411720e-01
      vertex   9.603553e-01 4.326880e-01 -8.244180e-01
    endloop
  endfacet
  facet normal 7.070306e-01 3.411871e-01 -6.194345e-01
    outer loop
      vertex   1.820711e+00 3.473006e-02 -6.159402e-02
      vertex   9.603553e-01 4.326880e-01 -8.244180e-01
      vertex   9.603553e-01 4.655330e-01 -8.063268e-01
    endloop
  endfacet
  facet normal 7.071949e-01 1.765255e-01 -6.846270e-01
    outer loop
      vertex   1.820711e+00 1.163682e-02 -6.974657e-02
      vertex   9.603553e-01 2.228187e-01 -9.040109e-01
      vertex   1.820711e+00 2.353907e-02 -6.667767e-02
    endloop
  endfacet
  facet normal 7.071166e-01 1.830102e-01 -6.830032e-01
    outer loop
      vertex   1.820711e+00 2.353907e-02 -6.667767e-02
      vertex   9.603553e-01 2.228187e-01 -9.040109e-01
      vertex   9.603553e-01 2.590388e-01 -8.943058e-01
    endloop
  endfacet
  facet normal 7.070494e-01 2.103835e-01 -6.751444e-01
    outer loop
      vertex   1.820711e+00 2.353907e-02 -6.667767e-02
      vertex   9.603553e-01 2.590388e-01 -8.943058e-01
      vertex   9.603553e-01 2.948388e-01 -8.831500e-01
    endloop
  endfacet
  facet normal 7.072157e-01 5.529955e-02 -7.048318e-01
    outer loop
      vertex   1.820711e+00 -6.170592e-04 -7.070799e-02
      vertex   9.603553e-01 7.491969e-02 -9.280469e-01
      vertex   1.820711e+00 1.163682e-02 -6.974657e-02
    endloop
  endfacet
  facet normal 7.070899e-01 7.108149e-02 -7.035420e-01
    outer loop
      vertex   1.820711e+00 1.163682e-02 -6.974657e-02
      vertex   9.603553e-01 7.491969e-02 -9.280469e-01
      vertex   9.603553e-01 1.122276e-01 -9.242775e-01
    endloop
  endfacet
  facet normal 7.070378e-01 9.935994e-02 -7.001608e-01
    outer loop
      vertex   1.820711e+00 1.163682e-02 -6.974657e-02
      vertex   9.603553e-01 1.122276e-01 -9.242775e-01
      vertex   9.603553e-01 1.493535e-01 -9.190090e-01
    endloop
  endfacet
  facet normal 7.071726e-01 -6.759627e-02 -7.038023e-01
    outer loop
      vertex   1.820711e+00 -1.285229e-02 -6.953286e-02
      vertex   9.603553e-01 -7.491969e-02 -9.280469e-01
      vertex   1.820711e+00 -6.170592e-04 -7.070799e-02
    endloop
  endfacet
  facet normal 7.070680e-01 -4.269639e-02 -7.058554e-01
    outer loop
      vertex   1.820711e+00 -6.170592e-04 -7.070799e-02
      vertex   9.603553e-01 -7.491969e-02 -9.280469e-01
      vertex   9.603553e-01 -3.749025e-02 -9.303109e-01
    endloop
  endfacet
  facet normal 7.070311e-01 -1.424057e-02 -7.070391e-01
    outer loop
      vertex   1.820711e+00 -6.170592e-04 -7.070799e-02
      vertex   9.603553e-01 -3.749025e-02 -9.303109e-01
      vertex   9.603553e-01 -1.140227e-16 -9.310660e-01
    endloop
  endfacet
  facet normal 7.071885e-01 -1.884487e-01 -6.814481e-01
    outer loop
      vertex   1.820711e+00 -2.469917e-02 -6.625671e-02
      vertex   9.603553e-01 -2.590388e-01 -8.943058e-01
      vertex   1.820711e+00 -1.285229e-02 -6.953286e-02
    endloop
  endfacet
  facet normal 7.071199e-01 -1.830093e-01 -6.830000e-01
    outer loop
      vertex   1.820711e+00 -1.285229e-02 -6.953286e-02
      vertex   9.603553e-01 -2.590388e-01 -8.943058e-01
      vertex   9.603553e-01 -2.228187e-01 -9.040109e-01
    endloop
  endfacet
  facet normal 7.070510e-01 -1.553744e-01 -6.898824e-01
    outer loop
      vertex   1.820711e+00 -1.285229e-02 -6.953286e-02
      vertex   9.603553e-01 -2.228187e-01 -9.040109e-01
      vertex   9.603553e-01 -1.862371e-01 -9.122498e-01
    endloop
  endfacet
  facet normal 7.072166e-01 -3.035964e-01 -6.384935e-01
    outer loop
      vertex   1.820711e+00 -3.579973e-02 -6.097852e-02
      vertex   9.603553e-01 -3.991411e-01 -8.411720e-01
      vertex   1.820711e+00 -2.469917e-02 -6.625671e-02
    endloop
  endfacet
  facet normal 7.070926e-01 -2.902115e-01 -6.448235e-01
    outer loop
      vertex   1.820711e+00 -2.469917e-02 -6.625671e-02
      vertex   9.603553e-01 -3.991411e-01 -8.411720e-01
      vertex   9.603553e-01 -3.649468e-01 -8.565616e-01
    endloop
  endfacet
  facet normal 7.070389e-01 -2.640318e-01 -6.560360e-01
    outer loop
      vertex   1.820711e+00 -2.469917e-02 -6.625671e-02
      vertex   9.603553e-01 -3.649468e-01 -8.565616e-01
      vertex   9.603553e-01 -3.301606e-01 -8.705618e-01
    endloop
  endfacet
  facet normal 7.071806e-01 -4.095988e-01 -5.763024e-01
    outer loop
      vertex   1.820711e+00 -4.581855e-02 -5.385778e-02
      vertex   9.603553e-01 -5.289058e-01 -7.662523e-01
      vertex   1.820711e+00 -3.579973e-02 -6.097852e-02
    endloop
  endfacet
  facet normal 7.070702e-01 -3.899026e-01 -5.899387e-01
    outer loop
      vertex   1.820711e+00 -3.579973e-02 -6.097852e-02
      vertex   9.603553e-01 -5.289058e-01 -7.662523e-01
      vertex   9.603553e-01 -4.976230e-01 -7.869278e-01
    endloop
  endfacet
  facet normal 7.070316e-01 -3.658520e-01 -6.051931e-01
    outer loop
      vertex   1.820711e+00 -3.579973e-02 -6.097852e-02
      vertex   9.603553e-01 -4.976230e-01 -7.869278e-01
      vertex   9.603553e-01 -4.655330e-01 -8.063268e-01
    endloop
  endfacet
  facet normal 7.071814e-01 -5.032087e-01 -4.966644e-01
    outer loop
      vertex   1.820711e+00 -5.445291e-02 -4.510965e-02
      vertex   9.603553e-01 -6.714871e-01 -6.449721e-01
      vertex   1.820711e+00 -4.581855e-02 -5.385778e-02
    endloop
  endfacet
  facet normal 7.071232e-01 -4.999884e-01 -4.999884e-01
    outer loop
      vertex   1.820711e+00 -4.581855e-02 -5.385778e-02
      vertex   9.603553e-01 -6.714871e-01 -6.449721e-01
      vertex   9.603553e-01 -6.449721e-01 -6.714871e-01
    endloop
  endfacet
  facet normal 7.070527e-01 -4.794982e-01 -5.197672e-01
    outer loop
      vertex   1.820711e+00 -4.581855e-02 -5.385778e-02
      vertex   9.603553e-01 -6.449721e-01 -6.714871e-01
      vertex   9.603553e-01 -6.174110e-01 -6.969129e-01
    endloop
  endfacet
  facet normal 7.072166e-01 -5.815848e-01 -4.019997e-01
    outer loop
      vertex   1.820711e+00 -6.144190e-02 -3.499848e-02
      vertex   9.603553e-01 -7.662523e-01 -5.289058e-01
      vertex   1.820711e+00 -5.445291e-02 -4.510965e-02
    endloop
  endfacet
  facet normal 7.070954e-01 -5.737400e-01 -4.133261e-01
    outer loop
      vertex   1.820711e+00 -5.445291e-02 -4.510965e-02
      vertex   9.603553e-01 -7.662523e-01 -5.289058e-01
      vertex   9.603553e-01 -7.443340e-01 -5.593307e-01
    endloop
  endfacet
  facet normal 7.070400e-01 -5.566754e-01 -4.361273e-01
    outer loop
      vertex   1.820711e+00 -5.445291e-02 -4.510965e-02
      vertex   9.603553e-01 -7.443340e-01 -5.593307e-01
      vertex   9.603553e-01 -7.212084e-01 -5.888484e-01
    endloop
  endfacet
  facet normal 7.071878e-01 -6.424389e-01 -2.952248e-01
    outer loop
      vertex   1.820711e+00 -6.657433e-02 -2.382978e-02
      vertex   9.603553e-01 -8.411720e-01 -3.991411e-01
      vertex   1.820711e+00 -6.144190e-02 -3.499848e-02
    endloop
  endfacet
  facet normal 7.070725e-01 -6.326329e-01 -3.159495e-01
    outer loop
      vertex   1.820711e+00 -6.144190e-02 -3.499848e-02
      vertex   9.603553e-01 -8.411720e-01 -3.991411e-01
      vertex   9.603553e-01 -8.244180e-01 -4.326880e-01
    endloop
  endfacet
  facet normal 7.070322e-01 -6.194331e-01 -3.411863e-01
    outer loop
      vertex   1.820711e+00 -6.144190e-02 -3.499848e-02
      vertex   9.603553e-01 -8.244180e-01 -4.326880e-01
      vertex   9.603553e-01 -8.063268e-01 -4.655330e-01
    endloop
  endfacet
  facet normal 7.071734e-01 -6.838710e-01 -1.795165e-01
    outer loop
      vertex   1.820711e+00 -6.969513e-02 -1.194103e-02
      vertex   9.603553e-01 -9.040109e-01 -2.228187e-01
      vertex   1.820711e+00 -6.657433e-02 -2.382978e-02
    endloop
  endfacet
  facet normal 7.071267e-01 -6.829935e-01 -1.830076e-01
    outer loop
      vertex   1.820711e+00 -6.657433e-02 -2.382978e-02
      vertex   9.603553e-01 -9.040109e-01 -2.228187e-01
      vertex   9.603553e-01 -8.943058e-01 -2.590388e-01
    endloop
  endfacet
  facet normal 7.070544e-01 -6.751396e-01 -2.103820e-01
    outer loop
      vertex   1.820711e+00 -6.657433e-02 -2.382978e-02
      vertex   9.603553e-01 -8.943058e-01 -2.590388e-01
      vertex   9.603553e-01 -8.831500e-01 -2.948388e-01
    endloop
  endfacet
  facet normal 7.072159e-01 -7.045837e-01 -5.837442e-02
    outer loop
      vertex   1.820711e+00 -7.071001e-02 3.085326e-04
      vertex   9.603553e-01 -9.280469e-01 -7.491969e-02
      vertex   1.820711e+00 -6.969513e-02 -1.194103e-02
    endloop
  endfacet
  facet normal 7.070983e-01 -7.035336e-01 -7.108064e-02
    outer loop
      vertex   1.820711e+00 -6.969513e-02 -1.194103e-02
      vertex   9.603553e-01 -9.280469e-01 -7.491969e-02
      vertex   9.603553e-01 -9.242775e-01 -1.122276e-01
    endloop
  endfacet
  facet normal 7.070412e-01 -7.001575e-01 -9.935947e-02
    outer loop
      vertex   1.820711e+00 -6.969513e-02 -1.194103e-02
      vertex   9.603553e-01 -9.242775e-01 -1.122276e-01
      vertex   9.603553e-01 -9.190090e-01 -1.493535e-01
    endloop
  endfacet
  facet normal 7.071943e-01 -7.040689e-01 6.452274e-02
    outer loop
      vertex   1.820711e+00 -6.958828e-02 1.254877e-02
      vertex   9.603553e-01 -9.280469e-01 7.491969e-02
      vertex   1.820711e+00 -7.071001e-02 3.085326e-04
    endloop
  endfacet
  facet normal 7.070748e-01 -7.058486e-01 4.269597e-02
    outer loop
      vertex   1.820711e+00 -7.071001e-02 3.085326e-04
      vertex   9.603553e-01 -9.280469e-01 7.491969e-02
      vertex   9.603553e-01 -9.303109e-01 3.749025e-02
    endloop
  endfacet
  facet normal 7.070328e-01 -7.070374e-01 1.424054e-02
    outer loop
      vertex   1.820711e+00 -7.071001e-02 3.085326e-04
      vertex   9.603553e-01 -9.303109e-01 3.749025e-02
      vertex   9.603553e-01 -9.310660e-01 5.701135e-17
    endloop
  endfacet
  facet normal 7.071646e-01 -6.822869e-01 1.854798e-01
    outer loop
      vertex   1.820711e+00 -6.636385e-02 2.440984e-02
      vertex   9.603553e-01 -8.943058e-01 2.590388e-01
      vertex   1.820711e+00 -6.958828e-02 1.254877e-02
    endloop
  endfacet
  facet normal 7.071302e-01 -6.829901e-01 1.830066e-01
    outer loop
      vertex   1.820711e+00 -6.958828e-02 1.254877e-02
      vertex   9.603553e-01 -8.943058e-01 2.590388e-01
      vertex   9.603553e-01 -9.040109e-01 2.228187e-01
    endloop
  endfacet
  facet normal 7.070562e-01 -6.898773e-01 1.553732e-01
    outer loop
      vertex   1.820711e+00 -6.958828e-02 1.254877e-02
      vertex   9.603553e-01 -9.040109e-01 2.228187e-01
      vertex   9.603553e-01 -9.122498e-01 1.862371e-01
    endloop
  endfacet
  facet normal 7.072143e-01 -6.398142e-01 3.008085e-01
    outer loop
      vertex   1.820711e+00 -6.113414e-02 3.553332e-02
      vertex   9.603553e-01 -8.411720e-01 3.991411e-01
      vertex   1.820711e+00 -6.636385e-02 2.440984e-02
    endloop
  endfacet
  facet normal 7.071013e-01 -6.448156e-01 2.902079e-01
    outer loop
      vertex   1.820711e+00 -6.636385e-02 2.440984e-02
      vertex   9.603553e-01 -8.411720e-01 3.991411e-01
      vertex   9.603553e-01 -8.565616e-01 3.649468e-01
    endloop
  endfacet
  facet normal 7.070424e-01 -6.560327e-01 2.640304e-01
    outer loop
      vertex   1.820711e+00 -6.636385e-02 2.440984e-02
      vertex   9.603553e-01 -8.565616e-01 3.649468e-01
      vertex   9.603553e-01 -8.705618e-01 3.301606e-01
    endloop
  endfacet
  facet normal 7.071999e-01 -5.780683e-01 4.070692e-01
    outer loop
      vertex   1.820711e+00 -5.405718e-02 4.558312e-02
      vertex   9.603553e-01 -7.662523e-01 5.289058e-01
      vertex   1.820711e+00 -6.113414e-02 3.553332e-02
    endloop
  endfacet
  facet normal 7.070772e-01 -5.899328e-01 3.898988e-01
    outer loop
      vertex   1.820711e+00 -6.113414e-02 3.553332e-02
      vertex   9.603553e-01 -7.662523e-01 5.289058e-01
      vertex   9.603553e-01 -7.869278e-01 4.976230e-01
    endloop
  endfacet
  facet normal 7.070335e-01 -6.051914e-01 3.658510e-01
    outer loop
      vertex   1.820711e+00 -6.113414e-02 3.553332e-02
      vertex   9.603553e-01 -7.869278e-01 4.976230e-01
      vertex   9.603553e-01 -8.063268e-01 4.655330e-01
    endloop
  endfacet
  facet normal 7.071551e-01 -4.988739e-01 5.010554e-01
    outer loop
      vertex   1.820711e+00 -4.534682e-02 5.425556e-02
      vertex   9.603553e-01 -6.449721e-01 6.714871e-01
      vertex   1.820711e+00 -5.405718e-02 4.558312e-02
    endloop
  endfacet
  facet normal 7.071337e-01 -4.999810e-01 4.999810e-01
    outer loop
      vertex   1.820711e+00 -5.405718e-02 4.558312e-02
      vertex   9.603553e-01 -6.449721e-01 6.714871e-01
      vertex   9.603553e-01 -6.714871e-01 6.449721e-01
    endloop
  endfacet
  facet normal 7.070580e-01 -5.197633e-01 4.794946e-01
    outer loop
      vertex   1.820711e+00 -5.405718e-02 4.558312e-02
      vertex   9.603553e-01 -6.714871e-01 6.449721e-01
      vertex   9.603553e-01 -6.969129e-01 6.174110e-01
    endloop
  endfacet
  facet normal 7.072119e-01 -4.045362e-01 5.798291e-01
    outer loop
      vertex   1.820711e+00 -3.526624e-02 6.128860e-02
      vertex   9.603553e-01 -5.289058e-01 7.662523e-01
      vertex   1.820711e+00 -4.534682e-02 5.425556e-02
    endloop
  endfacet
  facet normal 7.071043e-01 -4.133210e-01 5.737328e-01
    outer loop
      vertex   1.820711e+00 -4.534682e-02 5.425556e-02
      vertex   9.603553e-01 -5.289058e-01 7.662523e-01
      vertex   9.603553e-01 -5.593307e-01 7.443340e-01
    endloop
  endfacet
  facet normal 7.070437e-01 -4.361250e-01 5.566724e-01
    outer loop
      vertex   1.820711e+00 -4.534682e-02 5.425556e-02
      vertex   9.603553e-01 -5.593307e-01 7.443340e-01
      vertex   9.603553e-01 -5.888484e-01 7.212084e-01
    endloop
  endfacet
  facet normal 7.072047e-01 -2.980180e-01 6.411293e-01
    outer loop
      vertex   1.820711e+00 -2.412004e-02 6.646972e-02
      vertex   9.603553e-01 -3.991411e-01 8.411720e-01
      vertex   1.820711e+00 -3.526624e-02 6.128860e-02
    endloop
  endfacet
  facet normal 7.070797e-01 -3.159463e-01 6.326265e-01
    outer loop
      vertex   1.820711e+00 -3.526624e-02 6.128860e-02
      vertex   9.603553e-01 -3.991411e-01 8.411720e-01
      vertex   9.603553e-01 -4.326880e-01 8.244180e-01
    endloop
  endfacet
  facet normal 7.070343e-01 -3.411853e-01 6.194313e-01
    outer loop
      vertex   1.820711e+00 -3.526624e-02 6.128860e-02
      vertex   9.603553e-01 -4.326880e-01 8.244180e-01
      vertex   9.603553e-01 -4.655330e-01 8.063268e-01
    endloop
  endfacet
  facet normal 7.071447e-01 -1.825062e-01 6.831090e-01
    outer loop
      vertex   1.820711e+00 -1.224502e-02 6.964237e-02
      vertex   9.603553e-01 -2.228187e-01 9.040109e-01
      vertex   1.820711e+00 -2.412004e-02 6.646972e-02
    endloop
  endfacet
  facet normal 7.071373e-01 -1.830048e-01 6.829832e-01
    outer loop
      vertex   1.820711e+00 -2.412004e-02 6.646972e-02
      vertex   9.603553e-01 -2.228187e-01 9.040109e-01
      vertex   9.603553e-01 -2.590388e-01 8.943058e-01
    endloop
  endfacet
  facet normal 7.070600e-01 -2.103804e-01 6.751343e-01
    outer loop
      vertex   1.820711e+00 -2.412004e-02 6.646972e-02
      vertex   9.603553e-01 -2.590388e-01 8.943058e-01
      vertex   9.603553e-01 -2.948388e-01 8.831500e-01
    endloop
  endfacet
  facet normal 7.072084e-01 -6.144882e-02 7.043297e-01
    outer loop
      vertex   1.820711e+00 0.000000e+00 7.071068e-02
      vertex   9.603553e-01 -7.481586e-02 9.280552e-01
      vertex   1.820711e+00 -1.224502e-02 6.964237e-02
    endloop
  endfacet
  facet normal 7.071079e-01 -7.098130e-02 7.035340e-01
    outer loop
      vertex   1.820711e+00 -1.224502e-02 6.964237e-02
      vertex   9.603553e-01 -7.481586e-02 9.280552e-01
      vertex   9.603553e-01 -1.120725e-01 9.242963e-01
    endloop
  endfacet
  facet normal 7.070445e-01 -9.930025e-02 7.001625e-01
    outer loop
      vertex   1.820711e+00 -1.224502e-02 6.964237e-02
      vertex   9.603553e-01 -1.120725e-01 9.242963e-01
      vertex   9.603553e-01 -1.493535e-01 9.190090e-01
    endloop
  endfacet
  facet normal 7.070823e-01 -4.263630e-02 7.058447e-01
    outer loop
      vertex   9.603553e-01 -7.481586e-02 9.280552e-01
      vertex   1.820711e+00 0.000000e+00 7.071068e-02
      vertex   9.603553e-01 -3.743821e-02 9.303130e-01
    endloop
  endfacet
  facet normal 7.070413e-01 1.424037e-02 -7.070289e-01
    outer loop
      vertex   9.603553e-01 -1.140227e-16 -9.310660e-01
      vertex   9.603553e-01 3.749025e-02 -9.303109e-01
      vertex   1.820711e+00 -6.170592e-04 -7.070799e-02
    endloop
  endfacet
  facet normal 7.070986e-01 4.269454e-02 -7.058248e-01
    outer loop
      vertex   1.820711e+00 -6.170592e-04 -7.070799e-02
      vertex   9.603553e-01 3.749025e-02 -9.303109e-01
      vertex   9.603553e-01 7.491969e-02 -9.280469e-01
    endloop
  endfacet
  facet normal 7.070329e-01 1.274729e-01 -6.955970e-01
    outer loop
      vertex   9.603553e-01 1.493535e-01 -9.190090e-01
      vertex   9.603553e-01 1.862371e-01 -9.122498e-01
      vertex   1.820711e+00 1.163682e-02 -6.974657e-02
    endloop
  endfacet
  facet normal 7.070751e-01 1.553691e-01 -6.898589e-01
    outer loop
      vertex   1.820711e+00 1.163682e-02 -6.974657e-02
      vertex   9.603553e-01 1.862371e-01 -9.122498e-01
      vertex   9.603553e-01 2.228187e-01 -9.040109e-01
    endloop
  endfacet
  facet normal 7.070293e-01 2.374049e-01 -6.661445e-01
    outer loop
      vertex   9.603553e-01 2.948388e-01 -8.831500e-01
      vertex   9.603553e-01 3.301606e-01 -8.705618e-01
      vertex   1.820711e+00 2.353907e-02 -6.667767e-02
    endloop
  endfacet
  facet normal 7.070564e-01 2.640252e-01 -6.560198e-01
    outer loop
      vertex   1.820711e+00 2.353907e-02 -6.667767e-02
      vertex   9.603553e-01 3.301606e-01 -8.705618e-01
      vertex   9.603553e-01 3.649468e-01 -8.565616e-01
    endloop
  endfacet
  facet normal 7.071305e-01 2.901959e-01 -6.447889e-01
    outer loop
      vertex   1.820711e+00 2.353907e-02 -6.667767e-02
      vertex   9.603553e-01 3.649468e-01 -8.565616e-01
      vertex   9.603553e-01 3.991411e-01 -8.411720e-01
    endloop
  endfacet
  facet normal 7.071016e-01 3.898853e-01 -5.899125e-01
    outer loop
      vertex   9.603553e-01 5.289058e-01 -7.662523e-01
      vertex   1.820711e+00 3.473006e-02 -6.159402e-02
      vertex   9.603553e-01 4.976230e-01 -7.869278e-01
    endloop
  endfacet
  facet normal 7.070425e-01 3.658463e-01 -6.051837e-01
    outer loop
      vertex   9.603553e-01 4.976230e-01 -7.869278e-01
      vertex   1.820711e+00 3.473006e-02 -6.159402e-02
      vertex   9.603553e-01 4.655330e-01 -8.063268e-01
    endloop
  endfacet
  facet normal 7.070336e-01 4.581928e-01 -5.386677e-01
    outer loop
      vertex   9.603553e-01 5.888484e-01 -7.212084e-01
      vertex   9.603553e-01 6.174110e-01 -6.969129e-01
      vertex   1.820711e+00 4.487163e-02 -5.464922e-02
    endloop
  endfacet
  facet normal 7.070775e-01 4.794814e-01 -5.197490e-01
    outer loop
      vertex   1.820711e+00 4.487163e-02 -5.464922e-02
      vertex   9.603553e-01 6.174110e-01 -6.969129e-01
      vertex   9.603553e-01 6.449721e-01 -6.714871e-01
    endloop
  endfacet
  facet normal 7.070295e-01 5.386708e-01 -4.581955e-01
    outer loop
      vertex   9.603553e-01 6.969129e-01 -6.174110e-01
      vertex   9.603553e-01 7.212084e-01 -5.888484e-01
      vertex   1.820711e+00 5.365734e-02 -4.605312e-02
    endloop
  endfacet
  facet normal 7.070582e-01 5.566610e-01 -4.361160e-01
    outer loop
      vertex   1.820711e+00 5.365734e-02 -4.605312e-02
      vertex   9.603553e-01 7.212084e-01 -5.888484e-01
      vertex   9.603553e-01 7.443340e-01 -5.593307e-01
    endloop
  endfacet
  facet normal 7.071341e-01 5.737086e-01 -4.133035e-01
    outer loop
      vertex   1.820711e+00 5.365734e-02 -4.605312e-02
      vertex   9.603553e-01 7.443340e-01 -5.593307e-01
      vertex   9.603553e-01 7.662523e-01 -5.289058e-01
    endloop
  endfacet
  facet normal 7.071046e-01 6.326042e-01 -3.159352e-01
    outer loop
      vertex   9.603553e-01 8.411720e-01 -3.991411e-01
      vertex   1.820711e+00 6.082173e-02 -3.606546e-02
      vertex   9.603553e-01 8.244180e-01 -4.326880e-01
    endloop
  endfacet
  facet normal 7.070439e-01 6.194229e-01 -3.411807e-01
    outer loop
      vertex   9.603553e-01 8.244180e-01 -4.326880e-01
      vertex   1.820711e+00 6.082173e-02 -3.606546e-02
      vertex   9.603553e-01 8.063268e-01 -4.655330e-01
    endloop
  endfacet
  facet normal 7.070343e-01 6.661397e-01 -2.374033e-01
    outer loop
      vertex   9.603553e-01 8.705618e-01 -3.301606e-01
      vertex   9.603553e-01 8.831500e-01 -2.948388e-01
      vertex   1.820711e+00 6.614830e-02 -2.498803e-02
    endloop
  endfacet
  facet normal 7.070799e-01 6.751152e-01 -2.103744e-01
    outer loop
      vertex   1.820711e+00 6.614830e-02 -2.498803e-02
      vertex   9.603553e-01 8.831500e-01 -2.948388e-01
      vertex   9.603553e-01 8.943058e-01 -2.590388e-01
    endloop
  endfacet
  facet normal 7.070297e-01 6.956001e-01 -1.274735e-01
    outer loop
      vertex   9.603553e-01 9.122498e-01 -1.862371e-01
      vertex   9.603553e-01 9.190090e-01 -1.493535e-01
      vertex   1.820711e+00 6.947612e-02 -1.315556e-02
    endloop
  endfacet
  facet normal 7.070602e-01 7.001387e-01 -9.935680e-02
    outer loop
      vertex   1.820711e+00 6.947612e-02 -1.315556e-02
      vertex   9.603553e-01 9.190090e-01 -1.493535e-01
      vertex   9.603553e-01 9.242775e-01 -1.122276e-01
    endloop
  endfacet
  facet normal 7.071377e-01 7.034944e-01 -7.107668e-02
    outer loop
      vertex   1.820711e+00 6.947612e-02 -1.315556e-02
      vertex   9.603553e-01 9.242775e-01 -1.122276e-01
      vertex   9.603553e-01 9.280469e-01 -7.491969e-02
    endloop
  endfacet
  facet normal 7.071077e-01 7.058158e-01 4.269399e-02
    outer loop
      vertex   9.603553e-01 9.280469e-01 7.491969e-02
      vertex   1.820711e+00 7.070462e-02 -9.255742e-04
      vertex   9.603553e-01 9.303109e-01 3.749025e-02
    endloop
  endfacet
  facet normal 7.070452e-01 7.070249e-01 1.424029e-02
    outer loop
      vertex   9.603553e-01 9.303109e-01 3.749025e-02
      vertex   1.820711e+00 7.070462e-02 -9.255742e-04
      vertex   9.603553e-01 9.310660e-01 5.701135e-17
    endloop
  endfacet
  facet normal 7.070825e-01 6.898517e-01 1.553675e-01
    outer loop
      vertex   9.603553e-01 9.040109e-01 2.228187e-01
      vertex   1.820711e+00 6.979668e-02 1.133238e-02
      vertex   9.603553e-01 9.122498e-01 1.862371e-01
    endloop
  endfacet
  facet normal 7.070349e-01 6.955998e-01 1.274466e-01
    outer loop
      vertex   9.603553e-01 9.122498e-01 1.862371e-01
      vertex   1.820711e+00 6.979668e-02 1.133238e-02
      vertex   9.603553e-01 9.190201e-01 1.492849e-01
    endloop
  endfacet
  facet normal 7.070300e-01 6.661438e-01 2.374047e-01
    outer loop
      vertex   9.603553e-01 8.831500e-01 2.948388e-01
      vertex   9.603553e-01 8.705618e-01 3.301606e-01
      vertex   1.820711e+00 6.677975e-02 2.324791e-02
    endloop
  endfacet
  facet normal 7.070621e-01 6.560144e-01 2.640231e-01
    outer loop
      vertex   1.820711e+00 6.677975e-02 2.324791e-02
      vertex   9.603553e-01 8.705618e-01 3.301606e-01
      vertex   9.603553e-01 8.565616e-01 3.649468e-01
    endloop
  endfacet
  facet normal 7.070296e-01 6.194353e-01 3.411875e-01
    outer loop
      vertex   9.603553e-01 8.244180e-01 4.326880e-01
      vertex   9.603553e-01 8.063268e-01 4.655330e-01
      vertex   1.820711e+00 6.174497e-02 3.446097e-02
    endloop
  endfacet
  facet normal 7.070467e-01 6.051802e-01 3.658442e-01
    outer loop
      vertex   1.820711e+00 6.174497e-02 3.446097e-02
      vertex   9.603553e-01 8.063268e-01 4.655330e-01
      vertex   9.603553e-01 7.869278e-01 4.976230e-01
    endloop
  endfacet
  facet normal 7.071108e-01 5.899048e-01 3.898803e-01
    outer loop
      vertex   1.820711e+00 6.174497e-02 3.446097e-02
      vertex   9.603553e-01 7.869278e-01 4.976230e-01
      vertex   9.603553e-01 7.662523e-01 5.289058e-01
    endloop
  endfacet
  facet normal 7.070851e-01 5.197434e-01 4.794763e-01
    outer loop
      vertex   9.603553e-01 6.714871e-01 6.449721e-01
      vertex   1.820711e+00 5.484449e-02 4.463275e-02
      vertex   9.603553e-01 6.969129e-01 6.174110e-01
    endloop
  endfacet
  facet normal 7.070361e-01 5.386658e-01 4.581912e-01
    outer loop
      vertex   9.603553e-01 6.969129e-01 6.174110e-01
      vertex   1.820711e+00 5.484449e-02 4.463275e-02
      vertex   9.603553e-01 7.212084e-01 5.888484e-01
    endloop
  endfacet
  facet normal 7.070303e-01 4.581949e-01 5.386702e-01
    outer loop
      vertex   9.603553e-01 6.174110e-01 6.969129e-01
      vertex   9.603553e-01 5.888484e-01 7.212084e-01
      vertex   1.820711e+00 4.628680e-02 5.345589e-02
    endloop
  endfacet
  facet normal 7.070642e-01 4.361124e-01 5.566563e-01
    outer loop
      vertex   1.820711e+00 4.628680e-02 5.345589e-02
      vertex   9.603553e-01 5.888484e-01 7.212084e-01
      vertex   9.603553e-01 5.593307e-01 7.443340e-01
    endloop
  endfacet
  facet normal 7.070294e-01 3.658531e-01 6.051949e-01
    outer loop
      vertex   9.603553e-01 4.976230e-01 7.869278e-01
      vertex   9.603553e-01 4.655330e-01 8.063268e-01
      vertex   1.820711e+00 3.633050e-02 6.066379e-02
    endloop
  endfacet
  facet normal 7.070482e-01 3.411786e-01 6.194191e-01
    outer loop
      vertex   1.820711e+00 3.633050e-02 6.066379e-02
      vertex   9.603553e-01 4.655330e-01 8.063268e-01
      vertex   9.603553e-01 4.326880e-01 8.244180e-01
    endloop
  endfacet
  facet normal 7.071140e-01 3.159310e-01 6.325958e-01
    outer loop
      vertex   1.820711e+00 3.633050e-02 6.066379e-02
      vertex   9.603553e-01 4.326880e-01 8.244180e-01
      vertex   9.603553e-01 3.991411e-01 8.411720e-01
    endloop
  endfacet
  facet normal 7.070877e-01 2.103721e-01 6.751078e-01
    outer loop
      vertex   9.603553e-01 2.590388e-01 8.943058e-01
      vertex   1.820711e+00 2.527642e-02 6.603864e-02
      vertex   9.603553e-01 2.948388e-01 8.831500e-01
    endloop
  endfacet
  facet normal 7.070370e-01 2.374024e-01 6.661372e-01
    outer loop
      vertex   9.603553e-01 2.948388e-01 8.831500e-01
      vertex   1.820711e+00 2.527642e-02 6.603864e-02
      vertex   9.603553e-01 3.301606e-01 8.705618e-01
    endloop
  endfacet
  facet normal 7.070307e-01 1.274733e-01 6.955991e-01
    outer loop
      vertex   9.603553e-01 1.862371e-01 9.122498e-01
      vertex   9.603553e-01 1.493535e-01 9.190090e-01
      vertex   1.820711e+00 1.345858e-02 6.941806e-02
    endloop
  endfacet
  facet normal 7.070663e-01 9.935594e-02 7.001326e-01
    outer loop
      vertex   1.820711e+00 1.345858e-02 6.941806e-02
      vertex   9.603553e-01 1.493535e-01 9.190090e-01
      vertex   9.603553e-01 1.122276e-01 9.242775e-01
    endloop
  endfacet
  facet normal 7.070299e-01 -1.274734e-01 6.955999e-01
    outer loop
      vertex   9.603553e-01 -1.493535e-01 9.190090e-01
      vertex   9.603553e-01 -1.862371e-01 9.122498e-01
      vertex   1.820711e+00 -1.224502e-02 6.964237e-02
    endloop
  endfacet
  facet normal 7.070619e-01 -1.553720e-01 6.898717e-01
    outer loop
      vertex   1.820711e+00 -1.224502e-02 6.964237e-02
      vertex   9.603553e-01 -1.862371e-01 9.122498e-01
      vertex   9.603553e-01 -2.228187e-01 9.040109e-01
    endloop
  endfacet
  facet normal 7.070297e-01 -2.374048e-01 6.661441e-01
    outer loop
      vertex   9.603553e-01 -2.948388e-01 8.831500e-01
      vertex   9.603553e-01 -3.301606e-01 8.705618e-01
      vertex   1.820711e+00 -2.412004e-02 6.646972e-02
    endloop
  endfacet
  facet normal 7.070465e-01 -2.640289e-01 6.560289e-01
    outer loop
      vertex   1.820711e+00 -2.412004e-02 6.646972e-02
      vertex   9.603553e-01 -3.301606e-01 8.705618e-01
      vertex   9.603553e-01 -3.649468e-01 8.565616e-01
    endloop
  endfacet
  facet normal 7.071105e-01 -2.902042e-01 6.448072e-01
    outer loop
      vertex   1.820711e+00 -2.412004e-02 6.646972e-02
      vertex   9.603553e-01 -3.649468e-01 8.565616e-01
      vertex   9.603553e-01 -3.991411e-01 8.411720e-01
    endloop
  endfacet
  facet normal 7.070848e-01 -3.898946e-01 5.899265e-01
    outer loop
      vertex   9.603553e-01 -5.289058e-01 7.662523e-01
      vertex   1.820711e+00 -3.526624e-02 6.128860e-02
      vertex   9.603553e-01 -4.976230e-01 7.869278e-01
    endloop
  endfacet
  facet normal 7.070360e-01 -3.658497e-01 6.051893e-01
    outer loop
      vertex   9.603553e-01 -4.976230e-01 7.869278e-01
      vertex   1.820711e+00 -3.526624e-02 6.128860e-02
      vertex   9.603553e-01 -4.655330e-01 8.063268e-01
    endloop
  endfacet
  facet normal 7.070303e-01 -4.581949e-01 5.386702e-01
    outer loop
      vertex   9.603553e-01 -5.888484e-01 7.212084e-01
      vertex   9.603553e-01 -6.174110e-01 6.969129e-01
      vertex   1.820711e+00 -4.534682e-02 5.425556e-02
    endloop
  endfacet
  facet normal 7.070640e-01 -4.794906e-01 5.197589e-01
    outer loop
      vertex   1.820711e+00 -4.534682e-02 5.425556e-02
      vertex   9.603553e-01 -6.174110e-01 6.969129e-01
      vertex   9.603553e-01 -6.449721e-01 6.714871e-01
    endloop
  endfacet
  facet normal 7.070295e-01 -5.386708e-01 4.581955e-01
    outer loop
      vertex   9.603553e-01 -6.969129e-01 6.174110e-01
      vertex   9.603553e-01 -7.212084e-01 5.888484e-01
      vertex   1.820711e+00 -5.405718e-02 4.558312e-02
    endloop
  endfacet
  facet normal 7.070480e-01 -5.566690e-01 4.361223e-01
    outer loop
      vertex   1.820711e+00 -5.405718e-02 4.558312e-02
      vertex   9.603553e-01 -7.212084e-01 5.888484e-01
      vertex   9.603553e-01 -7.443340e-01 5.593307e-01
    endloop
  endfacet
  facet normal 7.071137e-01 -5.737252e-01 4.133155e-01
    outer loop
      vertex   1.820711e+00 -5.405718e-02 4.558312e-02
      vertex   9.603553e-01 -7.443340e-01 5.593307e-01
      vertex   9.603553e-01 -7.662523e-01 5.289058e-01
    endloop
  endfacet
  facet normal 7.070874e-01 -6.326195e-01 3.159429e-01
    outer loop
      vertex   9.603553e-01 -8.411720e-01 3.991411e-01
      vertex   1.820711e+00 -6.113414e-02 3.553332e-02
      vertex   9.603553e-01 -8.244180e-01 4.326880e-01
    endloop
  endfacet
  facet normal 7.070369e-01 -6.194290e-01 3.411840e-01
    outer loop
      vertex   9.603553e-01 -8.244180e-01 4.326880e-01
      vertex   1.820711e+00 -6.113414e-02 3.553332e-02
      vertex   9.603553e-01 -8.063268e-01 4.655330e-01
    endloop
  endfacet
  facet normal 7.070307e-01 -6.661432e-01 2.374045e-01
    outer loop
      vertex   9.603553e-01 -8.705618e-01 3.301606e-01
      vertex   9.603553e-01 -8.831500e-01 2.948388e-01
      vertex   1.820711e+00 -6.636385e-02 2.440984e-02
    endloop
  endfacet
  facet normal 7.070661e-01 -6.751285e-01 2.103785e-01
    outer loop
      vertex   1.820711e+00 -6.636385e-02 2.440984e-02
      vertex   9.603553e-01 -8.831500e-01 2.948388e-01
      vertex   9.603553e-01 -8.943058e-01 2.590388e-01
    endloop
  endfacet
  facet normal 7.070293e-01 -6.956005e-01 1.274735e-01
    outer loop
      vertex   9.603553e-01 -9.122498e-01 1.862371e-01
      vertex   9.603553e-01 -9.190090e-01 1.493535e-01
      vertex   1.820711e+00 -6.958828e-02 1.254877e-02
    endloop
  endfacet
  facet normal 7.070496e-01 -7.001492e-01 9.935829e-02
    outer loop
      vertex   1.820711e+00 -6.958828e-02 1.254877e-02
      vertex   9.603553e-01 -9.190090e-01 1.493535e-01
      vertex   9.603553e-01 -9.242775e-01 1.122276e-01
    endloop
  endfacet
  facet normal 7.071169e-01 -7.035151e-01 7.107877e-02
    outer loop
      vertex   1.820711e+00 -6.958828e-02 1.254877e-02
      vertex   9.603553e-01 -9.242775e-01 1.122276e-01
      vertex   9.603553e-01 -9.280469e-01 7.491969e-02
    endloop
  endfacet
  facet normal 7.070901e-01 -7.058333e-01 -4.269505e-02
    outer loop
      vertex   9.603553e-01 -9.280469e-01 -7.491969e-02
      vertex   1.820711e+00 -7.071001e-02 3.085326e-04
      vertex   9.603553e-01 -9.303109e-01 -3.749025e-02
    endloop
  endfacet
  facet normal 7.070379e-01 -7.070323e-01 -1.424043e-02
    outer loop
      vertex   9.603553e-01 -9.303109e-01 -3.749025e-02
      vertex   1.820711e+00 -7.071001e-02 3.085326e-04
      vertex   9.603553e-01 -9.310660e-01 5.701135e-17
    endloop
  endfacet
  facet normal 7.070311e-01 -6.955987e-01 -1.274732e-01
    outer loop
      vertex   9.603553e-01 -9.190090e-01 -1.493535e-01
      vertex   9.603553e-01 -9.122498e-01 -1.862371e-01
      vertex   1.820711e+00 -6.969513e-02 -1.194103e-02
    endloop
  endfacet
  facet normal 7.070682e-01 -6.898656e-01 -1.553706e-01
    outer loop
      vertex   1.820711e+00 -6.969513e-02 -1.194103e-02
      vertex   9.603553e-01 -9.122498e-01 -1.862371e-01
      vertex   9.603553e-01 -9.040109e-01 -2.228187e-01
    endloop
  endfacet
  facet normal 7.070292e-01 -6.661446e-01 -2.374050e-01
    outer loop
      vertex   9.603553e-01 -8.831500e-01 -2.948388e-01
      vertex   9.603553e-01 -8.705618e-01 -3.301606e-01
      vertex   1.820711e+00 -6.657433e-02 -2.382978e-02
    endloop
  endfacet
  facet normal 7.070512e-01 -6.560246e-01 -2.640272e-01
    outer loop
      vertex   1.820711e+00 -6.657433e-02 -2.382978e-02
      vertex   9.603553e-01 -8.705618e-01 -3.301606e-01
      vertex   9.603553e-01 -8.565616e-01 -3.649468e-01
    endloop
  endfacet
  facet normal 7.071202e-01 -6.447983e-01 -2.902002e-01
    outer loop
      vertex   1.820711e+00 -6.657433e-02 -2.382978e-02
      vertex   9.603553e-01 -8.565616e-01 -3.649468e-01
      vertex   9.603553e-01 -8.411720e-01 -3.991411e-01
    endloop
  endfacet
  facet normal 7.070929e-01 -5.899197e-01 -3.898901e-01
    outer loop
      vertex   9.603553e-01 -7.662523e-01 -5.289058e-01
      vertex   1.820711e+00 -6.144190e-02 -3.499848e-02
      vertex   9.603553e-01 -7.869278e-01 -4.976230e-01
    endloop
  endfacet
  facet normal 7.070390e-01 -6.051868e-01 -3.658482e-01
    outer loop
      vertex   9.603553e-01 -7.869278e-01 -4.976230e-01
      vertex   1.820711e+00 -6.144190e-02 -3.499848e-02
      vertex   9.603553e-01 -8.063268e-01 -4.655330e-01
    endloop
  endfacet
  facet normal 7.070316e-01 -5.386692e-01 -4.581940e-01
    outer loop
      vertex   9.603553e-01 -7.212084e-01 -5.888484e-01
      vertex   9.603553e-01 -6.969129e-01 -6.174110e-01
      vertex   1.820711e+00 -5.445291e-02 -4.510965e-02
    endloop
  endfacet
  facet normal 7.070704e-01 -5.197542e-01 -4.794862e-01
    outer loop
      vertex   1.820711e+00 -5.445291e-02 -4.510965e-02
      vertex   9.603553e-01 -6.969129e-01 -6.174110e-01
      vertex   9.603553e-01 -6.714871e-01 -6.449721e-01
    endloop
  endfacet
  facet normal 7.070292e-01 -4.581956e-01 -5.386710e-01
    outer loop
      vertex   9.603553e-01 -6.174110e-01 -6.969129e-01
      vertex   9.603553e-01 -5.888484e-01 -7.212084e-01
      vertex   1.820711e+00 -4.581855e-02 -5.385778e-02
    endloop
  endfacet
  facet normal 7.070528e-01 -4.361194e-01 -5.566652e-01
    outer loop
      vertex   1.820711e+00 -4.581855e-02 -5.385778e-02
      vertex   9.603553e-01 -5.888484e-01 -7.212084e-01
      vertex   9.603553e-01 -5.593307e-01 -7.443340e-01
    endloop
  endfacet
  facet normal 7.071236e-01 -4.133097e-01 -5.737171e-01
    outer loop
      vertex   1.820711e+00 -4.581855e-02 -5.385778e-02
      vertex   9.603553e-01 -5.593307e-01 -7.443340e-01
      vertex   9.603553e-01 -5.289058e-01 -7.662523e-01
    endloop
  endfacet
  facet normal 7.070957e-01 -3.159392e-01 -6.326121e-01
    outer loop
      vertex   9.603553e-01 -3.991411e-01 -8.411720e-01
      vertex   1.820711e+00 -3.579973e-02 -6.097852e-02
      vertex   9.603553e-01 -4.326880e-01 -8.244180e-01
    endloop
  endfacet
  facet normal 7.070401e-01 -3.411825e-01 -6.194262e-01
    outer loop
      vertex   9.603553e-01 -4.326880e-01 -8.244180e-01
      vertex   1.820711e+00 -3.579973e-02 -6.097852e-02
      vertex   9.603553e-01 -4.655330e-01 -8.063268e-01
    endloop
  endfacet
  facet normal 7.070322e-01 -2.374040e-01 -6.661417e-01
    outer loop
      vertex   9.603553e-01 -3.301606e-01 -8.705618e-01
      vertex   9.603553e-01 -2.948388e-01 -8.831500e-01
      vertex   1.820711e+00 -2.469917e-02 -6.625671e-02
    endloop
  endfacet
  facet normal 7.070727e-01 -2.103766e-01 -6.751221e-01
    outer loop
      vertex   1.820711e+00 -2.469917e-02 -6.625671e-02
      vertex   9.603553e-01 -2.948388e-01 -8.831500e-01
      vertex   9.603553e-01 -2.590388e-01 -8.943058e-01
    endloop
  endfacet
  facet normal 7.070292e-01 -1.274735e-01 -6.956006e-01
    outer loop
      vertex   9.603553e-01 -1.862371e-01 -9.122498e-01
      vertex   9.603553e-01 -1.493535e-01 -9.190090e-01
      vertex   1.820711e+00 -1.285229e-02 -6.953286e-02
    endloop
  endfacet
  facet normal 7.070546e-01 -9.935758e-02 -7.001442e-01
    outer loop
      vertex   1.820711e+00 -1.285229e-02 -6.953286e-02
      vertex   9.603553e-01 -1.493535e-01 -9.190090e-01
      vertex   9.603553e-01 -1.122276e-01 -9.242775e-01
    endloop
  endfacet
  facet normal 7.071270e-01 -7.107776e-02 -7.035050e-01
    outer loop
      vertex   1.820711e+00 -1.285229e-02 -6.953286e-02
      vertex   9.603553e-01 -1.122276e-01 -9.242775e-01
      vertex   9.603553e-01 -7.491969e-02 -9.280469e-01
    endloop
  endfacet
  facet normal 3.564326e-17 -9.998477e-01 1.745241e-02
    outer loop
      vertex   1.000000e-01 3.126461e-02 1.791149e+00
      vertex   1.000000e-01 2.879647e-02 1.649749e+00
      vertex   1.820711e+00 1.234071e-03 7.069991e-02
    endloop
  endfacet
  facet normal -6.226101e-17 -9.998477e-01 1.745241e-02
    outer loop
      vertex   1.820711e+00 1.234071e-03 7.069991e-02
      vertex   1.000000e-01 2.879647e-02 1.649749e+00
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal -7.069444e-01 -2.708198e-02 -7.067504e-01
    outer loop
      vertex   1.000000e-01 9.753610e-02 1.647115e+00
      vertex   8.750000e-01 3.569001e-02 8.742718e-01
      vertex   1.000000e-01 2.879647e-02 1.649749e+00
    endloop
  endfacet
  facet normal -7.070827e-01 -2.059340e-02 -7.068309e-01
    outer loop
      vertex   1.000000e-01 2.879647e-02 1.649749e+00
      vertex   8.750000e-01 3.569001e-02 8.742718e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal -7.071882e-01 -4.324284e-02 -7.057017e-01
    outer loop
      vertex   8.750000e-01 3.569001e-02 8.742718e-01
      vertex   1.000000e-01 9.753610e-02 1.647115e+00
      vertex   8.750000e-01 7.132062e-02 8.720885e-01
    endloop
  endfacet
  facet normal -7.069437e-01 -5.651720e-02 -7.050081e-01
    outer loop
      vertex   8.750000e-01 7.132062e-02 8.720885e-01
      vertex   1.000000e-01 9.753610e-02 1.647115e+00
      vertex   1.000000e-01 1.661062e-01 1.641618e+00
    endloop
  endfacet
  facet normal -7.071893e-01 -7.199132e-02 -7.033495e-01
    outer loop
      vertex   8.750000e-01 7.132062e-02 8.720885e-01
      vertex   1.000000e-01 1.661062e-01 1.641618e+00
      vertex   8.750000e-01 1.068325e-01 8.684537e-01
    endloop
  endfacet
  facet normal -7.069433e-01 -8.585421e-02 -7.020401e-01
    outer loop
      vertex   8.750000e-01 1.068325e-01 8.684537e-01
      vertex   1.000000e-01 1.661062e-01 1.641618e+00
      vertex   1.000000e-01 2.343876e-01 1.633267e+00
    endloop
  endfacet
  facet normal -7.071898e-01 -1.006200e-01 -6.998273e-01
    outer loop
      vertex   8.750000e-01 1.068325e-01 8.684537e-01
      vertex   1.000000e-01 2.343876e-01 1.633267e+00
      vertex   8.750000e-01 1.421666e-01 8.633734e-01
    endloop
  endfacet
  facet normal -7.069432e-01 -1.150420e-01 -6.978515e-01
    outer loop
      vertex   8.750000e-01 1.421666e-01 8.633734e-01
      vertex   1.000000e-01 2.343876e-01 1.633267e+00
      vertex   1.000000e-01 3.022616e-01 1.622078e+00
    endloop
  endfacet
  facet normal -7.071897e-01 -1.290812e-01 -6.951409e-01
    outer loop
      vertex   8.750000e-01 1.421666e-01 8.633734e-01
      vertex   1.000000e-01 3.022616e-01 1.622078e+00
      vertex   8.750000e-01 1.772641e-01 8.568561e-01
    endloop
  endfacet
  facet normal -7.069434e-01 -1.440297e-01 -6.924496e-01
    outer loop
      vertex   8.750000e-01 1.772641e-01 8.568561e-01
      vertex   1.000000e-01 3.022616e-01 1.622078e+00
      vertex   1.000000e-01 3.696102e-01 1.608070e+00
    endloop
  endfacet
  facet normal -7.071889e-01 -1.573278e-01 -6.892980e-01
    outer loop
      vertex   8.750000e-01 1.772641e-01 8.568561e-01
      vertex   1.000000e-01 3.696102e-01 1.608070e+00
      vertex   8.750000e-01 2.120665e-01 8.489127e-01
    endloop
  endfacet
  facet normal -7.069439e-01 -1.727670e-01 -6.858439e-01
    outer loop
      vertex   8.750000e-01 2.120665e-01 8.489127e-01
      vertex   1.000000e-01 3.696102e-01 1.608070e+00
      vertex   1.000000e-01 4.363164e-01 1.591266e+00
    endloop
  endfacet
  facet normal -7.071876e-01 -1.853127e-01 -6.823085e-01
    outer loop
      vertex   8.750000e-01 2.120665e-01 8.489127e-01
      vertex   1.000000e-01 4.363164e-01 1.591266e+00
      vertex   8.750000e-01 2.465160e-01 8.395564e-01
    endloop
  endfacet
  facet normal -7.069448e-01 -2.012039e-01 -6.780457e-01
    outer loop
      vertex   8.750000e-01 2.465160e-01 8.395564e-01
      vertex   1.000000e-01 4.363164e-01 1.591266e+00
      vertex   1.000000e-01 5.022642e-01 1.571697e+00
    endloop
  endfacet
  facet normal -7.071857e-01 -2.129894e-01 -6.741839e-01
    outer loop
      vertex   8.750000e-01 2.465160e-01 8.395564e-01
      vertex   1.000000e-01 5.022642e-01 1.571697e+00
      vertex   8.750000e-01 2.805552e-01 8.288026e-01
    endloop
  endfacet
  facet normal -7.069460e-01 -2.292909e-01 -6.690688e-01
    outer loop
      vertex   8.750000e-01 2.805552e-01 8.288026e-01
      vertex   1.000000e-01 5.022642e-01 1.571697e+00
      vertex   1.000000e-01 5.673390e-01 1.549396e+00
    endloop
  endfacet
  facet normal -7.071832e-01 -2.403121e-01 -6.649377e-01
    outer loop
      vertex   8.750000e-01 2.805552e-01 8.288026e-01
      vertex   1.000000e-01 5.673390e-01 1.549396e+00
      vertex   8.750000e-01 3.141274e-01 8.166695e-01
    endloop
  endfacet
  facet normal -7.069475e-01 -2.569792e-01 -6.589286e-01
    outer loop
      vertex   8.750000e-01 3.141274e-01 8.166695e-01
      vertex   1.000000e-01 5.673390e-01 1.549396e+00
      vertex   1.000000e-01 6.314277e-01 1.524401e+00
    endloop
  endfacet
  facet normal -7.071800e-01 -2.672351e-01 -6.545852e-01
    outer loop
      vertex   8.750000e-01 3.141274e-01 8.166695e-01
      vertex   1.000000e-01 6.314277e-01 1.524401e+00
      vertex   8.750000e-01 3.471767e-01 8.031770e-01
    endloop
  endfacet
  facet normal -7.070964e-01 -2.755917e-01 -6.512018e-01
    outer loop
      vertex   8.750000e-01 3.471767e-01 8.031770e-01
      vertex   1.000000e-01 6.314277e-01 1.524401e+00
      vertex   0.000000e+00 6.696960e-01 1.616789e+00
    endloop
  endfacet
  facet normal -7.069738e-01 -2.834255e-01 -6.479646e-01
    outer loop
      vertex   8.750000e-01 3.471767e-01 8.031770e-01
      vertex   0.000000e+00 6.696960e-01 1.616789e+00
      vertex   3.209238e-16 7.326545e-01 1.589251e+00
    endloop
  endfacet
  facet normal -7.071758e-01 -2.937141e-01 -6.431441e-01
    outer loop
      vertex   8.750000e-01 3.471767e-01 8.031770e-01
      vertex   3.209238e-16 7.326545e-01 1.589251e+00
      vertex   8.750000e-01 3.796483e-01 7.883478e-01
    endloop
  endfacet
  facet normal -7.069718e-01 -3.086468e-01 -6.363395e-01
    outer loop
      vertex   8.750000e-01 3.796483e-01 7.883478e-01
      vertex   3.209238e-16 7.326545e-01 1.589251e+00
      vertex   3.209238e-16 7.944834e-01 1.559261e+00
    endloop
  endfacet
  facet normal -7.071789e-01 -3.197012e-01 -6.306260e-01
    outer loop
      vertex   8.750000e-01 3.796483e-01 7.883478e-01
      vertex   3.209238e-16 7.944834e-01 1.559261e+00
      vertex   8.750000e-01 4.114879e-01 7.722064e-01
    endloop
  endfacet
  facet normal -7.069707e-01 -3.333920e-01 -6.237325e-01
    outer loop
      vertex   8.750000e-01 4.114879e-01 7.722064e-01
      vertex   3.209238e-16 7.944834e-01 1.559261e+00
      vertex   3.209238e-16 8.550872e-01 1.526868e+00
    endloop
  endfacet
  facet normal -7.071802e-01 -3.451568e-01 -6.170599e-01
    outer loop
      vertex   8.750000e-01 4.114879e-01 7.722064e-01
      vertex   3.209238e-16 8.550872e-01 1.526868e+00
      vertex   8.750000e-01 4.426427e-01 7.547797e-01
    endloop
  endfacet
  facet normal -7.069705e-01 -3.576227e-01 -6.101629e-01
    outer loop
      vertex   8.750000e-01 4.426427e-01 7.547797e-01
      vertex   3.209238e-16 8.550872e-01 1.526868e+00
      vertex   3.209238e-16 9.143725e-01 1.492120e+00
    endloop
  endfacet
  facet normal -7.071800e-01 -3.700387e-01 -6.024681e-01
    outer loop
      vertex   8.750000e-01 4.426427e-01 7.547797e-01
      vertex   3.209238e-16 9.143725e-01 1.492120e+00
      vertex   8.750000e-01 4.730607e-01 7.360968e-01
    endloop
  endfacet
  facet normal -7.069710e-01 -3.813016e-01 -5.956518e-01
    outer loop
      vertex   8.750000e-01 4.730607e-01 7.360968e-01
      vertex   3.209238e-16 9.143725e-01 1.492120e+00
      vertex   3.209238e-16 9.722479e-01 1.455072e+00
    endloop
  endfacet
  facet normal -7.071780e-01 -3.943057e-01 -5.868750e-01
    outer loop
      vertex   8.750000e-01 4.730607e-01 7.360968e-01
      vertex   3.209238e-16 9.722479e-01 1.455072e+00
      vertex   8.750000e-01 5.026914e-01 7.161888e-01
    endloop
  endfacet
  facet normal -7.069724e-01 -4.043920e-01 -5.802217e-01
    outer loop
      vertex   8.750000e-01 5.026914e-01 7.161888e-01
      vertex   3.209238e-16 9.722479e-01 1.455072e+00
      vertex   3.209238e-16 1.028624e+00 1.415780e+00
    endloop
  endfacet
  facet normal -7.071745e-01 -4.179175e-01 -5.703063e-01
    outer loop
      vertex   8.750000e-01 5.026914e-01 7.161888e-01
      vertex   3.209238e-16 1.028624e+00 1.415780e+00
      vertex   8.750000e-01 5.314854e-01 6.950887e-01
    endloop
  endfacet
  facet normal -7.069746e-01 -4.268583e-01 -5.638962e-01
    outer loop
      vertex   8.750000e-01 5.314854e-01 6.950887e-01
      vertex   3.209238e-16 1.028624e+00 1.415780e+00
      vertex   3.209238e-16 1.083414e+00 1.374305e+00
    endloop
  endfacet
  facet normal -7.071692e-01 -4.408349e-01 -5.527895e-01
    outer loop
      vertex   8.750000e-01 5.314854e-01 6.950887e-01
      vertex   3.209238e-16 1.083414e+00 1.374305e+00
      vertex   8.750000e-01 5.593948e-01 6.728317e-01
    endloop
  endfacet
  facet normal -7.069776e-01 -4.486657e-01 -5.467008e-01
    outer loop
      vertex   8.750000e-01 5.593948e-01 6.728317e-01
      vertex   3.209238e-16 1.083414e+00 1.374305e+00
      vertex   3.209238e-16 1.136534e+00 1.330710e+00
    endloop
  endfacet
  facet normal -7.071623e-01 -4.630201e-01 -5.343537e-01
    outer loop
      vertex   8.750000e-01 5.593948e-01 6.728317e-01
      vertex   3.209238e-16 1.136534e+00 1.330710e+00
      vertex   8.750000e-01 5.863731e-01 6.494549e-01
    endloop
  endfacet
  facet normal -7.069815e-01 -4.697806e-01 -5.286618e-01
    outer loop
      vertex   8.750000e-01 5.863731e-01 6.494549e-01
      vertex   3.209238e-16 1.136534e+00 1.330710e+00
      vertex   3.209238e-16 1.187901e+00 1.285064e+00
    endloop
  endfacet
  facet normal -7.071538e-01 -4.844362e-01 -5.150293e-01
    outer loop
      vertex   8.750000e-01 5.863731e-01 6.494549e-01
      vertex   3.209238e-16 1.187901e+00 1.285064e+00
      vertex   8.750000e-01 6.123754e-01 6.249971e-01
    endloop
  endfacet
  facet normal -7.069820e-01 -4.902953e-01 -5.096929e-01
    outer loop
      vertex   8.750000e-01 6.123754e-01 6.249971e-01
      vertex   3.209238e-16 1.187901e+00 1.285064e+00
      vertex   1.000000e-01 1.166726e+00 1.166726e+00
    endloop
  endfacet
  facet normal -7.071507e-01 -5.050425e-01 -4.948434e-01
    outer loop
      vertex   8.750000e-01 6.123754e-01 6.249971e-01
      vertex   1.000000e-01 1.166726e+00 1.166726e+00
      vertex   8.750000e-01 6.373586e-01 5.994990e-01
    endloop
  endfacet
  facet normal -7.069857e-01 -5.098078e-01 -4.901707e-01
    outer loop
      vertex   8.750000e-01 6.373586e-01 5.994990e-01
      vertex   1.000000e-01 1.166726e+00 1.166726e+00
      vertex   1.000000e-01 1.211632e+00 1.120021e+00
    endloop
  endfacet
  facet normal -7.071381e-01 -5.248156e-01 -4.738400e-01
    outer loop
      vertex   8.750000e-01 6.373586e-01 5.994990e-01
      vertex   1.000000e-01 1.211632e+00 1.120021e+00
      vertex   8.750000e-01 6.612809e-01 5.730031e-01
    endloop
  endfacet
  facet normal -7.069928e-01 -5.286534e-01 -4.697731e-01
    outer loop
      vertex   8.750000e-01 6.612809e-01 5.730031e-01
      vertex   1.000000e-01 1.211632e+00 1.120021e+00
      vertex   1.000000e-01 1.254670e+00 1.071589e+00
    endloop
  endfacet
  facet normal -7.071237e-01 -5.437171e-01 -4.520484e-01
    outer loop
      vertex   8.750000e-01 6.612809e-01 5.730031e-01
      vertex   1.000000e-01 1.254670e+00 1.071589e+00
      vertex   8.750000e-01 6.841025e-01 5.455536e-01
    endloop
  endfacet
  facet normal -7.070009e-01 -5.466828e-01 -4.486509e-01
    outer loop
      vertex   8.750000e-01 6.841025e-01 5.455536e-01
      vertex   1.000000e-01 1.254670e+00 1.071589e+00
      vertex   1.000000e-01 1.295773e+00 1.021505e+00
    endloop
  endfacet
  facet normal -7.071075e-01 -5.617159e-01 -4.295046e-01
    outer loop
      vertex   8.750000e-01 6.841025e-01 5.455536e-01
      vertex   1.000000e-01 1.295773e+00 1.021505e+00
      vertex   8.750000e-01 7.057856e-01 5.171960e-01
    endloop
  endfacet
  facet normal -7.070100e-01 -5.638680e-01 -4.268369e-01
    outer loop
      vertex   8.750000e-01 7.057856e-01 5.171960e-01
      vertex   1.000000e-01 1.295773e+00 1.021505e+00
      vertex   1.000000e-01 1.334878e+00 9.698457e-01
    endloop
  endfacet
  facet normal -7.070896e-01 -5.787820e-01 -4.062459e-01
    outer loop
      vertex   8.750000e-01 7.057856e-01 5.171960e-01
      vertex   1.000000e-01 1.334878e+00 9.698457e-01
      vertex   8.750000e-01 7.262939e-01 4.879776e-01
    endloop
  endfacet
  facet normal -7.070199e-01 -5.801827e-01 -4.043648e-01
    outer loop
      vertex   8.750000e-01 7.262939e-01 4.879776e-01
      vertex   1.000000e-01 1.334878e+00 9.698457e-01
      vertex   1.000000e-01 1.371925e+00 9.166909e-01
    endloop
  endfacet
  facet normal -7.070699e-01 -5.948871e-01 -3.823107e-01
    outer loop
      vertex   8.750000e-01 7.262939e-01 4.879776e-01
      vertex   1.000000e-01 1.371925e+00 9.166909e-01
      vertex   8.750000e-01 7.455934e-01 4.579470e-01
    endloop
  endfacet
  facet normal -7.070308e-01 -5.956015e-01 -3.812693e-01
    outer loop
      vertex   8.750000e-01 7.455934e-01 4.579470e-01
      vertex   1.000000e-01 1.371925e+00 9.166909e-01
      vertex   1.000000e-01 1.406856e+00 8.621226e-01
    endloop
  endfacet
  facet normal -7.070485e-01 -6.100044e-01 -3.577388e-01
    outer loop
      vertex   8.750000e-01 7.455934e-01 4.579470e-01
      vertex   1.000000e-01 1.406856e+00 8.621226e-01
      vertex   8.750000e-01 7.636520e-01 4.271542e-01
    endloop
  endfacet
  facet normal -7.070427e-01 -6.101006e-01 -3.575862e-01
    outer loop
      vertex   8.750000e-01 7.636520e-01 4.271542e-01
      vertex   1.000000e-01 1.406856e+00 8.621226e-01
      vertex   1.000000e-01 1.439618e+00 8.062250e-01
    endloop
  endfacet
  facet normal -7.070347e-01 -6.236761e-01 -3.333618e-01
    outer loop
      vertex   8.750000e-01 7.636520e-01 4.271542e-01
      vertex   1.000000e-01 1.439618e+00 8.062250e-01
      vertex   1.000000e-01 1.470161e+00 7.490843e-01
    endloop
  endfacet
  facet normal -7.070386e-01 -4.901340e-01 -5.097696e-01
    outer loop
      vertex   3.209238e-16 1.187901e+00 1.285064e+00
      vertex   0.000000e+00 1.237437e+00 1.237437e+00
      vertex   1.000000e-01 1.166726e+00 1.166726e+00
    endloop
  endfacet
  facet normal -7.070630e-01 -6.240757e-01 -3.325531e-01
    outer loop
      vertex   8.750000e-01 7.636520e-01 4.271542e-01
      vertex   1.000000e-01 1.470161e+00 7.490843e-01
      vertex   8.750000e-01 7.804395e-01 3.956504e-01
    endloop
  endfacet
  facet normal -7.070235e-01 -6.362931e-01 -3.086243e-01
    outer loop
      vertex   8.750000e-01 7.804395e-01 3.956504e-01
      vertex   1.000000e-01 1.470161e+00 7.490843e-01
      vertex   1.000000e-01 1.498436e+00 6.907886e-01
    endloop
  endfacet
  facet normal -7.070832e-01 -6.371024e-01 -3.068124e-01
    outer loop
      vertex   8.750000e-01 7.804395e-01 3.956504e-01
      vertex   1.000000e-01 1.498436e+00 6.907886e-01
      vertex   8.750000e-01 7.959280e-01 3.634881e-01
    endloop
  endfacet
  facet normal -7.070132e-01 -6.479285e-01 -2.834097e-01
    outer loop
      vertex   8.750000e-01 7.959280e-01 3.634881e-01
      vertex   1.000000e-01 1.498436e+00 6.907886e-01
      vertex   1.000000e-01 1.524401e+00 6.314277e-01
    endloop
  endfacet
  facet normal -7.071017e-01 -6.490697e-01 -2.805632e-01
    outer loop
      vertex   8.750000e-01 7.959280e-01 3.634881e-01
      vertex   1.000000e-01 1.524401e+00 6.314277e-01
      vertex   8.750000e-01 8.100918e-01 3.307209e-01
    endloop
  endfacet
  facet normal -7.071056e-01 -6.539704e-01 -2.689317e-01
    outer loop
      vertex   8.750000e-01 8.100918e-01 3.307209e-01
      vertex   1.000000e-01 1.524401e+00 6.314277e-01
      vertex   0.000000e+00 1.616789e+00 6.696960e-01
    endloop
  endfacet
  facet normal -7.070078e-01 -6.585606e-01 -2.577556e-01
    outer loop
      vertex   8.750000e-01 8.100918e-01 3.307209e-01
      vertex   0.000000e+00 1.616789e+00 6.696960e-01
      vertex   3.209238e-16 1.641835e+00 6.057048e-01
    endloop
  endfacet
  facet normal -7.071133e-01 -6.599625e-01 -2.538509e-01
    outer loop
      vertex   8.750000e-01 8.100918e-01 3.307209e-01
      vertex   3.209238e-16 1.641835e+00 6.057048e-01
      vertex   8.750000e-01 8.229073e-01 2.974031e-01
    endloop
  endfacet
  facet normal -7.070004e-01 -6.681793e-01 -2.317044e-01
    outer loop
      vertex   8.750000e-01 8.229073e-01 2.974031e-01
      vertex   3.209238e-16 1.641835e+00 6.057048e-01
      vertex   3.209238e-16 1.664349e+00 5.407797e-01
    endloop
  endfacet
  facet normal -7.071274e-01 -6.697542e-01 -2.267162e-01
    outer loop
      vertex   8.750000e-01 8.229073e-01 2.974031e-01
      vertex   3.209238e-16 1.664349e+00 5.407797e-01
      vertex   8.750000e-01 8.343531e-01 2.635904e-01
    endloop
  endfacet
  facet normal -7.069937e-01 -6.767672e-01 -2.052951e-01
    outer loop
      vertex   8.750000e-01 8.343531e-01 2.635904e-01
      vertex   3.209238e-16 1.664349e+00 5.407797e-01
      vertex   3.209238e-16 1.684297e+00 4.750208e-01
    endloop
  endfacet
  facet normal -7.071398e-01 -6.784323e-01 -1.992057e-01
    outer loop
      vertex   8.750000e-01 8.343531e-01 2.635904e-01
      vertex   3.209238e-16 1.684297e+00 4.750208e-01
      vertex   8.750000e-01 8.444102e-01 2.293390e-01
    endloop
  endfacet
  facet normal -7.069879e-01 -6.843109e-01 -1.785685e-01
    outer loop
      vertex   8.750000e-01 8.444102e-01 2.293390e-01
      vertex   3.209238e-16 1.684297e+00 4.750208e-01
      vertex   3.209238e-16 1.701647e+00 4.085294e-01
    endloop
  endfacet
  facet normal -7.071505e-01 -6.859826e-01 -1.713650e-01
    outer loop
      vertex   8.750000e-01 8.444102e-01 2.293390e-01
      vertex   3.209238e-16 1.701647e+00 4.085294e-01
      vertex   8.750000e-01 8.530619e-01 1.947058e-01
    endloop
  endfacet
  facet normal -7.069830e-01 -6.907987e-01 -1.515660e-01
    outer loop
      vertex   8.750000e-01 8.530619e-01 1.947058e-01
      vertex   3.209238e-16 1.701647e+00 4.085294e-01
      vertex   3.209238e-16 1.716374e+00 3.414081e-01
    endloop
  endfacet
  facet normal -7.071596e-01 -6.923926e-01 -1.432403e-01
    outer loop
      vertex   8.750000e-01 8.530619e-01 1.947058e-01
      vertex   3.209238e-16 1.716374e+00 3.414081e-01
      vertex   8.750000e-01 8.602938e-01 1.597486e-01
    endloop
  endfacet
  facet normal -7.069788e-01 -6.962206e-01 -1.243292e-01
    outer loop
      vertex   8.750000e-01 8.602938e-01 1.597486e-01
      vertex   3.209238e-16 1.716374e+00 3.414081e-01
      vertex   3.209238e-16 1.728455e+00 2.737603e-01
    endloop
  endfacet
  facet normal -7.071671e-01 -6.976516e-01 -1.148782e-01
    outer loop
      vertex   8.750000e-01 8.602938e-01 1.597486e-01
      vertex   3.209238e-16 1.728455e+00 2.737603e-01
      vertex   8.750000e-01 8.660938e-01 1.245255e-01
    endloop
  endfacet
  facet normal -7.069755e-01 -7.005683e-01 -9.690034e-02
    outer loop
      vertex   8.750000e-01 8.660938e-01 1.245255e-01
      vertex   3.209238e-16 1.728455e+00 2.737603e-01
      vertex   3.209238e-16 1.737870e+00 2.056904e-01
    endloop
  endfacet
  facet normal -7.071729e-01 -7.017509e-01 -8.632565e-02
    outer loop
      vertex   8.750000e-01 8.660938e-01 1.245255e-01
      vertex   3.209238e-16 1.737870e+00 2.056904e-01
      vertex   8.750000e-01 8.704522e-01 8.909511e-02
    endloop
  endfacet
  facet normal -7.069730e-01 -7.038350e-01 -6.932169e-02
    outer loop
      vertex   8.750000e-01 8.704522e-01 8.909511e-02
      vertex   3.209238e-16 1.737870e+00 2.056904e-01
      vertex   3.209238e-16 1.744605e+00 1.373034e-01
    endloop
  endfacet
  facet normal -7.071770e-01 -7.046839e-01 -5.763004e-02
    outer loop
      vertex   8.750000e-01 8.704522e-01 8.909511e-02
      vertex   3.209238e-16 1.744605e+00 1.373034e-01
      vertex   8.750000e-01 8.733619e-01 5.351645e-02
    endloop
  endfacet
  facet normal -7.069714e-01 -7.060155e-01 -4.163591e-02
    outer loop
      vertex   8.750000e-01 8.733619e-01 5.351645e-02
      vertex   3.209238e-16 1.744605e+00 1.373034e-01
      vertex   3.209238e-16 1.748651e+00 6.870468e-02
    endloop
  endfacet
  facet normal -7.071795e-01 -7.064457e-01 -2.883892e-02
    outer loop
      vertex   8.750000e-01 8.733619e-01 5.351645e-02
      vertex   3.209238e-16 1.748651e+00 6.870468e-02
      vertex   8.750000e-01 8.748179e-01 1.784872e-02
    endloop
  endfacet
  facet normal -7.069664e-01 -7.071151e-01 -1.366952e-02
    outer loop
      vertex   8.750000e-01 8.748179e-01 1.784872e-02
      vertex   3.209238e-16 1.748651e+00 6.870468e-02
      vertex   1.000000e-01 1.650000e+00 1.172146e-15
    endloop
  endfacet
  facet normal -7.071898e-01 -7.070237e-01 -0.000000e+00
    outer loop
      vertex   8.750000e-01 8.748179e-01 1.784872e-02
      vertex   1.000000e-01 1.650000e+00 1.172146e-15
      vertex   8.750000e-01 8.748179e-01 -1.784872e-02
    endloop
  endfacet
  facet normal -7.069618e-01 -7.071154e-01 1.388596e-02
    outer loop
      vertex   8.750000e-01 8.748179e-01 -1.784872e-02
      vertex   1.000000e-01 1.650000e+00 1.172146e-15
      vertex   1.000000e-01 1.648728e+00 -6.477870e-02
    endloop
  endfacet
  facet normal -7.071889e-01 -7.064362e-01 2.883853e-02
    outer loop
      vertex   8.750000e-01 8.748179e-01 -1.784872e-02
      vertex   1.000000e-01 1.648728e+00 -6.477870e-02
      vertex   8.750000e-01 8.733619e-01 -5.351645e-02
    endloop
  endfacet
  facet normal -7.069627e-01 -7.060242e-01 4.163643e-02
    outer loop
      vertex   8.750000e-01 8.733619e-01 -5.351645e-02
      vertex   1.000000e-01 1.648728e+00 -6.477870e-02
      vertex   1.000000e-01 1.644914e+00 -1.294575e-01
    endloop
  endfacet
  facet normal -7.071863e-01 -7.046747e-01 5.762928e-02
    outer loop
      vertex   8.750000e-01 8.733619e-01 -5.351645e-02
      vertex   1.000000e-01 1.644914e+00 -1.294575e-01
      vertex   8.750000e-01 8.704522e-01 -8.909511e-02
    endloop
  endfacet
  facet normal -7.069646e-01 -7.038434e-01 6.932252e-02
    outer loop
      vertex   8.750000e-01 8.704522e-01 -8.909511e-02
      vertex   1.000000e-01 1.644914e+00 -1.294575e-01
      vertex   1.000000e-01 1.638563e+00 -1.939367e-01
    endloop
  endfacet
  facet normal -7.071819e-01 -7.017420e-01 8.632455e-02
    outer loop
      vertex   8.750000e-01 8.704522e-01 -8.909511e-02
      vertex   1.000000e-01 1.638563e+00 -1.939367e-01
      vertex   8.750000e-01 8.660938e-01 -1.245255e-01
    endloop
  endfacet
  facet normal -7.069674e-01 -7.005764e-01 9.690145e-02
    outer loop
      vertex   8.750000e-01 8.660938e-01 -1.245255e-01
      vertex   1.000000e-01 1.638563e+00 -1.939367e-01
      vertex   1.000000e-01 1.629686e+00 -2.581169e-01
    endloop
  endfacet
  facet normal -7.071757e-01 -6.976430e-01 1.148768e-01
    outer loop
      vertex   8.750000e-01 8.660938e-01 -1.245255e-01
      vertex   1.000000e-01 1.629686e+00 -2.581169e-01
      vertex   8.750000e-01 8.602938e-01 -1.597486e-01
    endloop
  endfacet
  facet normal -7.069711e-01 -6.962282e-01 1.243306e-01
    outer loop
      vertex   8.750000e-01 8.602938e-01 -1.597486e-01
      vertex   1.000000e-01 1.629686e+00 -2.581169e-01
      vertex   1.000000e-01 1.618296e+00 -3.218990e-01
    endloop
  endfacet
  facet normal -7.071678e-01 -6.923846e-01 1.432387e-01
    outer loop
      vertex   8.750000e-01 8.602938e-01 -1.597486e-01
      vertex   1.000000e-01 1.618296e+00 -3.218990e-01
      vertex   8.750000e-01 8.530619e-01 -1.947058e-01
    endloop
  endfacet
  facet normal -7.069758e-01 -6.908057e-01 1.515675e-01
    outer loop
      vertex   8.750000e-01 8.530619e-01 -1.947058e-01
      vertex   1.000000e-01 1.618296e+00 -3.218990e-01
      vertex   1.000000e-01 1.604410e+00 -3.851849e-01
    endloop
  endfacet
  facet normal -7.071581e-01 -6.859753e-01 1.713632e-01
    outer loop
      vertex   8.750000e-01 8.530619e-01 -1.947058e-01
      vertex   1.000000e-01 1.604410e+00 -3.851849e-01
      vertex   8.750000e-01 8.444102e-01 -2.293390e-01
    endloop
  endfacet
  facet normal -7.069814e-01 -6.843172e-01 1.785702e-01
    outer loop
      vertex   8.750000e-01 8.444102e-01 -2.293390e-01
      vertex   1.000000e-01 1.604410e+00 -3.851849e-01
      vertex   1.000000e-01 1.588051e+00 -4.478767e-01
    endloop
  endfacet
  facet normal -7.071467e-01 -6.784257e-01 1.992038e-01
    outer loop
      vertex   8.750000e-01 8.444102e-01 -2.293390e-01
      vertex   1.000000e-01 1.588051e+00 -4.478767e-01
      vertex   8.750000e-01 8.343531e-01 -2.635904e-01
    endloop
  endfacet
  facet normal -7.069879e-01 -6.767727e-01 2.052968e-01
    outer loop
      vertex   8.750000e-01 8.343531e-01 -2.635904e-01
      vertex   1.000000e-01 1.588051e+00 -4.478767e-01
      vertex   1.000000e-01 1.569243e+00 -5.098780e-01
    endloop
  endfacet
  facet normal -7.071335e-01 -6.697484e-01 2.267142e-01
    outer loop
      vertex   8.750000e-01 8.343531e-01 -2.635904e-01
      vertex   1.000000e-01 1.569243e+00 -5.098780e-01
      vertex   8.750000e-01 8.229073e-01 -2.974031e-01
    endloop
  endfacet
  facet normal -7.069954e-01 -6.681840e-01 2.317060e-01
    outer loop
      vertex   8.750000e-01 8.229073e-01 -2.974031e-01
      vertex   1.000000e-01 1.569243e+00 -5.098780e-01
      vertex   1.000000e-01 1.548016e+00 -5.710931e-01
    endloop
  endfacet
  facet normal -7.071185e-01 -6.599577e-01 2.538490e-01
    outer loop
      vertex   8.750000e-01 8.229073e-01 -2.974031e-01
      vertex   1.000000e-01 1.548016e+00 -5.710931e-01
      vertex   8.750000e-01 8.100918e-01 -3.307209e-01
    endloop
  endfacet
  facet normal -7.070038e-01 -6.585643e-01 2.577571e-01
    outer loop
      vertex   8.750000e-01 8.100918e-01 -3.307209e-01
      vertex   1.000000e-01 1.548016e+00 -5.710931e-01
      vertex   1.000000e-01 1.524401e+00 -6.314277e-01
    endloop
  endfacet
  facet normal -7.071017e-01 -6.490697e-01 2.805632e-01
    outer loop
      vertex   8.750000e-01 8.100918e-01 -3.307209e-01
      vertex   1.000000e-01 1.524401e+00 -6.314277e-01
      vertex   8.750000e-01 7.959280e-01 -3.634881e-01
    endloop
  endfacet
  facet normal -7.070505e-01 -6.483991e-01 2.822379e-01
    outer loop
      vertex   8.750000e-01 7.959280e-01 -3.634881e-01
      vertex   1.000000e-01 1.524401e+00 -6.314277e-01
      vertex   0.000000e+00 1.616789e+00 -6.696960e-01
    endloop
  endfacet
  facet normal -7.070161e-01 -6.479258e-01 2.834086e-01
    outer loop
      vertex   8.750000e-01 7.959280e-01 -3.634881e-01
      vertex   0.000000e+00 1.616789e+00 -6.696960e-01
      vertex   3.209238e-16 1.589251e+00 -7.326545e-01
    endloop
  endfacet
  facet normal -7.070386e-01 -7.070386e-01 -1.388446e-02
    outer loop
      vertex   3.209238e-16 1.748651e+00 6.870468e-02
      vertex   0.000000e+00 1.750000e+00 1.209542e-15
      vertex   1.000000e-01 1.650000e+00 1.172146e-15
    endloop
  endfacet
  facet normal -7.070802e-01 -6.371051e-01 3.068137e-01
    outer loop
      vertex   8.750000e-01 7.959280e-01 -3.634881e-01
      vertex   3.209238e-16 1.589251e+00 -7.326545e-01
      vertex   8.750000e-01 7.804395e-01 -3.956504e-01
    endloop
  endfacet
  facet normal -7.070252e-01 -6.362915e-01 3.086235e-01
    outer loop
      vertex   8.750000e-01 7.804395e-01 -3.956504e-01
      vertex   3.209238e-16 1.589251e+00 -7.326545e-01
      vertex   3.209238e-16 1.559261e+00 -7.944834e-01
    endloop
  endfacet
  facet normal -7.070612e-01 -6.240772e-01 3.325539e-01
    outer loop
      vertex   8.750000e-01 7.804395e-01 -3.956504e-01
      vertex   3.209238e-16 1.559261e+00 -7.944834e-01
      vertex   8.750000e-01 7.636520e-01 -4.271542e-01
    endloop
  endfacet
  facet normal -7.070351e-01 -6.236757e-01 3.333616e-01
    outer loop
      vertex   8.750000e-01 7.636520e-01 -4.271542e-01
      vertex   3.209238e-16 1.559261e+00 -7.944834e-01
      vertex   3.209238e-16 1.526868e+00 -8.550872e-01
    endloop
  endfacet
  facet normal -7.070422e-01 -6.101010e-01 3.575864e-01
    outer loop
      vertex   8.750000e-01 7.636520e-01 -4.271542e-01
      vertex   3.209238e-16 1.526868e+00 -8.550872e-01
      vertex   3.209238e-16 1.492120e+00 -9.143725e-01
    endloop
  endfacet
  facet normal -7.070476e-01 -6.100052e-01 3.577393e-01
    outer loop
      vertex   8.750000e-01 7.636520e-01 -4.271542e-01
      vertex   3.209238e-16 1.492120e+00 -9.143725e-01
      vertex   8.750000e-01 7.455934e-01 -4.579470e-01
    endloop
  endfacet
  facet normal -7.070317e-01 -5.956007e-01 3.812688e-01
    outer loop
      vertex   8.750000e-01 7.455934e-01 -4.579470e-01
      vertex   3.209238e-16 1.492120e+00 -9.143725e-01
      vertex   3.209238e-16 1.455072e+00 -9.722479e-01
    endloop
  endfacet
  facet normal -7.070677e-01 -5.948890e-01 3.823119e-01
    outer loop
      vertex   8.750000e-01 7.455934e-01 -4.579470e-01
      vertex   3.209238e-16 1.455072e+00 -9.722479e-01
      vertex   8.750000e-01 7.262939e-01 -4.879776e-01
    endloop
  endfacet
  facet normal -7.070221e-01 -5.801809e-01 4.043636e-01
    outer loop
      vertex   8.750000e-01 7.262939e-01 -4.879776e-01
      vertex   3.209238e-16 1.455072e+00 -9.722479e-01
      vertex   3.209238e-16 1.415780e+00 -1.028624e+00
    endloop
  endfacet
  facet normal -7.070862e-01 -5.787848e-01 4.062478e-01
    outer loop
      vertex   8.750000e-01 7.262939e-01 -4.879776e-01
      vertex   3.209238e-16 1.415780e+00 -1.028624e+00
      vertex   8.750000e-01 7.057856e-01 -5.171960e-01
    endloop
  endfacet
  facet normal -7.070132e-01 -5.638654e-01 4.268350e-01
    outer loop
      vertex   8.750000e-01 7.057856e-01 -5.171960e-01
      vertex   3.209238e-16 1.415780e+00 -1.028624e+00
      vertex   3.209238e-16 1.374305e+00 -1.083414e+00
    endloop
  endfacet
  facet normal -7.071030e-01 -5.617195e-01 4.295073e-01
    outer loop
      vertex   8.750000e-01 7.057856e-01 -5.171960e-01
      vertex   3.209238e-16 1.374305e+00 -1.083414e+00
      vertex   8.750000e-01 6.841025e-01 -5.455536e-01
    endloop
  endfacet
  facet normal -7.070052e-01 -5.466794e-01 4.486482e-01
    outer loop
      vertex   8.750000e-01 6.841025e-01 -5.455536e-01
      vertex   3.209238e-16 1.374305e+00 -1.083414e+00
      vertex   3.209238e-16 1.330710e+00 -1.136534e+00
    endloop
  endfacet
  facet normal -7.071182e-01 -5.437214e-01 4.520519e-01
    outer loop
      vertex   8.750000e-01 6.841025e-01 -5.455536e-01
      vertex   3.209238e-16 1.330710e+00 -1.136534e+00
      vertex   8.750000e-01 6.612809e-01 -5.730031e-01
    endloop
  endfacet
  facet normal -7.069981e-01 -5.286495e-01 4.697696e-01
    outer loop
      vertex   8.750000e-01 6.612809e-01 -5.730031e-01
      vertex   3.209238e-16 1.330710e+00 -1.136534e+00
      vertex   3.209238e-16 1.285064e+00 -1.187901e+00
    endloop
  endfacet
  facet normal -7.071317e-01 -5.248203e-01 4.738443e-01
    outer loop
      vertex   8.750000e-01 6.612809e-01 -5.730031e-01
      vertex   3.209238e-16 1.285064e+00 -1.187901e+00
      vertex   8.750000e-01 6.373586e-01 -5.994990e-01
    endloop
  endfacet
  facet normal -7.069896e-01 -5.097032e-01 4.902737e-01
    outer loop
      vertex   8.750000e-01 6.373586e-01 -5.994990e-01
      vertex   3.209238e-16 1.285064e+00 -1.187901e+00
      vertex   1.000000e-01 1.166726e+00 -1.166726e+00
    endloop
  endfacet
  facet normal -7.071507e-01 -5.050425e-01 4.948434e-01
    outer loop
      vertex   8.750000e-01 6.373586e-01 -5.994990e-01
      vertex   1.000000e-01 1.166726e+00 -1.166726e+00
      vertex   8.750000e-01 6.123754e-01 -6.249971e-01
    endloop
  endfacet
  facet normal -7.069794e-01 -4.901750e-01 5.098123e-01
    outer loop
      vertex   8.750000e-01 6.123754e-01 -6.249971e-01
      vertex   1.000000e-01 1.166726e+00 -1.166726e+00
      vertex   1.000000e-01 1.120021e+00 -1.211632e+00
    endloop
  endfacet
  facet normal -7.071615e-01 -4.844308e-01 5.150236e-01
    outer loop
      vertex   8.750000e-01 6.123754e-01 -6.249971e-01
      vertex   1.000000e-01 1.120021e+00 -1.211632e+00
      vertex   8.750000e-01 5.863731e-01 -6.494549e-01
    endloop
  endfacet
  facet normal -7.069741e-01 -4.697855e-01 5.286674e-01
    outer loop
      vertex   8.750000e-01 5.863731e-01 -6.494549e-01
      vertex   1.000000e-01 1.120021e+00 -1.211632e+00
      vertex   1.000000e-01 1.071589e+00 -1.254670e+00
    endloop
  endfacet
  facet normal -7.071706e-01 -4.630146e-01 5.343474e-01
    outer loop
      vertex   8.750000e-01 5.863731e-01 -6.494549e-01
      vertex   1.000000e-01 1.071589e+00 -1.254670e+00
      vertex   8.750000e-01 5.593948e-01 -6.728317e-01
    endloop
  endfacet
  facet normal -7.069698e-01 -4.486707e-01 5.467068e-01
    outer loop
      vertex   8.750000e-01 5.593948e-01 -6.728317e-01
      vertex   1.000000e-01 1.071589e+00 -1.254670e+00
      vertex   1.000000e-01 1.021505e+00 -1.295773e+00
    endloop
  endfacet
  facet normal -7.071780e-01 -4.408295e-01 5.527827e-01
    outer loop
      vertex   8.750000e-01 5.593948e-01 -6.728317e-01
      vertex   1.000000e-01 1.021505e+00 -1.295773e+00
      vertex   8.750000e-01 5.314854e-01 -6.950887e-01
    endloop
  endfacet
  facet normal -7.069663e-01 -4.268633e-01 5.639028e-01
    outer loop
      vertex   8.750000e-01 5.314854e-01 -6.950887e-01
      vertex   1.000000e-01 1.021505e+00 -1.295773e+00
      vertex   1.000000e-01 9.698457e-01 -1.334878e+00
    endloop
  endfacet
  facet normal -7.071836e-01 -4.179121e-01 5.702990e-01
    outer loop
      vertex   8.750000e-01 5.314854e-01 -6.950887e-01
      vertex   1.000000e-01 9.698457e-01 -1.334878e+00
      vertex   8.750000e-01 5.026914e-01 -7.161888e-01
    endloop
  endfacet
  facet normal -7.069638e-01 -4.043969e-01 5.802287e-01
    outer loop
      vertex   8.750000e-01 5.026914e-01 -7.161888e-01
      vertex   1.000000e-01 9.698457e-01 -1.334878e+00
      vertex   1.000000e-01 9.166909e-01 -1.371925e+00
    endloop
  endfacet
  facet normal -7.071874e-01 -3.943005e-01 5.868672e-01
    outer loop
      vertex   8.750000e-01 5.026914e-01 -7.161888e-01
      vertex   1.000000e-01 9.166909e-01 -1.371925e+00
      vertex   8.750000e-01 4.730607e-01 -7.360968e-01
    endloop
  endfacet
  facet normal -7.069623e-01 -3.813063e-01 5.956592e-01
    outer loop
      vertex   8.750000e-01 4.730607e-01 -7.360968e-01
      vertex   1.000000e-01 9.166909e-01 -1.371925e+00
      vertex   1.000000e-01 8.621226e-01 -1.406856e+00
    endloop
  endfacet
  facet normal -7.071894e-01 -3.700338e-01 6.024600e-01
    outer loop
      vertex   8.750000e-01 4.730607e-01 -7.360968e-01
      vertex   1.000000e-01 8.621226e-01 -1.406856e+00
      vertex   8.750000e-01 4.426427e-01 -7.547797e-01
    endloop
  endfacet
  facet normal -7.069617e-01 -3.576271e-01 6.101705e-01
    outer loop
      vertex   8.750000e-01 4.426427e-01 -7.547797e-01
      vertex   1.000000e-01 8.621226e-01 -1.406856e+00
      vertex   1.000000e-01 8.062250e-01 -1.439618e+00
    endloop
  endfacet
  facet normal -7.071897e-01 -3.451522e-01 6.170516e-01
    outer loop
      vertex   8.750000e-01 4.426427e-01 -7.547797e-01
      vertex   1.000000e-01 8.062250e-01 -1.439618e+00
      vertex   8.750000e-01 4.114879e-01 -7.722064e-01
    endloop
  endfacet
  facet normal -7.069620e-01 -3.333961e-01 6.237402e-01
    outer loop
      vertex   8.750000e-01 4.114879e-01 -7.722064e-01
      vertex   1.000000e-01 8.062250e-01 -1.439618e+00
      vertex   1.000000e-01 7.490843e-01 -1.470161e+00
    endloop
  endfacet
  facet normal -7.071883e-01 -3.196970e-01 6.306176e-01
    outer loop
      vertex   8.750000e-01 4.114879e-01 -7.722064e-01
      vertex   1.000000e-01 7.490843e-01 -1.470161e+00
      vertex   8.750000e-01 3.796483e-01 -7.883478e-01
    endloop
  endfacet
  facet normal -7.069632e-01 -3.086506e-01 6.363473e-01
    outer loop
      vertex   8.750000e-01 3.796483e-01 -7.883478e-01
      vertex   1.000000e-01 7.490843e-01 -1.470161e+00
      vertex   1.000000e-01 6.907886e-01 -1.498436e+00
    endloop
  endfacet
  facet normal -7.071850e-01 -2.937103e-01 6.431358e-01
    outer loop
      vertex   8.750000e-01 3.796483e-01 -7.883478e-01
      vertex   1.000000e-01 6.907886e-01 -1.498436e+00
      vertex   8.750000e-01 3.471767e-01 -8.031770e-01
    endloop
  endfacet
  facet normal -7.069654e-01 -2.834289e-01 6.479722e-01
    outer loop
      vertex   8.750000e-01 3.471767e-01 -8.031770e-01
      vertex   1.000000e-01 6.907886e-01 -1.498436e+00
      vertex   1.000000e-01 6.314277e-01 -1.524401e+00
    endloop
  endfacet
  facet normal -7.071800e-01 -2.672351e-01 6.545852e-01
    outer loop
      vertex   8.750000e-01 3.471767e-01 -8.031770e-01
      vertex   1.000000e-01 6.314277e-01 -1.524401e+00
      vertex   8.750000e-01 3.141274e-01 -8.166695e-01
    endloop
  endfacet
  facet normal -7.070780e-01 -2.622576e-01 6.567051e-01
    outer loop
      vertex   8.750000e-01 3.141274e-01 -8.166695e-01
      vertex   1.000000e-01 6.314277e-01 -1.524401e+00
      vertex   0.000000e+00 6.696960e-01 -1.616789e+00
    endloop
  endfacet
  facet normal -7.069765e-01 -2.577670e-01 6.585897e-01
    outer loop
      vertex   8.750000e-01 3.141274e-01 -8.166695e-01
      vertex   0.000000e+00 6.696960e-01 -1.616789e+00
      vertex   3.209238e-16 6.057048e-01 -1.641835e+00
    endloop
  endfacet
  facet normal -7.070386e-01 -5.097696e-01 4.901340e-01
    outer loop
      vertex   3.209238e-16 1.285064e+00 -1.187901e+00
      vertex   0.000000e+00 1.237437e+00 -1.237437e+00
      vertex   1.000000e-01 1.166726e+00 -1.166726e+00
    endloop
  endfacet
  facet normal -7.071648e-01 -2.403183e-01 6.649549e-01
    outer loop
      vertex   8.750000e-01 3.141274e-01 -8.166695e-01
      vertex   3.209238e-16 6.057048e-01 -1.641835e+00
      vertex   8.750000e-01 2.805552e-01 -8.288026e-01
    endloop
  endfacet
  facet normal -7.069801e-01 -2.317110e-01 6.681984e-01
    outer loop
      vertex   8.750000e-01 2.805552e-01 -8.288026e-01
      vertex   3.209238e-16 6.057048e-01 -1.641835e+00
      vertex   3.209238e-16 5.407797e-01 -1.664349e+00
    endloop
  endfacet
  facet normal -7.071568e-01 -2.129982e-01 6.742114e-01
    outer loop
      vertex   8.750000e-01 2.805552e-01 -8.288026e-01
      vertex   3.209238e-16 5.407797e-01 -1.664349e+00
      vertex   8.750000e-01 2.465160e-01 -8.395564e-01
    endloop
  endfacet
  facet normal -7.069845e-01 -2.052977e-01 6.767760e-01
    outer loop
      vertex   8.750000e-01 2.465160e-01 -8.395564e-01
      vertex   3.209238e-16 5.407797e-01 -1.664349e+00
      vertex   3.209238e-16 4.750208e-01 -1.684297e+00
    endloop
  endfacet
  facet normal -7.071471e-01 -1.853233e-01 6.823476e-01
    outer loop
      vertex   8.750000e-01 2.465160e-01 -8.395564e-01
      vertex   3.209238e-16 4.750208e-01 -1.684297e+00
      vertex   8.750000e-01 2.120665e-01 -8.489127e-01
    endloop
  endfacet
  facet normal -7.069898e-01 -1.785680e-01 6.843091e-01
    outer loop
      vertex   8.750000e-01 2.120665e-01 -8.489127e-01
      vertex   3.209238e-16 4.750208e-01 -1.684297e+00
      vertex   3.209238e-16 4.085294e-01 -1.701647e+00
    endloop
  endfacet
  facet normal -7.071358e-01 -1.573396e-01 6.893498e-01
    outer loop
      vertex   8.750000e-01 2.120665e-01 -8.489127e-01
      vertex   3.209238e-16 4.085294e-01 -1.701647e+00
      vertex   8.750000e-01 1.772641e-01 -8.568561e-01
    endloop
  endfacet
  facet normal -7.069958e-01 -1.515632e-01 6.907861e-01
    outer loop
      vertex   8.750000e-01 1.772641e-01 -8.568561e-01
      vertex   3.209238e-16 4.085294e-01 -1.701647e+00
      vertex   3.209238e-16 3.414081e-01 -1.716374e+00
    endloop
  endfacet
  facet normal -7.071229e-01 -1.290934e-01 6.952065e-01
    outer loop
      vertex   8.750000e-01 1.772641e-01 -8.568561e-01
      vertex   3.209238e-16 3.414081e-01 -1.716374e+00
      vertex   8.750000e-01 1.421666e-01 -8.633734e-01
    endloop
  endfacet
  facet normal -7.070027e-01 -1.243250e-01 6.961971e-01
    outer loop
      vertex   8.750000e-01 1.421666e-01 -8.633734e-01
      vertex   3.209238e-16 3.414081e-01 -1.716374e+00
      vertex   3.209238e-16 2.737603e-01 -1.728455e+00
    endloop
  endfacet
  facet normal -7.071083e-01 -1.006316e-01 6.999080e-01
    outer loop
      vertex   8.750000e-01 1.421666e-01 -8.633734e-01
      vertex   3.209238e-16 2.737603e-01 -1.728455e+00
      vertex   8.750000e-01 1.068325e-01 -8.684537e-01
    endloop
  endfacet
  facet normal -7.070105e-01 -9.689555e-02 7.005337e-01
    outer loop
      vertex   8.750000e-01 1.068325e-01 -8.684537e-01
      vertex   3.209238e-16 2.737603e-01 -1.728455e+00
      vertex   3.209238e-16 2.056904e-01 -1.737870e+00
    endloop
  endfacet
  facet normal -7.070920e-01 -7.200123e-02 7.034463e-01
    outer loop
      vertex   8.750000e-01 1.068325e-01 -8.684537e-01
      vertex   3.209238e-16 2.056904e-01 -1.737870e+00
      vertex   8.750000e-01 7.132062e-02 -8.720885e-01
    endloop
  endfacet
  facet normal -7.070190e-01 -6.931718e-02 7.037892e-01
    outer loop
      vertex   8.750000e-01 7.132062e-02 -8.720885e-01
      vertex   3.209238e-16 2.056904e-01 -1.737870e+00
      vertex   3.209238e-16 1.373034e-01 -1.744605e+00
    endloop
  endfacet
  facet normal -7.070740e-01 -4.324983e-02 7.058157e-01
    outer loop
      vertex   8.750000e-01 7.132062e-02 -8.720885e-01
      vertex   3.209238e-16 1.373034e-01 -1.744605e+00
      vertex   8.750000e-01 3.569001e-02 -8.742718e-01
    endloop
  endfacet
  facet normal -7.070284e-01 -4.163256e-02 7.059586e-01
    outer loop
      vertex   8.750000e-01 3.569001e-02 -8.742718e-01
      vertex   3.209238e-16 1.373034e-01 -1.744605e+00
      vertex   3.209238e-16 6.870468e-02 -1.748651e+00
    endloop
  endfacet
  facet normal -7.070545e-01 -1.442501e-02 7.070120e-01
    outer loop
      vertex   8.750000e-01 3.569001e-02 -8.742718e-01
      vertex   3.209238e-16 6.870468e-02 -1.748651e+00
      vertex   8.750000e-01 1.071566e-16 -8.750000e-01
    endloop
  endfacet
  facet normal -7.070386e-01 -1.388446e-02 7.070386e-01
    outer loop
      vertex   8.750000e-01 1.071566e-16 -8.750000e-01
      vertex   3.209238e-16 6.870468e-02 -1.748651e+00
      vertex   1.000000e-01 1.844151e-15 -1.650000e+00
    endloop
  endfacet
  facet normal -7.070386e-01 1.388446e-02 7.070386e-01
    outer loop
      vertex   8.750000e-01 1.071566e-16 -8.750000e-01
      vertex   1.000000e-01 1.844151e-15 -1.650000e+00
      vertex   1.000000e-01 -6.477870e-02 -1.648728e+00
    endloop
  endfacet
  facet normal -7.070386e-01 -1.388446e-02 7.070386e-01
    outer loop
      vertex   3.209238e-16 6.870468e-02 -1.748651e+00
      vertex   0.000000e+00 1.871810e-15 -1.750000e+00
      vertex   1.000000e-01 1.844151e-15 -1.650000e+00
    endloop
  endfacet
  facet normal -7.070558e-01 1.442498e-02 7.070106e-01
    outer loop
      vertex   8.750000e-01 1.071566e-16 -8.750000e-01
      vertex   1.000000e-01 -6.477870e-02 -1.648728e+00
      vertex   8.750000e-01 -3.569001e-02 -8.742718e-01
    endloop
  endfacet
  facet normal -7.070271e-01 4.163264e-02 7.059599e-01
    outer loop
      vertex   8.750000e-01 -3.569001e-02 -8.742718e-01
      vertex   1.000000e-01 -6.477870e-02 -1.648728e+00
      vertex   1.000000e-01 -1.294575e-01 -1.644914e+00
    endloop
  endfacet
  facet normal -7.070767e-01 4.324967e-02 7.058130e-01
    outer loop
      vertex   8.750000e-01 -3.569001e-02 -8.742718e-01
      vertex   1.000000e-01 -1.294575e-01 -1.644914e+00
      vertex   8.750000e-01 -7.132062e-02 -8.720885e-01
    endloop
  endfacet
  facet normal -7.070165e-01 6.931743e-02 7.037917e-01
    outer loop
      vertex   8.750000e-01 -7.132062e-02 -8.720885e-01
      vertex   1.000000e-01 -1.294575e-01 -1.644914e+00
      vertex   1.000000e-01 -1.939367e-01 -1.638563e+00
    endloop
  endfacet
  facet normal -7.070958e-01 7.200085e-02 7.034426e-01
    outer loop
      vertex   8.750000e-01 -7.132062e-02 -8.720885e-01
      vertex   1.000000e-01 -1.939367e-01 -1.638563e+00
      vertex   8.750000e-01 -1.068325e-01 -8.684537e-01
    endloop
  endfacet
  facet normal -7.070068e-01 9.689605e-02 7.005373e-01
    outer loop
      vertex   8.750000e-01 -1.068325e-01 -8.684537e-01
      vertex   1.000000e-01 -1.939367e-01 -1.638563e+00
      vertex   1.000000e-01 -2.581169e-01 -1.629686e+00
    endloop
  endfacet
  facet normal -7.071131e-01 1.006309e-01 6.999032e-01
    outer loop
      vertex   8.750000e-01 -1.068325e-01 -8.684537e-01
      vertex   1.000000e-01 -2.581169e-01 -1.629686e+00
      vertex   8.750000e-01 -1.421666e-01 -8.633734e-01
    endloop
  endfacet
  facet normal -7.069981e-01 1.243258e-01 6.962017e-01
    outer loop
      vertex   8.750000e-01 -1.421666e-01 -8.633734e-01
      vertex   1.000000e-01 -2.581169e-01 -1.629686e+00
      vertex   1.000000e-01 -3.218990e-01 -1.618296e+00
    endloop
  endfacet
  facet normal -7.071287e-01 1.290924e-01 6.952009e-01
    outer loop
      vertex   8.750000e-01 -1.421666e-01 -8.633734e-01
      vertex   1.000000e-01 -3.218990e-01 -1.618296e+00
      vertex   8.750000e-01 -1.772641e-01 -8.568561e-01
    endloop
  endfacet
  facet normal -7.069903e-01 1.515644e-01 6.907915e-01
    outer loop
      vertex   8.750000e-01 -1.772641e-01 -8.568561e-01
      vertex   1.000000e-01 -3.218990e-01 -1.618296e+00
      vertex   1.000000e-01 -3.851849e-01 -1.604410e+00
    endloop
  endfacet
  facet normal -7.071425e-01 1.573381e-01 6.893434e-01
    outer loop
      vertex   8.750000e-01 -1.772641e-01 -8.568561e-01
      vertex   1.000000e-01 -3.851849e-01 -1.604410e+00
      vertex   8.750000e-01 -2.120665e-01 -8.489127e-01
    endloop
  endfacet
  facet normal -7.069835e-01 1.785696e-01 6.843152e-01
    outer loop
      vertex   8.750000e-01 -2.120665e-01 -8.489127e-01
      vertex   1.000000e-01 -3.851849e-01 -1.604410e+00
      vertex   1.000000e-01 -4.478767e-01 -1.588051e+00
    endloop
  endfacet
  facet normal -7.071545e-01 1.853214e-01 6.823405e-01
    outer loop
      vertex   8.750000e-01 -2.120665e-01 -8.489127e-01
      vertex   1.000000e-01 -4.478767e-01 -1.588051e+00
      vertex   8.750000e-01 -2.465160e-01 -8.395564e-01
    endloop
  endfacet
  facet normal -7.069775e-01 2.052998e-01 6.767826e-01
    outer loop
      vertex   8.750000e-01 -2.465160e-01 -8.395564e-01
      vertex   1.000000e-01 -4.478767e-01 -1.588051e+00
      vertex   1.000000e-01 -5.098780e-01 -1.569243e+00
    endloop
  endfacet
  facet normal -7.071648e-01 2.129958e-01 6.742038e-01
    outer loop
      vertex   8.750000e-01 -2.465160e-01 -8.395564e-01
      vertex   1.000000e-01 -5.098780e-01 -1.569243e+00
      vertex   8.750000e-01 -2.805552e-01 -8.288026e-01
    endloop
  endfacet
  facet normal -7.069726e-01 2.317135e-01 6.682055e-01
    outer loop
      vertex   8.750000e-01 -2.805552e-01 -8.288026e-01
      vertex   1.000000e-01 -5.098780e-01 -1.569243e+00
      vertex   1.000000e-01 -5.710931e-01 -1.548016e+00
    endloop
  endfacet
  facet normal -7.071733e-01 2.403154e-01 6.649469e-01
    outer loop
      vertex   8.750000e-01 -2.805552e-01 -8.288026e-01
      vertex   1.000000e-01 -5.710931e-01 -1.548016e+00
      vertex   8.750000e-01 -3.141274e-01 -8.166695e-01
    endloop
  endfacet
  facet normal -7.069685e-01 2.577699e-01 6.585971e-01
    outer loop
      vertex   8.750000e-01 -3.141274e-01 -8.166695e-01
      vertex   1.000000e-01 -5.710931e-01 -1.548016e+00
      vertex   1.000000e-01 -6.314277e-01 -1.524401e+00
    endloop
  endfacet
  facet normal -7.071800e-01 2.672351e-01 6.545852e-01
    outer loop
      vertex   8.750000e-01 -3.141274e-01 -8.166695e-01
      vertex   1.000000e-01 -6.314277e-01 -1.524401e+00
      vertex   8.750000e-01 -3.471767e-01 -8.031770e-01
    endloop
  endfacet
  facet normal -7.070964e-01 2.755917e-01 6.512018e-01
    outer loop
      vertex   8.750000e-01 -3.471767e-01 -8.031770e-01
      vertex   1.000000e-01 -6.314277e-01 -1.524401e+00
      vertex   0.000000e+00 -6.696960e-01 -1.616789e+00
    endloop
  endfacet
  facet normal -7.069738e-01 2.834255e-01 6.479646e-01
    outer loop
      vertex   8.750000e-01 -3.471767e-01 -8.031770e-01
      vertex   0.000000e+00 -6.696960e-01 -1.616789e+00
      vertex   3.209238e-16 -7.326545e-01 -1.589251e+00
    endloop
  endfacet
  facet normal -7.071758e-01 2.937141e-01 6.431441e-01
    outer loop
      vertex   8.750000e-01 -3.471767e-01 -8.031770e-01
      vertex   3.209238e-16 -7.326545e-01 -1.589251e+00
      vertex   8.750000e-01 -3.796483e-01 -7.883478e-01
    endloop
  endfacet
  facet normal -7.069718e-01 3.086468e-01 6.363395e-01
    outer loop
      vertex   8.750000e-01 -3.796483e-01 -7.883478e-01
      vertex   3.209238e-16 -7.326545e-01 -1.589251e+00
      vertex   3.209238e-16 -7.944834e-01 -1.559261e+00
    endloop
  endfacet
  facet normal -7.071789e-01 3.197012e-01 6.306260e-01
    outer loop
      vertex   8.750000e-01 -3.796483e-01 -7.883478e-01
      vertex   3.209238e-16 -7.944834e-01 -1.559261e+00
      vertex   8.750000e-01 -4.114879e-01 -7.722064e-01
    endloop
  endfacet
  facet normal -7.069707e-01 3.333920e-01 6.237325e-01
    outer loop
      vertex   8.750000e-01 -4.114879e-01 -7.722064e-01
      vertex   3.209238e-16 -7.944834e-01 -1.559261e+00
      vertex   3.209238e-16 -8.550872e-01 -1.526868e+00
    endloop
  endfacet
  facet normal -7.071802e-01 3.451568e-01 6.170599e-01
    outer loop
      vertex   8.750000e-01 -4.114879e-01 -7.722064e-01
      vertex   3.209238e-16 -8.550872e-01 -1.526868e+00
      vertex   8.750000e-01 -4.426427e-01 -7.547797e-01
    endloop
  endfacet
  facet normal -7.069705e-01 3.576227e-01 6.101629e-01
    outer loop
      vertex   8.750000e-01 -4.426427e-01 -7.547797e-01
      vertex   3.209238e-16 -8.550872e-01 -1.526868e+00
      vertex   3.209238e-16 -9.143725e-01 -1.492120e+00
    endloop
  endfacet
  facet normal -7.071800e-01 3.700387e-01 6.024681e-01
    outer loop
      vertex   8.750000e-01 -4.426427e-01 -7.547797e-01
      vertex   3.209238e-16 -9.143725e-01 -1.492120e+00
      vertex   8.750000e-01 -4.730607e-01 -7.360968e-01
    endloop
  endfacet
  facet normal -7.069710e-01 3.813016e-01 5.956518e-01
    outer loop
      vertex   8.750000e-01 -4.730607e-01 -7.360968e-01
      vertex   3.209238e-16 -9.143725e-01 -1.492120e+00
      vertex   3.209238e-16 -9.722479e-01 -1.455072e+00
    endloop
  endfacet
  facet normal -7.071780e-01 3.943057e-01 5.868750e-01
    outer loop
      vertex   8.750000e-01 -4.730607e-01 -7.360968e-01
      vertex   3.209238e-16 -9.722479e-01 -1.455072e+00
      vertex   8.750000e-01 -5.026914e-01 -7.161888e-01
    endloop
  endfacet
  facet normal -7.069724e-01 4.043920e-01 5.802217e-01
    outer loop
      vertex   8.750000e-01 -5.026914e-01 -7.161888e-01
      vertex   3.209238e-16 -9.722479e-01 -1.455072e+00
      vertex   3.209238e-16 -1.028624e+00 -1.415780e+00
    endloop
  endfacet
  facet normal -7.071745e-01 4.179175e-01 5.703063e-01
    outer loop
      vertex   8.750000e-01 -5.026914e-01 -7.161888e-01
      vertex   3.209238e-16 -1.028624e+00 -1.415780e+00
      vertex   8.750000e-01 -5.314854e-01 -6.950887e-01
    endloop
  endfacet
  facet normal -7.069746e-01 4.268583e-01 5.638962e-01
    outer loop
      vertex   8.750000e-01 -5.314854e-01 -6.950887e-01
      vertex   3.209238e-16 -1.028624e+00 -1.415780e+00
      vertex   3.209238e-16 -1.083414e+00 -1.374305e+00
    endloop
  endfacet
  facet normal -7.071692e-01 4.408349e-01 5.527895e-01
    outer loop
      vertex   8.750000e-01 -5.314854e-01 -6.950887e-01
      vertex   3.209238e-16 -1.083414e+00 -1.374305e+00
      vertex   8.750000e-01 -5.593948e-01 -6.728317e-01
    endloop
  endfacet
  facet normal -7.069776e-01 4.486657e-01 5.467008e-01
    outer loop
      vertex   8.750000e-01 -5.593948e-01 -6.728317e-01
      vertex   3.209238e-16 -1.083414e+00 -1.374305e+00
      vertex   3.209238e-16 -1.136534e+00 -1.330710e+00
    endloop
  endfacet
  facet normal -7.071623e-01 4.630201e-01 5.343537e-01
    outer loop
      vertex   8.750000e-01 -5.593948e-01 -6.728317e-01
      vertex   3.209238e-16 -1.136534e+00 -1.330710e+00
      vertex   8.750000e-01 -5.863731e-01 -6.494549e-01
    endloop
  endfacet
  facet normal -7.069815e-01 4.697806e-01 5.286618e-01
    outer loop
      vertex   8.750000e-01 -5.863731e-01 -6.494549e-01
      vertex   3.209238e-16 -1.136534e+00 -1.330710e+00
      vertex   3.209238e-16 -1.187901e+00 -1.285064e+00
    endloop
  endfacet
  facet normal -7.071538e-01 4.844362e-01 5.150293e-01
    outer loop
      vertex   8.750000e-01 -5.863731e-01 -6.494549e-01
      vertex   3.209238e-16 -1.187901e+00 -1.285064e+00
      vertex   8.750000e-01 -6.123754e-01 -6.249971e-01
    endloop
  endfacet
  facet normal -7.069820e-01 4.902953e-01 5.096929e-01
    outer loop
      vertex   8.750000e-01 -6.123754e-01 -6.249971e-01
      vertex   3.209238e-16 -1.187901e+00 -1.285064e+00
      vertex   1.000000e-01 -1.166726e+00 -1.166726e+00
    endloop
  endfacet
  facet normal -7.071507e-01 5.050425e-01 4.948434e-01
    outer loop
      vertex   8.750000e-01 -6.123754e-01 -6.249971e-01
      vertex   1.000000e-01 -1.166726e+00 -1.166726e+00
      vertex   8.750000e-01 -6.373586e-01 -5.994990e-01
    endloop
  endfacet
  facet normal -7.069857e-01 5.098078e-01 4.901707e-01
    outer loop
      vertex   8.750000e-01 -6.373586e-01 -5.994990e-01
      vertex   1.000000e-01 -1.166726e+00 -1.166726e+00
      vertex   1.000000e-01 -1.211632e+00 -1.120021e+00
    endloop
  endfacet
  facet normal -7.071381e-01 5.248156e-01 4.738400e-01
    outer loop
      vertex   8.750000e-01 -6.373586e-01 -5.994990e-01
      vertex   1.000000e-01 -1.211632e+00 -1.120021e+00
      vertex   8.750000e-01 -6.612809e-01 -5.730031e-01
    endloop
  endfacet
  facet normal -7.069928e-01 5.286534e-01 4.697731e-01
    outer loop
      vertex   8.750000e-01 -6.612809e-01 -5.730031e-01
      vertex   1.000000e-01 -1.211632e+00 -1.120021e+00
      vertex   1.000000e-01 -1.254670e+00 -1.071589e+00
    endloop
  endfacet
  facet normal -7.071237e-01 5.437171e-01 4.520484e-01
    outer loop
      vertex   8.750000e-01 -6.612809e-01 -5.730031e-01
      vertex   1.000000e-01 -1.254670e+00 -1.071589e+00
      vertex   8.750000e-01 -6.841025e-01 -5.455536e-01
    endloop
  endfacet
  facet normal -7.070009e-01 5.466828e-01 4.486509e-01
    outer loop
      vertex   8.750000e-01 -6.841025e-01 -5.455536e-01
      vertex   1.000000e-01 -1.254670e+00 -1.071589e+00
      vertex   1.000000e-01 -1.295773e+00 -1.021505e+00
    endloop
  endfacet
  facet normal -7.071075e-01 5.617159e-01 4.295046e-01
    outer loop
      vertex   8.750000e-01 -6.841025e-01 -5.455536e-01
      vertex   1.000000e-01 -1.295773e+00 -1.021505e+00
      vertex   8.750000e-01 -7.057856e-01 -5.171960e-01
    endloop
  endfacet
  facet normal -7.070100e-01 5.638680e-01 4.268369e-01
    outer loop
      vertex   8.750000e-01 -7.057856e-01 -5.171960e-01
      vertex   1.000000e-01 -1.295773e+00 -1.021505e+00
      vertex   1.000000e-01 -1.334878e+00 -9.698457e-01
    endloop
  endfacet
  facet normal -7.070896e-01 5.787820e-01 4.062459e-01
    outer loop
      vertex   8.750000e-01 -7.057856e-01 -5.171960e-01
      vertex   1.000000e-01 -1.334878e+00 -9.698457e-01
      vertex   8.750000e-01 -7.262939e-01 -4.879776e-01
    endloop
  endfacet
  facet normal -7.070199e-01 5.801827e-01 4.043648e-01
    outer loop
      vertex   8.750000e-01 -7.262939e-01 -4.879776e-01
      vertex   1.000000e-01 -1.334878e+00 -9.698457e-01
      vertex   1.000000e-01 -1.371925e+00 -9.166909e-01
    endloop
  endfacet
  facet normal -7.070699e-01 5.948871e-01 3.823107e-01
    outer loop
      vertex   8.750000e-01 -7.262939e-01 -4.879776e-01
      vertex   1.000000e-01 -1.371925e+00 -9.166909e-01
      vertex   8.750000e-01 -7.455934e-01 -4.579470e-01
    endloop
  endfacet
  facet normal -7.070308e-01 5.956015e-01 3.812693e-01
    outer loop
      vertex   8.750000e-01 -7.455934e-01 -4.579470e-01
      vertex   1.000000e-01 -1.371925e+00 -9.166909e-01
      vertex   1.000000e-01 -1.406856e+00 -8.621226e-01
    endloop
  endfacet
  facet normal -7.070485e-01 6.100044e-01 3.577388e-01
    outer loop
      vertex   8.750000e-01 -7.455934e-01 -4.579470e-01
      vertex   1.000000e-01 -1.406856e+00 -8.621226e-01
      vertex   8.750000e-01 -7.636520e-01 -4.271542e-01
    endloop
  endfacet
  facet normal -7.070427e-01 6.101006e-01 3.575862e-01
    outer loop
      vertex   8.750000e-01 -7.636520e-01 -4.271542e-01
      vertex   1.000000e-01 -1.406856e+00 -8.621226e-01
      vertex   1.000000e-01 -1.439618e+00 -8.062250e-01
    endloop
  endfacet
  facet normal -7.070347e-01 6.236761e-01 3.333618e-01
    outer loop
      vertex   8.750000e-01 -7.636520e-01 -4.271542e-01
      vertex   1.000000e-01 -1.439618e+00 -8.062250e-01
      vertex   1.000000e-01 -1.470161e+00 -7.490843e-01
    endloop
  endfacet
  facet normal -7.070386e-01 4.901340e-01 5.097696e-01
    outer loop
      vertex   3.209238e-16 -1.187901e+00 -1.285064e+00
      vertex   0.000000e+00 -1.237437e+00 -1.237437e+00
      vertex   1.000000e-01 -1.166726e+00 -1.166726e+00
    endloop
  endfacet
  facet normal -7.070630e-01 6.240757e-01 3.325531e-01
    outer loop
      vertex   8.750000e-01 -7.636520e-01 -4.271542e-01
      vertex   1.000000e-01 -1.470161e+00 -7.490843e-01
      vertex   8.750000e-01 -7.804395e-01 -3.956504e-01
    endloop
  endfacet
  facet normal -7.070235e-01 6.362931e-01 3.086243e-01
    outer loop
      vertex   8.750000e-01 -7.804395e-01 -3.956504e-01
      vertex   1.000000e-01 -1.470161e+00 -7.490843e-01
      vertex   1.000000e-01 -1.498436e+00 -6.907886e-01
    endloop
  endfacet
  facet normal -7.070832e-01 6.371024e-01 3.068124e-01
    outer loop
      vertex   8.750000e-01 -7.804395e-01 -3.956504e-01
      vertex   1.000000e-01 -1.498436e+00 -6.907886e-01
      vertex   8.750000e-01 -7.959280e-01 -3.634881e-01
    endloop
  endfacet
  facet normal -7.070132e-01 6.479285e-01 2.834097e-01
    outer loop
      vertex   8.750000e-01 -7.959280e-01 -3.634881e-01
      vertex   1.000000e-01 -1.498436e+00 -6.907886e-01
      vertex   1.000000e-01 -1.524401e+00 -6.314277e-01
    endloop
  endfacet
  facet normal -7.071017e-01 6.490697e-01 2.805632e-01
    outer loop
      vertex   8.750000e-01 -7.959280e-01 -3.634881e-01
      vertex   1.000000e-01 -1.524401e+00 -6.314277e-01
      vertex   8.750000e-01 -8.100918e-01 -3.307209e-01
    endloop
  endfacet
  facet normal -7.071056e-01 6.539704e-01 2.689317e-01
    outer loop
      vertex   8.750000e-01 -8.100918e-01 -3.307209e-01
      vertex   1.000000e-01 -1.524401e+00 -6.314277e-01
      vertex   0.000000e+00 -1.616789e+00 -6.696960e-01
    endloop
  endfacet
  facet normal -7.070078e-01 6.585606e-01 2.577556e-01
    outer loop
      vertex   8.750000e-01 -8.100918e-01 -3.307209e-01
      vertex   0.000000e+00 -1.616789e+00 -6.696960e-01
      vertex   3.209238e-16 -1.641835e+00 -6.057048e-01
    endloop
  endfacet
  facet normal -7.071133e-01 6.599625e-01 2.538509e-01
    outer loop
      vertex   8.750000e-01 -8.100918e-01 -3.307209e-01
      vertex   3.209238e-16 -1.641835e+00 -6.057048e-01
      vertex   8.750000e-01 -8.229073e-01 -2.974031e-01
    endloop
  endfacet
  facet normal -7.070004e-01 6.681793e-01 2.317044e-01
    outer loop
      vertex   8.750000e-01 -8.229073e-01 -2.974031e-01
      vertex   3.209238e-16 -1.641835e+00 -6.057048e-01
      vertex   3.209238e-16 -1.664349e+00 -5.407797e-01
    endloop
  endfacet
  facet normal -7.071274e-01 6.697542e-01 2.267162e-01
    outer loop
      vertex   8.750000e-01 -8.229073e-01 -2.974031e-01
      vertex   3.209238e-16 -1.664349e+00 -5.407797e-01
      vertex   8.750000e-01 -8.343531e-01 -2.635904e-01
    endloop
  endfacet
  facet normal -7.069937e-01 6.767672e-01 2.052951e-01
    outer loop
      vertex   8.750000e-01 -8.343531e-01 -2.635904e-01
      vertex   3.209238e-16 -1.664349e+00 -5.407797e-01
      vertex   3.209238e-16 -1.684297e+00 -4.750208e-01
    endloop
  endfacet
  facet normal -7.071398e-01 6.784323e-01 1.992057e-01
    outer loop
      vertex   8.750000e-01 -8.343531e-01 -2.635904e-01
      vertex   3.209238e-16 -1.684297e+00 -4.750208e-01
      vertex   8.750000e-01 -8.444102e-01 -2.293390e-01
    endloop
  endfacet
  facet normal -7.069879e-01 6.843109e-01 1.785685e-01
    outer loop
      vertex   8.750000e-01 -8.444102e-01 -2.293390e-01
      vertex   3.209238e-16 -1.684297e+00 -4.750208e-01
      vertex   3.209238e-16 -1.701647e+00 -4.085294e-01
    endloop
  endfacet
  facet normal -7.071505e-01 6.859826e-01 1.713650e-01
    outer loop
      vertex   8.750000e-01 -8.444102e-01 -2.293390e-01
      vertex   3.209238e-16 -1.701647e+00 -4.085294e-01
      vertex   8.750000e-01 -8.530619e-01 -1.947058e-01
    endloop
  endfacet
  facet normal -7.069830e-01 6.907987e-01 1.515660e-01
    outer loop
      vertex   8.750000e-01 -8.530619e-01 -1.947058e-01
      vertex   3.209238e-16 -1.701647e+00 -4.085294e-01
      vertex   3.209238e-16 -1.716374e+00 -3.414081e-01
    endloop
  endfacet
  facet normal -7.071596e-01 6.923926e-01 1.432403e-01
    outer loop
      vertex   8.750000e-01 -8.530619e-01 -1.947058e-01
      vertex   3.209238e-16 -1.716374e+00 -3.414081e-01
      vertex   8.750000e-01 -8.602938e-01 -1.597486e-01
    endloop
  endfacet
  facet normal -7.069788e-01 6.962206e-01 1.243292e-01
    outer loop
      vertex   8.750000e-01 -8.602938e-01 -1.597486e-01
      vertex   3.209238e-16 -1.716374e+00 -3.414081e-01
      vertex   3.209238e-16 -1.728455e+00 -2.737603e-01
    endloop
  endfacet
  facet normal -7.071671e-01 6.976516e-01 1.148782e-01
    outer loop
      vertex   8.750000e-01 -8.602938e-01 -1.597486e-01
      vertex   3.209238e-16 -1.728455e+00 -2.737603e-01
      vertex   8.750000e-01 -8.660938e-01 -1.245255e-01
    endloop
  endfacet
  facet normal -7.069755e-01 7.005683e-01 9.690034e-02
    outer loop
      vertex   8.750000e-01 -8.660938e-01 -1.245255e-01
      vertex   3.209238e-16 -1.728455e+00 -2.737603e-01
      vertex   3.209238e-16 -1.737870e+00 -2.056904e-01
    endloop
  endfacet
  facet normal -7.071729e-01 7.017509e-01 8.632565e-02
    outer loop
      vertex   8.750000e-01 -8.660938e-01 -1.245255e-01
      vertex   3.209238e-16 -1.737870e+00 -2.056904e-01
      vertex   8.750000e-01 -8.704522e-01 -8.909511e-02
    endloop
  endfacet
  facet normal -7.069730e-01 7.038350e-01 6.932169e-02
    outer loop
      vertex   8.750000e-01 -8.704522e-01 -8.909511e-02
      vertex   3.209238e-16 -1.737870e+00 -2.056904e-01
      vertex   3.209238e-16 -1.744605e+00 -1.373034e-01
    endloop
  endfacet
  facet normal -7.071770e-01 7.046839e-01 5.763004e-02
    outer loop
      vertex   8.750000e-01 -8.704522e-01 -8.909511e-02
      vertex   3.209238e-16 -1.744605e+00 -1.373034e-01
      vertex   8.750000e-01 -8.733619e-01 -5.351645e-02
    endloop
  endfacet
  facet normal -7.069714e-01 7.060155e-01 4.163591e-02
    outer loop
      vertex   8.750000e-01 -8.733619e-01 -5.351645e-02
      vertex   3.209238e-16 -1.744605e+00 -1.373034e-01
      vertex   3.209238e-16 -1.748651e+00 -6.870468e-02
    endloop
  endfacet
  facet normal -7.071795e-01 7.064457e-01 2.883892e-02
    outer loop
      vertex   8.750000e-01 -8.733619e-01 -5.351645e-02
      vertex   3.209238e-16 -1.748651e+00 -6.870468e-02
      vertex   8.750000e-01 -8.748179e-01 -1.784872e-02
    endloop
  endfacet
  facet normal -7.069664e-01 7.071151e-01 1.366952e-02
    outer loop
      vertex   8.750000e-01 -8.748179e-01 -1.784872e-02
      vertex   3.209238e-16 -1.748651e+00 -6.870468e-02
      vertex   1.000000e-01 -1.650000e+00 -5.256849e-16
    endloop
  endfacet
  facet normal -7.071898e-01 7.070237e-01 0.000000e+00
    outer loop
      vertex   8.750000e-01 -8.748179e-01 -1.784872e-02
      vertex   1.000000e-01 -1.650000e+00 -5.256849e-16
      vertex   8.750000e-01 -8.748179e-01 1.784872e-02
    endloop
  endfacet
  facet normal -7.069618e-01 7.071154e-01 -1.388596e-02
    outer loop
      vertex   8.750000e-01 -8.748179e-01 1.784872e-02
      vertex   1.000000e-01 -1.650000e+00 -5.256849e-16
      vertex   1.000000e-01 -1.648728e+00 6.477870e-02
    endloop
  endfacet
  facet normal -7.071889e-01 7.064362e-01 -2.883853e-02
    outer loop
      vertex   8.750000e-01 -8.748179e-01 1.784872e-02
      vertex   1.000000e-01 -1.648728e+00 6.477870e-02
      vertex   8.750000e-01 -8.733619e-01 5.351645e-02
    endloop
  endfacet
  facet normal -7.069627e-01 7.060242e-01 -4.163643e-02
    outer loop
      vertex   8.750000e-01 -8.733619e-01 5.351645e-02
      vertex   1.000000e-01 -1.648728e+00 6.477870e-02
      vertex   1.000000e-01 -1.644914e+00 1.294575e-01
    endloop
  endfacet
  facet normal -7.071863e-01 7.046747e-01 -5.762928e-02
    outer loop
      vertex   8.750000e-01 -8.733619e-01 5.351645e-02
      vertex   1.000000e-01 -1.644914e+00 1.294575e-01
      vertex   8.750000e-01 -8.704522e-01 8.909511e-02
    endloop
  endfacet
  facet normal -7.069646e-01 7.038434e-01 -6.932252e-02
    outer loop
      vertex   8.750000e-01 -8.704522e-01 8.909511e-02
      vertex   1.000000e-01 -1.644914e+00 1.294575e-01
      vertex   1.000000e-01 -1.638563e+00 1.939367e-01
    endloop
  endfacet
  facet normal -7.071819e-01 7.017420e-01 -8.632455e-02
    outer loop
      vertex   8.750000e-01 -8.704522e-01 8.909511e-02
      vertex   1.000000e-01 -1.638563e+00 1.939367e-01
      vertex   8.750000e-01 -8.660938e-01 1.245255e-01
    endloop
  endfacet
  facet normal -7.069674e-01 7.005764e-01 -9.690145e-02
    outer loop
      vertex   8.750000e-01 -8.660938e-01 1.245255e-01
      vertex   1.000000e-01 -1.638563e+00 1.939367e-01
      vertex   1.000000e-01 -1.629686e+00 2.581169e-01
    endloop
  endfacet
  facet normal -7.071757e-01 6.976430e-01 -1.148768e-01
    outer loop
      vertex   8.750000e-01 -8.660938e-01 1.245255e-01
      vertex   1.000000e-01 -1.629686e+00 2.581169e-01
      vertex   8.750000e-01 -8.602938e-01 1.597486e-01
    endloop
  endfacet
  facet normal -7.069711e-01 6.962282e-01 -1.243306e-01
    outer loop
      vertex   8.750000e-01 -8.602938e-01 1.597486e-01
      vertex   1.000000e-01 -1.629686e+00 2.581169e-01
      vertex   1.000000e-01 -1.618296e+00 3.218990e-01
    endloop
  endfacet
  facet normal -7.071678e-01 6.923846e-01 -1.432387e-01
    outer loop
      vertex   8.750000e-01 -8.602938e-01 1.597486e-01
      vertex   1.000000e-01 -1.618296e+00 3.218990e-01
      vertex   8.750000e-01 -8.530619e-01 1.947058e-01
    endloop
  endfacet
  facet normal -7.069758e-01 6.908057e-01 -1.515675e-01
    outer loop
      vertex   8.750000e-01 -8.530619e-01 1.947058e-01
      vertex   1.000000e-01 -1.618296e+00 3.218990e-01
      vertex   1.000000e-01 -1.604410e+00 3.851849e-01
    endloop
  endfacet
  facet normal -7.071581e-01 6.859753e-01 -1.713632e-01
    outer loop
      vertex   8.750000e-01 -8.530619e-01 1.947058e-01
      vertex   1.000000e-01 -1.604410e+00 3.851849e-01
      vertex   8.750000e-01 -8.444102e-01 2.293390e-01
    endloop
  endfacet
  facet normal -7.069814e-01 6.843172e-01 -1.785702e-01
    outer loop
      vertex   8.750000e-01 -8.444102e-01 2.293390e-01
      vertex   1.000000e-01 -1.604410e+00 3.851849e-01
      vertex   1.000000e-01 -1.588051e+00 4.478767e-01
    endloop
  endfacet
  facet normal -7.071467e-01 6.784257e-01 -1.992038e-01
    outer loop
      vertex   8.750000e-01 -8.444102e-01 2.293390e-01
      vertex   1.000000e-01 -1.588051e+00 4.478767e-01
      vertex   8.750000e-01 -8.343531e-01 2.635904e-01
    endloop
  endfacet
  facet normal -7.069879e-01 6.767727e-01 -2.052968e-01
    outer loop
      vertex   8.750000e-01 -8.343531e-01 2.635904e-01
      vertex   1.000000e-01 -1.588051e+00 4.478767e-01
      vertex   1.000000e-01 -1.569243e+00 5.098780e-01
    endloop
  endfacet
  facet normal -7.071335e-01 6.697484e-01 -2.267142e-01
    outer loop
      vertex   8.750000e-01 -8.343531e-01 2.635904e-01
      vertex   1.000000e-01 -1.569243e+00 5.098780e-01
      vertex   8.750000e-01 -8.229073e-01 2.974031e-01
    endloop
  endfacet
  facet normal -7.069954e-01 6.681840e-01 -2.317060e-01
    outer loop
      vertex   8.750000e-01 -8.229073e-01 2.974031e-01
      vertex   1.000000e-01 -1.569243e+00 5.098780e-01
      vertex   1.000000e-01 -1.548016e+00 5.710931e-01
    endloop
  endfacet
  facet normal -7.071185e-01 6.599577e-01 -2.538490e-01
    outer loop
      vertex   8.750000e-01 -8.229073e-01 2.974031e-01
      vertex   1.000000e-01 -1.548016e+00 5.710931e-01
      vertex   8.750000e-01 -8.100918e-01 3.307209e-01
    endloop
  endfacet
  facet normal -7.070038e-01 6.585643e-01 -2.577571e-01
    outer loop
      vertex   8.750000e-01 -8.100918e-01 3.307209e-01
      vertex   1.000000e-01 -1.548016e+00 5.710931e-01
      vertex   1.000000e-01 -1.524401e+00 6.314277e-01
    endloop
  endfacet
  facet normal -7.071017e-01 6.490697e-01 -2.805632e-01
    outer loop
      vertex   8.750000e-01 -8.100918e-01 3.307209e-01
      vertex   1.000000e-01 -1.524401e+00 6.314277e-01
      vertex   8.750000e-01 -7.959280e-01 3.634881e-01
    endloop
  endfacet
  facet normal -7.070505e-01 6.483991e-01 -2.822379e-01
    outer loop
      vertex   8.750000e-01 -7.959280e-01 3.634881e-01
      vertex   1.000000e-01 -1.524401e+00 6.314277e-01
      vertex   0.000000e+00 -1.616789e+00 6.696960e-01
    endloop
  endfacet
  facet normal -7.070161e-01 6.479258e-01 -2.834086e-01
    outer loop
      vertex   8.750000e-01 -7.959280e-01 3.634881e-01
      vertex   0.000000e+00 -1.616789e+00 6.696960e-01
      vertex   3.209238e-16 -1.589251e+00 7.326545e-01
    endloop
  endfacet
  facet normal -7.070386e-01 7.070386e-01 1.388446e-02
    outer loop
      vertex   3.209238e-16 -1.748651e+00 -6.870468e-02
      vertex   0.000000e+00 -1.750000e+00 -5.911877e-16
      vertex   1.000000e-01 -1.650000e+00 -5.256849e-16
    endloop
  endfacet
  facet normal -7.070802e-01 6.371051e-01 -3.068137e-01
    outer loop
      vertex   8.750000e-01 -7.959280e-01 3.634881e-01
      vertex   3.209238e-16 -1.589251e+00 7.326545e-01
      vertex   8.750000e-01 -7.804395e-01 3.956504e-01
    endloop
  endfacet
  facet normal -7.070252e-01 6.362915e-01 -3.086235e-01
    outer loop
      vertex   8.750000e-01 -7.804395e-01 3.956504e-01
      vertex   3.209238e-16 -1.589251e+00 7.326545e-01
      vertex   3.209238e-16 -1.559261e+00 7.944834e-01
    endloop
  endfacet
  facet normal -7.070612e-01 6.240772e-01 -3.325539e-01
    outer loop
      vertex   8.750000e-01 -7.804395e-01 3.956504e-01
      vertex   3.209238e-16 -1.559261e+00 7.944834e-01
      vertex   8.750000e-01 -7.636520e-01 4.271542e-01
    endloop
  endfacet
  facet normal -7.070351e-01 6.236757e-01 -3.333616e-01
    outer loop
      vertex   8.750000e-01 -7.636520e-01 4.271542e-01
      vertex   3.209238e-16 -1.559261e+00 7.944834e-01
      vertex   3.209238e-16 -1.526868e+00 8.550872e-01
    endloop
  endfacet
  facet normal -7.070422e-01 6.101010e-01 -3.575864e-01
    outer loop
      vertex   8.750000e-01 -7.636520e-01 4.271542e-01
      vertex   3.209238e-16 -1.526868e+00 8.550872e-01
      vertex   3.209238e-16 -1.492120e+00 9.143725e-01
    endloop
  endfacet
  facet normal -7.070476e-01 6.100052e-01 -3.577393e-01
    outer loop
      vertex   8.750000e-01 -7.636520e-01 4.271542e-01
      vertex   3.209238e-16 -1.492120e+00 9.143725e-01
      vertex   8.750000e-01 -7.455934e-01 4.579470e-01
    endloop
  endfacet
  facet normal -7.070317e-01 5.956007e-01 -3.812688e-01
    outer loop
      vertex   8.750000e-01 -7.455934e-01 4.579470e-01
      vertex   3.209238e-16 -1.492120e+00 9.143725e-01
      vertex   3.209238e-16 -1.455072e+00 9.722479e-01
    endloop
  endfacet
  facet normal -7.070677e-01 5.948890e-01 -3.823119e-01
    outer loop
      vertex   8.750000e-01 -7.455934e-01 4.579470e-01
      vertex   3.209238e-16 -1.455072e+00 9.722479e-01
      vertex   8.750000e-01 -7.262939e-01 4.879776e-01
    endloop
  endfacet
  facet normal -7.070221e-01 5.801809e-01 -4.043636e-01
    outer loop
      vertex   8.750000e-01 -7.262939e-01 4.879776e-01
      vertex   3.209238e-16 -1.455072e+00 9.722479e-01
      vertex   3.209238e-16 -1.415780e+00 1.028624e+00
    endloop
  endfacet
  facet normal -7.070862e-01 5.787848e-01 -4.062478e-01
    outer loop
      vertex   8.750000e-01 -7.262939e-01 4.879776e-01
      vertex   3.209238e-16 -1.415780e+00 1.028624e+00
      vertex   8.750000e-01 -7.057856e-01 5.171960e-01
    endloop
  endfacet
  facet normal -7.070132e-01 5.638654e-01 -4.268350e-01
    outer loop
      vertex   8.750000e-01 -7.057856e-01 5.171960e-01
      vertex   3.209238e-16 -1.415780e+00 1.028624e+00
      vertex   3.209238e-16 -1.374305e+00 1.083414e+00
    endloop
  endfacet
  facet normal -7.071030e-01 5.617195e-01 -4.295073e-01
    outer loop
      vertex   8.750000e-01 -7.057856e-01 5.171960e-01
      vertex   3.209238e-16 -1.374305e+00 1.083414e+00
      vertex   8.750000e-01 -6.841025e-01 5.455536e-01
    endloop
  endfacet
  facet normal -7.070052e-01 5.466794e-01 -4.486482e-01
    outer loop
      vertex   8.750000e-01 -6.841025e-01 5.455536e-01
      vertex   3.209238e-16 -1.374305e+00 1.083414e+00
      vertex   3.209238e-16 -1.330710e+00 1.136534e+00
    endloop
  endfacet
  facet normal -7.071182e-01 5.437214e-01 -4.520519e-01
    outer loop
      vertex   8.750000e-01 -6.841025e-01 5.455536e-01
      vertex   3.209238e-16 -1.330710e+00 1.136534e+00
      vertex   8.750000e-01 -6.612809e-01 5.730031e-01
    endloop
  endfacet
  facet normal -7.069981e-01 5.286495e-01 -4.697696e-01
    outer loop
      vertex   8.750000e-01 -6.612809e-01 5.730031e-01
      vertex   3.209238e-16 -1.330710e+00 1.136534e+00
      vertex   3.209238e-16 -1.285064e+00 1.187901e+00
    endloop
  endfacet
  facet normal -7.071317e-01 5.248203e-01 -4.738443e-01
    outer loop
      vertex   8.750000e-01 -6.612809e-01 5.730031e-01
      vertex   3.209238e-16 -1.285064e+00 1.187901e+00
      vertex   8.750000e-01 -6.373586e-01 5.994990e-01
    endloop
  endfacet
  facet normal -7.069896e-01 5.097032e-01 -4.902737e-01
    outer loop
      vertex   8.750000e-01 -6.373586e-01 5.994990e-01
      vertex   3.209238e-16 -1.285064e+00 1.187901e+00
      vertex   1.000000e-01 -1.166726e+00 1.166726e+00
    endloop
  endfacet
  facet normal -7.071507e-01 5.050425e-01 -4.948434e-01
    outer loop
      vertex   8.750000e-01 -6.373586e-01 5.994990e-01
      vertex   1.000000e-01 -1.166726e+00 1.166726e+00
      vertex   8.750000e-01 -6.123754e-01 6.249971e-01
    endloop
  endfacet
  facet normal -7.069794e-01 4.901750e-01 -5.098123e-01
    outer loop
      vertex   8.750000e-01 -6.123754e-01 6.249971e-01
      vertex   1.000000e-01 -1.166726e+00 1.166726e+00
      vertex   1.000000e-01 -1.120021e+00 1.211632e+00
    endloop
  endfacet
  facet normal -7.071615e-01 4.844308e-01 -5.150236e-01
    outer loop
      vertex   8.750000e-01 -6.123754e-01 6.249971e-01
      vertex   1.000000e-01 -1.120021e+00 1.211632e+00
      vertex   8.750000e-01 -5.863731e-01 6.494549e-01
    endloop
  endfacet
  facet normal -7.069741e-01 4.697855e-01 -5.286674e-01
    outer loop
      vertex   8.750000e-01 -5.863731e-01 6.494549e-01
      vertex   1.000000e-01 -1.120021e+00 1.211632e+00
      vertex   1.000000e-01 -1.071589e+00 1.254670e+00
    endloop
  endfacet
  facet normal -7.071706e-01 4.630146e-01 -5.343474e-01
    outer loop
      vertex   8.750000e-01 -5.863731e-01 6.494549e-01
      vertex   1.000000e-01 -1.071589e+00 1.254670e+00
      vertex   8.750000e-01 -5.593948e-01 6.728317e-01
    endloop
  endfacet
  facet normal -7.069698e-01 4.486707e-01 -5.467068e-01
    outer loop
      vertex   8.750000e-01 -5.593948e-01 6.728317e-01
      vertex   1.000000e-01 -1.071589e+00 1.254670e+00
      vertex   1.000000e-01 -1.021505e+00 1.295773e+00
    endloop
  endfacet
  facet normal -7.071780e-01 4.408295e-01 -5.527827e-01
    outer loop
      vertex   8.750000e-01 -5.593948e-01 6.728317e-01
      vertex   1.000000e-01 -1.021505e+00 1.295773e+00
      vertex   8.750000e-01 -5.314854e-01 6.950887e-01
    endloop
  endfacet
  facet normal -7.069663e-01 4.268633e-01 -5.639028e-01
    outer loop
      vertex   8.750000e-01 -5.314854e-01 6.950887e-01
      vertex   1.000000e-01 -1.021505e+00 1.295773e+00
      vertex   1.000000e-01 -9.698457e-01 1.334878e+00
    endloop
  endfacet
  facet normal -7.071836e-01 4.179121e-01 -5.702990e-01
    outer loop
      vertex   8.750000e-01 -5.314854e-01 6.950887e-01
      vertex   1.000000e-01 -9.698457e-01 1.334878e+00
      vertex   8.750000e-01 -5.026914e-01 7.161888e-01
    endloop
  endfacet
  facet normal -7.069638e-01 4.043969e-01 -5.802287e-01
    outer loop
      vertex   8.750000e-01 -5.026914e-01 7.161888e-01
      vertex   1.000000e-01 -9.698457e-01 1.334878e+00
      vertex   1.000000e-01 -9.166909e-01 1.371925e+00
    endloop
  endfacet
  facet normal -7.071874e-01 3.943005e-01 -5.868672e-01
    outer loop
      vertex   8.750000e-01 -5.026914e-01 7.161888e-01
      vertex   1.000000e-01 -9.166909e-01 1.371925e+00
      vertex   8.750000e-01 -4.730607e-01 7.360968e-01
    endloop
  endfacet
  facet normal -7.069623e-01 3.813063e-01 -5.956592e-01
    outer loop
      vertex   8.750000e-01 -4.730607e-01 7.360968e-01
      vertex   1.000000e-01 -9.166909e-01 1.371925e+00
      vertex   1.000000e-01 -8.621226e-01 1.406856e+00
    endloop
  endfacet
  facet normal -7.071894e-01 3.700338e-01 -6.024600e-01
    outer loop
      vertex   8.750000e-01 -4.730607e-01 7.360968e-01
      vertex   1.000000e-01 -8.621226e-01 1.406856e+00
      vertex   8.750000e-01 -4.426427e-01 7.547797e-01
    endloop
  endfacet
  facet normal -7.069617e-01 3.576271e-01 -6.101705e-01
    outer loop
      vertex   8.750000e-01 -4.426427e-01 7.547797e-01
      vertex   1.000000e-01 -8.621226e-01 1.406856e+00
      vertex   1.000000e-01 -8.062250e-01 1.439618e+00
    endloop
  endfacet
  facet normal -7.071897e-01 3.451522e-01 -6.170516e-01
    outer loop
      vertex   8.750000e-01 -4.426427e-01 7.547797e-01
      vertex   1.000000e-01 -8.062250e-01 1.439618e+00
      vertex   8.750000e-01 -4.114879e-01 7.722064e-01
    endloop
  endfacet
  facet normal -7.069620e-01 3.333961e-01 -6.237402e-01
    outer loop
      vertex   8.750000e-01 -4.114879e-01 7.722064e-01
      vertex   1.000000e-01 -8.062250e-01 1.439618e+00
      vertex   1.000000e-01 -7.490843e-01 1.470161e+00
    endloop
  endfacet
  facet normal -7.071883e-01 3.196970e-01 -6.306176e-01
    outer loop
      vertex   8.750000e-01 -4.114879e-01 7.722064e-01
      vertex   1.000000e-01 -7.490843e-01 1.470161e+00
      vertex   8.750000e-01 -3.796483e-01 7.883478e-01
    endloop
  endfacet
  facet normal -7.069632e-01 3.086506e-01 -6.363473e-01
    outer loop
      vertex   8.750000e-01 -3.796483e-01 7.883478e-01
      vertex   1.000000e-01 -7.490843e-01 1.470161e+00
      vertex   1.000000e-01 -6.907886e-01 1.498436e+00
    endloop
  endfacet
  facet normal -7.071850e-01 2.937103e-01 -6.431358e-01
    outer loop
      vertex   8.750000e-01 -3.796483e-01 7.883478e-01
      vertex   1.000000e-01 -6.907886e-01 1.498436e+00
      vertex   8.750000e-01 -3.471767e-01 8.031770e-01
    endloop
  endfacet
  facet normal -7.069654e-01 2.834289e-01 -6.479722e-01
    outer loop
      vertex   8.750000e-01 -3.471767e-01 8.031770e-01
      vertex   1.000000e-01 -6.907886e-01 1.498436e+00
      vertex   1.000000e-01 -6.314277e-01 1.524401e+00
    endloop
  endfacet
  facet normal -7.071800e-01 2.672351e-01 -6.545852e-01
    outer loop
      vertex   8.750000e-01 -3.471767e-01 8.031770e-01
      vertex   1.000000e-01 -6.314277e-01 1.524401e+00
      vertex   8.750000e-01 -3.141274e-01 8.166695e-01
    endloop
  endfacet
  facet normal -7.070780e-01 2.622576e-01 -6.567051e-01
    outer loop
      vertex   8.750000e-01 -3.141274e-01 8.166695e-01
      vertex   1.000000e-01 -6.314277e-01 1.524401e+00
      vertex   0.000000e+00 -6.696960e-01 1.616789e+00
    endloop
  endfacet
  facet normal -7.069765e-01 2.577670e-01 -6.585897e-01
    outer loop
      vertex   8.750000e-01 -3.141274e-01 8.166695e-01
      vertex   0.000000e+00 -6.696960e-01 1.616789e+00
      vertex   3.209238e-16 -6.057048e-01 1.641835e+00
    endloop
  endfacet
  facet normal -7.070386e-01 5.097696e-01 -4.901340e-01
    outer loop
      vertex   3.209238e-16 -1.285064e+00 1.187901e+00
      vertex   0.000000e+00 -1.237437e+00 1.237437e+00
      vertex   1.000000e-01 -1.166726e+00 1.166726e+00
    endloop
  endfacet
  facet normal -7.071648e-01 2.403183e-01 -6.649549e-01
    outer loop
      vertex   8.750000e-01 -3.141274e-01 8.166695e-01
      vertex   3.209238e-16 -6.057048e-01 1.641835e+00
      vertex   8.750000e-01 -2.805552e-01 8.288026e-01
    endloop
  endfacet
  facet normal -7.069801e-01 2.317110e-01 -6.681984e-01
    outer loop
      vertex   8.750000e-01 -2.805552e-01 8.288026e-01
      vertex   3.209238e-16 -6.057048e-01 1.641835e+00
      vertex   3.209238e-16 -5.407797e-01 1.664349e+00
    endloop
  endfacet
  facet normal -7.071568e-01 2.129982e-01 -6.742114e-01
    outer loop
      vertex   8.750000e-01 -2.805552e-01 8.288026e-01
      vertex   3.209238e-16 -5.407797e-01 1.664349e+00
      vertex   8.750000e-01 -2.465160e-01 8.395564e-01
    endloop
  endfacet
  facet normal -7.069845e-01 2.052977e-01 -6.767760e-01
    outer loop
      vertex   8.750000e-01 -2.465160e-01 8.395564e-01
      vertex   3.209238e-16 -5.407797e-01 1.664349e+00
      vertex   3.209238e-16 -4.750208e-01 1.684297e+00
    endloop
  endfacet
  facet normal -7.071471e-01 1.853233e-01 -6.823476e-01
    outer loop
      vertex   8.750000e-01 -2.465160e-01 8.395564e-01
      vertex   3.209238e-16 -4.750208e-01 1.684297e+00
      vertex   8.750000e-01 -2.120665e-01 8.489127e-01
    endloop
  endfacet
  facet normal -7.069898e-01 1.785680e-01 -6.843091e-01
    outer loop
      vertex   8.750000e-01 -2.120665e-01 8.489127e-01
      vertex   3.209238e-16 -4.750208e-01 1.684297e+00
      vertex   3.209238e-16 -4.085294e-01 1.701647e+00
    endloop
  endfacet
  facet normal -7.071358e-01 1.573396e-01 -6.893498e-01
    outer loop
      vertex   8.750000e-01 -2.120665e-01 8.489127e-01
      vertex   3.209238e-16 -4.085294e-01 1.701647e+00
      vertex   8.750000e-01 -1.772641e-01 8.568561e-01
    endloop
  endfacet
  facet normal -7.069958e-01 1.515632e-01 -6.907861e-01
    outer loop
      vertex   8.750000e-01 -1.772641e-01 8.568561e-01
      vertex   3.209238e-16 -4.085294e-01 1.701647e+00
      vertex   3.209238e-16 -3.414081e-01 1.716374e+00
    endloop
  endfacet
  facet normal -7.071229e-01 1.290934e-01 -6.952065e-01
    outer loop
      vertex   8.750000e-01 -1.772641e-01 8.568561e-01
      vertex   3.209238e-16 -3.414081e-01 1.716374e+00
      vertex   8.750000e-01 -1.421666e-01 8.633734e-01
    endloop
  endfacet
  facet normal -7.070027e-01 1.243250e-01 -6.961971e-01
    outer loop
      vertex   8.750000e-01 -1.421666e-01 8.633734e-01
      vertex   3.209238e-16 -3.414081e-01 1.716374e+00
      vertex   3.209238e-16 -2.737603e-01 1.728455e+00
    endloop
  endfacet
  facet normal -7.071083e-01 1.006316e-01 -6.999080e-01
    outer loop
      vertex   8.750000e-01 -1.421666e-01 8.633734e-01
      vertex   3.209238e-16 -2.737603e-01 1.728455e+00
      vertex   8.750000e-01 -1.068325e-01 8.684537e-01
    endloop
  endfacet
  facet normal -7.070105e-01 9.689555e-02 -7.005337e-01
    outer loop
      vertex   8.750000e-01 -1.068325e-01 8.684537e-01
      vertex   3.209238e-16 -2.737603e-01 1.728455e+00
      vertex   3.209238e-16 -2.056904e-01 1.737870e+00
    endloop
  endfacet
  facet normal -7.070920e-01 7.200123e-02 -7.034463e-01
    outer loop
      vertex   8.750000e-01 -1.068325e-01 8.684537e-01
      vertex   3.209238e-16 -2.056904e-01 1.737870e+00
      vertex   8.750000e-01 -7.132062e-02 8.720885e-01
    endloop
  endfacet
  facet normal -7.070190e-01 6.931718e-02 -7.037892e-01
    outer loop
      vertex   8.750000e-01 -7.132062e-02 8.720885e-01
      vertex   3.209238e-16 -2.056904e-01 1.737870e+00
      vertex   3.209238e-16 -1.373034e-01 1.744605e+00
    endloop
  endfacet
  facet normal -7.070740e-01 4.324983e-02 -7.058157e-01
    outer loop
      vertex   8.750000e-01 -7.132062e-02 8.720885e-01
      vertex   3.209238e-16 -1.373034e-01 1.744605e+00
      vertex   8.750000e-01 -3.569001e-02 8.742718e-01
    endloop
  endfacet
  facet normal -7.070284e-01 4.163256e-02 -7.059586e-01
    outer loop
      vertex   8.750000e-01 -3.569001e-02 8.742718e-01
      vertex   3.209238e-16 -1.373034e-01 1.744605e+00
      vertex   3.209238e-16 -6.870468e-02 1.748651e+00
    endloop
  endfacet
  facet normal -7.070500e-01 1.391821e-02 -7.070266e-01
    outer loop
      vertex   8.750000e-01 -3.569001e-02 8.742718e-01
      vertex   3.209238e-16 -6.870468e-02 1.748651e+00
      vertex   1.000000e-01 -5.574642e-17 1.650000e+00
    endloop
  endfacet
  facet normal -7.070386e-01 1.388446e-02 -7.070386e-01
    outer loop
      vertex   1.000000e-01 -5.574642e-17 1.650000e+00
      vertex   3.209238e-16 -6.870468e-02 1.748651e+00
      vertex   3.209238e-16 0.000000e+00 1.750000e+00
    endloop
  endfacet
  facet normal -7.070332e-01 1.442544e-02 -7.070332e-01
    outer loop
      vertex   1.000000e-01 -5.574642e-17 1.650000e+00
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -3.569001e-02 8.742718e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -4.325232e-02 7.058564e-01
    outer loop
      vertex   8.750000e-01 3.569001e-02 -8.742718e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 7.132062e-02 -8.720885e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -7.200722e-02 7.035048e-01
    outer loop
      vertex   8.750000e-01 7.132062e-02 -8.720885e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 1.068325e-01 -8.684537e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -1.006423e-01 6.999823e-01
    outer loop
      vertex   8.750000e-01 1.068325e-01 -8.684537e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 1.421666e-01 -8.633734e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -1.291098e-01 6.952947e-01
    outer loop
      vertex   8.750000e-01 1.421666e-01 -8.633734e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 1.772641e-01 -8.568561e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -1.573624e-01 6.894499e-01
    outer loop
      vertex   8.750000e-01 1.772641e-01 -8.568561e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 2.120665e-01 -8.489127e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -1.853532e-01 6.824575e-01
    outer loop
      vertex   8.750000e-01 2.120665e-01 -8.489127e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 2.465160e-01 -8.395564e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -2.130354e-01 6.743293e-01
    outer loop
      vertex   8.750000e-01 2.465160e-01 -8.395564e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 2.805552e-01 -8.288026e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -2.403630e-01 6.650787e-01
    outer loop
      vertex   8.750000e-01 2.805552e-01 -8.288026e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 3.141274e-01 -8.166695e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -2.672906e-01 6.547211e-01
    outer loop
      vertex   8.750000e-01 3.141274e-01 -8.166695e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 3.471767e-01 -8.031770e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -2.937733e-01 6.432739e-01
    outer loop
      vertex   8.750000e-01 3.471767e-01 -8.031770e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 3.796483e-01 -7.883478e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -3.197671e-01 6.307559e-01
    outer loop
      vertex   8.750000e-01 3.796483e-01 -7.883478e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 4.114879e-01 -7.722064e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -3.452286e-01 6.171882e-01
    outer loop
      vertex   8.750000e-01 4.114879e-01 -7.722064e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 4.426427e-01 -7.547797e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -3.701156e-01 6.025932e-01
    outer loop
      vertex   8.750000e-01 4.426427e-01 -7.547797e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 4.730607e-01 -7.360968e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -3.943865e-01 5.869952e-01
    outer loop
      vertex   8.750000e-01 4.730607e-01 -7.360968e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 5.026914e-01 -7.161888e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -4.180010e-01 5.704202e-01
    outer loop
      vertex   8.750000e-01 5.026914e-01 -7.161888e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 5.314854e-01 -6.950887e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -4.409197e-01 5.528959e-01
    outer loop
      vertex   8.750000e-01 5.314854e-01 -6.950887e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 5.593948e-01 -6.728317e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -4.631046e-01 5.344512e-01
    outer loop
      vertex   8.750000e-01 5.593948e-01 -6.728317e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 5.863731e-01 -6.494549e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -4.845188e-01 5.151171e-01
    outer loop
      vertex   8.750000e-01 5.863731e-01 -6.494549e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 6.123754e-01 -6.249971e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -5.051264e-01 4.949256e-01
    outer loop
      vertex   8.750000e-01 6.123754e-01 -6.249971e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 6.373586e-01 -5.994990e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -5.248934e-01 4.739103e-01
    outer loop
      vertex   8.750000e-01 6.373586e-01 -5.994990e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 6.612809e-01 -5.730031e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -5.437867e-01 4.521063e-01
    outer loop
      vertex   8.750000e-01 6.612809e-01 -5.730031e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 6.841025e-01 -5.455536e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -5.617749e-01 4.295497e-01
    outer loop
      vertex   8.750000e-01 6.841025e-01 -5.455536e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 7.057856e-01 -5.171960e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -5.788282e-01 4.062782e-01
    outer loop
      vertex   8.750000e-01 7.057856e-01 -5.171960e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 7.262939e-01 -4.879776e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -5.949180e-01 3.823306e-01
    outer loop
      vertex   8.750000e-01 7.262939e-01 -4.879776e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 7.455934e-01 -4.579470e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.100176e-01 3.577465e-01
    outer loop
      vertex   8.750000e-01 7.455934e-01 -4.579470e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 7.636520e-01 -4.271542e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.241019e-01 3.325671e-01
    outer loop
      vertex   8.750000e-01 7.636520e-01 -4.271542e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 7.804395e-01 -3.956504e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.371475e-01 3.068341e-01
    outer loop
      vertex   8.750000e-01 7.804395e-01 -3.956504e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 7.959280e-01 -3.634881e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.491326e-01 2.805904e-01
    outer loop
      vertex   8.750000e-01 7.959280e-01 -3.634881e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.100918e-01 -3.307209e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.600372e-01 2.538797e-01
    outer loop
      vertex   8.750000e-01 8.100918e-01 -3.307209e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.229073e-01 -2.974031e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.698434e-01 2.267464e-01
    outer loop
      vertex   8.750000e-01 8.229073e-01 -2.974031e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.343531e-01 -2.635904e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.785346e-01 1.992357e-01
    outer loop
      vertex   8.750000e-01 8.343531e-01 -2.635904e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.444102e-01 -2.293390e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.860964e-01 1.713935e-01
    outer loop
      vertex   8.750000e-01 8.444102e-01 -2.293390e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.530619e-01 -1.947058e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.925164e-01 1.432659e-01
    outer loop
      vertex   8.750000e-01 8.530619e-01 -1.947058e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.602938e-01 -1.597486e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.977837e-01 1.148999e-01
    outer loop
      vertex   8.750000e-01 8.602938e-01 -1.597486e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.660938e-01 -1.245255e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -7.018896e-01 8.634270e-02
    outer loop
      vertex   8.750000e-01 8.660938e-01 -1.245255e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.704522e-01 -8.909511e-02
    endloop
  endfacet
  facet normal -7.070332e-01 -7.048273e-01 5.764176e-02
    outer loop
      vertex   8.750000e-01 8.704522e-01 -8.909511e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.733619e-01 -5.351645e-02
    endloop
  endfacet
  facet normal -7.070332e-01 -7.065918e-01 2.884489e-02
    outer loop
      vertex   8.750000e-01 8.733619e-01 -5.351645e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.748179e-01 -1.784872e-02
    endloop
  endfacet
  facet normal -7.070332e-01 -7.071803e-01 0.000000e+00
    outer loop
      vertex   8.750000e-01 8.748179e-01 -1.784872e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.748179e-01 1.784872e-02
    endloop
  endfacet
  facet normal -7.070332e-01 -7.065918e-01 -2.884489e-02
    outer loop
      vertex   8.750000e-01 8.748179e-01 1.784872e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.733619e-01 5.351645e-02
    endloop
  endfacet
  facet normal -7.070332e-01 -7.048273e-01 -5.764176e-02
    outer loop
      vertex   8.750000e-01 8.733619e-01 5.351645e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.704522e-01 8.909511e-02
    endloop
  endfacet
  facet normal -7.070332e-01 -7.018896e-01 -8.634270e-02
    outer loop
      vertex   8.750000e-01 8.704522e-01 8.909511e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.660938e-01 1.245255e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.977837e-01 -1.148999e-01
    outer loop
      vertex   8.750000e-01 8.660938e-01 1.245255e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.602938e-01 1.597486e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.925164e-01 -1.432659e-01
    outer loop
      vertex   8.750000e-01 8.602938e-01 1.597486e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.530619e-01 1.947058e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.860964e-01 -1.713935e-01
    outer loop
      vertex   8.750000e-01 8.530619e-01 1.947058e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.444102e-01 2.293390e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.785346e-01 -1.992357e-01
    outer loop
      vertex   8.750000e-01 8.444102e-01 2.293390e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.343531e-01 2.635904e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.698434e-01 -2.267464e-01
    outer loop
      vertex   8.750000e-01 8.343531e-01 2.635904e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.229073e-01 2.974031e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.600372e-01 -2.538797e-01
    outer loop
      vertex   8.750000e-01 8.229073e-01 2.974031e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 8.100918e-01 3.307209e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.491326e-01 -2.805904e-01
    outer loop
      vertex   8.750000e-01 8.100918e-01 3.307209e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 7.959280e-01 3.634881e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.371475e-01 -3.068341e-01
    outer loop
      vertex   8.750000e-01 7.959280e-01 3.634881e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 7.804395e-01 3.956504e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.241019e-01 -3.325671e-01
    outer loop
      vertex   8.750000e-01 7.804395e-01 3.956504e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 7.636520e-01 4.271542e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -6.100176e-01 -3.577465e-01
    outer loop
      vertex   8.750000e-01 7.636520e-01 4.271542e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 7.455934e-01 4.579470e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -5.949180e-01 -3.823306e-01
    outer loop
      vertex   8.750000e-01 7.455934e-01 4.579470e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 7.262939e-01 4.879776e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -5.788282e-01 -4.062782e-01
    outer loop
      vertex   8.750000e-01 7.262939e-01 4.879776e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 7.057856e-01 5.171960e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -5.617749e-01 -4.295497e-01
    outer loop
      vertex   8.750000e-01 7.057856e-01 5.171960e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 6.841025e-01 5.455536e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -5.437867e-01 -4.521063e-01
    outer loop
      vertex   8.750000e-01 6.841025e-01 5.455536e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 6.612809e-01 5.730031e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -5.248934e-01 -4.739103e-01
    outer loop
      vertex   8.750000e-01 6.612809e-01 5.730031e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 6.373586e-01 5.994990e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -5.051264e-01 -4.949256e-01
    outer loop
      vertex   8.750000e-01 6.373586e-01 5.994990e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 6.123754e-01 6.249971e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -4.845188e-01 -5.151171e-01
    outer loop
      vertex   8.750000e-01 6.123754e-01 6.249971e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 5.863731e-01 6.494549e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -4.631046e-01 -5.344512e-01
    outer loop
      vertex   8.750000e-01 5.863731e-01 6.494549e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 5.593948e-01 6.728317e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -4.409197e-01 -5.528959e-01
    outer loop
      vertex   8.750000e-01 5.593948e-01 6.728317e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 5.314854e-01 6.950887e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -4.180010e-01 -5.704202e-01
    outer loop
      vertex   8.750000e-01 5.314854e-01 6.950887e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 5.026914e-01 7.161888e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -3.943865e-01 -5.869952e-01
    outer loop
      vertex   8.750000e-01 5.026914e-01 7.161888e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 4.730607e-01 7.360968e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -3.701156e-01 -6.025932e-01
    outer loop
      vertex   8.750000e-01 4.730607e-01 7.360968e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 4.426427e-01 7.547797e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -3.452286e-01 -6.171882e-01
    outer loop
      vertex   8.750000e-01 4.426427e-01 7.547797e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 4.114879e-01 7.722064e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -3.197671e-01 -6.307559e-01
    outer loop
      vertex   8.750000e-01 4.114879e-01 7.722064e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 3.796483e-01 7.883478e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -2.937733e-01 -6.432739e-01
    outer loop
      vertex   8.750000e-01 3.796483e-01 7.883478e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 3.471767e-01 8.031770e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -2.672906e-01 -6.547211e-01
    outer loop
      vertex   8.750000e-01 3.471767e-01 8.031770e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 3.141274e-01 8.166695e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -2.403630e-01 -6.650787e-01
    outer loop
      vertex   8.750000e-01 3.141274e-01 8.166695e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 2.805552e-01 8.288026e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -2.130354e-01 -6.743293e-01
    outer loop
      vertex   8.750000e-01 2.805552e-01 8.288026e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 2.465160e-01 8.395564e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -1.853532e-01 -6.824575e-01
    outer loop
      vertex   8.750000e-01 2.465160e-01 8.395564e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 2.120665e-01 8.489127e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -1.573624e-01 -6.894499e-01
    outer loop
      vertex   8.750000e-01 2.120665e-01 8.489127e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 1.772641e-01 8.568561e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -1.291098e-01 -6.952947e-01
    outer loop
      vertex   8.750000e-01 1.772641e-01 8.568561e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 1.421666e-01 8.633734e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -1.006423e-01 -6.999823e-01
    outer loop
      vertex   8.750000e-01 1.421666e-01 8.633734e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 1.068325e-01 8.684537e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -7.200722e-02 -7.035048e-01
    outer loop
      vertex   8.750000e-01 1.068325e-01 8.684537e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 7.132062e-02 8.720885e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -4.325232e-02 -7.058564e-01
    outer loop
      vertex   8.750000e-01 7.132062e-02 8.720885e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 3.569001e-02 8.742718e-01
    endloop
  endfacet
  facet normal -7.070332e-01 4.325232e-02 -7.058564e-01
    outer loop
      vertex   8.750000e-01 -3.569001e-02 8.742718e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -7.132062e-02 8.720885e-01
    endloop
  endfacet
  facet normal -7.070332e-01 7.200722e-02 -7.035048e-01
    outer loop
      vertex   8.750000e-01 -7.132062e-02 8.720885e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -1.068325e-01 8.684537e-01
    endloop
  endfacet
  facet normal -7.070332e-01 1.006423e-01 -6.999823e-01
    outer loop
      vertex   8.750000e-01 -1.068325e-01 8.684537e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -1.421666e-01 8.633734e-01
    endloop
  endfacet
  facet normal -7.070332e-01 1.291098e-01 -6.952947e-01
    outer loop
      vertex   8.750000e-01 -1.421666e-01 8.633734e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -1.772641e-01 8.568561e-01
    endloop
  endfacet
  facet normal -7.070332e-01 1.573624e-01 -6.894499e-01
    outer loop
      vertex   8.750000e-01 -1.772641e-01 8.568561e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -2.120665e-01 8.489127e-01
    endloop
  endfacet
  facet normal -7.070332e-01 1.853532e-01 -6.824575e-01
    outer loop
      vertex   8.750000e-01 -2.120665e-01 8.489127e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -2.465160e-01 8.395564e-01
    endloop
  endfacet
  facet normal -7.070332e-01 2.130354e-01 -6.743293e-01
    outer loop
      vertex   8.750000e-01 -2.465160e-01 8.395564e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -2.805552e-01 8.288026e-01
    endloop
  endfacet
  facet normal -7.070332e-01 2.403630e-01 -6.650787e-01
    outer loop
      vertex   8.750000e-01 -2.805552e-01 8.288026e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -3.141274e-01 8.166695e-01
    endloop
  endfacet
  facet normal -7.070332e-01 2.672906e-01 -6.547211e-01
    outer loop
      vertex   8.750000e-01 -3.141274e-01 8.166695e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -3.471767e-01 8.031770e-01
    endloop
  endfacet
  facet normal -7.070332e-01 2.937733e-01 -6.432739e-01
    outer loop
      vertex   8.750000e-01 -3.471767e-01 8.031770e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -3.796483e-01 7.883478e-01
    endloop
  endfacet
  facet normal -7.070332e-01 3.197671e-01 -6.307559e-01
    outer loop
      vertex   8.750000e-01 -3.796483e-01 7.883478e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -4.114879e-01 7.722064e-01
    endloop
  endfacet
  facet normal -7.070332e-01 3.452286e-01 -6.171882e-01
    outer loop
      vertex   8.750000e-01 -4.114879e-01 7.722064e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -4.426427e-01 7.547797e-01
    endloop
  endfacet
  facet normal -7.070332e-01 3.701156e-01 -6.025932e-01
    outer loop
      vertex   8.750000e-01 -4.426427e-01 7.547797e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -4.730607e-01 7.360968e-01
    endloop
  endfacet
  facet normal -7.070332e-01 3.943865e-01 -5.869952e-01
    outer loop
      vertex   8.750000e-01 -4.730607e-01 7.360968e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -5.026914e-01 7.161888e-01
    endloop
  endfacet
  facet normal -7.070332e-01 4.180010e-01 -5.704202e-01
    outer loop
      vertex   8.750000e-01 -5.026914e-01 7.161888e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -5.314854e-01 6.950887e-01
    endloop
  endfacet
  facet normal -7.070332e-01 4.409197e-01 -5.528959e-01
    outer loop
      vertex   8.750000e-01 -5.314854e-01 6.950887e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -5.593948e-01 6.728317e-01
    endloop
  endfacet
  facet normal -7.070332e-01 4.631046e-01 -5.344512e-01
    outer loop
      vertex   8.750000e-01 -5.593948e-01 6.728317e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -5.863731e-01 6.494549e-01
    endloop
  endfacet
  facet normal -7.070332e-01 4.845188e-01 -5.151171e-01
    outer loop
      vertex   8.750000e-01 -5.863731e-01 6.494549e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -6.123754e-01 6.249971e-01
    endloop
  endfacet
  facet normal -7.070332e-01 5.051264e-01 -4.949256e-01
    outer loop
      vertex   8.750000e-01 -6.123754e-01 6.249971e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -6.373586e-01 5.994990e-01
    endloop
  endfacet
  facet normal -7.070332e-01 5.248934e-01 -4.739103e-01
    outer loop
      vertex   8.750000e-01 -6.373586e-01 5.994990e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -6.612809e-01 5.730031e-01
    endloop
  endfacet
  facet normal -7.070332e-01 5.437867e-01 -4.521063e-01
    outer loop
      vertex   8.750000e-01 -6.612809e-01 5.730031e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -6.841025e-01 5.455536e-01
    endloop
  endfacet
  facet normal -7.070332e-01 5.617749e-01 -4.295497e-01
    outer loop
      vertex   8.750000e-01 -6.841025e-01 5.455536e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -7.057856e-01 5.171960e-01
    endloop
  endfacet
  facet normal -7.070332e-01 5.788282e-01 -4.062782e-01
    outer loop
      vertex   8.750000e-01 -7.057856e-01 5.171960e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -7.262939e-01 4.879776e-01
    endloop
  endfacet
  facet normal -7.070332e-01 5.949180e-01 -3.823306e-01
    outer loop
      vertex   8.750000e-01 -7.262939e-01 4.879776e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -7.455934e-01 4.579470e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.100176e-01 -3.577465e-01
    outer loop
      vertex   8.750000e-01 -7.455934e-01 4.579470e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -7.636520e-01 4.271542e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.241019e-01 -3.325671e-01
    outer loop
      vertex   8.750000e-01 -7.636520e-01 4.271542e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -7.804395e-01 3.956504e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.371475e-01 -3.068341e-01
    outer loop
      vertex   8.750000e-01 -7.804395e-01 3.956504e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -7.959280e-01 3.634881e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.491326e-01 -2.805904e-01
    outer loop
      vertex   8.750000e-01 -7.959280e-01 3.634881e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.100918e-01 3.307209e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.600372e-01 -2.538797e-01
    outer loop
      vertex   8.750000e-01 -8.100918e-01 3.307209e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.229073e-01 2.974031e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.698434e-01 -2.267464e-01
    outer loop
      vertex   8.750000e-01 -8.229073e-01 2.974031e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.343531e-01 2.635904e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.785346e-01 -1.992357e-01
    outer loop
      vertex   8.750000e-01 -8.343531e-01 2.635904e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.444102e-01 2.293390e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.860964e-01 -1.713935e-01
    outer loop
      vertex   8.750000e-01 -8.444102e-01 2.293390e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.530619e-01 1.947058e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.925164e-01 -1.432659e-01
    outer loop
      vertex   8.750000e-01 -8.530619e-01 1.947058e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.602938e-01 1.597486e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.977837e-01 -1.148999e-01
    outer loop
      vertex   8.750000e-01 -8.602938e-01 1.597486e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.660938e-01 1.245255e-01
    endloop
  endfacet
  facet normal -7.070332e-01 7.018896e-01 -8.634270e-02
    outer loop
      vertex   8.750000e-01 -8.660938e-01 1.245255e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.704522e-01 8.909511e-02
    endloop
  endfacet
  facet normal -7.070332e-01 7.048273e-01 -5.764176e-02
    outer loop
      vertex   8.750000e-01 -8.704522e-01 8.909511e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.733619e-01 5.351645e-02
    endloop
  endfacet
  facet normal -7.070332e-01 7.065918e-01 -2.884489e-02
    outer loop
      vertex   8.750000e-01 -8.733619e-01 5.351645e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.748179e-01 1.784872e-02
    endloop
  endfacet
  facet normal -7.070332e-01 7.065918e-01 2.884489e-02
    outer loop
      vertex   8.750000e-01 -8.748179e-01 -1.784872e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.733619e-01 -5.351645e-02
    endloop
  endfacet
  facet normal -7.070332e-01 7.048273e-01 5.764176e-02
    outer loop
      vertex   8.750000e-01 -8.733619e-01 -5.351645e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.704522e-01 -8.909511e-02
    endloop
  endfacet
  facet normal -7.070332e-01 7.018896e-01 8.634270e-02
    outer loop
      vertex   8.750000e-01 -8.704522e-01 -8.909511e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.660938e-01 -1.245255e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.977837e-01 1.148999e-01
    outer loop
      vertex   8.750000e-01 -8.660938e-01 -1.245255e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.602938e-01 -1.597486e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.925164e-01 1.432659e-01
    outer loop
      vertex   8.750000e-01 -8.602938e-01 -1.597486e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.530619e-01 -1.947058e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.860964e-01 1.713935e-01
    outer loop
      vertex   8.750000e-01 -8.530619e-01 -1.947058e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.444102e-01 -2.293390e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.785346e-01 1.992357e-01
    outer loop
      vertex   8.750000e-01 -8.444102e-01 -2.293390e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.343531e-01 -2.635904e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.698434e-01 2.267464e-01
    outer loop
      vertex   8.750000e-01 -8.343531e-01 -2.635904e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.229073e-01 -2.974031e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.600372e-01 2.538797e-01
    outer loop
      vertex   8.750000e-01 -8.229073e-01 -2.974031e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.100918e-01 -3.307209e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.491326e-01 2.805904e-01
    outer loop
      vertex   8.750000e-01 -8.100918e-01 -3.307209e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -7.959280e-01 -3.634881e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.371475e-01 3.068341e-01
    outer loop
      vertex   8.750000e-01 -7.959280e-01 -3.634881e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -7.804395e-01 -3.956504e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.241019e-01 3.325671e-01
    outer loop
      vertex   8.750000e-01 -7.804395e-01 -3.956504e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -7.636520e-01 -4.271542e-01
    endloop
  endfacet
  facet normal -7.070332e-01 6.100176e-01 3.577465e-01
    outer loop
      vertex   8.750000e-01 -7.636520e-01 -4.271542e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -7.455934e-01 -4.579470e-01
    endloop
  endfacet
  facet normal -7.070332e-01 5.949180e-01 3.823306e-01
    outer loop
      vertex   8.750000e-01 -7.455934e-01 -4.579470e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -7.262939e-01 -4.879776e-01
    endloop
  endfacet
  facet normal -7.070332e-01 5.788282e-01 4.062782e-01
    outer loop
      vertex   8.750000e-01 -7.262939e-01 -4.879776e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -7.057856e-01 -5.171960e-01
    endloop
  endfacet
  facet normal -7.070332e-01 5.617749e-01 4.295497e-01
    outer loop
      vertex   8.750000e-01 -7.057856e-01 -5.171960e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -6.841025e-01 -5.455536e-01
    endloop
  endfacet
  facet normal -7.070332e-01 5.437867e-01 4.521063e-01
    outer loop
      vertex   8.750000e-01 -6.841025e-01 -5.455536e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -6.612809e-01 -5.730031e-01
    endloop
  endfacet
  facet normal -7.070332e-01 5.248934e-01 4.739103e-01
    outer loop
      vertex   8.750000e-01 -6.612809e-01 -5.730031e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -6.373586e-01 -5.994990e-01
    endloop
  endfacet
  facet normal -7.070332e-01 5.051264e-01 4.949256e-01
    outer loop
      vertex   8.750000e-01 -6.373586e-01 -5.994990e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -6.123754e-01 -6.249971e-01
    endloop
  endfacet
  facet normal -7.070332e-01 4.845188e-01 5.151171e-01
    outer loop
      vertex   8.750000e-01 -6.123754e-01 -6.249971e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -5.863731e-01 -6.494549e-01
    endloop
  endfacet
  facet normal -7.070332e-01 4.631046e-01 5.344512e-01
    outer loop
      vertex   8.750000e-01 -5.863731e-01 -6.494549e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -5.593948e-01 -6.728317e-01
    endloop
  endfacet
  facet normal -7.070332e-01 4.409197e-01 5.528959e-01
    outer loop
      vertex   8.750000e-01 -5.593948e-01 -6.728317e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -5.314854e-01 -6.950887e-01
    endloop
  endfacet
  facet normal -7.070332e-01 4.180010e-01 5.704202e-01
    outer loop
      vertex   8.750000e-01 -5.314854e-01 -6.950887e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -5.026914e-01 -7.161888e-01
    endloop
  endfacet
  facet normal -7.070332e-01 3.943865e-01 5.869952e-01
    outer loop
      vertex   8.750000e-01 -5.026914e-01 -7.161888e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -4.730607e-01 -7.360968e-01
    endloop
  endfacet
  facet normal -7.070332e-01 3.701156e-01 6.025932e-01
    outer loop
      vertex   8.750000e-01 -4.730607e-01 -7.360968e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -4.426427e-01 -7.547797e-01
    endloop
  endfacet
  facet normal -7.070332e-01 3.452286e-01 6.171882e-01
    outer loop
      vertex   8.750000e-01 -4.426427e-01 -7.547797e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -4.114879e-01 -7.722064e-01
    endloop
  endfacet
  facet normal -7.070332e-01 3.197671e-01 6.307559e-01
    outer loop
      vertex   8.750000e-01 -4.114879e-01 -7.722064e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -3.796483e-01 -7.883478e-01
    endloop
  endfacet
  facet normal -7.070332e-01 2.937733e-01 6.432739e-01
    outer loop
      vertex   8.750000e-01 -3.796483e-01 -7.883478e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -3.471767e-01 -8.031770e-01
    endloop
  endfacet
  facet normal -7.070332e-01 2.672906e-01 6.547211e-01
    outer loop
      vertex   8.750000e-01 -3.471767e-01 -8.031770e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -3.141274e-01 -8.166695e-01
    endloop
  endfacet
  facet normal -7.070332e-01 2.403630e-01 6.650787e-01
    outer loop
      vertex   8.750000e-01 -3.141274e-01 -8.166695e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -2.805552e-01 -8.288026e-01
    endloop
  endfacet
  facet normal -7.070332e-01 2.130354e-01 6.743293e-01
    outer loop
      vertex   8.750000e-01 -2.805552e-01 -8.288026e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -2.465160e-01 -8.395564e-01
    endloop
  endfacet
  facet normal -7.070332e-01 1.853532e-01 6.824575e-01
    outer loop
      vertex   8.750000e-01 -2.465160e-01 -8.395564e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -2.120665e-01 -8.489127e-01
    endloop
  endfacet
  facet normal -7.070332e-01 1.573624e-01 6.894499e-01
    outer loop
      vertex   8.750000e-01 -2.120665e-01 -8.489127e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -1.772641e-01 -8.568561e-01
    endloop
  endfacet
  facet normal -7.070332e-01 1.291098e-01 6.952947e-01
    outer loop
      vertex   8.750000e-01 -1.772641e-01 -8.568561e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -1.421666e-01 -8.633734e-01
    endloop
  endfacet
  facet normal -7.070332e-01 1.006423e-01 6.999823e-01
    outer loop
      vertex   8.750000e-01 -1.421666e-01 -8.633734e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -1.068325e-01 -8.684537e-01
    endloop
  endfacet
  facet normal -7.070332e-01 7.200722e-02 7.035048e-01
    outer loop
      vertex   8.750000e-01 -1.068325e-01 -8.684537e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -7.132062e-02 -8.720885e-01
    endloop
  endfacet
  facet normal -7.070332e-01 4.325232e-02 7.058564e-01
    outer loop
      vertex   8.750000e-01 -7.132062e-02 -8.720885e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -3.569001e-02 -8.742718e-01
    endloop
  endfacet
  facet normal -7.070332e-01 1.442544e-02 7.070332e-01
    outer loop
      vertex   8.750000e-01 -3.569001e-02 -8.742718e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 1.071566e-16 -8.750000e-01
    endloop
  endfacet
  facet normal -7.070332e-01 -1.442544e-02 7.070332e-01
    outer loop
      vertex   8.750000e-01 1.071566e-16 -8.750000e-01
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 3.569001e-02 -8.742718e-01
    endloop
  endfacet
  facet normal -7.070332e-01 7.071803e-01 0.000000e+00
    outer loop
      vertex   8.750000e-01 -8.748179e-01 1.784872e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
      vertex   8.750000e-01 -8.748179e-01 -1.784872e-02
    endloop
  endfacet
  facet normal 7.057651e-01 6.157405e-02 -7.057651e-01
    outer loop
      vertex   1.820711e+00 0.000000e+00 7.071068e-02
      vertex   1.820711e+00 -1.224502e-02 6.964237e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 1.828616e-01 -6.844394e-01
    outer loop
      vertex   1.820711e+00 -1.224502e-02 6.964237e-02
      vertex   1.820711e+00 -2.412004e-02 6.646972e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 2.986238e-01 -6.424325e-01
    outer loop
      vertex   1.820711e+00 -2.412004e-02 6.646972e-02
      vertex   1.820711e+00 -3.526624e-02 6.128860e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 4.053626e-01 -5.810136e-01
    outer loop
      vertex   1.820711e+00 -3.526624e-02 6.128860e-02
      vertex   1.820711e+00 -4.534682e-02 5.425556e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 4.998529e-01 -5.020386e-01
    outer loop
      vertex   1.820711e+00 -4.534682e-02 5.425556e-02
      vertex   1.820711e+00 -5.405718e-02 4.558312e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 5.792394e-01 -4.078939e-01
    outer loop
      vertex   1.820711e+00 -5.405718e-02 4.558312e-02
      vertex   1.820711e+00 -6.113414e-02 3.553332e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 6.411234e-01 -3.014241e-01
    outer loop
      vertex   1.820711e+00 -6.113414e-02 3.553332e-02
      vertex   1.820711e+00 -6.636385e-02 2.440984e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 6.836350e-01 -1.858463e-01
    outer loop
      vertex   1.820711e+00 -6.636385e-02 2.440984e-02
      vertex   1.820711e+00 -6.958828e-02 1.254877e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 7.054897e-01 -6.465294e-02
    outer loop
      vertex   1.820711e+00 -6.958828e-02 1.254877e-02
      vertex   1.820711e+00 -7.071001e-02 3.085326e-04
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 7.060270e-01 5.849400e-02
    outer loop
      vertex   1.820711e+00 -7.071001e-02 3.085326e-04
      vertex   1.820711e+00 -6.969513e-02 -1.194103e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 6.852308e-01 1.798735e-01
    outer loop
      vertex   1.820711e+00 -6.969513e-02 -1.194103e-02
      vertex   1.820711e+00 -6.657433e-02 -2.382978e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 6.437294e-01 2.958178e-01
    outer loop
      vertex   1.820711e+00 -6.657433e-02 -2.382978e-02
      vertex   1.820711e+00 -6.144190e-02 -3.499848e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 5.827768e-01 4.028236e-01
    outer loop
      vertex   1.820711e+00 -6.144190e-02 -3.499848e-02
      vertex   1.820711e+00 -5.445291e-02 -4.510965e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 5.042149e-01 4.976575e-01
    outer loop
      vertex   1.820711e+00 -5.445291e-02 -4.510965e-02
      vertex   1.820711e+00 -4.581855e-02 -5.385778e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 4.104174e-01 5.774541e-01
    outer loop
      vertex   1.820711e+00 -4.581855e-02 -5.385778e-02
      vertex   1.820711e+00 -3.579973e-02 -6.097852e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 3.042186e-01 6.398021e-01
    outer loop
      vertex   1.820711e+00 -3.579973e-02 -6.097852e-02
      vertex   1.820711e+00 -2.469917e-02 -6.625671e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 1.888274e-01 6.828176e-01
    outer loop
      vertex   1.820711e+00 -2.469917e-02 -6.625671e-02
      vertex   1.820711e+00 -1.285229e-02 -6.953286e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 6.773059e-02 7.052009e-01
    outer loop
      vertex   1.820711e+00 -1.285229e-02 -6.953286e-02
      vertex   1.820711e+00 -6.170592e-04 -7.070799e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -5.541283e-02 7.062755e-01
    outer loop
      vertex   1.820711e+00 -6.170592e-04 -7.070799e-02
      vertex   1.820711e+00 1.163682e-02 -6.974657e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -1.768819e-01 6.860091e-01
    outer loop
      vertex   1.820711e+00 1.163682e-02 -6.974657e-02
      vertex   1.820711e+00 2.353907e-02 -6.667767e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -2.930062e-01 6.450140e-01
    outer loop
      vertex   1.820711e+00 2.353907e-02 -6.667767e-02
      vertex   1.820711e+00 3.473006e-02 -6.159402e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -4.002769e-01 5.845289e-01
    outer loop
      vertex   1.820711e+00 3.473006e-02 -6.159402e-02
      vertex   1.820711e+00 4.487163e-02 -5.464922e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -4.954528e-01 5.063815e-01
    outer loop
      vertex   1.820711e+00 4.487163e-02 -5.464922e-02
      vertex   1.820711e+00 5.365734e-02 -4.605312e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -5.756578e-01 4.129331e-01
    outer loop
      vertex   1.820711e+00 5.365734e-02 -4.605312e-02
      vertex   1.820711e+00 6.082173e-02 -3.606546e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -6.384686e-01 3.070074e-01
    outer loop
      vertex   1.820711e+00 6.082173e-02 -3.606546e-02
      vertex   1.820711e+00 6.614830e-02 -2.498803e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -6.819872e-01 1.918050e-01
    outer loop
      vertex   1.820711e+00 6.614830e-02 -2.498803e-02
      vertex   1.820711e+00 6.947612e-02 -1.315556e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -7.048986e-01 7.080696e-02
    outer loop
      vertex   1.820711e+00 6.947612e-02 -1.315556e-02
      vertex   1.820711e+00 7.070462e-02 -9.255742e-04
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -7.065106e-01 -5.233060e-02
    outer loop
      vertex   1.820711e+00 7.070462e-02 -9.255742e-04
      vertex   1.820711e+00 6.979668e-02 1.133238e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -6.867744e-01 -1.738869e-01
    outer loop
      vertex   1.820711e+00 6.979668e-02 1.133238e-02
      vertex   1.820711e+00 6.677975e-02 2.324791e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -6.462863e-01 -2.901890e-01
    outer loop
      vertex   1.820711e+00 6.677975e-02 2.324791e-02
      vertex   1.820711e+00 6.174497e-02 3.446097e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -5.862699e-01 -3.977226e-01
    outer loop
      vertex   1.820711e+00 6.174497e-02 3.446097e-02
      vertex   1.820711e+00 5.484449e-02 4.463275e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -5.085385e-01 -4.932385e-01
    outer loop
      vertex   1.820711e+00 5.484449e-02 4.463275e-02
      vertex   1.820711e+00 4.628680e-02 5.345589e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -4.154410e-01 -5.738506e-01
    outer loop
      vertex   1.820711e+00 4.628680e-02 5.345589e-02
      vertex   1.820711e+00 3.633050e-02 6.066379e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -3.097903e-01 -6.371230e-01
    outer loop
      vertex   1.820711e+00 3.633050e-02 6.066379e-02
      vertex   1.820711e+00 2.527642e-02 6.603864e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -1.947789e-01 -6.811438e-01
    outer loop
      vertex   1.820711e+00 2.527642e-02 6.603864e-02
      vertex   1.820711e+00 1.345858e-02 6.941806e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal 7.057651e-01 -7.388197e-02 -7.045830e-01
    outer loop
      vertex   1.820711e+00 1.345858e-02 6.941806e-02
      vertex   1.820711e+00 1.234071e-03 7.069991e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
  facet normal -3.941867e-16 1.000000e+00 -3.941867e-16
    outer loop
      vertex   1.000000e-01 0.000000e+00 1.791421e+00
      vertex   1.820711e+00 0.000000e+00 7.071068e-02
      vertex   1.000000e-01 -5.574642e-17 1.650000e+00
    endloop
  endfacet
  facet normal -1.689285e-17 1.000000e+00 1.689285e-17
    outer loop
      vertex   1.000000e-01 -5.574642e-17 1.650000e+00
      vertex   1.820711e+00 0.000000e+00 7.071068e-02
      vertex   1.750000e+00 0.000000e+00 -5.551115e-16
    endloop
  endfacet
endsolid
```
---

## 3D-Chart-Print

This chart is a variation of the simple chart - optimized for 3D printing

3d-chart-print is a two part chart:
- top is a stencil 0.1mm that is laser cut
- bottom is a 3D printed part

the radius of the cone is 1.75mm, making the diameter of the projected chart 3.5mm - same idea a before, any point inside the chart can be on the top surface, which is the reference distance while any point at the same radius in the opened area is at a depth equal with its radius (provided the chart is flat to the camera).

The flatness of the chart is ensured by adjusting the chart until the outer ring has all points at the same depth.

[View Chart](https://3dviewer.net/#model=https://github.com/serg696f/Depth-Metrology/blob/main/3d-chart-print-complex.stp)

---

## 3D-Chart-Print-Complex

This chart is designed to project two surfaces - depth patterns - one in increasing depth, one in decreasing depth. At any radius, the openings compared to the closed areas are at 2*R depth (provided the chart is flat to the camera).

The flatness of the chart is ensured by adjusting the chart until the outer ring has all points at the same depth.




