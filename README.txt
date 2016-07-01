//===----------------------------------------------------------------------===//
// FORK OF LLVM Clang, by FabiC.net
//===----------------------------------------------------------------------===//

* __FC.2014-09-24 :__
  Forked it from https://github.com/llvm-mirror/clang
  Set 'master' to v3.5.0 + a couple of "personnal" commits.

* __FC.2016-07-01 :__
  Years after, re-applying Clang patch for default `libc++` against
  [`release_38`](https://github.com/llvm-mirror/clang/tree/release_38)

* See <https://github.com/fabic/llvm-clang> for the playground project that
  includes this one thing as a Git submodule.

* See the __patch__ file
  [`patches/fabic-clang-linux-libcxx-default.patch`](https://github.com/fabic/llvm-clang/blob/master/llvm-clang/patches/fabic-clang-linux-libcxx-default.patch)
  for a diff of the few changes brought here to the code of Clang.
  Apply with ex. `patch -Np1 -b -i ../patches/fabic-clang-linux-libcxx-default.patch`

//===----------------------------------------------------------------------===//
// C Language Family Front-end
//===----------------------------------------------------------------------===//

Welcome to Clang.  This is a compiler front-end for the C family of languages
(C, C++, Objective-C, and Objective-C++) which is built as part of the LLVM
compiler infrastructure project.

Unlike many other compiler frontends, Clang is useful for a number of things
beyond just compiling code: we intend for Clang to be host to a number of
different source-level tools.  One example of this is the Clang Static Analyzer.

If you're interested in more (including how to build Clang) it is best to read
the relevant web sites.  Here are some pointers:

Information on Clang:              http://clang.llvm.org/
Building and using Clang:          http://clang.llvm.org/get_started.html
Clang Static Analyzer:             http://clang-analyzer.llvm.org/
Information on the LLVM project:   http://llvm.org/

If you have questions or comments about Clang, a great place to discuss them is
on the Clang development mailing list:
  http://lists.llvm.org/mailman/listinfo/cfe-dev

If you find a bug in Clang, please file it in the LLVM bug tracker:
  http://llvm.org/bugs/
