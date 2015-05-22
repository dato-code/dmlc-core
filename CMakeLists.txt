project(dmlc-core)
include(ExternalProject)

ExternalProject_Add(ex_dmlc
  PREFIX ${CMAKE_SOURCE_DIR}/src/dmlc-core
  GIT_REPOSITORY https://github.com/dato-code/dmlc-core
  GIT_TAG redefine_macro
  CONFIGURE_COMMAND ""
  BUILD_COMMAND ""
  INSTALL_COMMAND ""
)




