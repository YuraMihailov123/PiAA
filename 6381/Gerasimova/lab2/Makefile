all: greedy a_star

greedy: lr2_1.o
	g++ lr2_1.o -o greedy -std=c++11
a_star: lr2_2.o
	g++ lr2_2.o -o a_star -std=c++11
lr2_1.o: lr2_1.cpp
	g++ -c lr2_1.cpp -std=c++11
lr2_2.o: lr2_2.cpp
	g++ -c lr2_2.cpp -std=c++11

