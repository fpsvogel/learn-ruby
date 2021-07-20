# Ruby and computer science: a self-learning curriculum

I am a former teacher working my way into software development. I am learning Ruby, Rails, and a healthy dose of computer science.

## Overview

- [Objections](#objections) ✅
- [Preliminaries](#preliminaries) ✅
- [Frontend basics](#frontend-basics) ✅
- [Ruby](#ruby) ✅
- [Rails](#rails) *(just started)*
- [Other essentials](#other-essentials)
- [Polish up my Ruby](#polish-up-my-ruby)
- [Meanwhile, computer science](#meanwhile-computer-science) *(~30%)*
- [Other programming/CS resource lists](#other-programmingcs-resource-lists)

## Objections

*Why Ruby?? Isn't JavaScript the obvious choice for web development?* Ruby is a good first language to master because its ecosystem is stable, the community is experienced, and for me Ruby is very enjoyable to write. Not convinced? [Read this](https://medium.com/learn-love-code/why-teach-ruby-bac8416c77ba) or [watch this](https://youtu.be/IlVfHG-pAag?t=1534).

*OK, but why so many books and courses?? Isn't practice more important than reading?* Yes, you should be spending more time coding than reading, but starting a project and getting into a coding routine is easy, whereas knowing what to read is not at all obvious at the beginning. Hence the larger space devoted to books and courses here. Besides the obvious reasons to undertake serious study (to learn from others so that I don't have to learn the hard way, and of course the bragging rights), I also simply enjoy knowing how things work under the hood.

## Preliminaries

- If you've never written a line of code in your life, you may want to start with the free tutorials at [BigBinary Academy](https://academy.bigbinary.com/learn-ruby) and/or [Learn to Program](https://pine.fm/LearnToProgram/) (or buy [the updated book version](https://pragprog.com/titles/ltp3/learn-to-program-third-edition/)). I studied some computer science in high school, so I had a bit of a head start.
- If you are a working adult, make sure your day job is conducive to part-time studying. Last year I was a first-year schoolteacher. That meant hours of grading in the evenings and on weekends, which would have made studying impossible. For this and other reasons I switched to a remote tech support job, which freed up my evenings and weekends (and early mornings, with no commute).
- Find a system for keeping *organized* notes, code snippets, and articles/videos saved for later. I use a simple text file ([similar to this](https://illdoitlater.xyz/t/plaintext)), which is more effortless than any knowledge base app that I've tried.
- Dip into the Ruby and wider programming communities. For example:
  - Join a local [Ruby meetup](https://www.meetup.com/topics/ruby/all/) and/or [Rails meetup](https://www.meetup.com/topics/ruby-on-rails/all/)
  - [Hacker Newsletter](https://hackernewsletter.com/)
  - [DEV newsletter](https://dev.to/t/newsletter)
  - [Ruby Radar newsletter](https://rubyradar.mailchimpsites.com/)
  - Ruby: [Reddit](https://www.reddit.com/r/ruby), [Discord](https://discord.gg/tSFdeuVfpc), [Slack](https://www.rubyonrails.link/)
  - Rails: [Reddit](https://www.reddit.com/r/rails) and [Discord](https://discord.gg/AuDNwjsyfm)
  - others on Discord: [Bridgetown](https://discord.gg/Cugms94QFM), [StimulusReflex](https://discord.com/invite/stimulus-reflex)
- Last but not least, take care of yourself! Studying (especially while working) can easily be overdone. Exercise and get plenty of sleep. If you develop wrist pain from computer use, act swiftly: get an ergonomic mouse and keyboard, do daily RSI stretches, and start using a break app such as [Workrave](https://workrave.org/).

So without further ado, here are my recommendations from what I studied. Resources that are free of charge are marked with a star (⭐). If you need more free resources, see the links to other lists at the bottom. You may be able to find the books for free (from your local library or more dubious sources) but be sure to buy them when you can, to support the authors. 🙂

## Frontend basics

- [x] Treehouse's [Frontend Web Development](https://teamtreehouse.com/tracks/front-end-web-development) track, or The Odin Project's ⭐[Foundations](https://www.theodinproject.com/paths/foundations/courses/foundations) + ⭐[HTML and CSS](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/html-and-css) + ⭐[JavaScript](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/javascript)
- [x] **Build a blog from scratch:** I have rebuilt it by now, but [here is that first iteration](https://fpsvogel-2020.netlify.app), and [here's how I built it](https://fpsvogel.com/posts/2020/zs). I am also posting daily discoveries on Twitter, where—confession—[I sometimes talk to myself](https://twitter.com/fpsvogel/status/1389915714098802692).

## Ruby

- [x] **Basics:** [The Well-Grounded Rubyist](https://www.manning.com/books/the-well-grounded-rubyist-third-edition) or ⭐[The Odin Project](https://www.theodinproject.com/courses/ruby-programming).
- [x] **Guided practice:** ⭐[Exercism](https://exercism.io/my/tracks/ruby), then ⭐[CodeWars](https://www.codewars.com) if you want more. Be sure to take notes each time you learn something new in an exercise, and [write up a reflection](https://fpsvogel.com/posts/2020/exercism-ruby) at the end.
- [x] **OOP:** [Practical Object-Oriented Design: An Agile Primer Using Ruby](https://www.poodr.com) (a.k.a. POODR), then [99 Bottles of OOP](https://sandimetz.com/99bottles-sample-ruby). More than any other books, these are worth the price tag.
- [x] **Ruby app:** Apply those OOP lessons. I made a CLI (command-line interface) [app that gives statistics on a reading log](https://fpsvogel.com/posts/2021/my-first-ruby-app-lessons-learned). Along the way I also [published a Ruby gem](https://fpsvogel.com/posts/2020/ruby-functional-programming), though in the end I abandoned it because I realized it did more harm than good. All part of the learning process…
- [x] **Design patterns:** [Head First Design Patterns](https://www.oreilly.com/library/view/head-first-design/9781492077992/). Also ⭐[Refactoring.Guru](https://refactoring.guru/) for a catalog of code smells, refactoring recipes, and design patterns.
- [x] **Bridgetown:** I [remade my blog](https://fpsvogel.com/posts/2021/build-a-blog-with-bridgetown) with ⭐[Bridgetown](https://github.com/bridgetownrb/bridgetown) (an updated Jekyll), and built a Ruby component for [a reading list](https://fpsvogel.com/reading/).

## Rails

- [ ] **Basics:**
  - [ ] ⭐[Rails for Beginners](https://gorails.com/series/rails-for-beginners)
  - [ ] [A general Rails course on Udemy](https://www.udemy.com/course/ruby-on-rails-6-learn-20-gems-build-an-e-learning-platform/) (or [find a newer one](https://www.udemy.com/courses/search/?duration=extraLong&q=ruby+on+rails&ratings=4.0&sort=newest&src=ukw) if that one is of date by the time you read this)
  - [ ] [Ruby on Rails Tutorial](https://www.railstutorial.org)
  - [ ] ⭐[Rails Code Along](https://www.railscodealong.com/)
  - [ ] ⭐[Demystifying Rails](https://launchschool.com/books/demystifying_rails)
- [ ] **Dig deeper:**
  - [ ] [Dissecting Ruby on Rails](https://www.udemy.com/course/professional-rails-5-development-course/)
  - [ ] [Rebuilding Rails](http://rebuilding-rails.com/)
  - [ ] [Maintainable Rails](https://leanpub.com/maintain-rails)
  - [ ] [Sustainable Web Development with Ruby on Rails](https://sustainable-rails.com/)
- [ ] **Build Rails apps:**
  - [ ] A Rails app using ⭐[StimulusReflex](https://docs.stimulusreflex.com/) to build a reactive frontend.
  - [ ] A Rails API + a separate frontend, maybe React so that I'm familiar with it.
- [ ] **Deployment:** [Deployment from Scratch](https://deploymentfromscratch.com/) and [Deploying Rails Applications](https://leanpub.com/deploying_rails_applications).

## Other essentials

- [ ] **Git:** [Introduction to Git and GitHub](https://launchschool.com/books/git) and [Pro Git](https://git-scm.com/book/en/v2)
- [ ] **Linux:** [The Linux Command Line](https://linuxcommand.org/tlcl.php)
- [ ] **HTTP:** [MDN Web Doc on HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)
- [ ] **Intro to professional experience:**
  - [ ] Contribute to open source projects. ⭐[First Timers Only](https://www.firsttimersonly.com/) is a good place to start.
  - [ ] Volunteer through ⭐[Ruby for Good](https://rubyforgood.org/)?
  - [ ] Do a few contract jobs on Upwork?
- [ ] **The arcane arts of getting hired:**
  - [ ] [Cracking the Coding Interview](https://www.crackingthecodinginterview.com/)
  - [ ] [Elements of Programming Interviews](https://elementsofprogramminginterviews.com/)
  - [ ] [The Tech Resume Inside Out](https://thetechresume.com/)

## Polish up my Ruby

- [ ] **Books:**
  - [ ] [Polished Ruby Programming](https://www.packtpub.com/product/polished-ruby-programming/9781801072724)
  - [ ] [Ruby Science](https://github.com/thoughtbot/ruby-science)
  - [ ] [Metaprogramming Ruby](https://pragprog.com/titles/ppmetr2/metaprogramming-ruby-2/)
  - [ ] [The Complete Guide to Rails Performance](https://www.railsspeed.com/)
  - [ ] [The Ruby on Rails Performance Apocrypha](https://www.speedshop.co/2021/01/14/announcing-apocrypha.html)
- [ ] **Screencasts and courses:**
  - [ ] ⭐[Web-Crunch](https://web-crunch.com/collections)
  - [ ] ⭐[Upcase](https://thoughtbot.com/blog/announcing-upcase-is-free)
  - [ ] [GoRails](https://gorails.com)
  - [ ] [Drifting Ruby](https://www.driftingruby.com/)
  - [ ] [RubyTapas](https://www.rubytapas.com/)
  - [ ] [Destroy All Software](https://www.destroyallsoftware.com/screencasts/catalog)
- [ ] ⭐**Podcasts:**
  - [ ] [Remote Ruby](https://remoteruby.transistor.fm/episodes)
  - [ ] [Ruby on Rails Podcast](https://www.therubyonrailspodcast.com/)
  - [ ] [Ruby Rogues](https://devchat.tv/show/ruby-rogues/)
  - [ ] [The Bike Shed](https://www.bikeshed.fm/)
  - [ ] [Rails with Jason](https://www.codewithjason.com/rails-with-jason-podcast/)

## Meanwhile, computer science

- [x] **Computers 101:** [Code: The Hidden Language of Computer Hardware and Software](https://www.charlespetzold.com/code/)
- [x] **Algorithms I:** [Data Structures and Algorithms in Java](https://www.amazon.com/Data-Structures-Algorithms-Java-2nd/dp/0672324539)
  - [ ] for reinforcement: [Algorithms (Sedgewick & Wayne)](https://algs4.cs.princeton.edu/home/) and the accompanying course: ⭐[part 1](https://www.coursera.org/learn/algorithms-part1), ⭐[part 2](https://www.coursera.org/learn/algorithms-part2)
  - [ ] for practice: ⭐[Project Euler](https://projecteuler.net/)
- [x] **Usability:** [Don't Make Me Think](https://sensible.com/dont-make-me-think/), [The Design of Everyday Things](https://www.nngroup.com/books/design-everyday-things-revised/), and [50 UI Tips](https://fifty.user-interface.io/50_ui_tips.pdf)
- [x] **Operating systems:** [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/)
- [x] **Networks:** [Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/eighth.htm)
  - [ ] for reinforcement: read it again!
- [ ] **Computer architecture:** [The Elements of Computing Systems: Building a Modern Computer from First Principles](https://mitpress.mit.edu/books/elements-computing-systems-second-edition) plus ⭐[the site](https://www.nand2tetris.org/) and accompanying course: ⭐[part 1](https://www.coursera.org/learn/build-a-computer, ⭐[part 2](https://www.coursera.org/learn/nand2tetris2))
  - [ ] for a deeper dive: [Computer Systems: A Programmer's Perspective](https://csapp.cs.cmu.edu/)
- [ ] **Software architecture:** [Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/)
- [ ] **Databases:** ⭐[Readings in Database Systems](http://www.redbook.io/)
- [ ] **Compilers:** ⭐[Crafting Interpreters](https://craftinginterpreters.com/)
- [ ] **Math:** [Concrete Mathematics: A Foundation for Computer Science](https://www-cs-faculty.stanford.edu/~knuth/gkp.html). The math review that I'm doing leading up to this is proving to be a journey in itself, which I will outline separately in the future.
- [ ] **Algorithms II:** [The Algorithm Design Manual (Skiena)](https://www.algorist.com/)
  - [ ] for even more: [Algorithm Design (Kleinberg & Tardos)](https://www.cs.princeton.edu/~wayne/kleinberg-tardos/)
- [ ] **??:** ⭐[Structure and Interpretation of Computer Programs](https://sarabander.github.io/sicp/html/index.xhtml) (and [video lectures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/)). I'm still not sure what exactly this book is about (reading the first few pages only discouraged me from looking further) but it is an often-recommended introductory text on "programming". So, maybe someday I will learn this "programming", after I've learned the less intimidating stuff (all of the above).

## Other programming/CS resource lists

- [Teach Yourself CS](https://teachyourselfcs.com/)
- [p1xt Computer Science and Programming](https://github.com/P1xt/p1xt-guides)
- [Open Source Society University](https://github.com/ossu/computer-science)