add_executable(reservation-service
    src/main.cpp)
target_link_libraries(reservation-service PRIVATE userver::postgresql)
rsoi_target_defaults(reservation-service)

add_subdirectory(tests)
