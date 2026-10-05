Java Development Environment
1. Editor
An editor is a software tool used to write and edit source code.
Example:
- VS Code
- Notepad
- Sublime Text
- IntelliJ IDEA
Example Java code:
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}

The editor is where we type and save this code.
2. Compiler
A compiler converts the source code written by the programmer into a form that the computer/Java runtime can execute.
In Java:
Java Source Code
      ↓
   Compiler
      ↓
Bytecode (.class)

For example:
Main.java
   ↓
javac
   ↓
Main.class

Java's compiler is called javac.
3. VS Code
VS Code (Visual Studio Code) is a code editor.
It provides a place to:
- Write Java code
- Edit code
- Organize files
- Run/debug programs with the appropriate extensions and Java tools
Important:
VS Code itself is not the Java compiler, JDK, JRE, or JVM.

It is primarily the editor/interface you use to work with your Java development tools.
4. JDK — Java Development Kit
JDK = Java Development Kit
The JDK is the complete toolkit used to develop Java programs.
It contains tools needed to write, compile, debug, and run Java applications.
A simplified view:
JDK
│
├── Compiler (javac)
├── Java launcher (java)
├── Debugging/development tools
└── JRE
      └── JVM

So:
JDK = tools for developing Java programs + environment needed to run them

5. JRE — Java Runtime Environment
JRE = Java Runtime Environment
The JRE provides the environment required to run Java programs.
Simplified:
JRE
│
└── JVM

The JRE mainly contains:
- JVM
- Java class libraries
- Other files required for running Java applications
The important idea is:
JRE is for running Java programs.

6. JVM — Java Virtual Machine
JVM = Java Virtual Machine
The JVM is the component that runs Java bytecode.
Java execution works like this:
Main.java
    ↓
Java Compiler (javac)
    ↓
Main.class
    ↓
Bytecode
    ↓
JVM
    ↓
Program Output

The JVM allows the same Java bytecode to run on different operating systems, provided a suitable JVM is available.
This is the basis of:
Write Once, Run Anywhere

7. Relationship between JDK, JRE and JVM
Remember this simple hierarchy:
JDK
│
├── Development Tools
│      └── javac (compiler)
│
└── JRE
       │
       ├── Java Libraries
       │
       └── JVM

Very simple way to remember
JDK → Develop
JRE → Run
JVM → Execute
8. Complete Java Program Flow
Programmer
    ↓
Editor (VS Code / IntelliJ)
    ↓
Write Java source code
    ↓
Main.java
    ↓
JDK's Compiler (javac)
    ↓
Main.class
    ↓
Bytecode
    ↓
JVM
    ↓
Machine-level execution
    ↓
Output

One-line definitions
Editor   → Used to write and edit code.

Compiler → Converts Java source code into bytecode.

VS Code  → A code editor that can be used for Java development.

JDK      → Toolkit used to develop Java applications.

JRE      → Environment used to run Java applications.

JVM      → Executes Java bytecode.

One important distinction
VS Code = Where you write code
JDK     = Tools used to develop Java
JRE     = Environment for running Java
JVM     = Actually executes the bytecode
