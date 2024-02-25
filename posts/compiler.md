# What are compilers?
Compilers are the process that allows your human-readable code to be executable on the machine, it allows for your program to be able to run for the instructions that you have programmed with your programming language.

Compilers also are used in conjunctions with a Language Server, see ![this post](https://github.com/De-y/blog/blob/main/posts/what%20is%20an%20LSP.md).

# What are the steps that they take?
When you run your code or build it, your code goes through a nice process of going through a lexer, which will convert your code into tokens for the parser to analyze your code in tokens and will generate an AST, or an abstract syntax tree, which is a map of how your code works. Then after all that, the code will then be translated into binary for the machine to read.
