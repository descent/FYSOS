CC=gcc
CFLAGS=-m32 -DDJGPP
detcntlr: detcntlr.o
	$(CC) -g $(CFLAGS) -o $@ $<

detcntlr.o: detcntlr.c
	$(CC) $(CFLAGS) -c detcntlr.c -I../include 
