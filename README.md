# rtnextweek
https://raytracing.github.io/books/RayTracingTheNextWeek.html

Setup cmake (and refresh it if you modify CMakeLists.txt)
cmake -B build

Build
cmake --build build --config release

Run (render)
Mac/Linux
build/theNextWeek > image.ppm
Windows
build\Release\theNextWeek.exe > image.ppm