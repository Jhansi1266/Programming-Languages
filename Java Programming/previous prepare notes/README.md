# Introduction to Java
## 1. What is Java?
ava is a high-level, object-oriented, class-based, platform-independent programming language used to develop web, desktop, mobile, enterprise, and cloud applications.
## 2. History of Java
i. In 1991, a team at Sun Microsystems started the Green Project.
ii. The project was led by James Gosling, known as the Father of Java.
iii. Java was first called Oak, named after an oak tree outside Gosling's office.
iv. Since the name "Oak" was already trademarked, it was renamed Java.
v. Java was officially released in 1995.
vi. In 2010, Oracle Corporation acquired Sun Microsystems and became the owner of Java.
### a. Who Developed Java?
Java was developed by James Gosling and his team at Sun Microsystems.
### b. When Was Java Developed?
Java development started in 1991.
### c. When Was Java Released?
Java was officially released in 1995.
### d. Which Company Developed Java?
Sun Microsystems developed Java.
### e. Which Company Owns Java Now?
Oracle Corporation owns and maintains Java after acquiring Sun Microsystems in 2010.
### f. What Was the Original Name of Java?
The original name of Java was Oak.
### g. Why Was the Name Changed from Oak to Java?
The name was changed because "Oak" was already a registered trademark. The new name "Java" was chosen before the public release.
### h. Why is the programming language named Java?
Java was originally named "Oak" because there was an oak tree outside James Gosling's office. However, the name "Oak" was already registered as a trademark by another company. So, the development team chose a new name, "Java," inspired by Java coffee (coffee from the Indonesian island of Java). The name was officially adopted before the language was released in 1995.
### i. What Was the Green Project?
The Green Project was the research project started by Sun Microsystems in 1991 to develop software for consumer electronic devices. Java was created as part of this project.
### j. Which Version of Java Was First Released?
JDK 1.0 was the first official Java version, released in 1996.
## 3. Why Was Java Developed?
Java was developed to solve problems found in earlier programming languages.
#### Main goals:
      Platform independence
      Simplicity
      Security
      Reliability
      Object-oriented programming
      Internet application development
## 4. Why Learn Java?
#### Java is one of the most popular programming languages because it is:
      Easy to learn
      Platform independent
      Object-oriented
      Secure
      Reliable
      Widely used in industry
      In high demand for jobs
## 5. Why is Java Popular?
#### Java is popular because it is:
      Platform Independent
      Object-Oriented
      Secure
      Robust
      Portable
      Easy to Learn
      Multithreaded
      Widely Used in Industry
## 6. Features of Java
### 1. What are the Features of Java?
#### The main features of Java are:
      Simple
      Object-Oriented
      Platform Independent
      Secure
      Robust
      Portable
      Architecture Neutral
      Multithreaded
      Distributed
      Dynamic
      High Performance
### 2. Why is Java Simple?
Java is simple because it has easy-to-understand syntax, automatic memory management (Garbage Collection), and does not support complex features like pointers and operator overloading.
### 3. Why is Java Object-Oriented?
Java is object-oriented because programs are built using classes and objects. It supports the four OOP principles: Encapsulation, Inheritance, Polymorphism, and Abstraction.
### 4. Why is Java Platform Independent?
Java is platform independent because it is compiled into bytecode, which runs on any operating system that has a Java Virtual Machine (JVM). This is called Write Once, Run Anywhere (WORA).
### 5. Why is Java Secure?
Java is secure because it does not use pointers directly, performs bytecode verification, and runs programs inside the JVM, helping protect the system from unauthorized access.
### 6. Why is Java Robust?
Java is robust because it provides strong exception handling, automatic garbage collection, and type checking, making programs more reliable.
### 7. Why is Java Portable?
Java is portable because the same compiled bytecode can run on different operating systems without modification, as long as a JVM is available.
### 8. What is Architecture Neutral in Java?
Java is architecture neutral because the compiled bytecode is not tied to any specific processor architecture. The JVM converts the bytecode into machine code for the target system.
### 9. Why is Java Multithreaded?
Java supports multithreading, allowing multiple tasks to run simultaneously within the same program, improving performance and responsiveness.
#### Example: Downloading a file while playing music.
### 10. Why is Java Distributed?
Java is distributed because it provides built-in support for network programming, allowing applications to communicate over a network.
### 11. Why is Java Dynamic?
Java is dynamic because it can load classes and libraries during runtime, making applications more flexible.
### 12. Why is Java High Performance?
Java achieves high performance using the Just-In-Time (JIT) compiler, which converts frequently used bytecode into native machine code for faster execution.
### 13. Which Java Feature Makes It Run on Different Operating Systems?
Platform Independence is the feature that allows Java programs to run on different operating systems using the JVM.
### 14. What Does WORA Mean?
WORA stands for Write Once, Run Anywhere. It means Java code can be written once and run on any system with a JVM.
### 15. Which Feature of Java Helps Prevent Memory Leaks?
Garbage Collection automatically removes unused objects from memory, helping manage memory efficiently.
### 16. Which Java Feature Supports Code Reusability?
Object-Oriented Programming, especially Inheritance, supports code reusability.
### 17. Which Java Feature Improves Security?
Security features such as bytecode verification, JVM sandboxing, and the absence of direct pointer manipulation improve Java's security.
### 18. Which Java Feature Improves Program Reliability?
Robustness, through exception handling and garbage collection, improves program reliability.
## 7. Applications of Programming
### a. What are the applications of programming?
Programming is used in software development, web development, mobile app development, AI, data science, cloud computing, automation, gaming, banking, healthcare, and embedded systems.
### b. Why is programming important?
Programming helps solve problems, automate tasks, build applications, process data, and improve efficiency.
### c. Where is programming used in daily life?
Programming is used in ATMs, mobile apps, websites, online banking, smart devices, GPS navigation, and digital payment systems.
### d. Which industries use programming?
        Information Technology (IT)
        Banking
        Healthcare
        Education
        Manufacturing
        Retail
        Telecommunications
        Entertainment
### e. Which programming languages are commonly used?
        Java
        Python
        C
        C++
        JavaScript
        C#
### f. Programming is used for:
        💻 Software
        🌐 Websites
        📱 Mobile Apps
        🎮 Games
        🤖 AI & ML
        📊 Data Analysis
        ☁️ Cloud
        🏦 Banking
        🏥 Healthcare
        🏠 IoT & Smart Devices
## 8. Advantages of Java
      Easy to learn
      Platform independent
      Secure
      Object-oriented
      Portable
      Robust
      Large community support
      Rich libraries
      Excellent career opportunities

## 9. Disadvantages of Java
      Slower than C and C++
      Uses more memory
      Not suitable for low-level system programming
## # Java Installation & Setup

## 1. Install JDK

To develop Java applications, install the **JDK (Java Development Kit)**.

The JDK provides:

```text
JDK
├── java       → Runs Java applications
├── javac      → Compiles Java source code
├── jar        → Packages Java applications
├── javadoc    → Generates documentation
└── JVM + Java Class Libraries
```

---

## 2. Configure Environment Variables

### JAVA_HOME

`JAVA_HOME` points to the **JDK installation directory**.

Example:

```text
JAVA_HOME = C:\Program Files\Java\jdk-xx
```

### PATH

Add the JDK's `bin` directory to the system PATH:

```text
%JAVA_HOME%\bin
```

This allows commands such as `java` and `javac` to be used from any terminal.

---

## 3. Verify Installation

Open Command Prompt or Terminal and run:

```bash
java -version
```

Then:

```bash
javac -version
```

If both commands return a Java version, the JDK is correctly available.

---

## 4. Test Java Installation

Create:

```text
Hello.java
```

Code:

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello Java");
    }
}
```

### Compile

```bash
javac Hello.java
```

Output:

```text
Hello.class
```

### Run

```bash
java Hello
```

Output:

```text
Hello Java
```

---

## 5. Complete Java Setup Flow

```text
Install JDK
    ↓
Set JAVA_HOME
    ↓
Add JDK/bin to PATH
    ↓
java -version
javac -version
    ↓
Write Hello.java
    ↓
javac Hello.java
    ↓
Hello.class
    ↓
java Hello
    ↓
JVM executes bytecode
    ↓
Output
```

# 🎯 Interview Points

### What is required to develop Java applications?

> **JDK is required because it provides Java development tools and runtime components.**

### What is JAVA_HOME?

> **JAVA_HOME is an environment variable that points to the JDK installation directory.**

### Why is JDK/bin added to PATH?

> **To make Java commands such as `java` and `javac` available from any terminal.**

### How do you verify Java installation?

> Use `java -version` and `javac -version`.

### What happens during compilation?

> `javac` converts `.java` source code into `.class` bytecode.

### What happens when running the program?

> The `java` launcher starts the JVM, which loads and executes the bytecode.

## ⭐ Quick Revision

```text
JDK       → Develop Java applications
JAVA_HOME → JDK location
PATH      → Java command location
javac     → Compile
.java     → Source code
.class    → Bytecode
java      → Run
JVM       → Execute bytecode
```
## 11. Java Editions
### a. Java SE (Standard Edition)
Used for desktop applications and core Java development.
### b. Jakarta EE (formerly Java EE)
Used for enterprise and web applications.
### c. Java ME (Micro Edition)
Used for embedded systems and resource-constrained devices.
## 12. Editors/IDEs
### 1. What is an Editor?
An editor is software used to write and edit source code. It generally focuses on text/code editing and may require additional tools to compile and run programs.
#### Examples:
      Notepad
      Notepad++
      Sublime Text
      Visual Studio Code (VS Code)
### 2. What is an IDE?
IDE (Integrated Development Environment) is software that provides an integrated environment for writing, running, debugging, and managing code.
#### Examples:
      IntelliJ IDEA
      Eclipse
      NetBeans
      Visual Studio
### 3. Editor vs IDE
### Editor	                                       IDE
      Mainly used to write/edit code	Provides a complete development environment
      Usually lightweight	            Usually has more development features
      May need external compiler/tools	Often integrates compiler, debugger, build tools, etc.
      Example: Notepad	                  Example: IntelliJ IDEA
      Example: VS Code	                  Example: Eclipse
### 4. Is VS Code an Editor or IDE?
VS Code is primarily a source-code editor.
However, with extensions and additional development tools, it can provide many IDE-like features,
#### such as:
      Code completion
      Debugging
      Syntax highlighting
      Git integration
      Extensions
      Project management
      Java support
### 5. Visual Studio vs Visual Studio Code
Visual Studio and Visual Studio Code are different products.
Visual Studio → Full-featured IDE
Visual Studio Code → Lightweight, extensible code editor
### 6. Best Choice for Your Java Learning
Since you're learning Java from basics, you can use:
VS Code → lightweight and good for learning
or
IntelliJ IDEA → excellent dedicated Java development environment
or
Eclipse → widely used Java IDE and good for learning enterprise Java.
Recommended for your notes
#### Editors:
    Notepad
    Notepad++
    Sublime Text
    Visual Studio Code

#### IDEs:
    IntelliJ IDEA
    Eclipse
    NetBeans
    Visual Studio
#### Note:
    VS Code is primarily a code editor, but extensions can provide
    IDE-like features.
## 13.JDK, JRE and JVM
These are very important Java basics. Learn them before starting your first Java program.
### 1. JDK(Java Development Kit)
JDK (Java Development Kit) is a software development kit used to develop, compile, debug, document, package, and run Java applications.
JDK is used to develop Java Applications
#### Conceptually:
      JDK
       ├── Development Tools
       │    ├── javac (javac stands for Java Compiler. It is a command-line tool included in the    
                       JDK that compiles Java source code (.java) into bytecode (.class).)
       │    ├── java (run java programs)
       │    ├── jar (JAR = Java ARchive. It is used to package and distribute Java classes,
                     libraries, and resources in a single compressed file.)
       │    └── javadoc (Javadoc is a JDK tool used to generate HTML documentation from special  
                         comments written in Java source code.)
       │
       └── Runtime Components (Java runtime components include the JVM, Java Class Libraries, and  
                               supporting runtime files. They provide the environment required to
                               execute Java applications.)
            └── JVM (Executes Java Bytecode) + Libraries(Provides reusable java classes and APIs)
### 2. JRE(Java Runtime Environment)
JRE is a runtime environment that provides the JVM and Java class libraries required to execute Java applications.
JRE (Java Runtime Environment) is used to run Java applications.
#### Conceptually:
      JRE
      ├── JVM
      │    └── Executes Java bytecode (.class)
      │
      └── Java Class Libraries
           └── Provides pre-built Java classes and APIs
### 3. JVM(Java Virtual Machine)
JVM is the component of Java that runs Java bytecode and converts it into machine-level instructions that the computer can execute.
#### Conceptually:
      Java Program
          ↓
      Hello.java
          ↓
        javac
          ↓
      Hello.class (Bytecode)
          ↓
         JVM
          ↓
      Machine Code
          ↓
      Output
#### Main responsibilities of JVM
##### 1. Loads classes
         Loads .class files into memory.
##### 2. Verifies bytecode
         Checks bytecode for safety and correctness.
##### 3. Executes bytecode
         Executes Java bytecode using the execution engine.
##### 4. Memory management
         Manages memory areas used by Java programs.
##### 5. Garbage collection
         Automatically removes objects that are no longer needed.
##### 6. Provides platform independence
         The same Java bytecode can run on different operating systems when a suitable JVM is  
         available.
##### 7. JIT
         IT compiler converts frequently executed Java bytecode into native machine code during 
         program execution to make the program run faster.
         Uses JIT compilation to improve execution speed
#### Conceptually: 
      JVM
      └── Execution Engine
          ├── Interpreter(Execute lie by line bytecode to machine code)
          └── JIT Compiler(Compile and execute faster)
#### i.Source code:
Source code is the Java program written by a developer in a .java file.
#### ii. Bytecode:
Bytecode is the intermediate code generated by the Java compiler (javac) from the
### 4.Complete Java Flow
      Source Code
         .java
           ↓
         javac
           ↓
      Bytecode
         .class
           ↓
         JVM
           ↓
      Interpreter / JIT
           ↓
      Machine Code
           ↓
        Output 




