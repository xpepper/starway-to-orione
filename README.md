# Starway to Orione: the Orione Team Learning Path

This is the learning path every new dev has to follow when joins our team.

This path reflect our team's culture and values, which have its roots in the [agile values and principles](http://agilemanifesto.org/), as well as in those of XP, and in the [software craftsmanship manifesto](http://manifesto.softwarecraftsmanship.org/).

Please feel free to fork and contribute, add materials, fix the existing ones and propose new stuff.

## Main learning path

### Session 1 - Intro

* Read [The Pomodoro Technique](http://pomodorotechnique.com/) paper
* Read first three chapters of [XP Explained](https://www.amazon.com/Extreme-Programming-Explained-Embrace-Change/dp/0201616416)
* Read first chapter of ["Applying UML and Patterns"](http://www.amazon.com/Applying-UML-Patterns-Introduction-Object-Oriented/dp/0131489062)
  * Try to estimate the time needed to study that chapter (using the pomodoro technique)
  * Answer (for example on the team's wiki pages)
    * What is analysis?
    * What is design?
    * What's the difference between them?
    * What is design for?
      * in other words, how would you reply to the following statement: _"I just need to understand what to do (analysis) and than do it (coding). Everything else does not matter!"_
* Read the article [Keep It DRY, Shy, and Tell the Other Guy](http://media.pragprog.com/articles/may_04_oo1.pdf)
* Tell Don't Ask principle
  * read the article [Tell, Don't Ask](http://pragprog.com/articles/tell-dont-ask)
  * read the article [The Art of Enbugging](http://media.pragprog.com/articles/jan_03_enbug.pdf)
* Do the [Kata String Calculator](http://osherove.com/tdd-kata-1/)

### Session 2 - Testing and TDD

* Read [Test Driven Development: By Example](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530)
* See the Clean Code Talks series: these four videos (and the related blogpost series) are really valuable to learn how to design for testability.

  1. Watch ["The Clean Code Talks -- Unit Testing" video](http://www.youtube.com/watch?v=wEhu57pih5w) (~ 30 minutes) [[slides](https://docs.google.com/presentation/d/1mZsq0WljEfgIR9Df_IcW0VQfNl-Pk_cEBR3i9id-eR4/present#slide=id.i0)]. Then read [his blogpost](http://misko.hevery.com/2008/11/04/clean-code-talks-unit-testing/).

  2. Watch ["The Clean Code Talks -- Inheritance, Polymorphism, & Testing" video](https://www.youtube.com/watch?v=4F72VULWFvc) (~ 40 minutes). Then read [his blogpost](http://misko.hevery.com/2008/12/08/clean-code-talks-inheritance-polymorphism-testing/) (there you can find the slides too).

  3. Watch ["The Clean Code Talks - Don't Look For Things!" video](https://www.youtube.com/watch?v=RlfLCWKxHJ0) (~ 35 minutes) which talks about the Dependency Injection pattern. Then read [his blogpost](http://misko.hevery.com/2008/11/11/clean-code-talks-dependency-injection/) (there you can find the slides too).

  4. Watch ["The Clean Code Talks - "Global State and Singletons" video](https://www.youtube.com/watch?v=-FRm3VPhseI) (~ 55 minutes). Then read [his blogpost](http://misko.hevery.com/2008/11/21/clean-code-talks-global-state-and-singletons/) (there you can find the slides too).

  5. For each video you see, write a short post (e.g. on your public [gist](https://gist.github.com/)) on
    * what you learn
    * what puzzled you most?

  6. Read Miško Hevery's guide on ["Writing Testable Code"](http://misko.hevery.com/code-reviewers-guide/)
* See [Lets Play on TDD](http://www.jamesshore.com/Blog/Lets-Play) by James Shore
* For __italian speakers__, Piergiuliano Bossi's [screencasts on TDD](https://www.youtube.com/channel/UCKu3XCVh7pe06khn4N1uCiQ) are a good starting point: there are five basic lession and a final video on emergent design.
* Do the [Sales Kata](https://github.com/xpeppers/sales-taxes-problem) in TDD
* Extra: Follow the [The World's Best Intro to TDD](http://online-training.jbrains.ca/p/wbitdd-01) by J. B. Rainsberger

### Session 3 - Clean code

* Read first ten chapters of [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
* [SOLID principles](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)
  * [SRP: Single Responsability Principle](https://docs.google.com/open?id=0ByOwmqah_nuGNHEtcU5OekdDMkk)
  * [OCP: Open-Closed Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1&hl=en)
  * [LSP: Liskov Substitution Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh&hl=en)
  * [ISP: Interface Segregation Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi&hl=en)
  * [DIP: Dependency Inversion Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz&hl=en)
* Start the [Racing Car Katas](https://github.com/emilybache/Racing-Car-Katas)
  * find SOLID violations
* Read [The Pragmatic Programmer](https://pragprog.com/book/tpp/the-pragmatic-programmer)
* See [Is SOLID A Good Idea](http://vimeo.com/20388419)
* See [Responsive Design](http://www.infoq.com/presentations/responsive-design)
* Extra: Follow the [__"Clean coders"__](http://cleancoders.com/) screencasts by Robert C. Martin

### Session 4 - Hexagonal architecture

* Read http://alistair.cockburn.us/Hexagonal+architecture
* Read http://matteo.vaccari.name/blog/the-hexagonal-architecture
* Read http://matteo.vaccari.name/blog/archives/154
* Read http://www.mountaingoatsoftware.com/blog/the-forgotten-layer-of-the-test-automation-pyramid
* Read http://c2.com/cgi/wiki?HexagonalArchitecture

### Session 5: Refactoring

* See [Martin Fowler @ OOP2014 "Workflows of Refactoring"](https://www.youtube.com/watch?v=vqEg37e4Mkw)
* Read first three chapters of [Refactoring: Improving the design of existing code](http://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672)
* See [Testing and Refactoring Legacy Code](https://www.youtube.com/watch?v=_NnElPO5BU0)
  * [Example Code](https://github.com/sandromancuso/trip-service-kata)
* Try the [GildedRoseKata](https://github.com/joebew42/GildedRose)
  * Code Coverage
  * Code Refactoring
  * Add the new feature
* Try the [TennisRefactoringKata](https://github.com/emilybache/Tennis-Refactoring-Kata) (find code smells)

### Session 6: TDD and "Friends"

* [How to Write Clean, Testable Code](https://www.youtube.com/watch?v=XcT4yYu_TTs)
* [Good Design is Easily-Learned](http://blog.scottbellware.com/2009/01/good-design-is-easily-learned.html)
* Try to learn and repeat these Katas autonomously
  * [TheBowlingGameKata](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata)
  * [TheRomanNumeralsKata](http://www.codekatas.org/casts/roman-numerals-kata-with-audio-commentary)
* Read the first eight chapters of [Growing Object Oriented Software, Guided by Tests](http://www.growing-object-oriented-software.com/)
* [Mocks Aren't Stubs](http://martinfowler.com/articles/mocksArentStubs.html)
* Encapsulation e Information Hiding:
  * http://www.natpryce.com/articles/000498.html
  * http://c2.com/cgi/wiki?EncapsulationIsNotInformationHiding
* Read [The Four Elements of Simple Design](http://www.jbrains.ca/permalink/the-four-elements-of-simple-design)
* Read [Overcoming the one weakness of OOP](http://blogs.ugidotnet.org/luKa/archive/2015/01/20/overcoming-the-one-weakness-of-oop.aspx)
* Read [Object Calisthenics](http://williamdurand.fr/2013/06/03/object-calisthenics/)
* See [Ian Cooper - TDD, where did it all go wrong](http://vimeo.com/68375232)
* See [J.B. Rainsberger - Integrated Tests Are A Scam](http://vimeo.com/80533536)
* See [Sandro Mancuso - Testing and Refactoring Legacy Code](http://vimeo.com/76472757)
* See [Sandro Mancuso - Crafted Design](http://vimeo.com/101106002)
* See [Mock Roles Not Object States](http://www.infoq.com/news/2008/08/Mock-Roles-Pryce-and-Freeman)

## Side learning paths
* [Languages](study-path/languages)
* [Tools](study-path/tools)
* [Operations](study-path/operations)

### Contributors

* All XPeppers team members ([@xpeppers](https://twitter.com/xpeppers)), featuring:
  * Pietro Di Bello [@pierodibello](http://twitter.com/pierodibello)
  * Filippo Liverani [@filippo-liverani](https://github.com/filippo-liverani)
  * Paolo D'Incau [@pdincau](https://github.com/pdincau)
  * Christian Fei [@christian-fei](https://github.com/christian-fei)
  * Simon Vocella [@voxsim](https://github.com/voxsim)
  * Joe Bew [@joebew42](https://github.com/joebew42/study-path)

* Giuseppe Capizzi [@gcapizzi](https://github.com/gcapizzi)
* Pietro Campagnano [@fain182](https://github.com/fain182)

### Additional Bibliography
* [__"Patterns of Enterprise Application Architecture"__](http://www.amazon.it/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420) by Martin Fowler
* [__"Working Effectively with Legacy Code"__](http://www.amazon.com/Working-Effectively-Legacy-Michael-Feathers/dp/0131177052) by Micheal Feathers
* [__"Understanding the Four Rules of Simple Design"__](https://leanpub.com/4rulesofsimpledesign) by C.Haines
