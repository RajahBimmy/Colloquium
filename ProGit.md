# Pro Git (2014)

## Scott Chacon & Ben Straub

### Relevance

The git workflow starts out as just another way to manage projects, alongside the many ways McConnell outlines in Code Complete. The magic here is the way git can be extended, and the way git has allowed for the creation of GitHub, and the various communities present on it. Version Control is key in building the least possibly bugged software. It allows for more eyes to view the code, and according to Linus's Law, with enough eyes, all bugs are shallow.

### Context

In 2014, Pro Git was published as a way to introduce the git workflow to the uninitiated. The beauty of git is its extensibility. It's not just a program for programmers, it's a program for project-builders. Google Docs today bases a lot of its system on the idea of Version Control (albeit significantly more simple), and git can be applied to anything from code, to music, to word files, etc.

### Quotes

* "Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. For the examples in this book you will use software source code as the files being version controlled, though in reality you can do this with nearly any type of file on a computer."
  * Version control is another software design paradigm not actively taught by the likes of McConnell et al
* "In 2005, the relationship between the community that developed the Linux kernel and the commercial company that developed BitKeeper broke down, and the tool’s free-of-charge status was revoked. This prompted the Linux development community (and in particular Linus Torvalds, the creator of Linux) to develop their own tool based on some of the lessons they learned while using BitKeeper."
  * This is Torvalds' mantra at work. Build around what works. If it lets you down later, find or build something new which will make transition not sacrifice the quality of your own work.
* "Now, pay attention. This is the main thing to remember about Git if you want the rest of your learning process to go smoothly. Git has three main states that your files can reside in: committed, modified, and staged. Committed means that the data is safely stored in your local database. Modified means that you have changed the file but have not committed it to your database yet. Staged means that you have marked a modified file in its current version to go into your next commit snapshot."
  * Making local changes is key to not destroying, but true community and contribution comes from pushing. Obviously we need moderators to handle this transition for us. Sovereigns who set up the project at the start, but are willing and encourage collaborative efforts by the community.
* "Many Git developers have a workflow that embraces this approach, such as having only code that is entirely stable in their master branch – possibly only code that has been or will be released. They have another parallel branch named develop or next that they work from or use to test stability – it isn’t necessarily always stable, but whenever it gets to a stable state, it can be merged into master. It’s used to pull in topic branches (short-lived branches, like your earlier iss53 branch) when they’re ready, to make sure they pass all the tests and don’t introduce bugs."
  * This is the design workflow necessary to ensuring that the engine maintains smoothness. The hypothetical response to Brooks' argument that too many cooks will spoil the broth.
* "Historically, the term “fork” has been somewhat negative in context, meaning that someone took an open source project in a different direction, sometimes creating a competing project and splitting the contributors. In GitHub, a “fork” is simply the same project in your own namespace, allowing you to make changes to a project publicly as a way to contribute in a more open manner."
  * And this plays off of what Stallman initially posited as the reason for the Free Software movement: to allow users with new needs to make the changes necessary to enhance their version (and in turn the community at large's) product.
* "When you hit the Create pull request button on this screen, the owner of the project you forked will get a notification that someone is suggesting a change and will link to a page that has all of this information on it."
  * This is the modern day accelerated version of what Berners-Lee and Raymond encountered on their quest to build collaborative projects.
* "It’s important to understand that many projects don’t really think of Pull Requests as queues of perfect patches that should apply cleanly in order, as most mailing list-based projects think of patch series contributions. Most GitHub projects think about Pull Request branches as iterative conversations around a proposed change, culminating in a unified diff that is applied by merging."
  * Pull Requests can be more open source, but they can also just as well be patches implemented by the larger organization.

### Connected Books

* [Code Complete]
* [The Mythical Man-Month]
* [The Cathedral and the Bazaar](CathedralBazaar.md)
* [Weaving the Web](WeavingWeb.md)
