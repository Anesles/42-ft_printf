# **ft_printf (Cursus from 42 Porto)**
## **Grade: 100/100**
---
### **Summary:**

In this project I had to develop a clone of the standard printf function in C.

#### **Installing and running the project:**
* Clone this repository.
```
git clone git@github.com:Anesles/42-ft_printf.git
```
* Run `make`.
```
make
```
* Create a test file with a main that uses ft_printf.
``` C
#include "ft_printf.h"

int main(void)
{
	ft_printf("Teste %d", 42);
}
```
* Compile and run.
```
cc -Wall -Wextra -Werror name_of_file.c libftprinft.a
./a.out
```
---
### **Makefile targets**
* `make` or `make all` - Compiles the program.
* `make clean` - Cleans all object files.
* `make fclean` - Cleans all object files, _client_ and _server_.
## Disclaimer
> At [42School](https://en.wikipedia.org/wiki/42_(school)), almost every project must be written in accordance to the [Norm](./extras/en_norm.pdf), the schools' coding standard. As a result, the implementation of certain parts may appear strange and for sure had room for improvement.