//===----------------------------------------------------------------------===//
// C Language Family Front-end
//===----------------------------------------------------------------------===//

Welcome to Chime.  This is a port of clang and is a compiler front-end for the 
C family of languages (C, C++, Objective-C, and Objective-C++) which is built as 
part of the LLVM compiler infrastructure project.

Unlike many other compiler frontends, Chime is useful for a number of things
beyond just compiling code: we intend for Chime to be host to a number of
different source-level tools.  One example of this is the Chime Static Analyzer.

Chime intends to be a more "pluggable" version of clang. It's goal is to be
easier to modify the compiler and add new languages while retaining clang's
robustness and performance.

If you're interested in more (including how to build Chime) it is best to read
the relevant web sites for Clang.  Here are some pointers:

Information on Clang:              http://clang.llvm.org/
Building and using Clang:          http://clang.llvm.org/get_started.html
Clang Static Analyzer:             http://clang-analyzer.llvm.org/
Information on the LLVM project:   http://llvm.org/

If you have questions or comments about Clang, a great place to discuss them is
on the Clang development mailing list:
  http://lists.cs.uiuc.edu/mailman/listinfo/cfe-dev

If you find a bug in Clang, please file it in the LLVM bug tracker:
  http://llvm.org/bugs/
