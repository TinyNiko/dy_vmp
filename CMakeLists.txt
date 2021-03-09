cmake_minimum_required(VERSION 3.2)

PROJECT(dy_vmp)

INCLUDE_DIRECTORIES(
include
)

AUX_SOURCE_DIRECTORY(src DIR_SRCS)


SET(dy_vmp
${DIR_SRCS}
)


ADD_EXECUTABLE(${PROJECT_NAME} ${dy_vmp})
