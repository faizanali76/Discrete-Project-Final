cmake_minimum_required(VERSION 3.10)
project(DiscreteFinalProject)

set(CMAKE_CXX_STANDARD 17)

# Include all source files
set(SOURCE_FILES
    main.cpp
    University.cpp
    University.h
    Student.cpp
    Student.h
    Faculty.cpp
    Faculty.h
    Room.cpp
    Room.h
    Course.cpp
    Course.h
    Scheduler.cpp
    Scheduler.h
    ConsistencyChecker.cpp
    ConsistencyChecker.h
    TestingModule.cpp
    TestingModule.h
    # Interfaces for other modules (headers only for now)
    EfficiencyModule.h
    Functions.h
    GroupManager.h
    InferenceEngine.h
    PrerequisiteChecker.h
    ProofModule.h
    Relations.h
    SetOperations.h
)

add_executable(DiscreteFinalProject ${SOURCE_FILES})
