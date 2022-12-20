## Intro

This is a procedural road system made using Houdini's standard toolset and quite a few custom tools written in VEX and Python. It only takes the terrain and basic 
curves for roads, and it will output the following assets:
  - modified terrain (fill/erode the terrain to accquire a road base shape)
  - road mesh (with intersections, procedurally UVed)
  - decals for intersections (helps to have a better visual at intersections)
  - decals for tire marks (yes, tire marks)
  - point cloud of road crack decals (cracks, potholes, etc...)
