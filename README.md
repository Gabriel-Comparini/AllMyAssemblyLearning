# AllMyAssemblyLearning

## Compiling in Arch Linux (64 bits):

### Requirements:
- **Nasm:** 
```bash
sudo pacman -S nasm
```

### Code:
```bash
nasm -f elf64 src/hello_world.asm -o bin/hello_world.o
ld -o bin/hello bin/hello_world.o
```

### Syscalls for any linux 64 bits:
[Syscalls](https://blog.rchapman.org/posts/Linux_System_Call_Table_for_x86_64/)

(I will add more stuff futurely)