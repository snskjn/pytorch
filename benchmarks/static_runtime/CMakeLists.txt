list(APPEND STATIC_RUNTIME_BENCHMARK_SRCS ${CMAKE_CURRENT_SOURCE_DIR}/deep_wide_pt_bench.cc)
list(APPEND STATIC_RUNTIME_BENCHMARK_SRCS ${CMAKE_CURRENT_SOURCE_DIR}/deep_wide_pt.cc)
set(STATIC_RUNTIME_BENCHMARK_SRCS ${STATIC_RUNTIME_BENCHMARK_SRCS} PARENT_SCOPE)
