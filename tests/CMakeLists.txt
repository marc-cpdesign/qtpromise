find_package(QT NAMES Qt6 Qt5 REQUIRED COMPONENTS Concurrent Test)
find_package(Qt${QT_VERSION_MAJOR} REQUIRED COMPONENTS Concurrent Test)

include(QtPromiseAddTest)

add_subdirectory(auto)
