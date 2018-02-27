# Lexical-Analyzer
This is a class project from the Compiler course.
This is the beginning of a series of programs that creates a compiler for the c- programming language.
The first program is the lexical analyzer that tokenize the input source file, and outputs a file of tokens.

The project description of the lexical analyzer: A few notable features:
0) the project's general goal is to construct a list of tokens capable
   of being passed to a parser.
1) comments should be totally ignored, not passed to the parser and
   not reported.
2) comments might be nested.
3) one line comments are designated by //
4) multiple line comments are designated by /* followed by */ in 
   a match up fashion for the nesting.
5) a symbol table* for identifiers should be constructed (as
   per recommendation of your text, I actually recommend
   construction of the symbol table during parsing).
   a) the symbol table should keep track of the identifier
   b) be extensible
   c) keep track of scope
   d) be constructed efficiently
   * this will not be evaluated until project 3
6) upon reporting of identifiers, their nesting depth/declarations
   should be displayed.
 

