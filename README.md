# Introduction 
This is a tiny renderder used in paper 

An, L., Ren, J., Yu, T., Hai, T., Jia, Y., &Liu, Y. Three-dimensional surface motion capture of multiple freely moving pigs using MAMMAL. *biorxiv* (2022).

This renderer could render textured mesh, monocolor mesh, vertex-colored mesh, and provides a solution for skeleton rendering. 

# Usage 
After cloning the repository, put `pig_render/` to your own workspace, and follow `demo_gl.py`. 

# Dependencies 
You should install glfw, OpenGL, glm by 
```shell
pip install PyOpenGL
pip install pyGLM
pip install glfw
```
Note that, you should `pip install pyGLM` for `glm` lib not `pip install glm`. 

