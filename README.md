urdfdom_headers
===============
This fork adds a constraint description based on constraint elements representing cut joints or links to describe closed loops without breaking surrounding packages.
The structure is based on the joint elmeent, but adding a child_frame origin and a child axis for a description of the two cut element frames. The type defines the structure of the constraint by giving the name of the cut element:

  UNKNOWN     unknown type
  
  REVOLUTE    1-dof rotation joint
  
  PRISMATIC   prismatic joint
  
  UNIVERSAL   universal joint
  
  SPHERICAL   spherical joint
  
  PLANAR      planar joint
  
  LINK        link
  
  More might be added.
  
The description of the constraints follows the usual modelling techniques for parallel robots.

The URDF (U-Robot Description Format) headers provides core data structure headers for URDF.

For now, the details of the URDF specifications reside on http://ros.org/wiki/urdf
