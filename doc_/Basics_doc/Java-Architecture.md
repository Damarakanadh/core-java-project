# Java Architecture

Java follows a three-step architecture that allows programs to run on multiple platforms without modification.

## 1. Source Code

You write `.java` files in any editor or IDE.

## 2. Java Compiler (javac)

The Java compiler converts `.java` files into **bytecode** (`.class` files).
### What the compiler does:
- Checks for error
- Converts high-level Java code into platform-independent bytecode.
- Generates one .class file per class
#### Output:
Demo.java  -> Demo.class
## 3. Java Virtual Machine (JVM)

The JVM executes bytecode.  
Each OS has its own JVM implementation, enabling platform independence.

## Java Environment Components

### 🔹 JDK (Java Development Kit)

Contains:

- Compiler (`javac`)
- Tools (javadoc, jdb)
- JRE

### 🔹 JRE (Java Runtime Environment)

Contains:

- JVM
- Core libraries

### 🔹 JVM (Java Virtual Machine)

Responsible for:

- Loading classes
- Verifying bytecode
- Interpreting/executing bytecode
- Memory management (heap, stack)
- Garbage collection

## Execution Flow

.java → javac → .class (bytecode) → JVM → Output

The Java execution model is designed to make programs portable, secure, and efficient. This flow ensures that the same .java file can run on any operating system without modification.

### Java Basic Program

- Public class Demo {
- public static void main(String[] args) {
- System.out.println("Hello, World!");
- }
- }

At this stage:

- Syntax has no validation yet.
- No memory is allocated.
- Just plain text code.

### Compilation using [javaC] (Compiler)

The Java compiler checks your code for syntax errors, type checking and semantic rules.

If the code is vaild, it produces bytecode(.class files).



