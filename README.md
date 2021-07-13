|**Windows, Linux, and macOS**|
|:--:|
|[![CI Build Status](https://github.com/gambit/gambit/workflows/Gambit%20-%20CI/badge.svg?branch=master)](https://github.com/gambit/gambit/actions?query=workflow%3A%22Gambit+-+CI%22)|

[![Join the chat at https://gitter.im/gambit/gambit](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/gambit/gambit?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![tip for next commit](http://prime4commit.com/projects/121.svg)](http://prime4commit.com/projects/121)

The Gambit Scheme system is a complete, portable, efficient and
reliable implementation of the Scheme programming language.

The latest official release of the system and other helpful documents
related to Gambit can be obtained from the Gambit wiki at:

  http://gambitscheme.org

<hr>

### Quick-install instructions for a typical installation

    git clone https://github.com/gambit/gambit.git
    cd gambit
    ./configure        # --enable-single-host optional but recommended
    make               # build runtime library, gsi and gsc (add -j8 if you can)
    make modules       # compile the builtin modules (optional but recommended)
    make check         # run self tests (optional but recommended)
    make doc           # build the documentation
    sudo make install  # install

Detailed installation instructions are given in the file [INSTALL.txt](https://github.com/gambit/gambit/blob/master/INSTALL.txt).

<hr>

### SRFIs provided

0: [Feature-based conditional expansion construct](https://srfi.schemers.org/srfi-0/srfi-0.html) (builtin)

2: [AND-LET*: an AND with local bindings, a guarded LET* special form](https://srfi.schemers.org/srfi-2/srfi-2.html)

4: [Homogeneous numeric vector datatypes](https://srfi.schemers.org/srfi-4/srfi-4.html) (builtin)

6: [Basic String Ports](https://srfi.schemers.org/srfi-6/srfi-6.html) (builtin)

8: [receive: Binding to multiple values](https://srfi.schemers.org/srfi-8/srfi-8.html) (builtin)

9: [Defining Record Types](https://srfi.schemers.org/srfi-9/srfi-9.html) (builtin)

16: [Syntax for procedures of variable arity](https://srfi.schemers.org/srfi-16/srfi-16.html) (builtin)

18: [Multithreading support](https://srfi.schemers.org/srfi-18/srfi-18.html) (builtin)

21: [Real-time multithreading support](https://srfi.schemers.org/srfi-21/srfi-21.html) (builtin)

22: [Running Scheme Scripts on Unix](https://srfi.schemers.org/srfi-22/srfi-22.html) (builtin)

23: [Error reporting mechanism](https://srfi.schemers.org/srfi-23/srfi-23.html) (builtin)

26: [Notation for Specializing Parameters without Currying](https://srfi.schemers.org/srfi-26/srfi-26.html)

27: [Sources of Random Bits](https://srfi.schemers.org/srfi-27/srfi-27.html) (builtin)

28: [Basic Format Strings](https://srfi.schemers.org/srfi-28/srfi-28.html)

30: [Nested Multi-line Comments](https://srfi.schemers.org/srfi-30/srfi-30.html) (builtin)

31: [A special form rec for recursive evaluation](https://srfi.schemers.org/srfi-31/srfi-31.html)

39: [Parameter objects](https://srfi.schemers.org/srfi-39/srfi-39.html) (builtin)

41: [Streams](https://srfi.schemers.org/srfi-41/srfi-41.html)

64: [A Scheme API for test suites](https://srfi.schemers.org/srfi-64/srfi-64.html) (incomplete implementation)

69: [Basic hash tables](https://srfi.schemers.org/srfi-69/srfi-69.html)

88: [Keyword objects](https://srfi.schemers.org/srfi-88/srfi-88.html) (builtin)

132: [Sort Libraries](https://srfi.schemers.org/srfi-132/srfi-132.html)

158: [Generators and Accumulators](https://srfi.schemers.org/srfi-158/srfi-158.html)

179: [Nonempty Intervals and Generalized Arrays (Updated)](https://srfi.schemers.org/srfi-179/srfi-179.html)

193: [Command line](https://srfi.schemers.org/srfi-193/srfi-193.html) (builtin)

219: [Define higher-order lambda](https://srfi.schemers.org/srfi-219/srfi-219.html)
