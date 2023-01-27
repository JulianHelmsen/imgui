cmake_minimum_required(VERSION 3.4...3.20 FATAL_ERROR)

target_sources(scrimed PUBLIC
    backends/imgui_impl_glfw.cpp
    backends/imgui_impl_opengl3.cpp
    imgui.cpp
    imgui_draw.cpp
    imgui_tables.cpp
    imgui_widgets.cpp
    imgui_demo.cpp
)

