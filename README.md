// spinning_cube.cpp
// A simple spinning 3D cube using OpenGL + GLUT (freeglut)
//
// BUILD (Linux):
//   sudo apt-get install freeglut3-dev
//   g++ spinning_cube.cpp -o spinning_cube -lGL -lGLU -lglut
//   ./spinning_cube
//
// BUILD (macOS):
//   g++ spinning_cube.cpp -o spinning_cube -framework OpenGL -framework GLUT
//   ./spinning_cube
//   (You may see deprecation warnings on newer macOS — GLUT still works.)
//
// BUILD (Windows, MinGW + freeglut):
//   g++ spinning_cube.cpp -o spinning_cube.exe -lfreeglut -lopengl32 -lglu32
//   spinning_cube.exe
