build: Product.o Factory.o main.o
	g++ -o build Factory.o Product.o main.o

main.o: main.cpp Factory.h Product.h
	g++ -g -c main.cpp

Factory.o: Factory.h Product.h Factory.cpp
	g++ -g -c Factory.cpp

Product.o: Product.h Product.cpp
	g++ -g -c Product.cpp

clean:
	del *.o build.exe