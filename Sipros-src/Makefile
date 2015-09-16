CC=	g++
CFLAGS=	-Wall -O2 -fopenmp
Sipros_openmp: ptm.cpp ptm.h peptide.cpp proteindatabase.cpp tokenvector.cpp tokenvector.h  ms2scan.h  ms2scan.cpp ms2scanvector.h  ms2scanvector.cpp main.cpp directoryStructure.cpp directoryStructure.h proNovoConfig.cpp proNovoConfig.h tokenvector.h tokenvector.cpp isotopologue.cpp isotopologue.h
	$(CC) $(CFLAGS) -o Sipros_openmp main.cpp ms2scan.cpp proNovoConfig.cpp directoryStructure.cpp ms2scanvector.cpp proteindatabase.cpp isotopologue.cpp peptide.cpp ptm.cpp tokenvector.cpp

clean:
	rm Sipros_openmp

