AS=asm -v -n -C 6801

%.S19:	%.ASM
	$(AS) -l $*.LST -o $@ $^

.PHONY: clean distclean

all: LILBUG.S19

clean:
	-rm -f *.LST
distclean: clean
	-rm -f *.S19

