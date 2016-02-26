Introduction
------------

Go is a new language.
Go 是一種嶄新的語言。

Although it borrows ideas from existing languages,
it has unusual properties that make effective Go programs different in
character from programs written in its relatives.
>`雖然 Go 借鏡了許多既有程式語言，但 Go 程式本身也具有獨特性。`

A straightforward
translation of a C++ or Java program into Go is unlikely to produce a
satisfactory result—Java programs are written in Java, not Go.
>`直接以撰寫 C++ 或 Java 程式的思維來寫 Go 程式，恐怕得到的結果。因為 Java 程式是用 Java 寫的，而非 Go 。`

On the
other hand, thinking about the problem from a Go perspective could
produce a successful but quite different program.
>`另一方面，以 Go 思維來解決問題、撰寫程式，將可寫出成功且與眾不同的程式。`

In other words, to
write Go well, it's important to understand its properties and idioms.
It's also important to know the established conventions for programming
in Go, such as naming, formatting, program construction, and so on, so
that programs you write will be easy for other Go programmers to
understand.

This document gives tips for writing clear, idiomatic Go code. It
augments the [language specification](/ref/spec), the [Tour of
Go](//tour.golang.org/), and [How to Write Go Code](/doc/code.html), all
of which you should read first.

### Examples

The [Go package sources](/src/) are intended to serve not only as the
core library but also as examples of how to use the language. Moreover,
many of the packages contain working, self-contained executable examples
you can run directly from the [golang.org](//golang.org) web site, such
as [this one](//golang.org/pkg/strings/#example_Map) (if necessary,
click on the word "Example" to open it up). If you have a question about
how to approach a problem or how something might be implemented, the
documentation, code and examples in the library can provide answers,
ideas and background.
