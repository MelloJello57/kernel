# CMakeLists.txt

cmake_minimum_required (2.8)						# Set the required version of CMake to complete the build
project (kernel)							# Tell CMake the name of the project

# Set required build flags
set(CMAKE_CXX_FLAGS "-ffreestanding -fno-rtti -O2")			# Tell compiler we need it to be freestanding and we don't need a runtime environment

