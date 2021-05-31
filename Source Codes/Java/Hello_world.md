# Java program to print Hello world

```Java
class Main{  
    public static void main(String args[]){  
     System.out.println("Hello World!");  
    }  
}  
```
>Save this file as Main.java

#### To compile:
>javac Main.java

#### To execute:
>java Main

### Output:
>Hello World!

### How Java "Hello, World!" Program Works?
// Your First Program

* In Java, any line starting with // is a comment. Comments are intended for users reading the code to understand the intent and functionality of the program. It is completely ignored by the Java compiler (an application that translates Java program to Java bytecode that computer can execute). To learn more, visit Java comments.
class HelloWorld { ... }

* In Java, every application begins with a class definition. In the program, HelloWorld is the name of the class, and the class definition is:
```Java
class HelloWorld {
... .. ...
}
```

* For now, just remember that every Java application has a class definition, and the name of the class should match the filename in Java.
public static void main(String[] args) { ... }

* This is the main method. Every application in Java must contain the main method. The Java compiler starts executing the code from the main method.

* How does it work? Good question. However, we will not discuss it in this article. After all, it's a basic program to introduce Java programming language to a newbie. We will learn the meaning of public, static, void, and how methods work? in later chapters.

* For now, just remember that the main function is the entry point of your Java application, and it's mandatory in a Java program. The signature of the main method in Java is:
```Java
public static void main(String[] args) {
... .. ...
}

System.out.println("Hello, World!");
```
* The code above is a print statement. It prints the text Hello, World! to standard output (your screen). The text inside the quotation marks is called String in Java.

* Notice the print statement is inside the main function, which is inside the class definition.

* Things to take away
Every valid Java Application must have a class definition (that matches the filename).
The main method must be inside the class definition.
The compiler executes the codes starting from the main function.
This is a valid Java program that does nothing.

```Java
public class HelloWorld {
    public static void main(String[] args) {
        // Write your code here
    }
}
```

### Contributed By:
```
B Shashi Kumar
Roll No:11706004
```
