# Ruby and computer science: a self-learning curriculum

Hi! I'm a former teacher working my way into software development. I'm learning Ruby, Rails, and a healthy dose of computer science. If you have a favorite resource that's missing below, let me know by [opening an issue](https://github.com/fpsvogel/learn-ruby-and-cs/issues/new/choose)!

## Overview

- [Objections](#objections) ✅
- [Preliminaries](#preliminaries) ✅
- [Frontend basics](#frontend-basics) ✅
- [Ruby](#ruby) ✅
- [Rails](#rails) *(~10% finished)*
- [Other essentials](#other-essentials)
- [Ruby 'casts](#ruby-casts)
- [Meanwhile, computer science](#meanwhile-computer-science) *(~30% finished)*
- [Other programming/CS resource lists](#other-programmingcs-resource-lists)

## Objections

*Why Ruby?? Isn't JavaScript the obvious choice for web development?* JavaScript is definitely more popular, but Ruby is a good choice for self-taught developers like me because (a) it's enjoyable to write, and (b) it's optimized for speed of development. Not convinced? [Here's a piece that I wrote](https://fpsvogel.com/posts/2021/why-learn-ruby) which goes into more detail and answers common objections to Ruby. Or if you want a second opinion, [read this](https://medium.com/learn-love-code/why-teach-ruby-bac8416c77ba) or [watch this](https://youtu.be/IlVfHG-pAag?t=1534).

*OK, but why so many books and courses?? Isn't practice more important than reading?* Yes, you should be spending more time coding than reading, but starting a project and getting into a coding routine is easy (if you can't think of any project ideas, just ["build your own X"](https://build-your-own-x.vercel.app/)), whereas knowing what to read is not at all obvious at the beginning. Hence the larger space devoted to books and courses here. Also, by learning from more experienced developers, you'll actually save time because you can avoid lots of mistakes and dead ends without having to learn those lessons the hard way.

## Preliminaries

- If you've never written a line of code in your life, you may want to start with the free tutorials at [BigBinary Academy](https://academy.bigbinary.com/learn-ruby) and/or [Learn to Program](https://pine.fm/LearnToProgram/) (or buy [the updated book version](https://pragprog.com/titles/ltp3/learn-to-program-third-edition/)). I studied some computer science in high school, so I had a bit of a head start.
- If you are a working adult, make sure your day job is conducive to part-time studying. I used to be a teacher and spent hours grading in the evenings and on weekends, which would have made studying impossible. For this and other reasons I switched to a remote tech support job, which freed up my schedule.
- Find a system for keeping *organized* notes, code snippets, and articles/videos saved for later. I use [a simple text file](https://fpsvogel.com/posts/2021/plain-text-knowledge-base), which is more effortless than any knowledge base app that I've tried.
- Last but not least, take care of yourself! Studying (especially while working) can easily be overdone. Exercise and get plenty of sleep. If you develop wrist pain from heavy computer use, act swiftly: get an ergonomic keyboard ([the one I use](https://fpsvogel.com/posts/2021/keyboardio-atreus) is effective and affordable), [do daily RSI stretches](https://youtu.be/fdD7CgN5FGg), and start using a break app such as [Workrave](https://workrave.org/).

So without further ado, here are my recommendations from what I studied. Resources that cost money are marked with 💲. If you need more free resources, see the links to other lists at the bottom. You may be able to find the books for free (from your local library or more dubious sources) but be sure to buy them when you can, to support the authors. 🙂

## Frontend basics

- Subscribe to programming newsletters for inspiration. My favorites:
  - [Hacker Newsletter](https://hackernewsletter.com/)
  - [DEV newsletter](https://dev.to/t/newsletter)
- [x] Treehouse's 💲[Frontend Web Development](https://teamtreehouse.com/tracks/front-end-web-development) track, or The Odin Project's [Foundations](https://www.theodinproject.com/paths/foundations/courses/foundations) + [HTML and CSS](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/html-and-css) + [JavaScript](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/javascript)
- [x] **Build a blog from scratch:** I have rebuilt it by now, but [here is that first iteration](https://fpsvogel-2020.netlify.app), and [here's how I built it](https://fpsvogel.com/posts/2020/zs). I am also posting some of my learnings on Twitter, where—confession—[I sometimes talk to myself](https://twitter.com/fpsvogel/status/1389915714098802692).

## Ruby

- **Community:**
  - [Reddit](https://www.reddit.com/r/ruby)
  - [Discord](https://discord.gg/tSFdeuVfpc)
  - [Ruby Weekly newsletter](https://rubyweekly.com/)
  - [Ruby Radar newsletter](https://rubyradar.mailchimpsites.com/)
- [x] **Basics:** There a few good options here.
  - [The Ruby Programming course on The Odin Project](https://www.theodinproject.com/courses/ruby-programming)
  - [Ruby Is For Fun](https://github.com/ro31337/rubyisforfun)
  - 💲[The Well-Grounded Rubyist](https://www.manning.com/books/the-well-grounded-rubyist-third-edition) (worth re-reading later, as it covers some advanced Ruby)
- [x] **Guided practice:** [Exercism](https://exercism.io/my/tracks/ruby), then [CodeWars](https://www.codewars.com) if you want more. Be sure to take notes each time you learn something new in an exercise, and write up a reflection at the end ([here is mine](https://fpsvogel.com/posts/2020/exercism-ruby)).
- [x] **OOP:** 💲[Practical Object-Oriented Design: An Agile Primer Using Ruby](https://www.poodr.com) (a.k.a. POODR), then 💲[99 Bottles of OOP](https://sandimetz.com/99bottles-sample-ruby). More than any other Ruby books, these are worth the price tag.
- [x] **Build a Ruby app:** Apply those OOP lessons. I made a CLI (command-line interface) [app that gives statistics on a reading log](https://fpsvogel.com/posts/2021/my-first-ruby-app-lessons-learned). Along the way I also [published a Ruby gem](https://fpsvogel.com/posts/2020/ruby-functional-programming), though in the end I abandoned it because I realized it did more harm than good. All part of the learning process…
- [x] **Design patterns:** 💲[Head First Design Patterns](https://www.oreilly.com/library/view/head-first-design/9781492077992/). Also [Refactoring.Guru](https://refactoring.guru/) for a catalog of code smells, refactoring recipes, and design patterns.
- [x] **Build a site with Bridgetown:** I [remade my blog](https://fpsvogel.com/posts/2021/build-a-blog-with-bridgetown) with [Bridgetown](https://github.com/bridgetownrb/bridgetown) (an updated Jekyll), and built a Ruby component for [a reading list](https://fpsvogel.com/reading/). Be sure to [join their Discord server](https://discord.gg/Cugms94QFM)—the maintainers are very welcoming and helpful to newbies.

## Rails

Only courses are listed below, but be sure to *build stuff* as you learn. [Here's how I started building my first Rails app right from the beginning.](https://fpsvogel.com/posts/2021/first-rails-app-plain-reading) Another invaluable form of practice is to [start contributing to open source](https://fpsvogel.com/posts/2021/how-to-contribute-to-open-source-ruby-rails).

- **Community:**
  - [Reddit](https://www.reddit.com/r/rails)
  - [Slack](https://www.rubyonrails.link/)
  - [StimulusReflex on Discord](https://discord.com/invite/stimulus-reflex): you don't need to wait until you start using StimulusReflex to join, because these folks are very helpful to beginners struggling with Rails frontend issues in general.
- **Basics:**
  - [x] [GoRails - Rails for Beginners](https://gorails.com/series/rails-for-beginners) is great for getting started quickly. If you'd like a slightly longer follow-up, try [Ruby on Rails: A Beginner's Guide](https://www.udemy.com/course/ruby-on-rails-a-beginners-guide-free/).
  - [x] 💲[Ruby on Rails Tutorial](https://www.railstutorial.org) will teach you Rails testing, good Git habits, and how to build an authentication (user login) system from scratch.
  - [x] [Rails Guides](https://guides.rubyonrails.org/)
  - [ ] For a review of everything so far: [Full Stack Ruby on Rails at The Odin Project](https://www.theodinproject.com/paths/full-stack-ruby-on-rails) or (if you prefer videos) [App Academy Open](https://www.appacademy.io/course/app-academy-open).
- **Testing:** Minitest is familiar at this point. Now it's time to learn RSpec and Rails-specific testing techniques.
  - [x] 💲[Jason Swett - The Complete Guide to Rails Testing](https://www.codewithjason.com/complete-guide-to-rails-testing/)
  - [ ] 💲[Jason Swett - An upcoming (2022) Rails testing course](https://twitter.com/JasonSwett/status/1446497878093013018)
  - [ ] 💲[Effective Testing with RSpec 3](https://pragprog.com/titles/rspec3/effective-testing-with-rspec-3/)
- **Intermediate:**
  - [x] [Thoughtbot - Ruby Science](https://github.com/thoughtbot/ruby-science) (design patterns)
  - [ ] [Upcase](https://thoughtbot.com/upcase), especially [Advanced ActiveRecord Querying](https://thoughtbot.com/upcase/advanced-activerecord-querying)
  - [ ] [Rails Authentication from Scratch](https://github.com/stevepolitodesign/rails-authentication-from-scratch)
  - [ ] 💲[Agile Web Development with Rails 7](https://www.pragprog.com/titles/rails7/agile-web-development-with-rails-7/)
  - [ ] 💲[The Rails 6 Way](https://leanpub.com/therails6way)
- **Architecture:**
  - [ ] 💲[Maintainable Rails](https://leanpub.com/maintain-rails)
  - [ ] 💲[Sustainable Web Development with Ruby on Rails](https://sustainable-rails.com/)
- **Code-alongs:**
  - [ ] [Rails Code Along](https://www.railscodealong.com/)
  - [ ] [Web-Crunch - Let's Build](https://web-crunch.com/collections/lets-build-for-ruby-and-rails-developers)
  - [ ] [CJ Avilla - clearbnb](https://youtube.com/playlist?list=PLS6F722u-R6LoD3UN0EE_cKtHVG2EWn0t)
  - [ ] [CJ Avilla - Stock App](https://youtube.com/playlist?list=PLS6F722u-R6JOyF7jKb4aZsX0l6eDARp1)
  - [ ] [SupeRails Code Along](https://youtube.com/playlist?list=PLdTytUiloS14ejJJeuUkf8ZRhzdzYCJMh)
  - [ ] 💲[Ruby on Rails 6: Learn 25+ gems and build a Startup MVP](https://www.udemy.com/course/ruby-on-rails-6-learn-20-gems-build-an-e-learning-platform/)
    - By the way, you can get any Udemy course for less than $20 if you use a discount code, which you can get either by signing up for their email updates, or by leaving a course in your cart for a few days.
- **Performance:**
  - [ ] (coming soon) resources on Active Record and SQL
  - [ ] 💲[The Complete Guide to Rails Performance](https://www.railsspeed.com/)
  - [ ] 💲[The Ruby on Rails Performance Apocrypha](https://www.speedshop.co/2021/01/14/announcing-apocrypha.html)
- **Rails internals:**
  - [ ] [Demystifying Rails](https://launchschool.com/books/demystifying_rails)
  - [ ] 💲[Dissecting Ruby on Rails](https://www.udemy.com/course/professional-rails-5-development-course/)
  - [ ] 💲[Rebuilding Rails](http://rebuilding-rails.com/)
- **Codebases to study:** These are Rails projects that I've seen mentioned more than once as good examples to learn from. For lots more open-source Rails projects, see [OpenSourceRails](https://opensourcerails.org/) and [Awesome Ruby and Rails Open Source Apps](https://github.com/asyraffff/Open-Source-Ruby-and-Rails-Apps).
  - [ ] [github.com/thoughtbot/upcase](https://github.com/thoughtbot/upcase)
  - [ ] [github.com/alphagov/whitehall](https://github.com/alphagov/whitehall)
  - [ ] [github.com/houndci/hound](https://github.com/houndci/hound)
  - [ ] [github.com/codetriage/codetriage](https://github.com/codetriage/codetriage)
  - [ ] [github.com/mastodon/mastodon](https://github.com/mastodon/mastodon)
  - [ ] [github.com/rubygems/rubygems.org](https://github.com/rubygems/rubygems.org)
  - [ ] [github.com/forem/forem](https://github.com/forem/forem)
  - [ ] [github.com/solidusio/solidus](https://github.com/solidusio/solidus)
- **Hotwire:**
  - [ ] [Read the docs](https://hotwired.dev/)
  - [ ] [GoRails screencast](https://gorails.com/episodes/hotwire-rails)
  - [ ] Evil Martians [talk](https://www.youtube.com/watch?v=sIxvxp7E0xg) and [blog post](https://evilmartians.com/chronicles/hotwire-reactive-rails-with-no-javascript)
  - [ ] [Turbo Rails tutorial](https://www.hotrails.dev/)
  - [ ] [Hotwired ATS: Modern, full-stack Rails development](https://davidcolby.gumroad.com/l/hotwired-ats/68y8c5c)
  - [ ] 💲[Learn Hotwire by Building a Forum](https://store.afomera.dev/learn-hotwire)
- **StimulusReflex:**
  - [ ] [Read the docs](https://docs.stimulusreflex.com/)
  - [ ] 💲[Interactive Rails with StimulusReflex](https://courses.jasoncharnes.com/stimulus-reflex)
  - [ ] 💲[An upcoming book by David Colby](https://twitter.com/davidcolbyatx/status/1458171481029021704)
  - [ ] 💲[StimulusReflex Patterns](https://www.stimulusreflexpatterns.com/)
  - [ ] [Better StimulusJS](https://www.betterstimulus.com/)
  - [ ] [Stimulus components](https://stimulus-components.netlify.app/)
  - [ ] [Stimulus Use](https://stimulus-use.github.io/stimulus-use/#/)
- **Advanced Ruby:**
  - [ ] 💲[Metaprogramming Ruby](https://pragprog.com/titles/ppmetr2/metaprogramming-ruby-2/)
  - [ ] 💲[Ruby Under a Microscope](https://patshaughnessy.net/ruby-under-a-microscope)
- **Deployment:**
  - [ ] 💲[Deployment from Scratch](https://deploymentfromscratch.com/)
  - [ ] 💲[Deploying Rails Applications](https://leanpub.com/deploying_rails_applications)

## Other essentials

- **Open source:**
  - [x] Contribute to open source projects. I've written [a short guide on how to get started with this](https://fpsvogel.com/posts/2021/how-to-contribute-to-open-source-ruby-rails).
  - [ ] 💲[How to Open Source](https://howtoopensource.dev/)
- [ ] **Git:** [Introduction to Git and GitHub](https://github.com/bobbyiliev/introduction-to-git-and-github-ebook/) (and [here's another good one by the same name](https://launchschool.com/books/git)), then [Pro Git](https://git-scm.com/book/en/v2). Lots more resources [are listed here](https://dev.to/anaveecodes/how-to-get-better-with-git-25d1).
- [ ] **Linux:** [The Linux Command Line](https://linuxcommand.org/tlcl.php)
- [ ] **HTTP:** [MDN Web Doc on HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP). See also "Networks" under [the computer science section](#meanwhile-computer-science).
- [ ] **Security:** 💲[Web Security for Developers: Real Threats, Practical Defense](https://www.amazon.com/Web-Security-Developers-Malcolm-McDonald-ebook/dp/B07V78WH7V)
- [ ] **Learn another Ruby app framework:** Probably [Roda](https://roda.jeremyevans.net/) given its increasing [connection with Bridgetown](https://github.com/bridgetownrb/bridgetown/issues/379), but I should also learn how [Hanami](https://hanamirb.org/) works. Jobs in Ruby are mostly in Rails, but it's still valuable to broaden my horizons and learn different approaches.
- **Intro to professional experience:**
  - [ ] Join [Year One](https://www.joinyearone.io/).
  - [ ] Get involved in [Product Hunt](https://www.producthunt.com/).
  - [ ] Do a few contract jobs on [Upwork](https://www.upwork.com/) or [Freelancer](https://www.freelancer.com/).
- **The arcane arts of getting hired:**
  - [x] [How to find your first Rails job](https://fpsvogel.com/posts/2022/how-to-find-ruby-rails-job), notes from my own job search.
  - [x] 💲[Get Your First Developer Job](https://learnetto.com/users/hrishio/courses/get-your-first-developer-job)
  - [x] Attend some [Ruby meetups](https://www.meetup.com/find/?keywords=ruby), where you might find job leads.
  - [ ] 💲[The Tech Resume Inside Out](https://thetechresume.com/)
  - I didn't read any of the popular books on interview prep because I wanted to avoid that type of algorithm/whiteboarding interview, which in any case is not very common in the Ruby world. But if you want to be ready for that: 💲[Cracking the Coding Interview](https://www.crackingthecodinginterview.com/) and/or 💲[Elements of Programming Interviews](https://elementsofprogramminginterviews.com/)

## Ruby blogs and 'casts

- **Blogs:**
  - [ ] [Thoughtbot](https://thoughtbot.com/blog)
  - [ ] [Code with Jason](https://www.codewithjason.com/articles/)
- **Screencasts:** Checking one of these off means "I've watched all the episodes that interest me from the past three years or so, and I'm keeping an eye out for new episodes that would help me, or old unwatched episodes when they become relevant to me."
  - [ ] [Web-Crunch - Ruby on Rails](https://web-crunch.com/collections/ruby-on-rails) and [an older collection](https://web-crunch.com/collections/lets-build-with-ruby-on-rails)
  - [ ] [SupeRails](https://www.youtube.com/c/SupeRails/playlists)
  - [ ] [Phil Smy - Ruby on Rails](https://youtube.com/playlist?list=PLiJC12qFqVo3DrqGZn80DvdT8qGsQT9wh)
  - [ ] [DHH - On Writing Software Well](https://youtube.com/playlist?list=PL9wALaIpe0Py6E_oHCgTrD6FvFETwJLlx)
  - [ ] 💲[GoRails](https://gorails.com)
  - [x] 💲[Drifting Ruby](https://www.driftingruby.com/)
  - [ ] 💲[Destroy All Software](https://www.destroyallsoftware.com/screencasts/catalog)
- **Podcasts:**
  - [ ] [Remote Ruby](https://remoteruby.transistor.fm/episodes)
  - [ ] [Ruby on Rails Podcast](https://www.therubyonrailspodcast.com/)
  - [ ] [Ruby Rogues](https://devchat.tv/show/ruby-rogues/)
  - [ ] [The Bike Shed](https://www.bikeshed.fm/)
  - [ ] [Code with Jason](https://www.codewithjason.com/code-with-jason-podcast/)
  - [ ] [Running in Production – Rails](https://runninginproduction.com/tags/rails)

## Meanwhile, computer science

- **How computers work:**
  - [x] 💲[Code: The Hidden Language of Computer Hardware and Software](https://www.charlespetzold.com/code/)
  - [x] for hands-on learning: *From Nand to Tetris* course ([Part 1](https://www.coursera.org/learn/build-a-computer), [Part 2](https://www.coursera.org/learn/nand2tetris2)) along with the textbook 💲[The Elements of Computing Systems: Building a Modern Computer from First Principles](https://mitpress.mit.edu/books/elements-computing-systems-second-edition)
  - [ ] going deeper: 💲[Computer Systems: A Programmer's Perspective](https://csapp.cs.cmu.edu/)
- **Algorithms:**
  - [x] 💲[Data Structures and Algorithms in Java](https://www.amazon.com/Data-Structures-Algorithms-Java-2nd/dp/0672324539)
  - [ ] for reinforcement: *Algorithms* course by Sedgewick & Wayne ([Part 1](https://www.coursera.org/learn/algorithms-part1), [Part 2](https://www.coursera.org/learn/algorithms-part2)) along with the textbook 💲[Algorithms](https://algs4.cs.princeton.edu/home/)
  - [ ] going deeper: 💲[The Algorithm Design Manual (Skiena)](https://www.algorist.com/)
  - [ ] and deeper again: 💲[Algorithm Design (Kleinberg & Tardos)](https://www.cs.princeton.edu/~wayne/kleinberg-tardos/)
  - [ ] for practice: [Project Euler](https://projecteuler.net/)
- **Usability and UI:**
  - [x] 💲[Don't Make Me Think](https://sensible.com/dont-make-me-think/)
  - [x] 💲[The Design of Everyday Things](https://www.nngroup.com/books/design-everyday-things-revised/)
  - [ ] [Victor Ponamariov - 50 UI Tips](https://fifty.user-interface.io/50_ui_tips.pdf)
  - [ ] 💲[Victor Ponamariov - 100 UI/UX Tips & Tricks](https://akcium.gumroad.com/l/ui-ux-tips)
  - [ ] 💲[Refactoring UI](https://www.refactoringui.com/book)
- [x] **Operating systems:** 💲[Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/)
- **Networks:**
  - [x] 💲[Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/eighth.htm)
  - [ ] for reinforcement: read it again!
  - [ ] for a fun review: [How DNS Works](https://howdns.works/ep1/)
- [ ] **Software architecture:** 💲[Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/)
- **Databases:**
  - [ ] [Readings in Database Systems](http://www.redbook.io/)
  - [ ] [The Art of SQL](https://www.oreilly.com/library/view/the-art-of/0596008945/)
- [ ] **Compilers:** [Crafting Interpreters](https://craftinginterpreters.com/)
- [ ] **Math:** 💲[Concrete Mathematics: A Foundation for Computer Science](https://www-cs-faculty.stanford.edu/~knuth/gkp.html). The math review that I'm doing leading up to this is proving to be a journey in itself, which I will outline separately in the future.
- [ ] **??:** [Structure and Interpretation of Computer Programs](https://sarabander.github.io/sicp/html/index.xhtml) (and [video lectures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/)). I'm still not sure what exactly this book is about (even after reading the first few pages) but it is an often-recommended introductory text on "programming". So, maybe someday I will learn this "programming", after I've learned the less intimidating stuff (all of the above).

## Other programming/CS resource lists

- [Backend (Ruby) track at Turing School](https://backend.turing.edu/module1/)
- [Teach Yourself CS](https://teachyourselfcs.com/)
- [p1xt Computer Science and Programming](https://github.com/P1xt/p1xt-guides)
- [Open Source Society University](https://github.com/ossu/computer-science)
