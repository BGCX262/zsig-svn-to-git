#
# Src-level CMakeLists.txt for ZSIG library examples
#
set(EX1_SRCS example_zpol.cc)
set(EX2_SRCS example_zproj.cc)
set(EX3_SRCS example_sig.cc)
set(EX4_SRCS example_mesh.cc)
add_executable(ex1 ${EX1_SRCS})
add_executable(ex2 ${EX2_SRCS})
add_executable(ex3 ${EX3_SRCS})
add_executable(ex4 ${EX4_SRCS})

set(APP1_SRCS app_compute_signature.cc)
set(APP2_SRCS app_paint_signature.cc)
add_executable(compute_signature ${APP1_SRCS})
add_executable(paint_signature ${APP2_SRCS})
