project(HW3)

include_directories(../deps)
include_directories(OpenCV_INCLUDE_DIRS)

add_executable(HW3 main.cpp rasterizer.hpp rasterizer.cpp global.hpp Triangle.hpp Triangle.cpp Texture.hpp Texture.cpp Shader.hpp OBJ_Loader.h)
target_link_libraries(HW3 ${OpenCV_LIBRARIES})
