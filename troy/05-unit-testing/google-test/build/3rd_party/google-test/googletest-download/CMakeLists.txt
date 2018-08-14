cmake_minimum_required(VERSION 2.8.2)

project(google-download NONE)

include(ExternalProject)

ExternalProject_Add(googletest
  GIT_REPOSITORY    https://github.com/google/googletest.git
  GIT_TAG           master
  SOURCE_DIR        "/home/warproxxx/Desktop/Practise/troy/05-unit-testing/google-test/build/googletest-src"
  BINARY_DIR        "/home/warproxxx/Desktop/Practise/troy/05-unit-testing/google-test/build/googletest-build"
  CONFIGURE_COMMAND ""
  BUILD_COMMAND     ""
  INSTALL_COMMAND   ""
  TEST_COMMAND      ""
)
