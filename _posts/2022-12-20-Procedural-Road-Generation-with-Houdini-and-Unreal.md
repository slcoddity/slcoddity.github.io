## Intro

This is a procedural road generator made using Houdini's standard sop nodes and quite a few custom tools written in VEX. It only takes a heightfield and basic 
curves for roads, and it will output the following assets:
  - modified terrain (fill/erode the terrain to accquire a road base shape)
  - road mesh (with intersections, autometically generated and UVed)
  - decals for intersections (helps to have a better visual at intersections)
  - decals for tire marks (yes, tire marks)
  - point cloud of road crack decals (cracks, potholes, etc...)
  - traffic control data (rules for roads and intersections)

This is the overall graph of the tool, I'd like to have everything workflow-associated on the same page, so that I can easily jump between nodes and make changes.   
![screenshot](https://github.com/slcoddity/slcoddity.github.io/blob/master/assets/Screenshot%202022-12-21%20111310.png?raw=true)

Some screen shots of the results:
![screenshot]()
![screenshot]()
![screenshot]()

## Base Shape

## Roads

## Intersections

## Decals
