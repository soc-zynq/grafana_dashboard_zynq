# Create a library called "grafana_dashboard_zynq"
add_library(grafana_dashboard_zynq_lib grafana_dashboard_zynq.cpp)

# Specify include directories for the library
target_include_directories(grafana_dashboard_zynq_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
