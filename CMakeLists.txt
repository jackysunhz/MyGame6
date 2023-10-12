# This cmake file does not actually build anything. It is only for CLion to understand imports.

cmake_minimum_required(VERSION 3.21)
project(MyGame6)

set(CMAKE_CXX_STANDARD 17)

include_directories(
        ../nest-libs/windows/SDL2/include
        ../nest-libs/windows/freetype/include
        ../nest-libs/windows/glm/include
        ../nest-libs/windows/harfbuzz/include
        ../nest-libs/windows/libogg/include
        ../nest-libs/windows/libopus/include
        ../nest-libs/windows/libopusenc/include
        ../nest-libs/windows/libpng/include
        ../nest-libs/windows/opus-tools/include
        ../nest-libs/windows/opusfile/include
        ../nest-libs/windows/zlib/include
)

add_executable(MyGame6
        ColorProgram.cpp
        ColorProgram.hpp
        ColorTextureProgram.cpp
        ColorTextureProgram.hpp
        data_path.cpp
        data_path.hpp
        DrawLines.cpp
        DrawLines.hpp
        Game.cpp 
        Game.hpp
        GL.cpp
        GL.hpp
        gl_compile_program.cpp
        gl_compile_program.hpp
        gl_errors.hpp
        glcorearb.h
        LitColorTextureProgram.cpp
        LitColorTextureProgram.hpp
        Load.cpp
        Load.hpp
        load_save_png.cpp
        load_save_png.hpp
        load_opus.cpp
        load_opus.hpp
        load_wav.cpp
        load_wav.hpp
        Mesh.cpp
        Mesh.hpp
        Mode.cpp
        Mode.hpp
        PathFont.cpp
        PathFont.hpp
        PathFont-font.cpp
        PlayMode.cpp
        PlayMode.hpp
        read_write_chunk.hpp
        Scene.cpp
        Scene.hpp
        show-meshes.cpp
        show-scene.cpp
        ShowMeshesMode.cpp
        ShowMeshesMode.hpp
        ShowSceneMode.cpp
        ShowSceneMode.hpp
        ShowMeshesProgram.cpp
        ShowMeshesProgram.hpp
        ShowSceneProgram.cpp
        ShowSceneProgram.hpp
        Sound.cpp
        Sound.hpp
        Connection.cpp
        Connection.hpp)
