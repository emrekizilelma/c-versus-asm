# c-versus-asm
Testing C with Assembly

Well, you need nasm and ld.

Write the "Hello World" in Assembly (Source is here)

## Dependencies
- nasm
- ld

## Installation
```sh
nasm -f elf64 -ı hello.o hello.s
ld -o hello hello.o
./hello

```

- Source: https://jameshfisher.com/2018/03/10/linux-assembly-hello-world/
