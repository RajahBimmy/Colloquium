# The Mythical Man-Month (1975)

## Fred Brooks

### Relevance

Mythical Man-Month introduces the challenges of working with teams of people, and that sometimes being open to all isn't always the best way to get something done the fastest (though Williams maintains that Raymond's idea of the Bazaar may be a workaround to this problem). He begins by introducing programming as an art and the programmer being very close to Da Vinci's artist. He is also very open to self-criticism and a good laugh. The overall motto of his book is: If you're collaborating, everyone go into your own unique corner, and focus on your job. It's less about being a jack of all trades, and instead building a team where everyone is a master of one. The more autonomy you give to a team, the stronger the project will end up being.

### Context

The Mythical Man-Month was published as a Bible for both Software Development and Management in general. It is quoted for being one of the best resource in maintaining efficient teams and looking for smart solutions, while at the same time making clear that there is "No Silver Bullet," or that "there is no single development, in either technology or management technique, which by itself promises even one order of magnitude [tenfold] improvement within a decade in productivity, in reliability, in simplicity."

### Quotes

* "Why is programming fun? What delights may its practitioner expect as his reward?
  * First is the sheer joy of making things. As the child delights in his mud pie, so the adult enjoys building things, especially things of his own design. I think this delight must be an image of God's delight in making things, a delight shown in the distinctness and newness of each leaf and each snowflake.
  * Second is the pleasure of making things that are useful to other people. Deep within, we want others to use our work and to find it helpful. In this respect the programming system is not essentially different from the child's first clay pencil holder "for Daddy's office."
  * Third is the fascination of fashioning complex puzzle-like objects of interlocking moving parts and watching them work in subtle cycles, playing out the consequences of principles built in from the beginning. The programmed computer has all the fascination of the pinball machine or the jukebox mechanism, carried to the ultimate.
  * Fourth is the joy of always learning, which springs from the nonrepeating nature of the task.
  * Finally, there is the delight of working in such a tractable medium. The programmer, like the poet, works only slightly removed from pure thought-stuff."
* "Men and months are interchangeable commodities only when a task can be partitioned among many workers with no communication among them. This is true of reaping wheat or picking cotton; not even approximately true of systems programming."
  * Redundant work is the death of productivity, and potentially plays into the undoing of the FSF
* "The conclusion is simple: if a 200-man project has 25 managers who are the most competent and experienced programmers, fire the 175 troops and put the managers back to programming."
* "Conceptual integrity in turn dictates that the design must proceed from one mind, or from a very small number of agreeing resonant minds. ... The separation of architectural effort from implementation is a very powerful way of getting conceptual integrity on very large projects."
  * Brooks agrees with McConnell here, in that architecture must be considered seriously beforehand. I think he reconciles this with the "Throw one away" comment by explaining that the meaning is to not get too attached, rather than simply not worrying at all on the first pass.
* "Where architecture tells what happens, implementation tells how it is made to happen."
  * Class vs. Instance
* "There are many examples from other arts and crafts that lead one to believe that discipline is good for art. Indeed, an artist's amorphism asserts, 'Form is liberating.'"
  * This is Brooks' Bronze bullet: Object-oriented programming and abstraction. Perhaps by making our problems more accessible via language, we'll fix them faster.
* "D. L. Parnas of Carnegie-Mellon University has proposed a still more radical solution. His thesis is that the programmer is most effective if shielded from, rather than exposed to the details of construction of system parts other than his own. This presupposes that all interfaces are completely and precisely defined."
  * The black box methodology introduced by McConnell
* "In most projects, the first system built is barely usable. It may be too slow, too big, awkward to use, or all three. There is no alternative but to start again, smarting but smarter, and build a redesigned version in which these problems are solved. The discard and redesign may be done in one lump, or it may be done piece-by-piece. But all large-system experience shows that it will be done. Where a new system concept or new technology is used, one has to build a system to throw away, for even the pilot system and throw it away. You will do that. The only question is whether to plan in advance to build a throwaway, or to promise to deliver the throwaway to customers. Seen this way, the answer is much clearer. Delivering that throwaway to customers buys time, but it does so only at the cost of agony for the user, distraction for the builders while they do the redesign, and a bad reputation for the product that the best redesign will find hard to live down. Hence plan to throw one away; you will, anyhow."
  * Brooks revisits this 20 years later and criticizes himself. This practice has now been drawn into Test-Driven Development
* "I am convinced that interactive systems will never displace batch systems for many applications."
  * Well, you're wrong.
* "The most pernicious and subtle bugs are system bugs arising from mismatched assumptions made by authors of various components."
  * This can be eliminated by combining McConnell and Brooks, having programmers work on their unique parts of a project, but rather than informing each other of the architecture after completion, they just explain what one should input and expect as output, to fit the black box model.
* "A baseball manager recognizes a nonphysical talent, hustle, as an essential gift of great players and great teams."
  * There are traits beyond pure coding skill, and sometimes the people with those traits are the ones who can keep the whole project rolling. Having different voices and unique skills provide for the best output.
* "As a software product is found to be useful, people try it in new cases at the edge of, or beyond, the original domain."
* "Incremental development—grow, not build, software. I still remember the jolt I felt in 1958 when I first heard a friend talk about building a program, as opposed to writing one. In a flash he broadened my whole view of the software process. The metaphor shift was powerful, and accurate. Today we understand how like other building processes the construction of software is, and we freely use other elements of the metaphor, such as specifications, assembly of components, and scaffolding . The building metaphor has outlived its usefulness. It is time to change again. If, as I believe, the conceptual structures we construct today are too complicated to be accurately specified in advance, and too complex to be built faultlessly, then we must take a radically different approach."
* "Especially noteworthy his comment that new people added late in a development project must be team players willing to pitch in and work within the process, and not attempt to alter or improve the process itself!"
  * A potential way of breaking Raymond's formula.

### Connected Books

* __Code Complete__
* __The Cathedral and the Bazaar__
* __Da Vinci's Notebooks__
* __Free as in Freedom__
