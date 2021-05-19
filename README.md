# Ruby and computer science: a self-learning curriculum

I am a former teacher working my way into software development. I am learning Ruby, Rails, and a healthy dose of computer science.

## Objections

*Why Ruby?? Isn't JavaScript the obvious choice for web development?* Ruby is a good first language to master because its ecosystem is stable, the community is more experienced, and for me Ruby is more enjoyable to write. Not convinced? [Read this](https://medium.com/learn-love-code/why-teach-ruby-bac8416c77ba) or [watch this](https://youtu.be/IlVfHG-pAag?t=1534).

*OK, but why so many books and courses?? Isn't practice more important than reading?* Yes, you should be spending more time coding than reading, but starting a project and getting into a coding routine is easy. Knowing what to read is not at all obvious at the beginning. Hence the larger space devoted to books and courses here. Besides the obvious reasons to undertake serious study (to learn from the masters, and to spice up my resume), I also simply enjoy knowing how things work under the hood.

## Preliminaries

- If you've never written a line of code in your life, you may want to start with [Learn to Program](https://pine.fm/LearnToProgram/). I studied some computer science in high school, so I had a bit of a head start.
- If you are a working adult, make sure your day job is conducive to part-time studying. Last year I was a first-year schoolteacher. That meant hours of grading in the evenings and on weekends, which would have made studying impossible. For this and other reasons I switched to a remote tech support job, which freed up my evenings and weekends (and early mornings, with no commute).
- Find a system for keeping *organized* notes, code snippets, and articles to read later. I use a simple text file ([similar to this](https://illdoitlater.xyz/t/plaintext)), which is more effortless than any knowledge base app that I've tried.
- It's worth dipping into the Ruby and wider programming communities. Here are my favorites:
  - [Hacker Newsletter](https://hackernewsletter.com/)
  - [DEV newsletter](https://dev.to/t/newsletter)
  - Ruby: [Reddit](https://www.reddit.com/r/ruby), [Discord](https://discord.gg/tSFdeuVfpc), [Slack](https://www.rubyonrails.link/)
  - Rails: [Reddit](https://www.reddit.com/r/rails) and [Discord](https://discord.gg/AuDNwjsyfm)
  - others on Discord: [Bridgetown](https://discord.gg/Cugms94QFM), [StimulusReflex](https://discord.com/invite/stimulus-reflex)
- Last but not least, take care of yourself! Studying (especially while working) can easily be overdone. Exercise and get plenty of sleep. If you develop wrist pain from computer use, act swiftly: get an ergonomic mouse and keyboard, do RSI stretches, and start using a break app such as [Workrave](https://workrave.org/).

So without further ado, here are my recommendations from what I studied. Resources that are free of charge are marked with a star (⭐). If you need more free resources, see the links to other lists at the bottom. But you may be able to find the books for free at your local library or via Interlibrary Loan.

## Frontend basics

- [x] [Frontend Web Development](https://teamtreehouse.com/tracks/front-end-web-development) track on Treehouse, OR The Odin Project: ⭐[Foundations](https://www.theodinproject.com/paths/foundations/courses/foundations) + ⭐[HTML and CSS](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/html-and-css) + ⭐[JavaScript](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/javascript)
- [x] **Build a blog from scratch:** Which you are reading. [Here's how I built it](https://fpsvogel.netlify.app/posts/2020-07-23-zs.html). I am also posting daily discoveries on Twitter, where—confession—[I sometimes talk to myself](https://twitter.com/fpsvogel/status/1389915714098802692).

## Ruby

- [x] **Basics:** [The Well-Grounded Rubyist](https://www.manning.com/books/the-well-grounded-rubyist-third-edition) or ⭐[The Odin Project](https://www.theodinproject.com/courses/ruby-programming).
- [x] **Guided practice:** ⭐[Exercism](https://exercism.io/my/tracks/ruby), then ⭐[CodeWars](https://www.codewars.com) if you want more. Be sure to take notes when you learn something new, and [write up a reflection](https://fpsvogel.netlify.app/posts/2020-11-03-exercism-ruby.html) at the end.
- [x] **OOP:** [Practical Object-Oriented Design: An Agile Primer Using Ruby](https://www.poodr.com) (a.k.a. POODR), then [99 Bottles of OOP](https://sandimetz.com/99bottles-sample-ruby). More than any other books, these are worth the price tag.
- [x] **Ruby app:** Apply those OOP lessons. I made a CLI (command-line interface) [app that gives statistics on a reading log](https://fpsvogel.netlify.app/posts/2021-05-19-my-first-ruby-app-lessons-learned.html). Along the way I also [published a Ruby gem](https://fpsvogel.netlify.app/posts/2020-12-21-ruby-functional-programming.html), though in the end I didn't use it for my project because I realized it leads to unclear code. But at least I improved my metaprogramming in the process of making the gem.
- [x] **Design patterns:** [Head First Design Patterns](https://www.oreilly.com/library/view/head-first-design/9781492077992/). Also ⭐[Refactoring.Guru](https://refactoring.guru/) for a catalog of code smells, refactoring recipes, and design patterns.
- [ ] **Bridgetown apps:** I'm remaking this blog on [Bridgetown](https://github.com/bridgetownrb/bridgetown) (an updated Jekyll), then I'll use it to make a couple of static web apps.
- [ ] **Rails:**
  - [ ] ⭐[Rails for Beginners](https://gorails.com/series/rails-for-beginners)
  - [ ] [A Rails course on Udemy](https://www.udemy.com/course/ruby-on-rails-6-learn-20-gems-build-an-e-learning-platform/) (or [find a newer one](https://www.udemy.com/courses/search/?duration=extraLong&q=ruby+on+rails&ratings=4.0&sort=newest&src=ukw) if that one is of date)
  - [ ] [Ruby on Rails Tutorial](https://www.railstutorial.org)
  - [ ] ⭐[Rails Code Along](https://www.railscodealong.com/)
  - [ ] [Dissecting Ruby on Rails](https://www.udemy.com/course/professional-rails-5-development-course/)
  - [ ] ⭐[Demystifying Rails](https://launchschool.com/books/demystifying_rails)
- [ ] **Rails app:** And learn [StimulusReflex](https://docs.stimulusreflex.com/).
- [ ] **Deployment:** [Deployment from Scratch](https://deploymentfromscratch.com/) and [Deploying Rails Applications](https://leanpub.com/deploying_rails_applications).
- [ ] **Open source contributions:** ⭐[First Timers Only](https://www.firsttimersonly.com/) is a good place to start.
- [ ] **Polishing up—books:**
  - [ ] [Polished Ruby Programming](https://www.packtpub.com/product/polished-ruby-programming/9781801072724)
  - [ ] [Ruby Science](https://github.com/thoughtbot/ruby-science)
  - [ ] [Metaprogramming Ruby](https://pragprog.com/titles/ppmetr2/metaprogramming-ruby-2/)
  - [ ] [The Complete Guide to Rails Performance](https://www.railsspeed.com/)
  - [ ] [The Ruby on Rails Performance Apocrypha](https://www.speedshop.co/2021/01/14/announcing-apocrypha.html)
- [ ] **Polishing up—screencasts and courses:**
  - [ ] ⭐[Web-Crunch](https://web-crunch.com/collections)
  - [ ] ⭐[Upcase](https://thoughtbot.com/blog/announcing-upcase-is-free)
  - [ ] [GoRails](https://gorails.com)
  - [ ] [Drifting Ruby](https://www.driftingruby.com/)
  - [ ] [RubyTapas](https://www.rubytapas.com/)
  - [ ] [Destroy All Software](https://www.destroyallsoftware.com/screencasts/catalog)
- [ ] ⭐**Polishing—podcasts:**
  - [ ] [Remote Ruby](https://remoteruby.transistor.fm/episodes)
  - [ ] [Ruby on Rails Podcast](https://5by5.tv/rubyonrails)
  - [ ] [The Bike Shed](https://www.bikeshed.fm/)

## Meanwhile, computer science

- [x] **Computers 101:** [Code: The Hidden Language of Computer Hardware and Software](https://www.charlespetzold.com/code/)
- [x] **Algorithms I:** [Data Structures and Algorithms in Java](https://www.amazon.com/Data-Structures-Algorithms-Java-2nd/dp/0672324539)
- [x] **Usability:** [Don't Make Me Think](https://sensible.com/dont-make-me-think/) and [The Design of Everyday Things](https://www.nngroup.com/books/design-everyday-things-revised/)
- [x] **Operating Systems:** [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/)
- [x] **Networks:** [Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/eighth.htm)
- [ ] **Computer Architecture:** [The Elements of Computing Systems: Building a Modern Computer from First Principles](https://mitpress.mit.edu/books/elements-computing-systems-second-edition) ([site](https://www.nand2tetris.org/). Free accompanying course: [part 1](https://www.coursera.org/learn/build-a-computer), [part 2](https://www.coursera.org/learn/nand2tetris2)).
- [ ] **Software Architecture:** [Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/)
- [ ] **Databases:** ⭐[Readings in Database Systems](http://www.redbook.io/)
- [ ] **Compilers:** ⭐[Crafting Interpreters](https://craftinginterpreters.com/)
- [ ] **Math:** [Concrete Mathematics: A Foundation for Computer Science](https://www-cs-faculty.stanford.edu/~knuth/gkp.html). The math review that I'm doing leading up to this has been a journey in itself, to be outlined in a future post.
- [ ] **Algorithms II:** [The Algorithm Design Manual](https://www.algorist.com/)
- [ ] **??:** ⭐[Structure and Interpretation of Computer Programs](https://sarabander.github.io/sicp/html/index.xhtml) (and [video lectures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/)). I have often seen this recommended, but its exact subject matter (and whether reading it amounts to anything more than a badge of honor) so far eludes me. Which, I'm sure some would retort, only shows how small my mind still is at this point.

## Other programming/CS resource lists

- [Teach Yourself CS](https://teachyourselfcs.com/)
- [p1xt Computer Science and Programming](https://github.com/P1xt/p1xt-guides)
- [Open Source Society University](https://github.com/ossu/computer-science)