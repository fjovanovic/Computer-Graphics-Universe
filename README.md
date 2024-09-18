# Computer Graphics Universe
The project was created for the Computer Graphics course using the [OpenGL](https://learnopengl.com/) specification.  
The scene displays models of the Sun, Moon and Mars.  
The models of a rocket and an astronaut are placed in boxes where the effects of [Blending-a](https://learnopengl.com/Advanced-OpenGL/Blending) and [Face culling-a](https://learnopengl.com/Advanced-OpenGL/Face-culling) have been applied.


## Interaction
  - `W`, `A`, `S`, `D` - Moving on the scene
  - `F1` - Menu (GUI)
  - `F1->HDR` - HDR effect activation
  - `F1->Bloom` - Bloom effect activation
  - `B` - Change between Phong and Blinn-Phong model (it can be seen only on the metal texture under the box)


## Resources
  - Just a few websites for models: [Turbosquid](https://www.turbosquid.com/Search/3D-Models), [Sketchfab](https://sketchfab.com/3d-models), [Artec3D](https://www.artec3d.com/3d-models), [CGtrader](https://www.cgtrader.com/3d-models)
  - Models
    - [Astronaut](https://sketchfab.com/3d-models/astronaut-obj-sva-sva-23512-0c780fc92a1c420bb2286cc19a400034) ([`Sketchfab`](https://sketchfab.com/3d-models))
    - [Rocket](https://www.turbosquid.com/3d-models/3d-toy-rocket-4k-free-1973134) ([`Turbosquid`](https://www.turbosquid.com/Search/3D-Models))
    - [Mars](https://www.turbosquid.com/3d-models/realistic-mars-photorealistic-2k-3d-1277433) ([`Turbosquid`](https://www.turbosquid.com/Search/3D-Models))
    - [Earth](https://www.turbosquid.com/3d-models/earth-max-free/1016431) ([`Turbosquid`](https://www.turbosquid.com/Search/3D-Models))
    - [Sun](https://sketchfab.com/3d-models/the-sun-0d28aa65eb174d948c2716d73e8fd3bd) ([`Sketchfab`](https://sketchfab.com/3d-models))
  - Textures:
    - Skybox (~link~)
    - The rest was built in [Photoshop-u](https://www.adobe.com/products/photoshop.html)


## Problems with models
  - If the model is loading but the texture is not, check if the `.mtl` file is present
  - Check if the texture is located under the mapping coordinates `map_Kd texture_name.ext`
  - Verify that the correct textures are mapped to the appropriate coordinates
  - Check the paths to the textures, as relative paths are based on the location of the `.mtl` file


## Lectures implementation
- Required lectures:
  - [x] weeks 1-8
  - [x] [Blending](https://learnopengl.com/Advanced-OpenGL/Blending) (Rocket model in the box)
  - [x] [Face culling](https://learnopengl.com/Advanced-OpenGL/Face-culling) (Astronaut model in the box)
  - [x] [Advanced lighting](https://learnopengl.com/Advanced-Lighting/Advanced-Lighting)
- Required lectures in group A:
  - [ ] [Framebuffers](https://learnopengl.com/Advanced-OpenGL/Framebuffers)
  - [x] [Cubemaps](https://learnopengl.com/Advanced-OpenGL/Cubemaps)
  - [ ] [Instancing](https://learnopengl.com/Advanced-OpenGL/Instancing)
  - [ ] [Anti Aliasing](https://learnopengl.com/Advanced-OpenGL/Anti-Aliasing)
- Required lectures in group B:
  - [ ] [Point shadows](https://learnopengl.com/Advanced-Lighting/Shadows/Point-Shadows)
  - [ ] [Normal mapping](https://learnopengl.com/Advanced-Lighting/Normal-Mapping), [Parallax mapping](https://learnopengl.com/Advanced-Lighting/Parallax-Mapping)
  - [x] [HDR](https://learnopengl.com/Advanced-Lighting/HDR), [Bloom](https://learnopengl.com/Advanced-Lighting/Bloom)
  - [ ] [Deffered Shading](https://learnopengl.com/Advanced-Lighting/Deferred-Shading)
  - [ ] [SSAO](https://learnopengl.com/Advanced-Lighting/SSAO)

- If project includes the required lectures (weeks 1-8, Blending, Face Culling, Advanced Lighting), the maximum number of points that can be earned is 15.
- If project includes the required lectures + 1 lecture from group A, the maximum number of points that can be earned is 25
- If project includes the required lectures + 1 lecture from group A + 1 lecture from group B, the maximum number of points that can be earned is 35
- If project includes the required lectures + 1 lecture from group A + 2 lectures from group B, the maximum number of points that can be earned is 40 (5 is bonus)


## Notes for students when creating the project
- All lighting in the scene should be calculated using the Blinn-Phong model [Advanced lighting](https://learnopengl.com/Advanced-Lighting/Advanced-Lighting)
- It's enought for the project to have 1 type of [Blending](https://learnopengl.com/Advanced-OpenGL/Blending) (Discard or blend)
- There must be a commit history on GitHub for the project to be reviewed
- The use of `.obj` models and textures from the main [repository](https://github.com/matf-racunarska-grafika/LearnOpenGL) is not permitted in the project