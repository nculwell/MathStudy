## Computer science

### Basic programming and intros to CS

* [*Structure and Interpretation of Computer Programs*](https://mitpress.mit.edu/sicp/full-text/book/book.html)
* Felleisen, Findler, Flatt, Krishnamurthi. *How to Design Programs: An Introduction to Programming and Computing* ([**FREE ONLINE**](http://www.htdp.org/), [1e](https://smile.amazon.com/dp/0262062186))
* Zelle. *Python Programming: An Introduction to Computer Science*
* [*CS Unplugged*](http://csunplugged.org/books/) (for kids)
* Eckel. *Thinking in Java* ([TIJ website](http://www.mindviewinc.com/Books/TIJ4/); old editions are free)
* [Haverbeke. *Eloquent Javascript*](http://eloquentjavascript.net/)
* Downey. *How to Think Like a Computer Scientist* ([C++ Version](http://greenteapress.com/thinkcpp/index.html), [OCaml Version](http://greenteapress.com/thinkocaml/index.html), [Learning with Python](http://greenteapress.com/thinkpython/thinkCSpy/index.html), [Python for Software Design](http://greenteapress.com/thinkpython/pythonsd.html))

* Friedman and Felleisen. *The Little Schemer* ([4e](https://smile.amazon.com/dp/0262560992))

  Sequels:

  * Friedman and Felleisen. *The Seasoned Schemer* ([1e](https://smile.amazon.com/dp/026256100X))
  * Friedman, Byrd, Kiselyov. *The Reasoned Schemer* ([1e](https://smile.amazon.com/dp/0262562146))
  * Friedman and Eastlund. *The Little Prover* ([1e](https://smile.amazon.com/dp/0262527952))

* Aho and Ullman, 1994. *Foundations of Computer Science: C Edition* ([1e](https://smile.amazon.com/dp/0716782847))

### Theory

See also: [Logic and Discrete Math](LogicDiscrete.md)

#### Intro

* Sipser, 2012 (3e) / 2006 (2e) / 1996 (1e). *Introduction to the Theory of Computation*

  This is the standard intro to CS theory at many (probably most) universities.
  The latest edition is very expensive (even used). Older editions are generally
  good alternatives, because in newer editions Sipser added some new sections
  but he didn't revise the old ones much.

* Hopcroft, Ullman, 1979. *Introduction to Automata Theory, Languages and Computation*
  * Hopcroft, Motwani, Ullman, 2006. *Introduction to Automata Theory, Languages, and Computation, 3rd Edition*

  A classic and influential introduction to computer science theory. Somewhat more challenging than Sipser.

* Cohen, 1991. *Introduction to Computer Theory*

  Another classic, this one is known for its readability. Covers formal languages, automata theory and Turing machines.

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

* Kozen, 1997. *Automata and Computability*

  Kozen's intro-level book. Somewhat shorter than others (e.g. Sipser, Hopcroft/Motwani/Ullman). Includes some different topics. Has homework sets, with some select hints and solutions provided.

* Kozen, 2006. *Theory of Computation*

  Graduate-level.

#### Complexity

* Papadimitriou, *Computational Complexity*

* Arora and Barak, *Computational Complexity: A Modern Approach*

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

  A classic book on algorithms.

  * ([3e intl at AbeBooks](http://www.abebooks.com/products/isbn/9780321455369))

* Skiena, 2008 (2e). *The Algorithm Design Manual*

  This book focuses somewhat more on how to do and evaluate algorithms vs. how to analyze them mathematically. There is a 1997 1st Edition, but it's hard to find and not a lot cheaper than a used copy of the 2nd Edition.

* Knuth, *The Art of Computer Programming*

  This collection of bulky tomes is a legendary institution in the field of computer science, as is their author.
  It's not the most up-to-date, but it is probably the most complete in-depth examination of algorithms.
  I don't think very many people who don't have a Ph.D. in CS have read all of the volumes...
  but if you have, it afford certain bragging rights.

* Manber. *Introduction to Algorithms: A Creative Approach* ([1e](https://smile.amazon.com/dp/0201120372))

  Focuses on how to design algorithms.

* Karumanchi. *Data Structure and Algorithmic Thinking with Python: Data Structure and Algorithmic Puzzles* ([1e](https://smile.amazon.com/dp/8192107590))

  A recent book that takes a relatively practical view (as opposed to mathematical). There are a bunch of mediocre Python-oriented CS books out there, but this one looks to be pretty good. Now that many people are learning Python as a first programming language, there's a pressing need for good books that use Python code to demonstrate concepts, so it's good to see some quality titles finally showing up.

* Groner. *Learning JavaScript Data Structures and Algorithms* ([At PACKT](https://www.packtpub.com/application-development/learning-javascript-data-structures-and-algorithms), [At Amazon](https://smile.amazon.com/dp/1783554878))

  If Javascript is the only language you know, then you'll need a Javascript-oriented book. This looks like a decent one.

* Okasaki. *Purely Functional Data Structures* ([1e](https://smile.amazon.com/dp/0521663504))
* Aho, Ullman, Hopcroft. *Data Structures and Algorithms* ([1e](https://smile.amazon.com/dp/0201000237))
* Brass. *Advanced Data Structures* ([1e](https://smile.amazon.com/dp/0521880378))

#### Specialized algorithms

These focus on some more specialized areas of algorithms.

* Motwani and Raghavan, 1995. *Randomized Algorithms*
* Mitzenmacher and Upfal, 2005. *Probability and Computing: Randomized Algorithms and Probabilistic Analysis*

* Papadimitriou and Steiglitz, 1982. *Combinatorial Optimization: Algorithms and Complexity* (c)

  There's a 1998 Dover edition, which has some corrections but isn't substantially different from the original 1982 version. This book has a unique choice of topics. It starts out with the linear programming problem and the simplex algorithm, a topic usually covered more in applied mathematics. Then, about halfway through, it switches gears and begins to look at graph algorithms. The point, as expressed in the introduction, is to look at the similarities between these continuous and discrete optimization problems, and how the fine differences between them result in dramatic differences in computational complexity. Thus, I think it can be said that, in a sense, this book teaches algorithms as a means to the end of understanding complexity.

* Bird. *Pearls of Functional Algorithm Design* ([1e](https://smile.amazon.com/dp/0521513383))

### Programming language theory

* Pierce, *Types and Programming Languages*
* Turbak, Gifford, Sheldon, 2008. *Design Concepts in Programming Languages*
* Winskel, *The Formal Semantics of Programming Languages*
* Slonneger, Kurtz, 1995. *Formal Syntax and Semantics of Programming Languages*
* Mitchell, 1996. *Foundations for Programming Languages*
* Pierce (ed), 2004. *Advanced Topics in Types and Programming Languages*
* Stepanov and Rose. *From Mathematics to Generic Programming* ([1e](https://smile.amazon.com/dp/0321942043))

### Compilers and interpreters

* Krishnamurthi, 2012. *Programming Languages: Application and Interpretation*

  AKA PLAI.
  The last version of this incarnation of the book. It goes with an online course, which is available here: https://cs.brown.edu/courses/cs173/2012/

  Together, these make an excellent introduction to the design and implementation of programming languages
  using an interpreter. This version of the book (and course) use a Racket language called typed PLAI,
  which is a Lisp with strong type inference.

* Krishnamurthi, 2015. *Programming and Programming Languages*

  From a glance, it looks to me like this is essentially a newer PLAI, retitled and revamped to use
  a new implementation language, Pyret.

  This book is under constant revision. Currently the latest stable version is here:
  http://papl.cs.brown.edu/2015/

* Friedman, Wand, Haynes, 1992. *Essentials of Programming Languages* ([1e](https://smile.amazon.com/dp/0262061457), [1e at AbeBooks](http://www.abebooks.com/products/isbn/9780262061452))
  * Friedman, Wand, Haynes, 2001. *Essentials of Programming Languages* ([2e](https://smile.amazon.com/dp/0262062178))
  * Friedman, Wand, 2008. *Essentials of Programming Languages* ([3e](https://smile.amazon.com/dp/0262062798))

  An more in-depth book about writing interpreters in Scheme. Shriram Krishnamurthi turned me onto this one.
  I have the first edition, which is a classic and can currently be bought used for under $10. I don't
  know how the later editions stack up. Judging from some online reviews, the first might really be the best.
  
  First edition search info:
  
  * MIT Press: ISBN 0-262-06145-7
  * McGraw-Hill: ISBN 0-07-033442-9
  * On Amazon: ASIN 0262061457

* Aho, Sethi, Ullman, 2006. *Compilers: Principles, Techniques, and Tools, Second Edition*
  * Aho, Sethi, Ullman, 1986. *Compilers: Principles, Techniques, and Tools*

  AKA "The Dragon Book" due to its well-known cover illustration.
  (1e is "the red dragon book", 2e is "the purple dragon book".)
  This is the standard book in the field of compilers, both as an introduction and as a reference.

* Aho and Ullman, 1977. *Principles of Compiler Design*

  AKA "the green dragon book".
  This one is obviously very out-of-date, but the basics are still relevant.
  It was well-loved in its day.

* Cooper and Torczon, 2011. *Engineering a Compiler, Second Edition*
  * Cooper and Torczon, 2003. *Engineering a Compiler*

  AKA EAC.
  Another beginning-to-end introduction to compiler development.
  The 2nd Edition is the most up-to-date compiler book available.
  It's the main competitor to The Dragon Book.

* Mak, 2011. *Writing Compilers and Interpreters: A Software Engineering Approach* (using Java)
  * Mak, 1996. *Writing Compilers and Interpreters: An Applied Approach Using C++*
  * Mak, 1991. *Writing Compilers and Interpreters: An Applied Approach* (using C)

  Another introduction to compiler writing that focuses more on high-level issues.
  The approach is to start out writing an interpreter, then turn it into a compiler.
  Mak's books are generally praised for their hands-on approach with concrete code
  listings.

* Appel, 1998. *Modern Compiler Implementation in ML*

  This is a beginning-to-end guide to writing a compiler. The implementation language is Standard ML,
  which is a very good language for writing compilers. By the end of the first half of the book, you
  have a working compiler. The second half covers advanced topics such as garbage collection,
  dataflow analysis and SSA form. I'm not sure how well this would work as a first book on compilers,
  but it's very nice as a view of how compilers work from a functional programming perspective,
  after you've gone through one of the more standard introductory books.

* Scott 2015 (4e), 2009 (3e), 2005 (2e), 1999 (1e). *Programming Language Pragmatics*

  This book won't teach you how to build a compiler or interpreter, but it's a great reference on
  lots of topics that come up when designing and implementing them. As such, it's a good *second*
  book on the subject.

* Muchnick, 1997. *Advanced Compiler Design and Implementation*

  A guide to more advanced techniques for code analysis and generation.
  It focuses more on optimization topics that can't be covered in a first book on compilers.

* Allen and Kennedy, 2001. *Optimizing Compilers for Modern Architectures: A Dependence-based Approach*

  Focuses on data dependence, vectorization and parallelism.
  Very important for taking advantage of the power of modern CPUs.

* Wolfe, 1996. *High Performance Compilers for Parallel Computing*

  Similar coverage to Allen and Kennedy (but less in-depth), also focuses on data dependence, vectorization and parallelism.
  Wolfe also discusses parallelism across multiple machines.

* Appel, 1992. *Compiling with Continuations*

  This is a book about about continuation-passing style as it applies to compiling functional languages.
  (In the context of interpreters, CPS is dicussed in PLAI and EOPL.) One of the nice things about this
  book is that, in large part, it describes the design of Standard ML of New Jersey
  (AKA SML/NJ: a popular implementation of Standard ML).
  Since SML/NJ is open source, you can go to http://www.smlnj.org/ and
  see a working example of many of the principles described in the book.

* Jones, Hosking, Moss, 2011. *The Garbage Collection Handbook: The Art of Automatic Memory Management*
  * Jones, Lins, 1996. *Garbage Collection: Algorithms for Automatic Dynamic Memory Management*

  The main reference on garbage collection.

### Numerical methods

* Trefethen and Bau, 1997. *Numerical Linear Algebra*
* Hamming, 1987. *Numerical Methods for Scientists and Engineers*
* Nocedal and Wright, 2006. *Numerical Optimization*
* Isaacson and Keller, 1966. *Analysis of Numerical Methods*
* Golub and Van Loan, 2012 (3e), 1996 (2e), 1989 (1e). *Matrix Computations*
* Higham, 2002 (2e). *Accuracy and Stability of Numerical Algorithms*
* Meikle, 2004. *A New Twist to Fourier Transforms*
* Brigham, 1988. *The Fast Fourier Transform and Its Applications*
* Trefethen, 2012, *Approximation Theory and Approximation Practice*

### Databases

* Elmasri and Nevathe. *Fundamentals of Database Systems* ([7e/2015](https://smile.amazon.com/dp/0133970779), [6e/2010](https://smile.amazon.com/dp/0136086209), [5e/2006](https://smile.amazon.com/dp/0321369572))

* Ullman and Widom. *A First Course in Database Systems* ([3e/2007](https://smile.amazon.com/dp/013600637X))

* Ullman. *Principles of Database & Knowledge-Base Systems*
  * *Vol. 1: Classical Database Systems* ([1e/1990](https://smile.amazon.com/dp/0716781581))
  * *Vol. 2: The New Technologies* ([1e/1989](https://smile.amazon.com/dp/071678162X))

* Abiteboul, Hull, Vianu. *Foundations of Databases: The Logical Level* ([1e/1994](https://smile.amazon.com/dp/0201537710))

  AKA The Alice Book.

* Garcia-Molina, Ullman, Widom. *Database Systems: The Complete Book* ([1e/2001](https://smile.amazon.com/dp/0130319953))

* Gray and Reuter. *Transaction Processing: Concepts and Techniques* ([1e/1992](https://smile.amazon.com/dp/1558601902))

* Bernstein and Newcomer. *Principles of Transaction Processing* ([2e/2009](https://smile.amazon.com/dp/1558606238))

* Maier. *Theory of Relational Databases* ([1e/1983](https://smile.amazon.com/dp/0914894420))

* Hellerstein and Stonebraker (eds). *Readings in Database Systems* ([4e/2005](https://smile.amazon.com/dp/0262693143))

### TODO

Systems, FP, AI
