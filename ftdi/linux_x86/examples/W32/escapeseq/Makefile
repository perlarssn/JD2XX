TOPDIR  := $(shell cd ..; cd ..; pwd)
include $(TOPDIR)/Rules.make

APP = w32_escapeseq

all: $(APP)

$(APP): main.c	
	$(CC) -o $(APP) $(CFLAGS) main.c
	
clean:
	rm -f *.o ; rm $(APP)
