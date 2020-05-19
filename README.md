# Decaf-Compiler
This is an assignment work for my Compiler Construction course.
It performs Lexical analysis on the source code.
After identifying a sequence it calls Syntax analyzer.
If syntax is correct it calls Semantic analyzer.
If the semantics of code upto to the cursor is correct it generates its Intermediate code, which is defined by rules.

It parse the whole code once. It loads source code in process memory, using memory mapping. It saves frequent I/O calls time.

I am using windows api for memory mapping. One can use this code in linux, using mmap. 
Let me know in case of issue!
