This is the lessons from [A Retrospective on PAIP](http://norvig.com/Lisp-retro.html), with page numbers that actually link to pages in the book. I'm using the OCR [PAIP.txt](https://github.com/norvig/paip-lisp/blob/main/PAIP.txt) as it contains magic `<a id="page-..."></a>` markers. All of the other 'cleaner' versions seem to 'clean' these out.

# What Lessons are in PAIP?

Here is my list of the 52 most important lessons in PAIP:

1. Use anonymous functions. [[p. 20]](/PAIP.md#page-20)
1. Create new functions (closures) at run time. [[p. 22]](/PAIP.md#page-22)
1. Use the most natural notation available to solve a problem. [[p. 42]](/PAIP.md#page-42)
1. Use the same data for several programs. [[p. 43]](/PAIP.md#page-43)
1. Be specific. Use abstractions. Be concise. Use the provided tools. Don't be obscure. Be consistent. [[p. 49]](/PAIP.md#page-49)
1. Use macros (if really necessary). [[p. 66]](/PAIP.md#page-66)
1. There are 20 or 30 major data types; familiarize yourself with them. [[p. 81]](/PAIP.md#page-81)
1. Whenever you develop a complex data structure, develop a corresponding consistency checker. [[p. 90]](/PAIP.md#page-90)
1. To solve a problem, describe it, specify it in algorithmic terms, implement it, test it, debug and analyze it. Expect this to be an iterative process. [[p. 110]](/PAIP.md#page-110)
1. AI programming is largely exploratory programming; the aim is often to discover more about the problem area. [[p. 119]](/PAIP.md#page-119)
1. A general problem solver should be able to solve different problems. [[p. 132]](/PAIP.md#page-132)
1. We must resist the temptation to believe that all thinking follows the computational model. [[p. 147]](/PAIP.md#page-147)
1. The main object of this book is to cause the reader to say to him or herself "I could have written that". [[p. 152]](/PAIP.md#page-152)
1. If we left out the prompt, we could write a complete Lisp interpreter using just four symbols. Consider what we would have to do to write a Lisp (or Pascal, or Java) interpreter in Pascal (or Java). [[p. 176]](/PAIP.md#page-176)
1. Design patterns can be used informally, or can be abstracted into a formal function, macro, or data type (often involving higher-order functions). [[p. 177]](/PAIP.md#page-177)
1. Use data-driven programming, where pattern/action pairs are stored in a table. [[p. 182]](/PAIP.md#page-182)
1. Sometimes "more is less": its easier to produce more output than just the right output. [[p. 231]](/PAIP.md#page-231)
1. Lisp is not inherently less efficient than other high-level languages - Richard Fateman. [[p. 265]](/PAIP.md#page-265)
1. First develop a working program. Second, instrument it. Third, replace the slow parts. [[p. 265]](/PAIP.md#page-265)
1. The expert Lisp programmer eventually develops a good "efficiency model". [[p. 268]](/PAIP.md#page-268)
1. There are four general techniques for speeding up an algorithm: caching, compiling, delaying computation, and indexing. [[p. 269]](/PAIP.md#page-269)
1. We can write a compiler as a set of macros. [[p. 277]](/PAIP.md#page-277)
1. Compilation and memoization can yield 100-fold speed-ups. [[p. 307]](/PAIP.md#page-307)
1. Low-level efficiency concerns can yield 40-fold speed-ups. [[p. 315]](/PAIP.md#page-315)
1. For efficiency, use declarations, avoid generic functions, avoid complex argument lists, avoid unnecessary consing, use the right data structure. [[p. 316]](/PAIP.md#page-316)
1. A language that doesn't affect the way you think about programming is not worth knowing - Alan Perlis. [[p. 348]](/PAIP.md#page-348)
1. Prolog relies on three important ideas: a uniform data base, logic variables, and automatic backtracking. [[p. 349]](/PAIP.md#page-349)
1. Prolog is similar to Lisp on the main points. [[p. 381]](/PAIP.md#page-381)
1. Object orientation = Objects + Classes + Inheritance - Peter Wegner [[p. 435]](/PAIP.md#page-435)
1. Instead of prohibiting global state (as functional programming does), object-oriented programming breaks up the unruly mass of global state and encapsulates it into small, manageable pieces, or objects. [[p. 435]](/PAIP.md#page-435)
1. Depending on your definition, CLOS is or is not object-oriented. It doesn't support encapsulation. [[p. 454]](/PAIP.md#page-454)
1. Prolog may not provide exactly the logic you want [[p. 465], nor the efficiency you want [p. 472]](/PAIP.md#page-465], nor the efficiency you want [p. 472). Other representation schemes are possible.
1. Rule-based translation is a powerful idea, however sometimes you need more efficiency, and need to give up the simplicity of a rule-based system [[p. 509]](/PAIP.md#page-509).
1. Translating inputs to a canonical form is often a good strategy [[p. 510]](/PAIP.md#page-510).
1. An "Expert System" goes beyond a simple logic programming system: it provides reasoning with uncertainty, explanations, and flexible flow of control [[p. 531]](/PAIP.md#page-531).
1. Certainty factors provide a simple way of dealing with uncertainty, but there is general agreement that probabilities provide a more solid foundation [[p. 534]](/PAIP.md#page-534).
1. The strategy you use to search for a sequence of good moves can be important [[p. 615]](/PAIP.md#page-615).
1. You can compare two different strategies for a task by running repeated trials of the two [[p. 626]](/PAIP.md#page-626).
1. It pays to precycle [[p. 633]](/PAIP.md#page-633).
1. Memoization can turn an inefficient program into an efficient one [[p. 662]](/PAIP.md#page-662).
1. It is often easier to deal with preferences among competing interpretations of inputs, rather than trying to strictly rule one interpretation in or out [p 670].
1. Logic programs have a simple way to express grammars [[p. 685]](/PAIP.md#page-685).
1. Handling quantifiers in natural language can be tricky [[p. 696]](/PAIP.md#page-696).
1. Handling long-distance dependencies in natural language can be tricky [[p. 702]](/PAIP.md#page-702).
1. Understanding how a Scheme interpreter works can give you a better appreciation of how Lisp works, and thus make you a better programmer [[p. 753]](/PAIP.md#page-753).
1. The truly amazing, wonderful thing about call/cc is the ability to return to a continuation point more than once. [[p. 771]](/PAIP.md#page-771).
1. The first Lisp interpreter was a result of a programmer ignoring his boss's advice. [[p. 777]](/PAIP.md#page-777).
1. Abelson and Sussman (1985) is probably the best introduction to computer science ever written [[p. 777]](/PAIP.md#page-777).
1. The simplest compiler need not be much more complex than an interpreter [[p. 784]](/PAIP.md#page-784).
1. An extraordinary feature of ANSI Common Lisp is the facility for handling errors [[p. 837]](/PAIP.md#page-837).
1. If you can understand how to write and when to use once-only, then you truly understand macros [[p. 853]](/PAIP.md#page-853).
1. A word to the wise: don't get carried away with macros [[p. 855]](/PAIP.md#page-855).
