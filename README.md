# ฅ^•ﻌ•^ฅ Java In a Page


<br>

![forthebadge](https://forthebadge.com/images/badges/built-with-swag.svg)   

---

![](https://img.shields.io/badge/Use-Ctrl%20%2B%20F-blue?style=for-the-badge)

# ƸӜƷ

Java is a **programming language** and a **platform** .
---

<details>
<summary>The platform</summary>

## Java, the platform

To get started you need JDK (Java Dev Kit).  
Namely OpenJDK. There are other forks too, maybe.  
**But you'll end up using OpenJDK, trust me on this.**  

JDK is consists of JRE (Java Runtime Environment);  
JRE contains JVM (Java Virtual Machine);  
java "runs" on JVM.    

For beginning, you need two cli tools bundles with jdk;  
`$ javac` : compiles source code ".java" files to ".class" files  
`$ java` : executes the program on JVM  

</details>

<details>
<summary>Dev Environment Setup</summary>
### Setup

    #Where should I download Java?

    With the introduction of the new release "cadence",
    many have asked where they should download Java, 
    and if it is still free. 
    To be clear, YES — Java is still free.

    If you would like to download Java for free, 
    you can get OpenJDK builds from the following vendors, 
    among others:

<ul>
<li><a href="http://jdk.java.net">Oracle</a></li>
<li><a href="https://developers.redhat.com/products/openjdk/download/">RedHat</a></li>
<li><a href="https://www.azul.com/downloads/zulu/">Azul</a></li>
<li><a href="https://adoptopenjdk.net">AdoptOpenJDK</a></li>
<li><a href="https://aws.amazon.com/corretto/">Amazon</a></li>
<li><a href="https://sap.github.io/SapMachine/">SAP</a><br></li>
<li><a href="https://bell-sw.com/">Liberica JDK</a><br></li>
</ul>

> source : reddit (r/learnjava)

**But you'll end up using Oracle, trust me on this.**   

    Download OpenJDK;    
    Setup env vars;  
    Make a folder locally, namely "jiap";  
    keep a terminal open and `cd` into that folder;  

</details>
<details>

<summary>Hello World</summary>

### Hello World!

    /path/to/jiap/hello.java

```java
class HelloWorld{
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

Open terminal in the same folder.  
Run.  

```bash
javac hello # compiles java
ls # a new hello.class file is created
java hello #run the class file
```

OUTPUT :

    Hello World!

</details>

---

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

---

## ಥ_ಥ TODO

---

<br>

![forthebadge](https://forthebadge.com/images/badges/cc-0.svg)  

Contribute ? Please ... `(づ￣ ³￣)づ`
