#2d-opengl-renderer
Minimal, fast OpenGL renderer for 2D sprites

![Screenshot 1](https://raw.githubusercontent.com/Tchayen/2d_opengl_renderer/master/screenshot1.png)

Loads one texture and uses it to render several sprites multiple thousand times each. Allowing for up to 20k on mobile Intel GPU in 60 fps (see [Screenshot 2](https://raw.githubusercontent.com/Tchayen/2d_opengl_renderer/master/screenshot2.png)).

#TODO:
- [x] basic logic of buffers etc.
- [x] updating vertex buffer, allowing to move objects

#License and dependencies
MIT license (see file LICENSE for copy).
Project uses GLFW, GLEW and SOIL but non of them are included here. [Fruit icons](http://www.flaticon.com/packs/gastronomy-set).
