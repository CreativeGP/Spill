spill: spill.o
	g++ spill.o -o spill -lpodofo -lfreetype -lfontconfig -ljpeg -lz

spill.o:
	g++ -c spill.cpp -o spill.o

clear:
	rm spill *.o
