# Gift Wrapping in Unity C# (Animated)
- Gift Wrapping 3D Algo Visualization in Unity.
- Generate Random points in sphere, and run the giftwrapping to create a mesh.
- Created using Psudo Code Reference: https://www.cs.jhu.edu/~misha/Spring16/09.pdf Page 21-24
- Uses Gizmo to draw and visualize output.
- Uses a simple co-routine implementation for the Algo Visualize.

https://github.com/KhiewJianBin/GiftWrappingAnimate/assets/5699978/90efc10b-d045-44b0-8327-8be37e7b9d2b

--------------

## Usage
1. Open in Unity Editor
2. Open Scene [GiftWrappingAnimate]
3. Play 

Note: The outputs is using OnDrawGizmo - so make sure Gizmo is enabled on the unity Editor Scene/Game Window

## TODO
  - Normals
  - Better Step Animation
  - Considering using async task instead of co-routines
 
## Issues with Algo
 1. Some points generated can cause additional triangles to be form inside the convex hull, not sure why
 2. If some points are co-planar, some faces might not be generated
 

if any one has ideas on how to solve issue 1. i would love to hear your ideas, please contact me: khiewbin@gmail.com
