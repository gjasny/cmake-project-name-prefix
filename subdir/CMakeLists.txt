project(Bar CXX)

#set_property(GLOBAL PROPERTY USE_FOLDERS TRUE)

add_library(bar bar.cpp)
add_library(baz bar.cpp)

set_target_properties(bar PROPERTIES FOLDER asdf)
