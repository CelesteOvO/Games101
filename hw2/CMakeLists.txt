project(HW2)

include_directories(../deps)
include_directories(OpenCV_INCLUDE_DIRS)

add_executable(HW2 main.cpp rasterizer.hpp rasterizer.cpp global.hpp Triangle.hpp Triangle.cpp)
target_link_libraries(HW2 ${OpenCV_LIBRARIES})
