# SquarerFive
Various stuff relating to procedural universe generation

## 3D and Rendering
- Generating Planets and terrain using Signed-Distance Fields [link] - Atmosphere shader by SkyTheDragon
- ![Current progress](https://media.discordapp.net/attachments/563601152885653533/776226747313815562/unknown.png?width=678&height=480)
- [![Raymarched SDF](http://img.youtube.com/vi/-yZO6COt8u0/0.jpg)](http://www.youtube.com/watch?v=-yZO6COt8u0)
- Planet generation using Voxels: (I've open sourced some of this in my PlanetSphericalProjection repository)
- ![Using Voxels](https://media.discordapp.net/attachments/532770468277780510/757815349289812098/unknown.png)


## Procedural Generation
### Meshing types:
  - Marching Cubes - GPU Acceleration if possible
  - Manifold Dual Contouring
  - Surface Nets
  
### Foliage Generation:
  - L-Systems http://paulbourke.net/fractals/lsys/

## Universe Rendering
- Camera relative hierarchical coordinate system  - [reference 1](https://dexyfex.com/2016/07/11/galaxia-the-basics-coordinates/)
- Galaxy Rendering - Currently I have this rendering in a seperate pass where it is downsampled, additionally it isn't rendered in world space.


![My current galaxy renderer](https://pbs.twimg.com/media/EkXvb7wUcAEc62Z?format=png&name=900x900)
