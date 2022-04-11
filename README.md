# raytracer

Here is my attempt at a small-ish real time ray-tracer using openGL 4.3. This is obviously not done so expect some progress in the comming weeks/months to this project.

Here is a picture of what the raytracer currently does:
![image](https://user-images.githubusercontent.com/62178977/162789246-bd803e01-73f3-41ff-8927-6ea9204d446d.png)

# Compiling on Linux:

the Compilation of this project is quite easy on linux:

First off, download the package for "glfw3" and any that might be missing (see compilation command): 

second off, install my configuration of glad which you can find here:
> https://glad.dav1d.de/generated/tmp7s7wppfaglad/

finaly in your terminal type in the project directory:
> g++ main.cpp glad/glad.c -lglfw -lGL -lX11 -lpthread -lXrandr -lXi -ldl -o executable


# controls:

> W : Forward motion

> A : Left motion

> S : Backward motion

> D : Right motion

> N : Visualize normals

> TAB : Free Mouse

> EXIT: exit the application

# To-Do list:

>~~add cubes~~ DONE

>~~add distance testing~~ DONE

>~~add shadow rays~~ DONE

>~~add shadow shading~~ DONE

>set up acceleration structure

>add voxel objects

>octree implementation on the voxel objects or some form of RLE compression

