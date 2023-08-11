---
title: VBA is the Best Programming Language Ever
layout: post
author: Matt Badger
date: 2023-08-11
categories: python, vba, programming languages
---

I need to be productive today, so naturally I just read a "X is a better than Python, Python is
crap" post on Mastodon, and I decided to write blog post to vent. 

## My Language Experience

I have been paid to write computer programming code since 2006, when I started using VBA in my first
post-university job as a risk analyst for an energy company. Since then, I have written computer
programming code for money in:

- VBA (First job)
- SQL (ibid)
- C++ (ibid)
- GAP (Computer algebra programming language, during my Masters)
- Maxima (Computer algebra programming language, during my PhD)
- Lisp (during my PhD)
- C# (As a quantitative analyst, after my PhD)
- Python (When I ran out of road trying to use C#)
- R (A little)
- JavaScript/TypeScript (Moonlighting as a full-stack dev)
- Go (Minimal, but enlightening)
- Fortran (Now I really am a software engineer)

In addition, I've played around with PHP, Haskell and, most recently, Rust. I can definitely see
myself using the latter in production in the next year.

I have no formal computer science training, but I do have three mathematics degrees and spent my
PhD working on and extending computer algebra systems, so hopefully that gives my some credit with
the CS crowd. I also share a birthday (modulo one year) with Donald Knuth, which must be worth
_something_.

Finally, I'll add that at no point have I been employed primarily as a software engineer. Today
I am a data scientist; before that I was a quant. Everything I write is tied very closely to a
business need, often one that I myself have identified.


## What is the Best Programming Language Ever?

The best programming language ever is Visual Basic for Applications, a.k.a. VBA. The reasons for
this are so obvious I hope I don't need to enumerate them here, but for the sake of completeness,
here we are:

1. It's already installed on your computer. Well, not yours, because you're a *nix douchebag who
   wrote their first `Makefile` before their seventh birthday. On normal people's computers, with
   Windows and Excel.
2. You can use Excel as the GUI to output information where a normal person, even more normal than
   you who can program, can read it. They also don't need to install anything on their machine
   because they already have Excel.
3. You can _record_ VBA without writing anything yourself. Just hit the record button in Excel, do
   whatever you need to, and then hit stop. Even if it doesn't do everything you need to
   immediately, it's a significant help.
4. Threading? Ownership? Type safety? Copy-on-write? All trivial computer nerd nonsense that you
   don't need to worry about with VBA.


## You are Deranged

Ok, I'll admit that the previous section was perhaps a bit much, but I want to highlight my major
issue that I believe makes software engineers so dismissive of Python: software engineers care
deeply about programming languages. The rest of us care deeply about business insights and results.
As a result, the loss function that they are using to evaluate a programming language looks entirely
at the inherent properties of the language itself and not, say, how people use it or how quickly
they can learn it. I started using Rust for Advent of Code last year (before my immediate family
was struck down by 'flu, which ended that rather quickly). It's a great language, it solves a _lot_
of the problems with C++ and has quite clearly been throughly considered in its design. But if I
have zero programming language experience and want to answer a business question before the end of
the week, do I try using Rust or Python?

Also, computer programmers–er, sorry, software _engineers_–are absolute snobs, and Python's
popularity is enough to write it off as shit. Don't read _50 Shades_, read _Infinite Jest_, don't
listen to X Factor winners, listen to Glenn Gould's _Goldberg Variations_, and don't look at
Instagram, look at Artemisia Gentileschi's _Judith Slaying Holofernes_.


## I was a Language Snob

From the end of 2012, for three years, I spent a large proportion of my time writing C#. Enough time
that I was for the first time really deep in the weeds of a programming language. I had Albahari and
Albahari's _C# 5 In a Nutshell_ on my desk at work and would reference it most days; I then took it
home to read at the weekends (oh life before children). I did a lot of multi-threaded work for Monte
Carlo simulations and used Microsoft's _Solver Foundation_ for for linear programming. I wrote
hedging optimisation and option valuation software, and ran it every day. And I hated Python.

That I hadn't actually written any Python before wasn't a problem, I didn't need to write it to hate
it. It used duck typing, and whitespace to denote blocks, and threading was a nightmare. Absolute
shit.

Then something happened. I was learning Latin at CityLit, and wanted to write a little website for
testing my grammar. amo amas amat amamus amatis amant, et cetera. I had written PHP during my
undergraduate days but that was absolute trash, and Flask was really becoming a thing so I decided
to write it in Python. The important part was that I wanted to test my Latin grammar, _not_ spend
a thousand hours using a programming language.

It turns out that when you spend your days using a _real_ programming language, you can get
up-to-speed with a toy language like Python pretty quickly. I spent a lot of time at work working on
my Latin website, largely because writing software afforded me so much spare time and my computer
monitor faced a window so people didn't know I wasn't being productive.

Anyway, after about a month I was done, but writing Python bought me into contact with the other
killer Python feature you dismiss if you're a lanuage snob: the package ecosystem is _massive_.
This was also right around the time that the original author of _Solver Foundation_ left Microsoft,
and I spent a lot of time with that library and was worried of being caught out. So I started using
NumPy, and pandas, and SciPy, and matplotlib. And I haven't looked back.


## X is Better than Y

In mathematical optimisation, an optimisation problem combines a _cost_ or _loss_ function, $f$,
which maps some element of a set $A$ to the real numbers $\mathbb{R}$, and an objective, usually
some $a_0 \in A$ such that $f(a_o) \leq f(a) \forall a \in A$. In our case, the set $A$ is "all
programming languages ever", and the function $f$ maps a programming language to its score, where
lowest is best. Then to solve the problem of "what is the best programming language ever", all we
need do is work out how to define $f$ and apply it to every programming language we can think of.

Except this is wrong and patently stupid. No $f$ exists. It's like asking for the best vehicle.
Is a bike better than a helicopter? Only an idiot would entertain the possibility of answering such
a question. Are you trying to get around your town doing a few light chores along the way? Get on
your bike. Are you trying to get aerial photos of Sydney habour? Probably a helicopter is better.
Of course being good mathematicians we might seek to define a higher-order function that considers
the entire set of functions $f$ that map a programming language to a score, and use some metric
for weighting the outcomes to reach a final best ever programming language, but hopefully it's clear
that trying to do that is also nonsense.


## Wake Up Sheeple

One of the best things about doing a mathematics PhD was existing in proximity to some of the
cleverest people on the planet. I didn't have imposter syndrome, I had No Actually You're Correct,
These People Are Intellectual Titans And You Are A Moron syndrome. In the years since I left
academia, I've found my groove in a much more complete way than while at university, and still
worked (and work!) with some extremely clever people, but it taught me humility in the face of the
evidence that remains to this day. And that in itself has been fantastically useful. If I don't
understand something, I ask. If there's no-one to ask, then I sit down and read and work until I
understand. Sometimes, I run out of steam and things intervene, like trying to learn Rust last
Christmas. Other times, I get so deep into a topic that I find myself editing Fortan code almost as
old as I am and it all seems so trivial.

It's straightforward to point to problems with Python; trying to reach full typedness is often a
nightmare. If you're not using a compiled library than it can get slow to the point that it does
impact the speed of your work. But if you dismiss Python as crap and worthless, and attribute its
popularity to people being sheep (who was the first sheep?!?!?!), its probably worth considering
that you are either being intellectually dishonest, or lack the humility to admit you don't
understand, or both.




