add_library(lua STATIC
    lua.c
    lauxlib.c
    lualib.c
)

target_include_directories(lua PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
