# CMakeList.txt : CMake project for Assignment1_Deadly_corp, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (Assignment1_Deadly_corp "Assignment1_Deadly_corp.cpp" "Assignment1_Deadly_corp.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Assignment1_Deadly_corp PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
