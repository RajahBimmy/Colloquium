# Code Complete (2004)

## Steve McConnell

### Relevance



### Context

In the 90s, Steve McConnell, a software engineer who made the rounds through Microsoft and Boeing, saw that the field was too much dominated by a philosophy of coding the solutions to problems as they presented themselves. As a response, McConnell put together __Code Complete__ to challenge this trend and establish a firm belief that software design is an architectural process.

### Quotes

* "Important developments often arise out of analogies. By comparing a topic you understand poorly to something similar you understand better, you can come up with insights that result in a better understanding of the less-familiar topic."
  * Based on Locke's idea of Abstractions, introduced in __An Essay on Human Understanding__
* "A software metaphor is more like a searchlight than a road map. It doesn't tell you where to find the answer; it tells you how to look for it. A metaphor serves more as a heuristic than it does as an algorithm."
* "Planning to throw one away might be practical when you're writing a polite how-do- system already costs as much as a 10-story office building or an ocean liner. It's easy to grab the brass ring if you can afford to sit on your favorite wooden pony for an unlimited number of spins around the carousel. The trick is to get it the first time around—or to take several chances when they're cheapest. Other metaphors better illuminate ways of attaining such goals."
  * This is McConnell's rebuttal of __The Mythical Man-Month__.
* "It generally doesn't make sense to code things you can buy ready made."
  * Playing into Raymond's idea of a __Bazaar__. Don't always feel obligated to code around your mantra.
* "Part of your job as a technical employee is to educate the nontechnical people around you about the development process."
* "The easiest way to handle such feature-intoxicated people is to say, "Gee, that sounds like a great idea. Since it's not in the requirements document, I'll work up a revised schedule and cost estimate so that you can decide whether you want to do it now or later." The words "schedule" and "cost" are more sobering than coffee and a cold shower, and many "must haves" will quickly turn into "nice to haves.""
  * Potential for branching, but not to remain in production (__Pro Git__)
* "Data should normally be accessed directly by only one subsystem or class, except through access classes or routines that allow access to the data in controlled and abstract ways."
  * Black box method, fleshed out more in __The Mythical Man-Month__
* "The architecture should provide estimates and explain why the architects believe the goals are achievable. If certain areas are at risk of failing to meet their goals, the architecture should say so. If certain areas require the use of specific algorithms or data types to meet their performance goals, the architecture should say that. The architecture can also include space and time budgets for each class or object."
* "The architecture should be a polished conceptual whole with few ad hoc additions. The central thesis of the most popular software-engineering book ever, The Mythical Man-Month , is that the essential problem with large systems is maintaining their conceptual integrity (Brooks 1995). A good architecture should fit the problem. When you look at the architecture, you should be pleased by how natural and easy the solution seems. It shouldn't look as if the problem and the architecture have been You might know of ways in which the architecture was changed during its development. Each change should fit in cleanly with the overall concept."
* "The Sapir-Whorf hypothesis says that your ability to think a thought depends on knowing words capable of expressing the thought. If you don't know the words, you can't express the thought and you might not even be able to formulate it (Whorf 1956)."
  * More on abstraction.
* "__Brooks__ argues that software development is made difficult because of two different classes of problems—the essential and the accidental . In referring to these two terms, Brooks draws on a philosophical tradition going back to Aristotle. In philosophy, the essential properties are the properties that a thing must have in order that don't really bear on whether the thing is what it is. A car could have a V8, a turbocharged 4-cylinder, or some other kind of engine and be a car regardless of that detail."
  * Much like Aristotle's __Categories__ and __Metaphysics__.
* "__Voltaire__ said that a book is finished not when nothing more can be added but when nothing more can be taken away."
* "From a complexity point of view, the principal benefit of abstraction is that it allows you to ignore irrelevant details. Most real-world objects are already abstractions of some kind. As just mentioned, a house is an abstraction of windows, doors, siding, wiring, plumbing, insulation, and a particular way of organizing them. A door is in turn an abstraction of a particular arrangement of a rectangular piece of material with hinges and a doorknob. And the doorknob is an abstraction of a particular formation of brass, nickel, iron, or steel."
  * Pulled from __Plato__
* "In the 20th Anniversary edition of __The Mythical Man Month__, Fred Brooks concluded about information hiding," he proclaimed (Brooks 1995). Barry Boehm reported that information hiding was a powerful technique for eliminating rework, and he pointed out that it was particularly effective in incremental, high-change environments (Boehm 1987). Information hiding is a particularly powerful heuristic for Software's Primary Technical Imperative because, beginning with its name and throughout its details, it emphasizes hiding complexity."
  * Think of black boxes
* "I would rather see 80 percent of the design effort go into creating and exploring numerous design alternatives and 20 percent go into creating less polished documentation than to have 20 percent go into creating mediocre design alternatives and 80 percent go into polishing documentation of designs that are not very good."
  * Attack on FSF in __Free as in Freedom__
* "Functional cohesion is the strongest and best kind of cohesion, occurring when a routine performs one and only one operation."
  * Action comes from __Categories__.
* "If you find that a routine is unusually buggy, start over. Don't hack around it—rewrite it. Hacks usually indicate incomplete understanding and guarantee errors both now and later."
* "The guiding principle is the Principle of Proximity: Keep related actions together."
* "For a small group of problems, recursion can produce simple, elegant solutions. For a slightly larger group of problems, it can produce simple, elegant, hard-to-understand solutions. For most problems, it produces massively complicated solutions—in those cases, simple iteration is usually more understandable. Use recursion selectively."
  * Shots fired at __How to Design Programs__.
* Software has both external and internal quality characteristics. External characteristics are characteristics that a user of the software product is aware of, including the following:
  * __Correctness__ The degree to which a system is free from faults in its specification, design, and implementation.
  * __Usability__ The ease with which users can learn and use a system.
  * __Efficiency__ Minimal use of system resources, including memory and execution time.
  * __Reliability__ The ability of a system to perform its required functions under stated conditions whenever required—having a long mean time between failures.
  * __Integrity__ The degree to which a system prevents unauthorized or improper access to its programs and its data. The idea of integrity includes restricting unauthorized user accesses as well as ensuring that data is accessed properly— that is, that tables with parallel data are modified in parallel, that date fields contain only valid dates, and so on.
  * __Adaptability__ The extent to which a system can be used, without modification, in applications or environments other than those for which it was specifically designed.
  * __Accuracy__ The degree to which a system, as built, is free from error, especially with respect to quantitative outputs. Accuracy differs from correctness; it is a determination of how well a system does the job it's built for rather than whether it was built correctly.
  * __Robustness__ The degree to which a system continues to function in the presence of invalid inputs or stressful environmental conditions.
* Programmers care about the internal characteristics of the software as well as the to change or add capabilities, improve performance, or correct defects.
  * __Flexibility__ The extent to which you can modify a system for uses or environments other than those for which it was specifically designed.
  * __Portability__ The ease with which you can modify a system to operate in an environment different from that for which it was specifically designed.
  * __Reusability__ The extent to which and the ease with which you can use parts of a system in other systems.
  * __Readability__ The ease with which you can read and understand the source code of a system, especially at the detailed-statement level.
  * __Testability__ The degree to which you can unit-test and system-test a system; the degree to which you can verify that the system meets its requirements.
  * __Understandability__ The ease with which you can comprehend a system at both the system-organizational and detailed-statement levels. Understandability has to do with the coherence of the system at a more general level than readability does.
* "With collective ownership, all code is owned by the group rather than by individuals and can be accessed and modified by various members of the group. This produces several valuable benefits:
  * Better code quality evolves from more sets of eyes seeing the code and multiple programmers working on code.
  * The impact of someone leaving the project is lessened because people are familiar with each section of code.
  * Defect-correction cycles are shorter overall because any of several programmers can potentially be assigned to fix bugs on an as-available basis."
* "The "DRY principle": Don't Repeat Yourself (2000). I think David Parnas says it best: "Copy and paste is a design error" (McConnell 1998b)."
* "Save the code you start with. Before you begin refactoring, make sure you can get back to the code you started with. Save a version in your revision control system, or copy the correct files to a backup directory."
  * __Pro Git__
* "Some creative programmers view the discipline of standards and conventions as stifling to their creativity. The opposite is true. Can you imagine a website on which even imaginable. Don't waste your creativity on things that don't matter. Establish conventions in noncritical areas so that you can focus your creative energies in the places that count. In a 15-year retrospective on work at NASA's Software Engineering Laboratory, McGarry and Pajerski reported that methods and tools that emphasize human discipline have been especially effective (1990). Many highly creative people have been extremely disciplined. "Form is liberating," as the saying goes. Great architects work within the constraints of physical materials, time, and cost. Great artists do, too. Anyone who has examined Leonardo's drawings has to admire his disciplined attention to detail."
  * __Da Vinci's Notebooks__ and __The Republic__.
* "Religion appears in software development in numerous incarnations—as dogmatic adherence to a single design method, as unswerving belief in a specific formatting or commenting style, or as a zealous avoidance of global data. Whatever the case, it's always inappropriate."
  * Don't let that get in the way of your mission (__Art of War__)

### Connected Books

* __The Art of War__
* __Da Vinci's Notebooks__
* __The Republic__
* __How to Design Programs__
* __Free as in Freedom__
* __The Categories__
* __Metaphysics__
* __Free Software, Free Society__
* __Pro Git__
* __The Mythical Man-Month__
* __The Cathedral and the Bazaar__
* __An Essay on Human Understanding__
* __Candide__
