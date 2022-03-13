
add_executable(chapter2Test
    test_chapter2.cpp
)

include(GoogleTest)

target_link_libraries(chapter2Test gtest_main)

gtest_discover_tests(
    chapter2Test
)
