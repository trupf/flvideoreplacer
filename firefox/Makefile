# Quick n dirty makefile

## For when we have releases tagged
# XPI_FILE=flvideoreplacer-$(shell git describe).xpi

XPI_FILE=flvideoreplacer@trupf.xpi

all: 
	zip -q -X -x Makefile -9r ../$(XPI_FILE) * 

clean:
	rm -f ../*.xpi 

.PHONY: all clean 

