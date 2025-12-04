add_avr_executable(template main.c)

target_include_directories(template.elf PRIVATE ${CMAKE_SOURCE_DIR}/include)
