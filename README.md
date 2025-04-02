This project is a basic raytracing renderer, it uses GLSL shaders to simulate a ray of light for each pixel. Every frame, a random position within the pixel is chosen to cast a ray towards. The color obtained is averaged out over several frames.
Most of the shading code can be found inside the viewer/shaders/gpgpu_fullrt.comp file.

To build, call make in the base directory, to execute call `./viewer/myViewer`. OpenGL is required.

A few 3D models and textures are included, some of the textures lack normal maps.
Once the viewer is launched, you can play around with the parameters, and you can change the model with file -> Open scene. You can change the floor texture with file -> Load texture.
