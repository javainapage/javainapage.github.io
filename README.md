# ฅ^•ﻌ•^ฅ Java In a Page


<br>

![forthebadge](https://forthebadge.com/images/badges/built-with-swag.svg)   

---

![](https://img.shields.io/badge/Use-Ctrl%20%2B%20F-blue?style=for-the-badge)

# ƸӜƷ

    @author : lakshay kiran
    @published : 
    @lastupdated :
    @url : http://javainapage.github.io/


Java is a **programming language** and a **platform** .
---

---

# TOC

---  


## Hello World


add(int, int)
add(int, int, int)
2. Data type of parameters.
For example:


- Development Environment
    - Download OpenJDK ([Oracle](https://www.java.com/en/download/))
    - Set Environmental Variables

unix user

```bash
    JAVA_HOME=jdk-install-dir

    export JAVA_HOME

    PATH=$JAVA_HOME/bin:$PATH

    export PATH
```

windows user

```bash
    setx -m JAVA_HOME "C:\Program Files\Java\jdk1.8.0" # jdk<version>
    setx -m PATH "%PATH%;%JAVA_HOME%\bin";
```

- Create a file with '.java' extension. (say 'hello.java')

_Moving On to Hello World Tradition_  
*You don't need to understant this code, by sense,*  
*just try to understand formation.*  

```bash
	mkdir tutorial
	cd tutorial
	touch hello.java
	vi hello.java
```

- Inside the file ...

Start with a bare class, let it be `HelloWorld`    

```java
	class HelloWorld{
		// all code here
	}
```

In class, add a function(method) named `main`  

**Class containing `main` method is "main" class.**  

```java
	class HelloWorld{
		public static void main(Strings[] args) {
			/*
			Special Method
			Recognised by JVM
			Main method , code that 'actually' runs !
			*/
		}
	}
```

**Carefully note :**
- `public` keyword
- `static` keyword
- `void` keyword
- `String[] args` inside parantheses

Inside `main` method  

```java
	// copy this into your hello.java file !
	class HelloWorld{
		public static void main(Strings args[]) {
			System.out.println('Hello World!');
		}
	}
```
## Method Overloading in Java 
Method Overloading is a feature that allows a class to have more than one method having the same name, if their argument lists are different. It is similar to constructor overloading in Java, that allows a class to have more than one constructor having different argument lists.

let’s get back to the point, when I say argument list it means the parameters that a method has: For example the argument list of a method add(int a, int b) having two parameters is different from the argument list of the method add(int a, int b, int c) having three parameters.
Three ways to overlaod a method:
In order to overload a method, the argument lists of the methods must differ in either of these:
1. Number of parameters.
For example: This is a valid case of overloading
add(int, int)
add(int, float)
3. Sequence of Data type of parameters.
For example:

add(int, float)
add(float, int)
Invalid case of me


**Carefully note :**
- `System.out.println`
	- dot notation
- Semi-colon (`;`) at the end

Now first we "compile the code",  

```bash
	javac hello
	ls # you'll see a hello.class file
```

Then we "run" it

```bash
	java hello
	#outputs : Hello World!
```

## Comments

```java
    // Single Line Comment

    /*
    Multi
    Line
    Comment
    */

    /*
    *
    *
    * DOCUMENTATION
    *
    *
    */

    /* Some Conventional meta information (DOCUMENTAION)
    *
    *
    * @author         Name of author.
    * @version        Version of the program.
    * @since          When this part of the program was first added.
    * @param          Mini Desc of parameters to a method.
    * @return         Type of return.
    * @deprecated  
    * @see         
    *
    *
    */
```

## Naming Conventions

```java
    // dot.notation
    import naming.convention.packages;
    // CamelCase
    class NamingConventionForClass{}
    //interface
    //generic class
    int namingConventionForVariable;
    //constant
    void namingConventionForMethod(){}  
```

rule of thumb   
- match top class with file name 

## Types

```java
    byte b = -20;
    short s = 10000;
    int a = 100000;               // Integer (whole number)
    long ab = 100000L;
    float myFloatNum = 5.99f;    // Floating point number
    double d1 = 12.3;
    char myLetter = 'D';         // Character
    boolean myBool = true;       // Boolean
    String myText = "Hello";     // String
```

## Operators

arithmetic operators are arithmetic operators.

```java
    // Arithmetic Operators
    System.out.println("5+4 = " + (i1 + i2)); 
    System.out.println("9-1 = " + (i2 - i1)); 
    System.out.println("2*3 = " + (i2 * i1)); 
    System.out.println("3/7 = " + (i1 / i2)); 
    System.out.println("1/2.0 = " + (i1 / (double)i2));
```

```java
    // Modulo operator
    System.out.println("11%3 = "+(11 % 3)); // => 2

    // Comparison operators
    System.out.println("9 == 8? " + (9 == 8)); 
    System.out.println("9 != 8? " + (9 != 8)); 
    System.out.println("9 > 8? " + (9 > 8)); 
    System.out.println("9 < 8? " + (9 < 8)); 
    System.out.println("8 <= 8? " + (8 <= 8)); 
    System.out.println("8 >= 8? " + (8 >= 8));  
```

boolean and bitwise to confuse you and me

```java
    /* Boolean Operators
    &	Logical AND
    |	Logical OR
    ^	Logical XOR (exclusive OR)
    ||	Short-circuit OR
    &&	Short-circuit AND
    !	Logical unary NOT
    &=	AND assignment
    |=	OR assignment
    ^=	XOR assignment
    ==	Equal to
    !=	Not equal to
    ? :	Ternary if-then-else
    */

    /* Bitwise Operators
    ~      Unary bitwise complement
    <<     Signed left shift
    >>     Signed/Arithmetic right shift
    >>>    Unsigned/Logical right shift
    &      Bitwise AND
    ^      Bitwise exclusive OR
    |      Bitwise inclusive OR
    */
```

at last ...

```java
    // Increment operators
    int i = 0;
    System.out.println(i++); // i = 1, prints 0 (post-increment)
    System.out.println(++i); // i = 2, prints 2 (pre-increment)
    System.out.println(i--); // i = 1, prints 2 (post-decrement)
    System.out.println(--i); // i = 0, prints 0 (pre-decrement)
```

## Statements

```java
    if (condition) {
        // code
    }
    
    if (condition) {
        // code
    } else {
        // code
    }
```
```java
    switch (key) {
        case value:
            //code 
            break;
    
        default:
            //code
            break;
    }
```
```java
    while (condition) {
        //code
    }

    do {
        //code
    } while (condition);
```

```java
    for(initialization; condition; iteration) {
        //code
    }

    for (String string : args) {
        
    }
```


## Access Modifiers

```java
    int defaultVar;
    public int publicVar; // Public: Can be accessed from anywhere
    private int privateVar;  // Private: Only accessible from within the class
    protected int protectedVar; // Protected: Accessible from the class and subclasses
```


## CLI arguments

`args` is an **array** of `String`s,  
which contains user supplied arguments from the terminal,  
all **values are strings** by default, even if numbers are supplied!  


Ensure args are provided  

```java
    if (args != null) {
        
    }
```

```java
    public class Echo {
        public static void main (String[] args) {
            if (args != null) {
                for (String s: args) {
                    System.out.println(s);
                }
            }
        }
    }
```

in case of numerical input  

```java
    // convert to integer
    firstArg = Integer.parseInt(args[0])
```
## User Input

```java
    import java.util.Scanner;

    class UserInput{
        public static void main(Strings[] args) {
            
            // Scanner Object
            Scanner scanner = new Scanner(System.in);

            // read string input
            String name = scanner.next();

            // read byte input
            byte numByte = scanner.nextByte();

            // read int input
            int numInt = scanner.nextInt();

            // read long input
            float numFloat = scanner.nextFloat();

            // read double input
            double numDouble = scanner.nextDouble();

            // read boolean input
            boolean bool = scanner.nextBoolean();
        }
    }
```

## Build Tool : Maven

- Download Maven ([Apache](https://maven.apache.org/download.cgi))

- Add to environment variables

unix user  

```bash
    PATH=path/to/bin:$PATH

    export PATH
```

windows user  

```bash
    setx -m PATH "%PATH;path/to/mvn/bin";
```

    > src : https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html  

    # Maven Phases

    Although hardly a comprehensive list, these are the most common default lifecycle phases executed.  


`validate`: validate the project is correct and all necessary information is available  
`compile`: compile the source code of the project  
`test`: test the compiled source code using a suitable unit testing framework. These tests should not require the code be packaged or deployed  
`package`: take the compiled code and package it in its distributable format, such as a JAR.  
`integration-test`: process and deploy the package if necessary into an environment where integration tests can be run  
`verify`: run any checks to verify the package is valid and meets quality criteria  
`install`: install the package into the local repository, for use as a dependency in other projects locally  
`deploy`: done in an integration or release environment, copies the final package to the remote repository for sharing with other developers and projects.  

    There are two other Maven lifecycles of note beyond the default list above. They are :

`clean`: cleans up artifacts created by prior builds  
`site`: generates site documentation for this project

```bash
    mvn package
```

```bash
    mvn site
```

## ಥ_ಥ TODO

- [x] comments
- [x] operators
- [x] types
- [ ] type wrappers
- [x] access modifiers
- [ ] statements
- [ ] packages
    - [ ] .jar

- [ ] interfaces
- [ ] abstract classes
- [ ] generic classes
- [ ] annotations


- [ ] exception handling
- [ ] context/resource management

- [ ] file I/O

- [ ] threading

- [ ] collections



    <!-- Global site tag (gtag.js) - Google Analytics -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=UA-177324402-1"></script>  
    <script>  
    window.dataLayer = window.dataLayer || [];  
    function gtag(){dataLayer.push(arguments);}  
    gtag('js', new Date());  
    
    gtag('config', 'UA-177324402-1');  
    </script>  


---

<br>

![forthebadge](https://forthebadge.com/images/badges/cc-0.svg)  

Contribute ? Please ... `(づ￣ ³￣)づ`
