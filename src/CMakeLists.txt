add_executable(test_cc test.cc)
add_executable(test_c test.c)
add_executable(test_f90 test.f90)

add_test(test_cc test_cc)
add_test(test_c test_c)
add_test(test_f90 test_f90)
