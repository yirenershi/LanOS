all: link
	dd if=test_elf of=ls bs=512 skip=8 conv=notrunc
link: lan_main 
	ld -m elf_i386 -T n.lds -o test_elf lan_main.o -L/common/lib -llansys
lan_main:
	gcc -I/common/header -m32 -g -fno-stack-protector -fno-pie -c lan_main.c 
clean:
	rm ls test_elf lan_main.o
cp:
	cp ls ../../root_fs/
	