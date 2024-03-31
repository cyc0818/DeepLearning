all: PixelConversion
PixelConversion: PixelConversion.cc
	g++ -o PixelConversion PixelConversion.cc PMTinfo.h `root-config --cflags --libs`

clean:
	rm ./PixelConversion

