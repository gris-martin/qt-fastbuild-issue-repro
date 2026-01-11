cmake_minimum_required(VERSION 4.2)

project(FastBuildQtExample LANGUAGES CXX)

add_executable(ExampleApp main.cpp)

find_package(Qt6 COMPONENTS Widgets REQUIRED)
target_link_libraries(ExampleApp PRIVATE
    Qt6::Core
    Qt6::Gui
    Qt6::Widgets)
