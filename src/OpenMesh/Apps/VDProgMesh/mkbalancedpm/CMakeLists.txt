include (ACGCommon)

include_directories (
  ../../../..
  ${CMAKE_CURRENT_SOURCE_DIR}
)

acg_add_executable (mkbalancedpm mkbalancedpm.cc)

target_link_libraries (mkbalancedpm
  OpenMeshCore
  OpenMeshTools
)

