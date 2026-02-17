# learning_java
 notes of java

**** Day 01 ******
#INTRODUCTION TO JAVA 
Before C/C++ --> Assembly language exists 

 Before JAVA ---> during 1980s / 90s  C/C++ exists (fast ,simple ,and low level language which is very close to hardware system ,has very less Abstraction levels.
WHY JAVA?
Source code  converted via ---> compiler --->  to machine code .
problem with C/C++ (Portability , simplicity , security )
compiler is platform dependent as well as C/C++ is also platform dependent . codes are not portable . we will have to compile source code again and again for different platform .
Platform is combination of :-
1)processors 
2)operating system 

To execute code of C/C++ file  we have to talk with Operating system . Different OS have their own system libraries to save raw files  , to allocate spaces for variables . this is the reason why machine code generated differently for different OS 
examples of OS MACOS and WINDOWS

Processors consists Trillions /Billions  Number of Transistors, alignment of transister are different for different processors . current pass through transistor gives value 1 otherwise 0.
different processors gives different binary values.
To Interact with Processors 
Program interact via ISA with processors . ISA Stands for Instruction Set Architecture.
ISA tells  how to ADD ,LOAD , STORE , JUMP Data with Processors.

JAVA is 
1)PORTABLE
2) SIMPLE 
3) SECURE 

# CONCEPT OF BYTECODE
It solves portability problem.
java Source code -----> compiler ---> BYTECODE ----> Platforms 
every platform consist java virtual machine (JVM) which converts bytecode into Machine code according to that platform. BYTECODE is platform independent  But  JVM is platform dependent 

IN C/C++ there were some complex topic like 1) POINTERS 2) MULTIPLE INHERITANCES 3) MANNUAL MEMORY ALLOCATION AND DEALLOCATION
JAVA removes these complexity 

#DAY 02 
**JVM VS JDK VS JRE ****
JDK---> JRE ---->JVM (jre ,jvm are inside of jdk)
JDK --> java development kit.
JRE--> java runtime environment.
JVM--> java virtual machine.It translate bytecode into machine code.

To convert bytecode into machine code we required software 
1) compiler :- it converts source code into machine code completely at once. 
2) interpreter -: It convert source code into machine code line by line.

Java is both compiled and interpreted language.
jvm does 
innitially 
Bytecode---> Interpreter-----> Machine Code
later on 
Bytecode---> Interpreter + JIT(just in time ) Compiler  ---> Machine Code.
frequently used source code converted by JIT into machine code . other  source code converted by interpreter.

JRE 
(JVM + class libraries)

JDK 
(compiler,debugger,java docs ,jvm ,jre.....etc ).
It consists all things that required to write  and run java code 












  



