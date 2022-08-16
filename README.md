Program(software):
prgram is a set of instruction that tell a computer what to do.
= we use programs to interact/ talk with computers.
= to write programs we use programming languages.

Programing languages:
it is a language that is used to write programs. 
-- We know computers are machines and they do not understand human languages.
-- Programs are written in a language a computer can understand which is called a programming language.

Machine Laanguage:
1. It is a computer's native language in which computer can understand any instruction. 
2. it uses 0 and 1 --> Binary language.
3. in machine language an instruction of adding 2 and 3 will be : 1101101010011010
which is very hard to write by human.
4. Machine language is machine dependent. Means  it differs among different types of machine.
5. All instruction written in other programing language.

Assembly language:
1. It was developed to make a programming easier.
2. It was machine dependent.
3. Keywordslike add, sub were introduced.
4. to add 2 and 3 and get the result the instruction will be: add,2,3,result.
5. "Assembler" is a program that translates assembly code with machine code.

Assembler:

High-level language:
1. It is a new generation of programing languages.
2. This language uses english words that's why it is easy to learn and easy to use.

4. this language is machine independent.
5. program will run on different machine.
6. Instructions are called "statements".
7. A program written using a high level programing language is called a 'source program' or 'source code'.

Compiler:
1. Compiler translates all the source code into machine code.
2. source program -> executable source code --compiler -> Machine code -- Executor -> output.

Interpreter:
1. translates each statement into machine code and executes it right away.

About Java:
1. It was developed at Sun Microsystems which was purchased by Oracle in 2010.
2. It is a General-purposed & powerful programing language.
3. Used for developing software that run on mobile, desktop and servers.
4. Machine independent.

API:
1. Fullform: Application Programming Interface
2. Also known as a 'Library'.
3. It contains predefined Java code that we can use to develop Java programs.
4. So, it is faster and easier development process and there is no need to write everything from scratch.

Editions of Java:
1. Java Standard Edition(SE): Development applications that run on desktop.
2. Java Enterprise Edition(EE): develop server-side applications.
3. Java Micro Edition(ME): develop applications for mobile devices.

JDK:
1. Fullform: Java Development Kit.
2. Set of programs that enable us to develop our programs.
3. contains JRE(Java Runtime Environment) that is used to run our programs.
4. JRE & JDK contain JVM(java virtual machine).
5. JVM executes our java programs on different machines. means java is          independent.

IDE:
1. Integrated development evironment.
2. where we write our source code.
3. then the code is compiled to translate the code into a machine code.
4. ide has a tool called debug which is used to find errors.
5. ide has a tool that can build files which can be executed by JVM
6. ide has tools called run that executes the program.

## **04 Anatomy of Java Program.**
### **Method**
Group of instraction to do a specific task.
Examples:
* Amethod to add two numbers.
* Amethod to say hi to the user.
* A method to get the user's name.

### **Method Structer**
Each methode consists of 4 main parts.
```
return_type method_name ( parameters) {
  code block
}
```
**Calling A Method**
Is basically using the method
```
method_name ( give parameters);
```
* The code blocek of this methode will be executed.

**NOTE: the `main()` methode is automatically called when we run our java program.**
* It is the first methode that is called.
* it is the string print of execution of our prgram.

**Access Modifires**

Specify how to access Classes & Methodes Discussed later in OOP.
* public
* private
* protected
* Default

#### Naming Conventions
* **Pascal Case Convention:**
> ThisIsAName
* **Camel Case Comvention:**
> thisIsAName
* **Snake Case Comvention:**
> this_is_a_name

#### **Java Programming Structer**

```
public class Main {
  public static void main(String[] args) {

  }   
}
```

### **Remember**
* Every Java program contains at least one Class.
* Pascal case is used with classes.
* Camel case is used with methods.
* A method exists inside a class.
* `main()` is the string point of excution of our program.


## **05 Display Masseges in Java.**

### **String**
Gropu of characters (Text).

String in Java should be put in double quotes.


```
"Hello"
"This is an string"
"2345678"
"!@#$%^&"
""
```


#6.  **Displaying Numbers In Java:**
### **Numbers in Java:**
Numbers in java are just like in mathematics.

Example:
```
0
-19
129
-0.5
90.81
```

### **Some Arithmatic Operators:**

Addition operator: +
Subtraction operator: -
Divison operator: /
Multiplication operator: *

### **Printing some Values:**
```
System.out.println(4);           4
System.out.println(5+2);         7
System.out.println(3-5);     =>  -2
System.out.println(6*3);         18
System.out.println(4/2);         2
```


# 9. **Our First Java Program:**

#### **Comments:**

We can use comments to
- write notes
- find errors

```
// this is a single line comment
/*this is a
multi-line
comment*/
```


# 10. **Java Packages, Classes and Methods:**

1. take ur cursor to sidebar on packages of the file.
2. left click -> new file.

   this will open a new file with a same package
3. use psvm and enter for public static void main()
4. use sout for System.out.println();
5. one can use a program by its class_name.function_name() in another program of another file.



# 11. **public, private and static in java:**

#### **public access modifier:**
Specify how to access classes, methods and fields.

The access level is everywhere
- inside a class
- outside a class
- inside a package
- outside a package 

#### **private access modifier:**
the access level is only ``` inside the class```

#### **static non-access modifier:**
you can access fields/methods using the class name

Example:

``` System.out```
        -> out is a static field of System.
        
        
       
# 12. **The void return type in Java:**

**Return Type:**
The type of data that a method returns/gives.

_ A method can return/give a value.

_ ```getUserName()```:
  - get the name of the user and return the value.
  - the return type is a text(string).

_```getUserAge()```:
  - get the age of the user and return the value.
  - the return type is a number(int, double,...).



**The Void Return Type:**

 ```main()```  has a void return type.
   -> void means nothing.
   -> main() does not return a value.

Example:
_ ```printUserName()``` :
  - we just want to print the namw of the user.
  - we do not want to get any value from this method.
  - the return type is void.

_ Note that every method has a very specific role.
  - ```getUserName();```
  - ```printUserName();```



# 13. **Command line Arguments in Java:**

1. in java we can pass comman line arguments through some different ways.
  - while using command prompt for compilation and running, at the time of running we can use  ```java folder_name arg1 arg2 arg3``` to pass arguments.
  - while using intellij IDEA we can pass arguments "by run->edit configuration -> write arguments" 
