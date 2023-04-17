project(HW4)

include_directories(../deps)
include_directories(OpenCV_INCLUDE_DIRS)

add_executable(HW4 main.cpp)

target_link_libraries(HW4 ${OpenCV_LIBRARIES})
