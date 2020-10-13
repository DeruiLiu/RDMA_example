CC = gcc
LDFLAGS = -libverbs -lpthread

TARGETS = dcini dctgt

all: $(TARGETS)

dcini: dcini.c
	$(CC) -o dcini dcini.c $(LDFLAGS)

dctgt: dctgt.c
	$(CC) -o dctgt dctgt.c $(LDFLAGS)

clean:
	rm dcini dctgt
