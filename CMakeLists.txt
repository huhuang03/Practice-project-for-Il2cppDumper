project(il2cpp-dumper)

file(GLOB_RECURSE SRC "src/*.cc")

add_executable(il2cp-dumper ${SRC})