cmake_minimum_required(VERSION 3.27)
project(Scooters)

set(CMAKE_CXX_STANDARD 17)

add_executable(Scooters
        Controller.h
        app.cpp
        Controller.cpp
        CSVFileRepo.h
        CSVFileRepo.cpp
        Domain.h
        Domain.cpp
        InMemoryRepo.h
        InMemoryRepo.cpp
        Repository.h
        UI.h
        UI.cpp
        Controller.cpp
)
