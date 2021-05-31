# C++ program to print Hello world

```c++
// Your First C++ Program

#include <iostream>

int main() {
    std::cout << "Hello World!";
    return 0;
}  
```
#### Output

>Hello World!


### Working of C++ "Hello World!" Program
// Your First C++ Program

1. In C++, any line starting with // is a comment. Comments are intended for the person reading the code to better understand the functionality of the program. It is completely ignored by the C++ compiler.
#include <iostream>

2. The #include is a preprocessor directive used to include files in our program. The above code is including the contents of the iostream file.

3. This allows us to use cout in our program to print output on the screen.

4. For now, just remember that we need to use #include <iostream> to use cout that allows us to print output on the screen.

```
int main() {...}
```

5. A valid C++ program must have the main() function. The curly braces indicate the start and the end of the function.

6. The execution of code beings from this function.
std::cout << "Hello World!";

* std::cout prints the content inside the quotation marks. It must be followed by << followed by the format string. In our example, "Hello World!" is the format string.

####  Note: ; is used to indicate the end of a statement.
* return 0;

7. The return 0; statement is the "Exit status" of the program. In simple terms, the program ends with this statement.
Things to take away
We use std:cout in order to print output on the screen.
We must include iostream if we want to use std::cout.
The execution of code begins from the main() function. This function is mandatory. This is a valid C++ program that does nothing.

```c++
int main() {
    // Write your code here
}
```

### Contributed By:
```
B Shashi Kumar
Roll No:11706004
```
<a href="https://shashiben.me">
<img src="https://media-exp1.licdn.com/dms/image/C5603AQEgY9OTq5ZNwQ/profile-displayphoto-shrink_800_800/0/1620666120685?e=1627516800&v=beta&t=RqxX0dBC8f8f2_eb3vLLVF5VJUiMnqks3E8Enocidt4"" width="100px;" alt=""/>
<br /><sub>
<b>B Shashi Kumar</b>
<br />
<b>11706004</b>
</sub></a><br />
          