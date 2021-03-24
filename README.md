# Libasm_42

## Introduction
An assembly (or assembler) language, often abbreviated asm, is a low-level programming language for a computer, or other programmable device, in which there is a very strong (but often not one-to-one) correspondence between the language and the architecture’s machine code instructions. Each assembly language is specific to a particular computer architecture. In contrast, most high-level programming languages are generally portable
across multiple architectures but require interpreting or compiling. Assembly language may also be called symbolic machine code.

## Rewriting the following functions in asm:
◦ ft_strlen (man 3 strlen) <br>
◦ ft_strcpy (man 3 strcpy) <br>
◦ ft_strcmp (man 3 strcmp) <br>
◦ ft_write (man 2 write) <br>
◦ ft_read (man 2 read) <br>
◦ ft_strdup (man 3 strdup, using malloc)

## Subject
+ [libasm_subject](/libasm_subject.pdf)




## How To Use
1. clone this repo.
2. run the `make` command.
3. To compile with the repository main:
    ```
    gcc -Wall -Werror -Wextra main.c libasm.a 
    ```