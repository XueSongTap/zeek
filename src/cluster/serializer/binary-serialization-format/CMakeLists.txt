zeek_add_plugin(
    Zeek Zeek_Binary_Serializer
    INCLUDE_DIRS ${CMAKE_CURRENT_SOURCE_DIR} ${CMAKE_CURRENT_BINARY_DIR}
    SOURCES Plugin.cc Serializer.cc)
