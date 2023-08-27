# Linux command to execute .asm files

1. Write assembly code to a .asm file (say hello.asm)
	`nano hello.asm`

2. Create a object file using nasm
	`nasm -f elf64 -o hello.o hello.asm`

3. Create executable file
	`ld hello.o -o hello`

4. Run the executable file
	`./hello`

