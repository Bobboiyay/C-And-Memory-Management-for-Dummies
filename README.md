# **C AND MEMORY MANAGEMENT FOR DUMMIES**

## Hello World!:

In order to print something we need to make the skeleton for our file

```C
int main() {

}
```
now we need a lil library that gives us our print function
```C
#include <stdio.h>
```

Next we just need our printing function:

```c
int main() {
  printf("Hello World!\n");
}
```

now just compile it
```sh
gcc main.c
```
Next run it:
```sh
./a.out
```
### 3 Beginners mistakes:
1. Forgetting \n, \n makes a newline, else it would be printed in the same line as the 
