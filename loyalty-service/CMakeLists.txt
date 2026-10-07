add_executable(loyalty-service
    src/main.cpp)
target_link_libraries(loyalty-service PRIVATE userver::postgresql)
rsoi_target_defaults(loyalty-service)

add_subdirectory(tests)
