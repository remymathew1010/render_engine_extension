copy files mtlshader.frag, mtlshader.vert and renderapp.cpp into skeleton folder, it should replace the existing files
then agian copy mtlshader.cpp to common directory to replace it with he existing file

the four codes files above was change to satisfy he requirements

Now i assume you have already set the following openGL files in the system
find_package(OpenGL REQUIRED)
find_package (GLEW REQUIRED)
find_package(glfw3 3.3 REQUIRED)
find_package(glm REQUIRED) 
as found in cmakelist.txt
then do the following to build the files; 
cmake -S . -B build

this will generate a make files in the build folder
 now run the following command
 make
 
 it should generate the file named skeleton
 
 to run the app use the following command
 ./Skeleton
