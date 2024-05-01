cmake_minimum_required(VERSION 3.20)
project(tst C)

cmake_host_system_information(RESULT HAVE_FPU QUERY HAS_FPU)
message("HAVE_FPU: ${HAVE_FPU}")

