link_directories(${LIB_DIR})

message(STATUS "LIB_DIR: " ${LIB_DIR})

link_libraries(tgcreator
                util
                sensors
                core    
                terrain 
                tgOpenGLSupport
		yaml-cpp
		TensegrityModel)

add_executable(App3BarTraditional1
    threeBarModel.cpp
    App3BarTraditional.cpp
) 