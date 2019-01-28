The nose cone for this directory is based on the Tangent Ogive Formula given
in: https://en.wikipedia.org/wiki/Nose_cone_design . The Formula produces a curve, and it is revolved around an axis to produce a nose cone.

Calculations are in the LibreOffice Calc file nose-cone.ods.

An export of the produced points from the Formula are given in ogive-points.csv.

A Salome-Meca Geometry file of the nose cone produced by revolving the points
about the x-axis is given in noseCone.hdf. 

An image of the vectorized plotted curve from the points is ogive-curve.png.

A stl file of the nose cone (surface of revolution) is in Revolution_1.stl.

CompleteNoseCone.step and CompleteNoseCone.stl includes a bulkhead along with the nose cone. This shape can be 3-D Printed. 

Meshing is Done in Salome-Meca:

Use the tutorials/incompressible/simpleFoam/pipeCyclic/constant/polyMesh/boundary for an example of a 3D-Mesh boundary
and /incompressible/simpleFoam/airFoail2D/constant/polyMesh for an example of flow over a surface

The icoFoam solver results are in:


In Post Processing in Paraview Do:

https://www.youtube.com/watch?v=J944HOj_4b0   [How to calculate aerodynamic forces with Paraview]

https://en.wikipedia.org/wiki/Drag_(physics)#Aerodynamics  [Wikipedia - Drag_(physics)]
