add_executable(gateway-service
    src/main.cpp)
target_link_libraries(gateway-service PRIVATE userver::core)
rsoi_target_defaults(gateway-service)

add_subdirectory(tests)
