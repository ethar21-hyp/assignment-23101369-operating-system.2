# Assignment: Linker & Loader Explanation

**Repository:** assignment-23101369-operating-system.2

## Overview

This assignment provides an explanation and implementation examples for
the *linker* and *loader* processes in the context of operating
systems.\
It contains C source files, a Makefile, and screenshots illustrating 
output and behaviour.

## Contents

-   `hello.c`, `hello1.c` --- simple C programs to demonstrate
    compilation/linking.\
-   `simple‑p.c` --- sample illustrating process creation or program
    behaviour.\
-   `fork_example (1).c` --- example using `fork()` to show child/parent
    processes.\
-   `makefile` --- automates build and linking steps.\
-   `lab5 explaination ass 23101369.txt` --- detailed textual
    explanation of the assignment.\
-   `os01.png` ... `os06.png` --- screenshots.\
-   `LICENSE` --- MIT License for this repository.

## Learning Objectives

-   Understand what a **linker** does: symbol resolution, relocation,
    combining object files.\
-   Understand what a **loader** does: loading the executable into
    memory, preparing runtime environment.\
-   See real code examples in C and how linking and loading steps
    occur.\
-   Use `make` to automate the build process.

##  How To Build & Run

``` bash
git clone https://github.com/ethar21-hyp/assignment-23101369-operating-system.2.git
cd assignment-23101369-operating-system.2
make
./hello
./simple-p
```

## Concepts Explained

-   **Linker**\
-   **Loader**\
-   **Compilation flow**

## AUTHOR
**Ethar Ahmed**

## License

MIT License.
