
cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "SHT2x.cpp"
                       INCLUDE_DIRS "." 
                       REQUIRES arduino)

