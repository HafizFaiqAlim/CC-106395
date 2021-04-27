# CC-106395
# assignment 2

IS JAVA IS INTERPRETER OR COMPILER??
Java can be considered both a compiled and an interpreted language because its source code is first compiled into a binary byte-code. This byte-code runs on the Java Virtual Machine (JVM), which is usually a software-based interpreter.
Java compilers are designed in such a way that converts source code into platform independent form i-e byte codes. These byte codes are then converted to machine code by interpreter. This is how compiler and interpreter both used in one language. Any system having JVM will run these byte codes.
Java implementations typically use a two-step compilation process. Java source code is compiled down to bytecode by the Java compiler. The bytecode is executed by a Java Virtual Machine (JVM). Modern JVMs use a technique called Just-in-Time (JIT) compilation to compile the bytecode to native instructions understood by hardware CPU on the fly at runtime.

Some implementations of JVM may choose to interpret the bytecode instead of JIT compiling it to machine code, and running it directly. While this is still considered an "interpreter," It's quite different from interpreters that read and execute the high level source code (i.e. in this case, Java source code is not interpreted directly, the bytecode, output of Java compiler, is.)

It is technically possible to compile Java down to native code ahead-of-time and run the resulting binary. It is also possible to interpret the Java code directly.

To summarize, depending on the execution environment, bytecode can be:

compiled ahead of time and executed as native code (similar to most C++ compilers)compiled just-in-time and executedinterpreteddirectly executed by a supported processor (bytecode is the native instruction set of some CPUs)

Sources 
https://stackoverflow.com/questions/1326071/is-java-a-compiled-or-an-interpreted-programming-language
