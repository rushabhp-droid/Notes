***
- The Code we write is called as source code.
- The Code that the computer/CPU understands is called as machine code.
- Source Code Example:
```c
  #include <stdio.h>
  
  int main() {
	  printf("Hello, World!\n");
	  return 0;
  }
  ```
  
  - Machine Code Example:
  ```text
  1010101001000110101
  0101010100010101000
  0001100000111010101
  0101010101010100001  
  ```

## Header File

- Anything that ends with a .h
- Libraries - Including Code that someone else wrote.
***

## Compiler
- How the ==compiler== works
 
![[compiler.png]]
***
# Data Types

| Types         | Format Code |
| ------------- | ----------- |
| int           | %i, %d      |
| double, float | %f          |
| long          | %li         |
| char          | %c          |
***
# Conditionals
```c
if (x > y) {
	doSomething();
}
else if (x < y) {
	doSomethingElse();
}
else if (x == y) {
	doAnything();
}
else {
	return -1;
}
```
***
# Loops

```c
i = 3;
while(i>0) {
	printf("%i", i);
	i--;
}
```

- the above loop is a while loop.
- for loop ex:
```c
for(int i = 0;i < 3;i++) {
	printf(%i, i);
}
```

- do while example:
```c
do
{
	printf("lmao\n");
}
while (n > 1)
```

***
# Functions

```c
#include <stdio.h>

void meow(int n); // Prototype

int main()
{
	meow(3);
}

void meow(int n) // user defined function
{
	for (int i = 0; i < n; i++) {
		printf("meow"\n);
	}
}
```

***