add_executable(ut_Evaluator ut_Evaluator.cpp)
target_link_libraries(ut_Evaluator Evaluator gtest_main)
gtest_discover_tests(ut_Evaluator)
