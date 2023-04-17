project(HW5)

include_directories(../deps)
include_directories(OpenCV_INCLUDE_DIRS)

add_executable(HW5 main.cpp Object.hpp Vector.hpp Sphere.hpp global.hpp Triangle.hpp Scene.cpp Scene.hpp Light.hpp Renderer.cpp)