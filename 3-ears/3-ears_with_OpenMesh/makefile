CFLAGS          = -g
CPPFLAGS        = -Wall -g -O3 -mtune=generic -DNDEBUG -std=c++0x -I./
OBJ1            = main.o PolyMesh.o ExactPredicates.o targa.o
main:	$(OBJ1) 
	$(CXX) -o $@ $(OBJ1)
clean:	
	rm -f adaptive/*
	rm -f double/*
	rm -f float/*
	rm -f *.o
	rm -f main

