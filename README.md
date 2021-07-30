# Intro to Ruby

## Learning Goals

- Understand how to learn a new programming language
- Learn the benefits and philosophy of Ruby as a language

## Introduction

Throughout your career as a developer, it's highly likely that you'll be
expected to learn multiple languages depending on the companies you work for and
the kind of projects you're working on. After gaining confidence with one
language, like JavaScript, it can feel overwhelming and even scary to start over
from scratch with a totally new language.

Thankfully, we can tell you from experience that learning a new programming
language isn't so bad! While you were learning JavaScript, you were also
learning some other (even more) important skills: how a computer program works;
how to **debug code**; how to **search for help** when you're stuck; how to
**think like a developer**; and **how you like to learn**.

With those tools at your disposal, learning your second language (and your
third, and fourth) will be easier than the first.

To help you on this journey of your second language, Ruby, this curriculum will
start by introducing new syntax and showing the similarities and differences
between Ruby and JavaScript (they have more in common than you may think). Once
you've learned the fundamentals, we'll explore what makes Ruby unique and start
building new applications.

As you're learning, it's ok (and completely normal) to make mistakes: every
developer that switches between languages forgets syntax (is it `.toUpperCase()`
or `.upcase`?) and needs to [look at the documentation][ruby docs upcase]
regularly. The most important things are to **write code** to develop your
muscle memory, and trust that you'll get better with practice.

## What is Ruby and Where Did it Come From?

Ruby is a dynamic object-oriented, general-purpose programming language. It was
designed and developed in the mid-1990s by Yukihiro "Matz" Matsumoto in Japan.
Matsumoto, often referred to as "Matz", first developed the idea for Ruby in the
early 1990s. From Matz's post to the _ruby-talk_ mailing list in 1999:

> I was talking with my colleague about the possibility of an object-oriented
> scripting language. I knew Perl (Perl4, not Perl5), but I didn't like it
> really, because it had the smell of a toy language (it still has). The
> object-oriented language seemed very promising. I knew Python then. But I
> didn't like it, because I didn't think it was a true object-oriented language
> — OO features appeared to be add-on to the language. As a language maniac and
> OO fan for 15 years, I really wanted a genuine object-oriented, easy-to-use
> scripting language. I looked for but couldn't find one. So I decided to make
> it.

## Why Do Developers Love It?

Every programming language was originally designed to solve some kind of
problem. For example, JavaScript was created by Brendan Eich help developers
make web pages interactive.

Matz designed Ruby in order to **make programmers happy**. He developed a
programming language that would be simple to use, elegant to write, but capable
of building vastly complex things. A few of his own thoughts on Ruby sum it up
best:

> The goal of Ruby is to make programmers happy. I started out to make a
> programming language that would make me happy, and as a side effect it’s made
> many, many programmers happy.
>
> I hope to see Ruby help every programmer in the world to be productive, and to
> enjoy programming, and to be happy. That is the primary purpose of Ruby
> language.
>
> — Yukihiro Matsumoto

![Yukihiro Matsumoto](http://readme-pics.s3.amazonaws.com/imgres-1.jpg)

## What Can Ruby Do?

In the first two phases of the program, you used JavaScript primarily for one
thing: to build **client-side** web applications that run in the browser. While
it's true that you can use JavaScript to create other kinds of programs as well
thanks to Node, we've stayed true to the original intent of the language by
using it for frontend development.

Building web applications in JavaScript means we have all kinds of great tools
at our disposal thanks to working in the browser environment:

- Make network requests
- Update the DOM
- Listen for events
- Debug our code in the browser's developer tools

But it also means working in a **sandboxed environment** that can't take full
advantage of everything our computers are capable of, like accessing the file
system, or connecting directly to a database, or listening for HTTP requests.

Ruby, on the other hand, **can't** run in the browser. Learning Ruby means you
can build different kinds of programs: **server-side** applications. Writing
these kind of applications will mean familiarizing yourself with a new
environment. It also means you'll have a new set of tools and features at your
disposal, which is awesome! We can use Ruby to do all sorts of things, like

- Read and write files
- Listen for network requests and send responses
- Connect to a database to access and update data

Thanks to Ruby's flexibility, it means we can make all kinds of different
applications, not just web applications:

- Command line interfaces
- Web servers
- Games
- Web scrapers

Since you'll be learning a new environment, it's important to familiarize
yourself not only with Ruby's syntax, but also how to run and debug Ruby code.
Make sure to code along with the lessons to come so that you can gain confidence
in how to not only write code, but also to check what your code is doing and
explore all the great features Ruby has to offer.

Be sure to check out the resources below as well, and bookmark them for future
reference!

## Resources

- [About Ruby](https://www.ruby-lang.org/en/about/)
- [Ruby documentation][ruby docs]
- [Ruby Style Guide](https://rubystyle.guide/)
- [Ruby VSCode Extension](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby)
- [Ruby Solargraph VSCode Extension](https://marketplace.visualstudio.com/items?itemName=castwide.solargraph)

[ruby docs]: https://ruby-doc.org
[ruby docs upcase]: https://ruby-doc.org/core-2.7.3/String.html#method-i-upcase
