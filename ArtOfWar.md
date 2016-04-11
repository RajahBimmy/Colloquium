# The Art of War (5th Century, B.C.)

## Sun Tzu

### Relevance

Steve McConnell would have loved Sun Tzu. The Art of War is all about being a strong manager, whose true talents are the ability to avoid disaster, rather than just being profitable. It covers everything from community building to architectural design in war, and how to prepare for all sides of conflict. Machiavelli would probably also very much enjoy the work, as it encourages leaders to be firm but fluid, willing to act in the best interest of his unit rather than the ideologically best manner. Success is paramount to all things. I think Brooks would agree with his chapters on socialization though, as a commonly looked over trait is the skill of a manager to be able to discern what teammates can bring to a project, rather than just giving them more to work with.

### Context

The Art of War, while intended simply for military stratagem, has historically been extended beyond that scope to political, legal, and even sports theory. It's based on the premise of waging war without ever needing to heavily engage in combat, and can be seen as a template for modeling software development as well.

### Most Valuable Chapters

* Laying Plans
  * Sun Tzu opens The Art of War with an overview of what he considers the most influential variables in warfare. Most are obvious to us (i.e. which army is stronger, which army is better trained), but he ends the chapter on calculations. He claims that he is able to “foresee who is likely to win or lose” entirely based on calculation. The amount of calculation you perform before war is directly proportional to the amount of success you’ll have. This makes sense, but isn’t just restricted to War. Contrasting the arguments between McConnell’s Code Complete and Brooks’ The Mythical Man-Month, we see there is a clear difference when it comes to opinions about calculations or preparations in the war of software development. So far, I see Sun Tzu’s general as a precursor for Steve McConnell’s software architect.
* Waging War
  * Chapter two is primarily focused on morale in war, specifically focusing on the length and energy required to wage war. This reminds me of McConnell’s concept of coding into a language rather than in it. The difference being that when you’re working with unfamiliar resources, you’re likely to stick to what you know rather than learning from new experiences. This leads to nonconforming code and frustration the deeper you go into the language. Morale is very important in the software development process, and if you are unable to find a way to keep the work flowing, a project will hit a stand still. The solution is to break up the grueling hours spent on three lines of code with bursts of several hundred lines of less intense algorithmic work.
* Attack by Stratagem
  * The meat and potatoes of chapter three are the three ways in which a ruler can bring misfortune upon his army:
    * “By commanding the army to advance or to retreat, being ignorant of the fact that it cannot obey. This is called hobbling the army.”
    * “By attempting to govern an army in the same way as he administers a kingdom, being ignorant of the conditions which obtain in an army. This causes restlessness in the soldier’s minds.”
    * “By employing the officers of his army without discrimination, through the ignorance of the military principle of adaptation to circumstances.”
  * This sounds is exactly like the WIMP, or “Why isn’t Mary Programming?” problem. The idea is that failure is practically guaranteed in a system where your general, manager, or whoever is unable to understand the perspective of their soldiers, developers, etc. The solution here is to keep people in the loop on what you’re doing while you’re doing it. Finding a way to explain things at a higher level so that even an incompetent general can right the course before the ship sinks.
* Maneuvering
  * “We are not fit to lead an army on the march unless we are familiar with the face of the country – its mountains and forests, its pitfalls and precipices, its marches and swamps. … Whether to concentrate or to divide your troops, most be decided by circumstances.” This points directly to collaboration in projects. I can’t tell you how many times I’ve gone back and forth on whether I work better in a group or by myself. At the end of the day, the honest answer is sometimes I like six of one, the rest of the time I prefer half a dozen of the other. The nature of the project matters. If I’ve been staring all day at a method making HTTP requests that isn’t returning the JSON I expect from it, it helps to have a breather and another set of eyes on the code telling me “Well duh, you forgot to call the built-in JSON parser it first.” It’s the simple stupid mistakes that helping hands can save, and you need a balance of both to get the more robust projects done.
* Terrain
  * “If the enemy has occupied [the terrain] before you, do not follow him, but retreat and try to entice him away.” If the program’s expectations seem too intense for just one coder, don’t panic. Testing is the bomb. Not building a test class for populating a binary search tree with different “potato” nodes is a grave mistake to make. In all seriousness, this is a practice I don’t utilize nearly as often as I should. Programs get out of hand when I make X call Y on Z, before ensuring that X is even capable of calling Y and that Z isn’t a string with contents “DROP TABLE client_records”. Testing is the morning skate before you head out onto the ice that night and get the hat-trick. General ideas are great, but sometimes you need to shoot the puck a little to get a better understanding of goal theory. Sorry for bringing hockey into an already feigned stretch of the imagination, it just helps me appreciate testing.
* The Use of Spies
  * It is always best to rely on the intel others collect before diving into a full-scale attack or project (see: Stack Overflow).

### Connected Books

* __Code Complete__
* __The Mythical Man-Month__
* __The Muqaddimah__
* __The Prince__
