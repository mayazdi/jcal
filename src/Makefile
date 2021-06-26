CC=gcc
CFLAGS=-I.

%.o: %.c
	$(CC) -c -o $@ $< $(CFLAGS)

cal: jcal.o jalali.o jtime.o
	$(CC) -o jcal jcal.o jalali.o jtime.o

date: jdate.o jalali.o jtime.o
	$(CC) -o jdate jdate.o jalali.o jtime.o

clean:
	rm -f *.o jcal jdate
