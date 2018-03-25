Garnet is a programming language that borrows features from the Ruby language and from the Turing language to extend PT Pascal

Garnet changes PT in the following ways:

- Ruby-style program, declaration and statement syntax, including removal of PT end-of-statement semicolons
- Turing single-line `%` comments replace PT { ... } and (* ... *)
- Ruby `modules` (anonymous classes) added
- Turing-style `string` type and operations replace PT `char` type
- Ruby general `case` statement with `else` added
- Ruby `elsif` clause added to `if` statements
- Ruby `unless` statement added
- Ruby/Turing-style general `do` replaces PT `repeat` statement


PT Pascal v3.1 (c) 2011 Queen's University, (c) 1980 University of Toronto
January 2011

This directory contains the sources and build scripts for 
PT Pascal version 3.1 as of January 2011.

To make all passes of PT Pascal, use the command "make".

To test the PT Pascal you have made, run the tests in 
the test subdirectory using the ptc and pti command scripts 
in that directory.

For a more challenging test, run the example programs
in the examples subdirectory using the ptc and pti command
scripts in that directory.

