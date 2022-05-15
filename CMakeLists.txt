# Embed CA, certificate & key directly into binary
idf_component_register(SRCS "MQTTEventHandler.cpp"
                    INCLUDE_DIRS "."
                    REQUIRES cpp-esp-e-handler mqtt)


set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
