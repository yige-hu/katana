generate_cython_source(_pyarrow_wrappers DEPENDS)
add_cython_module(_pyarrow_wrappers ${CMAKE_CURRENT_BINARY_DIR}/_pyarrow_wrappers.pyx)
