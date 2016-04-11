# How to Design Programs (2001)

## Felleisen, Findler, Flatt, Krishnamurthi

### Relevance

HTDP helps and hurts the aspiring developer quite a bit. While it teaches valuable design pieces like abstraction, MVC, and Lambdas, its language hinders it largely, and in the end makes it harder to contribute to what it's trying to do (make computer science accessible to all). McConnell would love it's Mission-statement oriented approach, while Brooks wouldn't be as much of a fan.

### Context

How to Design Programs was written as a response to the Structure and Interpretation of Computer Programs. It sees a problem with SICP's monolithic approach to viewing computer science as an all-in discipline. It consistently starts with tiny data, then works its way to larger and larger data sets, with a focus on clear definitions and abstractions to use the old to understand new scenarios.

### Quotes

* "We propose to solve this constraint problem with a second look at the primary goal and the timing constraints. Clearly, a computer science curriculum must not, and doesn’t have to, become a vocational training ground for the latest industrial programming language and programming tools."
  * The primary goal isn't to expose students to a world of programming concepts they'll never use, rather to induct the non-programmers into a world they can dabble with, and maybe explore further.
* "Students must learn to read problem statements carefully, extract information, and rewrite it into useful pieces: a. a concise purpose statement for the program and each of its major pieces. b. a description of the classes of data that play a role. c. a collection of examples that illustrate both the classes as well as the purpose statements."
  * HTDP's most reiterated statement is the idea of abstracting, and describing as much as humanly possible to understand new concepts and problems.
* "Given this context, we picked Scheme as the most suitable starting point for the first language. Scheme's syntax is simple. Scheme's semantics are easy to understand. Scheme is safe. Scheme is dynamically typed."
  * I think Scheme was a poor choice to make for language, as it constrains its users to learning a language with wholly useless syntax in any serious programming environment.
* "Software engineers use the slogan model-view-controller (MVC) for the way BSL and DrRacket separate data processing from parsing information into data and turning data into information."
  * Where HTDP does prevail is in introducing the MVC paradigm, which few other Computer Science books introduce from the get-go.
* "Write down a signature, a purpose statement, and a function header. A function signature is a BSL comment that tells the readers of your design how many inputs your function consumes, from what collection of data they are drawn, and what kind of output data it produces. A purpose statement is a BSL comment that summarizes the purpose of the function in a single line. Finally, a header is a simplistic function definition, also called a stub. Pick one parameter for each input data class in the signature; the body of the function can be any piece of data from the output class."
  * Give every line of code you write meaning, objective and design are paramount to McConnell as well, so I'd imagine he supports the way the HTDP team handles it.
* "Knowledge from external domains such as mathematics, music, biology, civil engineering, art, etc. Because programmers cannot know all of the application domains of computing, they must be prepared to understand the language of a variety of application areas so that they can discuss problems with domain experts. This language is often that of mathematics, but in some cases, the programmers must learn a language as they work through problems with domain experts."
  * A good piece of software isn't necessarily the programmer's program. It involves collaboration with other disciplines to produce the best possible program.
* "Testing quickly becomes a labor-intensive chore. While it is easy to run small programs in the interactions area, doing so requires a lot of mechanical labor and intricate inspections. As programmers grow their systems, they wish to conduct many tests. Soon this labor becomes overwhelming, and programmers start to neglect it. At the same time, testing is the first tool for discovering and preventing basic flaws."
  * Explanation that test-driven development can be hard to commit to. In modern day programming, I think it is a necessity to always be committed to carrying it out.
* "Put differently, the analysis of our failure suggests two ideas at once. First, we should solve a different, a more general looking problem. Second, we should use the solution for this generalized problem to solve the original one."
  * This is Locke's idea of abstraction, in full effect. Creating sub-problems and sub-definitions to understand the more complex ones. Think the Russian Dolls or Snake Game.
* "Designing with abstractions requires three steps: 1. Follow the design recipe for functions. 2. Find a matching abstraction which is more general. 3. Write down a template for future abstractions which may conform to this design. 4. Write the function to handle it."
  * Generalize as much as possible, but never cast aside your generalizations when you're done, as you may need them later.
* "To solve such complicated problems, programmers use generative recursion, a form of recursion that is strictly more powerful than structural recursion. The study of generative recursion is as old as mathematics and is often called the study of algorithms. The inputs of an algorithm represent a problem. An algorithm tends to re-arrange a problem into a set of several problems, solve those, and combine their solutions into one overall solution. Often some of these newly generated problems are the same kind of problem as the given one, in which case the algorithm can be re-used to solve them. In these cases, the algorithm is recursive but its recursion uses newly generated data not immediate parts of the input data."
  * The last concept HTDP introduces is Recursion.

### Connected Books

* __The Categories__
* __Code Complete__
* __An Essay on Human Understanding__
* __Introduction to Algorithms__
* __Metaphysics__
* __The Mythical Man-Month__
* __The Republic__
