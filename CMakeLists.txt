cmake_minimum_required(VERSION 3.7)
project(neat)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_SYSTEM_NAME Windows)

set(SOURCE_FILES
        cpp/src/Backup.cpp
        cpp/src/Backup.hpp
        cpp/src/Genotype.hpp
        cpp/src/main.cpp
        cpp/src/MutationManager.cpp
        cpp/src/MutationManager.hh
        cpp/src/Mutator.hpp
        cpp/src/NeatEngine.hpp
        cpp/src/NeatEngineException.cpp
        cpp/src/NeatEngineException.hh
        cpp/src/NeatPool.hpp
        cpp/src/Operator.hpp
        cpp/src/Phenotype.hpp
        cpp/src/Population.hpp)

add_executable(neat ${SOURCE_FILES})