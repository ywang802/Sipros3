project(sipros_openmp)

set(CMAKE_CXX_FLAGS "-fopenmp")

add_executable(sipros_openmp ${flags} ptm.cpp ptm.h peptide.cpp proteindatabase.cpp tokenvector.cpp tokenvector.h  ms2scan.cpp ms2scanvector.cpp main.cpp directoryStructure.cpp directoryStructure.h proNovoConfig.cpp proNovoConfig.h isotopologue.cpp isotopologue.h)


