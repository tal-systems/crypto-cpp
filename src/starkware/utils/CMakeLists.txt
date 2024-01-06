add_executable(math_test math_test.cc)
target_link_libraries(math_test GTest::GTest pthread)
add_test(math_test math_test)

add_executable(prng_test prng_test.cc)
target_link_libraries(prng_test GTest::GTest pthread)
add_test(prng_test prng_test)
