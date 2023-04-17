project(HW1)

include_directories(../deps)
include_directories(OpenCV_INCLUDE_DIRS)

add_executable(HW1 main.cpp rasterizer.hpp rasterizer.cpp Triangle.hpp Triangle.cpp)
target_link_libraries(HW1 ${OpenCV_LIBRARIES})
