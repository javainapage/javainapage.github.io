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

- Development Environment
    - Download OpenJDK ([Oracle](https://www.java.com/en/download/))
    - Set Environmental Variables

```bash
    JAVA_HOME=jdk-install-dir

    export JAVA_HOME

    PATH=$JAVA_HOME/bin:$PATH

    export PATH
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

```java
	class HelloWorld{
		public static void main(Strings args[]) {
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
- `String args[]` inside parantheses

Inside `main` method  

```java
	// copy this into your hello.java file !
	class HelloWorld{
		public static void main(Strings args[]) {
			System.out.println('Hello World!');
		}
	}
```

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

rule of thumbs   
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

## Access Modifiers

```java
    int defaultVar;
    public int publicVar; // Public: Can be accessed from anywhere
    private int privateVar;  // Private: Only accessible from within the class
    protected int protectedVar; // Protected: Accessible from the class and subclasses
```


## ಥ_ಥ TODO


---

<br>

![forthebadge](https://forthebadge.com/images/badges/cc-0.svg)  

Contribute ? Please ... `(づ￣ ³￣)づ`