# 1
>Pick an open source implementation of a language you like. Download the source code and poke around in it. Try to find the code that implements the scanner and parser. Are they handwritten, or generated using tools like Lex and Yacc? (.l or .y files usually imply the latter.)

In dart the scanner and parsers are written in itself. 
https://github.com/dart-lang/sdk/tree/main/pkg/_fe_analyzer_shared/lib/src/scanner
https://github.com/dart-lang/sdk/tree/main/pkg/_fe_analyzer_shared/lib/src/parser

# 2
>Just-in-time compilation tends to be the fastest way to implement dynamically typed languages, but not all of them use it. What reasons are there to not JIT?

Complexity, startup time

# 3
>Most Lisp implementations that compile to C also contain an interpreter that lets them execute Lisp code on the fly as well. Why?

Possibility to run without C toolchain, REPl, dynamic features.
