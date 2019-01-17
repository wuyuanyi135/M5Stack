file(GLOB_RECURSE SRC src/*.cpp src/*.c)

set(COMPONENT_SRCS ${SRC})

set(COMPONENT_ADD_INCLUDEDIRS
        src
  )

set(COMPONENT_REQUIRES arduino-esp32)

# add_definitions(-DESP32)
register_component()
