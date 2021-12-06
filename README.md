# Polar_coordinate_incrementor
When changing from Cartesian to polar coordinates, this script makes the A axis increment consecutively instead of always resetting to zero.
This script was intended to be used on a set of cnc coordinates that had used the x, y, and z axis and convert it to use x, y and A for a rotational axis for making items such as gunstocks or table legs. The conversion created a coordinate system that ranged from 0 to 360, but with each rotation turned the axis from the 360 degree mark backwards to 0 degrees as opposed to continuing to increment along its trajectory to the next rotation. 
This script fixes this bug by incrementing each rotation into the next rotation and never allowing the A axis to move "backwards".
This script was written for Microsoft Excel where I had done the Cartesian to Polar conversion. It was written to work on the column within a spreadsheet that contains the "A" axis coordinates. 
