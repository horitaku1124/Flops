basepath="Source/binaries-macos/"
flags=-O2 -lpthread -std=c++11

all:
	

dir:
	mkdir -p $(basepath)

haswell: dir
	$(CXX) Source/*.cpp -o $(basepath)2013-Haswell  $(flags) -march=haswell -D "x64_2013_Haswell"

clean:
	$(RM) $(basepath)/*