MCPP is a portable C/C++ preprocessor. It was hosted on
[sourceforge](http://sourceforge.net/projects/mcpp/), and has not been updated
since 2008. 

The author is Kiyoshi Matsui <kmatsui@t3.rim.or.jp>.

This is just a github mirror of the original one.

**Patching**

(h8liu) I applied a [patch](https://trac.macports.org/attachment/ticket/30036/patch-mcpp-comment-parsing-fix)
that fixes the line comment bug when `-C` and `-P` are both used.

(Sehun) Added new option "`-Y <file>`". The `<file>` contains a set of include directories in line-by-line fashion.

**Building (Windows)**

Using Developer Command Prompt for VS 2022, enter the `src` folder and type `nmake`.
