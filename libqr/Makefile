OBJECTS = qr.o qrcnv.o qrcnv_bmp.o
CC = gcc

qr: qrcmd.c $(OBJECTS)
	$(CC) -o $@ $^
	
clean:
	rm -f all $(OBJECTS)