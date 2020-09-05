
---  

## Classes

```java
class ClassName{

}
```

## Methods

## Fields





## Control Flow


### Conditional

#### If

```java
        if(){

        }
```

#### If-else

```java
        if(){

        }
        else{

        }
```

#### switch

```java
        switch (key) {
            case value:

                break;
        
            default:
                break;
        }
```

### Repeating

#### for

#### while

#### for in

## Errors & Exceptions

## OOP (Object Oriented programming)

















## Conditional Control Flow

**a.k.a loops**  


















## Naming Conventions

	CamelCase :
	Classes
	Interfaces

	firstLowerThanAllCaps:
	variables (nouns)
	methods (verbs)

	dot.notation:
	packages

	ALL_CAPS_WITH_UNDERSCORES:
	constants


















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
 









