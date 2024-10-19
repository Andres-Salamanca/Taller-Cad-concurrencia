cmake_minimum_required(VERSION 3.19)  # CMake version check
project(TallerCad)               


set(CMAKE_C_FLAGS "-fopenmp")
set(CMAKE_C_FLAGS_RELEASE "-O3")

# Add executable target with source files listed in SOURCE_FILES variable
add_executable(matrizFxC matrixFxC.c modulo.c)
add_executable(matrizFxT matrixFxT.c modulo.c)
add_executable(mmPosix MM_posix.c modulo.c)


