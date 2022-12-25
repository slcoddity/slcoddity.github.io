## Intro

This is a procedural road generator made using Houdini's standard sop nodes and quite a few custom nodes written in VEX. It only takes a heightfield and basic 
curves for roads, and it will output the following assets:
  - modified terrain (fill/erode the terrain to accquire a road base shape)
  - road mesh (with intersections, autometically generated and UVed)
  - decals for intersections (helps to have a better visual at intersections)
  - decals for tire marks (yes, tire marks)
  - point cloud of road crack decals (cracks, potholes, etc...)
  - point cloud of road crack grass (uv space to world space conversion)
  - traffic control data (rules for roads and intersections)

This is the overall graph of the tool, I'd like to have everything workflow-associated on the same page, so that I can easily jump between nodes and make changes.   
![screenshot](https://github.com/slcoddity/slcoddity.github.io/blob/master/assets/Screenshot%202022-12-21%20111310.png?raw=true)

Some screen shots of the results:

![screenshot](https://github.com/slcoddity/slcoddity.github.io/blob/master/assets/Screenshot%202022-12-25%20203830.png?raw=true)
![screenshot](https://github.com/slcoddity/slcoddity.github.io/blob/master/assets/Screenshot%202022-12-25%20204205.png?raw=true)
![screenshot](https://github.com/slcoddity/slcoddity.github.io/blob/master/assets/Screenshot%202022-12-25%20204304.png?raw=true)
![screenshot](https://github.com/slcoddity/slcoddity.github.io/blob/master/assets/Screenshot%202022-12-25%20204437.png?raw=true)
![screenshot](https://github.com/slcoddity/slcoddity.github.io/blob/master/assets/Screenshot%202022-12-25%20205234.png?raw=true)


## Base Shape
I wanted to build the road in a way that could represent the real construction process, so the first step would be building the base of the road, which is done on the terrain. Basically we want to smooth out the ground where the road will be, and make the base slightly higher in the middle. We do this by generating a road base polygon and mapping its shape onto the terrain. Here I have attached the steps of how the polygon is generated from a curve.         


## Roads

## Intersections

## Decals
