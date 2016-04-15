## Computer science

### Theory

* Sipser, 2012 (3e) / 2006 (2e) / 1996 (1e). *Introduction to the Theory of Computation*

  This is the standard intro to CS theory at many (probably most) universities.
  The latest edition is very expensive (even used). Older editions are generally
  good alternatives, because in newer editions Sipser added some new sections
  but he didn't revise the old ones much.

* Hopcroft, Ullman, 1979. *Introduction to Automata Theory, Languages and Computation*
  * Hopcroft, Motwani, Ullman, 2006. *Introduction to Automata Theory, Languages, and Computation, 3rd Edition*

  A classic and influential introduction to computer science theory. Somewhat more challenging than Sipser.

* Cohen, 1991. *Introduction to Computer Theory*

  Another classic, this one is known for its readability.

* Brookshear, 1989. *Theory of Computation: Formal Languages, Automata, and Complexity*

  Well-liked for its accessibility. Unfortunately, it's still pretty expensive for such an old book:
  about $90 used at the time of this writing. That its price has held up so long is a testament to its
  quality, but it also makes it harder to justify owning it when newer books covering the same material
  can be bought for $10-20.

* Kinber, Smith, 2001. *Theory of Computing: A Gentle Introduction*

  This is a shorter book, which might be appealing if you're in a hurry.
  It covers finite automata, context-free languages, Turing machines, undecidability
  and computational complexity, devoting 20-40 pages to each of these topics.
  It costs too much, though; for the price, you might as well buy Sipser's 2nd Edition.

### Data structures and algorithms

Data structures and algorithms are two sides of the same coin. (In 1976, Niklaus Wirth published a book on the subject called *Algorithms + Data Structures = Programs*.)

#### Standard topics

These books cover the basics, that is, the core algorithms that everyone needs to know: sorting, tree traversal, etc.

* Sedgewick and Wayne, 2011 (4e). *Algorithms*

  This is the latest incarnation of a long series of algorithms books by Robert Sedgewick.
  (Wayne joined more recently as co-author.)
  There are various other versions that feature specific example languages:
  *Algorithms in C++*, *Algorithms in Java*, *Algorithms in C*.
  This version uses Java, so I guess it supersedes the previous *Algorithms in Java*.
  Its website -- http://algs4.cs.princeton.edu/ --
  has links to Sedgewick's two free online algorithms courses.
  Considering its use of code to illustrate algorithms, its reasonable price and its accompanying
  courses, for most people this will probably be the best choice for a first book in algorithms.
  And if you're cheap, there are lots of used copies of the various older editions
  floating about, since this is a popular series.
  (The courses don't require the textbook, by the way.
  However, if you're going to be a programmer you really ought to have at least one
  algorithms book around anyway, even if it's the only computer book you own.)

* Cormen, Leiserson, Rivest, Stein, 2009. *Introduction to Algorithms, Third Edition*

  * Cormen, Leiserson, Rivest, Stein, 2001. *Introduction to Algorithms, Second Edition*
  * Cormen, Leiserson, Rivest, 1990. *Introduction to Algorithms*

  AKA CLRS.
  This is the standard book on algorithms, and it's a big, fat monster: about 1000 large-format pages.
  Currently it's pretty reasonably priced, though you can still save money by buying one of the older
  editions. There are arguably better approaches for learning the subject, but most people will at
  least want to have this one around as a reference.

* Aho, Hopcroft, Ullman, 1974. *The Design and Analysis of Computer Algorithms*

  A classic book on algorithms. I found the beginning of this one to be not so great for
  learning the material the first time.

* Skiena, 2008 (2e). *The Algorithm Design Manual*

  This book focuses somewhat more on how to do and evaluate algorithms vs. how to analyze them mathematically. There is a 1997 1st Edition, but it's hard to find and not a lot cheaper than a used copy of the 2nd Edition.

* Knuth, *The Art of Computer Programming*

  This collection of bulky tomes is a legendary institution in the field of computer science, as is their author.
  It's not the most up-to-date, but it is probably the most complete in-depth examination of algorithms.
  I don't think very many people who don't have a Ph.D. in CS have read all of the volumes...
  but if you have, it afford certain bragging rights.

* TODO: ALGORITHMS -- Manber. INTRO -- SICP ( https://mitpress.mit.edu/sicp/ ), HTDP ( http://www.htdp.org/ ), others?.

#### Specialized algorithms

These focus on some more specialized areas of algorithms.

* Motwani and Raghavan, 1995. *Randomized Algorithms*
* Mitzenmacher and Upfal, 2005. *Probability and Computing: Randomized Algorithms and Probabilistic Analysis*

* Papadimitriou and Steiglitz, 1982. *Combinatorial Optimization: Algorithms and Complexity* (c)

  There's a 1998 Dover edition, which has some corrections but isn't substantially different from the original 1982 version. This book has a unique choice of topics. It starts out with the linear programming problem and the simplex algorithm, a topic usually covered more in applied mathematics. Then, about halfway through, it switches gears and begins to look at graph algorithms. The point, as expressed in the introduction, is to look at the similarities between these continuous and discrete optimization problems, and how the fine differences between them result in dramatic differences in computational complexity. Thus, I think it can be said that, in a sense, this book teaches algorithms as a means to the end of understanding complexity.

### Programming language theory

* Pierce, *Types and Programming Languages*
* Turbak, Gifford, Sheldon, 2008. *Design Concepts in Programming Languages*
* Winskel, *The Formal Semantics of Programming Languages*
* Slonneger, Kurtz, 1995. *Formal Syntax and Semantics of Programming Languages*
* Mitchell, 1996. *Foundations for Programming Languages*
* Pierce (ed), 2004. *Advanced Topics in Types and Programming Languages*

### Compilers and interpreters

* Krishnamurthi, 2012. *Programming Languages: Application and Interpretation*

  The last version of this incarnation of the book. It goes with an online course, which is available here: https://cs.brown.edu/courses/cs173/2012/
  
  Together, these make an excellent introduction to the design and implementation of programming languages using an interpreter.

* Krishnamurthi, 2015. *Programming and Programming Languages*

  Krishnamurthi's latest incarnation of his intro to PLs.

  This book is under constant revision. Currently the latest stable version is here:
  http://papl.cs.brown.edu/2015/

* Aho, Sethi, Ullman, 2006. *Compilers: Principles, Techniques, and Tools, Second Edition*

  * Aho, Sethi, Ullman, 1986. *Compilers: Principles, Techniques, and Tools*

  AKA "The Dragon Book" due to its well-known cover illustration.
  This is the standard book in the field of compilers, both as an introduction and as a reference.
  This is one book where it's probably worthwhile to buy the latest edition, since compilers
  *have* changed a lot over the years. (There are even older and cheaper editions, though, as this
  title has roots in *Principles of Compiler Design* by Aho and Ullman.)

* Scott 2015 (4e), 2009 (3e), 2005 (2e), 1999 (1e), *Programming Language Pragmatics*

  This book won't teach you how to build a compiler or interpreter, but it's a great reference on
  lots of topics that come up when designing and implementing them. As such, it's a good *second*
  book on the subject.

* TODO: Fischer/LeBlanc, Appel (ML, CWC), Wolfe, EOPL, Muchnick, Cooper/Torczon.

### TODO

Data structures, databases, systems, FP
