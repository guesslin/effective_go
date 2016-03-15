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
>`換句話說，想寫好 Go 程式，了解它的特性與慣用語法是重要的。`

It's also important to know the established conventions for programming in Go,
such as naming, formatting, program construction, and so on, so that programs
you write will be easy for other Go programmers to understand.
>`對於 Go 程式中所使用的慣例也應當瞭解，例如：命名、格式、程式架構等。如此才能令其他 Go 開發者易讀。`

This document gives tips for writing clear, idiomatic Go code.
>`此份文件將提供撰秘訣，讓開發者可以寫出清楚、道地的 Go 程式碼。`

It augments the [language specification](/ref/spec), the [Tour of
Go](//tour.golang.org/), and [How to Write Go Code](/doc/code.html), all
of which you should read first.
>`此文件涵蓋語言規範、Go 語言導覽以及如何撰寫 Go 程式，這些都是應該先讀的文章。`

### Examples
>`範例`

The [Go package sources](/src/) are intended to serve not only as the
core library but also as examples of how to use the language.
>`Go package source 不僅是核心函式庫，且目的在於提供函式庫使用之範例。`

Moreover,
many of the packages contain working, self-contained executable examples
you can run directly from the [golang.org](//golang.org) web site, such
as [this one](//golang.org/pkg/strings/#example_Map) (if necessary,
click on the word "Example" to open it up).
>`此外，許多 package 包含了 working, self-contained 的可執行範例，這些範例可直接在 golang.org 網站上運行，例如[這個](必要時，點選 "Example" 將它打開。)`

If you have a question about
how to approach a problem or how something might be implemented, the
documentation, code and examples in the library can provide answers,
ideas and background.
>`若對於如何解決問題或該怎麼實作某功能，在函式庫中的文件、程式碼及範例都可提供答案、想法與背景知識介紹。`
