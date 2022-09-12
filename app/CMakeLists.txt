# main
add_executable(main "main.cpp")
target_link_libraries(main PUBLIC
    spdlog::spdlog
    OpenGL::GL
    glad
    glfw
    imgui
    imgui_glfw_opengl3
)