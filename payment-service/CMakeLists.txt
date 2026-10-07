add_executable(payment-service
    src/main.cpp)
target_link_libraries(payment-service PRIVATE userver::postgresql)
rsoi_target_defaults(payment-service)

add_subdirectory(tests)
