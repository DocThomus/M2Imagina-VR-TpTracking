all: compile execute

compile: PoursuiteCible.cpp
	g++ -o tracking PoursuiteCible.cpp -O2 -L/usr/X11R6/lib -lm -lpthread -lX11

execute: 
	./tracking ../Images/SequenceSansVariation/Image001.tif 