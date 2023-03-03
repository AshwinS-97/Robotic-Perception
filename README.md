
## Dimension Estimation by Affine rectification 
Given an image of a tetrahedron and a cuboid on a standard A4 sheet of paper (20.8cm x 29.6cm), we can extract the length of the objects and the angle of the vertices at their faces.

All the pixel coordinates are extracted using https://pixspy.com tool manually.

![affine_rectified](/res/perspective_transformation.jpg?raw=true "Screenshot")

By affine rectification(wrt to A4 sheet plane) all the ratios of length in that plane remains preserved.

The results are:
```
Angle of paper @ vertex a             = 90.0  (degrees)
Angle  of tetrahedron face @ vertex i = 65.8  (degrees)
Length of tetrahedron                 = 9.7   (cm)
Angle of cube face @ vertex e         = 86.4  (degrees)
Length of Cube                        = 8.3   (cm)
``` 
