all:
	gcc -c -I/usr/local/include -I. -std=c++11 *.cpp
	ar rc libheaan.a *.o


clean:
	rm *.o libheaan.a  || echo nothing to clean
	