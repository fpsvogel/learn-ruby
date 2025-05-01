<!-- omit in toc -->
# Learn Ruby: a resource list

Hi! This road map has helped me as a second-career developer who didn't do a bootcamp. I hope it helps you too.

Notice a broken link? Or want to suggest an addition? [Open an issue!](https://github.com/fpsvogel/learn-ruby/issues/new)

<!-- omit in toc -->
## Table of contents

The "not done" sections (currently "Foundational tools" and below) are somewhat chaotic because I haven't yet seen what's worth keeping there.

- [Preliminaries](#preliminaries)
- [Basics](#basics)
  - [Front-end basics](#front-end-basics)
  - [Ruby basics](#ruby-basics)
  - [Rails basics](#rails-basics)
  - [Getting hired](#getting-hired)
- [Foundations](#foundations)
  - [The Web](#the-web)
  - [SQL](#sql)
  - [Git](#git)
- [Advanced Ruby and Rails](#advanced-ruby-and-rails)
  - [Advanced Ruby](#advanced-ruby)
  - [Advanced Rails](#advanced-rails)
- [Front end](#front-end)
  - [HTML and CSS basics](#html-and-css-basics)
  - [JavaScript](#javascript)
  - [UI and usability](#ui-and-usability)
  - [Accessibility](#accessibility)
  - [Hotwire](#hotwire)
- [Ruby beyond web developement](#ruby-beyond-web-developement)
- [Beyond Ruby](#beyond-ruby)
- [Ruby media](#ruby-media)
  - [Chat / social media](#chat--social-media)
  - [Newsletters](#newsletters)
  - [Blogs](#blogs)
  - ["Let's build" screencasts](#lets-build-screencasts)
  - [Topical screencasts](#topical-screencasts)
  - [Streams](#streams)
  - [Podcasts](#podcasts)
- [Rails codebases to study](#rails-codebases-to-study)

## Preliminaries

- **If you want to keep it simple** and use just *one* resource that can take you from zero to hireable, I suggest the free [Odin Project](https://www.theodinproject.com/paths). If you want more variety and more depth on certain topics, keep reading!
- **Why did I chose Ruby?** At first I went for full-stack JS, but the JS ecosystem was confusing to me as a solo learner. Ruby was a lot more straightforward to me, and generally more enjoyable too.
- **Make sure your day job is conducive to part-time studying** if you're a working adult looking to switch careers. I used to be a teacher and spent many of my evenings and weekends grading assignments, which would have made it difficult to learn programming. So I switched to a remote customer support job to free up my schedule.
- **Take care of yourself!** Exercise and get plenty of sleep, and you'll better retain what you learn. If you develop wrist pain from heavy computer use, get an ergonomic keyboard, [do daily wrist stretches](https://youtube.com/watch?v=fdD7CgN5FGg), and try a break app such as [Stretchly](https://hovancik.net/stretchly).

Resources marked with a dollar sign (💲) cost money. You may be able to find books for free (from your local library, interlibrary loan, or more dubious sources) but buy them if/when you can, to support the authors.

## Basics

### Front-end basics

- [x] Learn some HTML, CSS, and JS: [The Odin Project - Foundations path](https://www.theodinproject.com/paths/foundations/courses/foundations) or resources under ["Front end"](#front-end) below. <!-- https://avatars.githubusercontent.com/u/4441966?s=400 -->
- [x] Build a blog from scratch. [GitHub Pages](https://pages.github.com) is an accessible way to do this. (Choose the option "Project site", then "Start from scratch".) <!-- https://letslearnruby.com/images/html-blog.png -->

### Ruby basics

- **Basics:**
  - [x] [The Odin Project - Ruby](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/ruby) <!-- https://avatars.githubusercontent.com/u/4441966?s=400 -->
  - [x] [GoRails - Ruby for Beginners](https://gorails.com/series/ruby-for-beginners) if you prefer videos. <!-- https://letslearnruby.com/images/gorails.jpg -->
  - [x] [Try Ruby](https://try.ruby-lang.org/) and [BigBinary Academy](https://academy.bigbinary.com/learn-ruby), if you like an interactive approach. <!-- https://www.globalnerdy.com/wordpress/wp-content/uploads/2009/08/chunky_bacon.jpg -->
  - [ ] [Eloquent Ruby, 2nd ed.](https://www.linkedin.com/posts/russolsen_im-thrilled-to-announce-that-brandon-weaver-activity-7310320740807888897-_w2f/?rcm=ACoAACJ6fHUBRp5BOTO2HiDVkkL1scMPO998sVA) (WIP)
- **Guided practice:**
  - [x] [Exercism - Ruby](https://exercism.org/tracks/ruby) <!-- https://avatars.githubusercontent.com/u/5624255?s=400 -->
  - [x] [Advent of Code](https://adventofcode.com) with other people's Ruby solutions to compare yours to. One way to do this is [my Advent of Ruby gem](https://github.com/fpsvogel/advent_of_ruby). <!-- https://letslearnruby.com/images/aoc.png -->
- **OOP (object-oriented programming):**
  - [x] 💲[Sandi Metz - Practical Object-Oriented Design](https://www.poodr.com) <!-- https://images.squarespace-cdn.com/content/v1/5527cdbae4b0ee7b897c2111/1530279450483-K5BJ5TZGMYSWYA3QQA63/POODR_2e_cover_low_res.jpg -->
  - [x] 💲[Sandi Metz & Katrina Owen - 99 Bottles of OOP](https://sandimetz.com/99bottles-sample-ruby) <!-- https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1477514056i/31183020.jpg -->
- **Build stuff with Ruby.** Here are some ideas:
  - A CLI (command-line interface) app. I made [one that gives statistics on a reading log](https://fpsvogel.com/posts/2021/my-first-ruby-app-lessons-learned). <!-- https://miro.medium.com/v2/resize:fit:774/1*PGxvXulYR1Zp3TPx7FjMsQ.png -->
  - A game. A text-based game is the most straightforward option, but [there are Ruby game engines](https://www.reddit.com/r/ruby/comments/qa8ida/what_game_engine_is_good_for_ruby/) for graphical games. <!-- https://letslearnruby.com/images/game.svg -->
  - A static site. [Bridgetown](https://github.com/bridgetownrb/bridgetown) is great for (among other things) building static sites, which are simpler than SSR (server-side rendered) sites à la Rails. Maybe [rebuild your blog](https://fpsvogel.com/posts/2021/build-a-blog-with-ruby-bridgetown)? Be sure to [join the Bridgetown Discord server](https://discord.gg/Cugms94QFM)—the maintainers are very welcoming and helpful to newbies. <!-- https://www.bridgetownrb.com/images/bridgetown-avatar.png -->
  - More ideas: [Coding Challenges](https://codingchallenges.fyi), [Build your own X](https://github.com/codecrafters-io/build-your-own-x), [Projectbook](https://projectbook.code.brettchalupa.com), [Project-based learning](https://github.com/practical-tutorials/project-based-learning#ruby) <!-- https://d31ezp3r8jwmks.cloudfront.net/2injd2hqjy28zry8i3khh7jauncy -->
- **Reference:**
  - [x] [Ruby API](https://rubyapi.org). Mentioning it up here because it's the best Ruby docs site but very little-known. Since its search uses a query param, you can add a search keyword to your browser to let you quickly search from the address bar, for example `rb partition` would take you to [https://rubyapi.org/3.4/o/s?q=partition](https://rubyapi.org/3.2/o/s?q=partition) <!-- https://upload.wikimedia.org/wikipedia/commons/7/73/Ruby_logo.svg -->

### Rails basics

Only books and courses are listed below, but be sure to *build things* as you learn. I myself [started building a large-ish Rails app](https://fpsvogel.com/posts/2021/first-rails-app-plain-reading) at first, but then I found it more helpful to build a series of small throwaway apps ([1](https://fpsvogel.com/posts/2021/gpt3-ai-story-writer), [2](https://fpsvogel.com/posts/2021/wikipedia-explorer-discover-articles-like-stumbleupon), [3](https://fpsvogel.com/posts/2021/pass-the-story-collaborative-writing-game), [4](https://fpsvogel.com/posts/2022/doctor-lookup-health-provider-search-tool)).

- **Basics:**
  - [x] [GoRails - Build a Blog with Rails 7](https://gorails.com/series/build-a-blog-with-rails-7) and if you want more along the same lines, [Rails 6 for Beginners](https://gorails.com/series/rails-6-for-beginners) <!-- https://letslearnruby.com/images/gorails.jpg -->
  - [x] [The Odin Project - Rails](https://www.theodinproject.com/paths/full-stack-ruby-on-rails) <!-- https://avatars.githubusercontent.com/u/4441966?s=400 -->
  - [x] [Beginners Guide to Ruby on Rails Performance](https://henry.bearblog.dev/beginners-guide-to-ruby-on-rails-performance-part-1) <!-- https://bear-images.sfo2.cdn.digitaloceanspaces.com/henry/performance.webp -->
- **Testing:**
  - [x] [thoughtbot - Testing Rails](https://github.com/thoughtbot/testing-rails) or [the summary blog post](https://thoughtbot.com/blog/how-we-test-rails-applications). (In the book, ignore controller specs because [they have been superseded by request specs](https://stackoverflow.com/a/46500842).) <!-- https://public-files.gumroad.com/g2f7k3fkbdgvubnh1b2cmsdcsenc -->
  - [x] 💲[Effective Testing with RSpec 3](https://pragprog.com/titles/rspec3/effective-testing-with-rspec-3/) <!-- https://pragprog.com/titles/rspec3/effective-testing-with-rspec-3/rspec3.jpg -->
  - [ ] 💲[Everyday Rails Testing with RSpec](https://leanpub.com/everydayrailsrspec)
- **Misc.:**
  - [x] [Explore Ruby communities (below)](#chat--social-media) <!-- https://uploads.sitepoint.com/wp-content/uploads/2014/07/1405277526rubygrows.png -->
  - [x] [Style guides](https://ruby.style/) for Ruby, Rails, and RSpec <!-- https://avatars.githubusercontent.com/u/10871348?s=400 -->

### Getting hired

- **Get real-world experience to put on your resume:**
  - Contribute to open-source projects. I've written [a short guide on how to get started](https://fpsvogel.com/posts/2021/how-to-contribute-to-open-source-ruby-rails). <!-- https://imgs.xkcd.com/comics/dependency_2x.png -->
  - [Ruby Central - Scholars and Guides Program](https://rubycentral.org/scholars_guides_program/) <!-- https://rubycentral.org/content/images/size/w256h256/format/png/2022/11/Ruby-Central-logo.svg -->
- **Mentorship:**
  - [First Ruby Friend](https://firstrubyfriend.org) where aspiring and first-year developers are connected with a mentor. <!-- https://firstrubyfriend.org/images/ruby-plus-one.svg -->
  - [r/rails](https://www.reddit.com/r/rails). Examples: [1](https://www.reddit.com/r/rails/comments/rvs7f2/rails_mentoring/), [2](https://www.reddit.com/r/rails/comments/lvwn41/finding_a_mentor/). <!-- https://letslearnruby.com/images/reddit.svg -->
- **The job search:**
  - [Ruby on Rails Technical Interview Questions](https://github.com/gardeziburhan/rails_interview_questions)
  - [Notes on my 2021-2022 job search](https://fpsvogel.com/posts/2022/how-to-find-ruby-rails-job) <!-- https://www.stockvault.net/data/2018/07/15/253106/preview16.jpg -->
  - [Notes on my 2023-2024 job search](https://fpsvogel.com/posts/2024/job-search-networking-for-engineers) <!-- https://letslearnruby.com/images/2023-job-search.jpg -->

## Foundations

### The Web

- **Basics:**
  - [x] [Hypermedia Systems, Part I: Hypermedia Concepts](https://hypermedia.systems/part/hypermedia-concepts/) by the creator of [htmx](https://htmx.org), one of [many libraries](https://htmx.org/essays/alternatives) that take a hypermedia-oriented approach to web development. <!-- https://m.media-amazon.com/images/I/812G33tb9aL._AC_UF1000,1000_QL80_.jpg -->
- **HTTP:**
  - [ ] [HTTP From Scratch](https://kmcd.dev/series/http-from-scratch/)
  - [ ] 💲[Rebuilding HTTP](https://noahgibbs.gumroad.com/l/rebuilding_http)
  - [ ] Build a web server from scratch. Here are Ruby resources: [Ruby HTTP server from the ground up](https://www.dmitry-ishkov.com/2021/07/ruby-http-server-from-ground-up.html), [How to Build a Web App with and without Rails Libraries](https://shopify.engineering/building-web-app-ruby-rails), and [a Reddit discussion with helpful comments](https://www.reddit.com/r/ruby/comments/vfc02l/newb_here_have_you_written_your_own_web_server)
- **Networking:**
  - [x] 💲[Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/eighth.htm) <!-- https://m.media-amazon.com/images/I/517X347vzZL.jpg -->
  - [ ] [Jesse Storimer - Working with TCP Sockets](https://workingwithruby.com/wwtcps/intro)
- **Security:**
  - [ ] 💲[Web Security for Developers: Real Threats, Practical Defense](https://www.amazon.com/Web-Security-Developers-Malcolm-McDonald-ebook/dp/B07V78WH7V) and the accompanying site [Hacksplaining](https://www.hacksplaining.com/)
  - [ ] [PortSwigger - web security exercises](https://portswigger.net/web-security/all-topics)
<!--
- **New Web APIs:**
  - [ ] [View Transitions](https://developer.mozilla.org/en-US/docs/Web/API/View_Transition_API)
  - [ ] [Speculation Rules](https://developer.mozilla.org/en-US/docs/Web/API/Speculation_Rules_API)
  - [ ] [command and commandfor](https://developer.chrome.com/blog/command-and-commandfor)
-->

### SQL

- **Basics:**
  - [x] [SQL Teaching](https://www.sqlteaching.com) <!-- https://www.sqlteaching.com/database.png -->
  - [x] [SQLBolt](https://sqlbolt.com) <!-- https://letslearnruby.com/images/sql-bolt.png -->
  - [x] [Select Star SQL](https://selectstarsql.com) <!-- https://selectstarsql.com/imgs/favicon-256.png -->
  <!-- Others: -->
  <!-- - [ ] [SQL Practice](https://www.sql-practice.com/) -->
  <!-- - [x] [SQL Murder Mystery](https://mystery.knightlab.com/) <!-- https://mystery.knightlab.com/174092-clue-illustration.png -->
  <!-- - [x] [PostgreSQL Exercises](https://pgexercises.com/) and [single-page guide](https://ozencb.github.io/postgresql-exercises/) <!-- https://opengraph.githubassets.com/5dc8f962a8ff3a00a68a35d74a38b117b653d05e8891b85360df152f6755b4b9/AlisdairO/pgexercises -->
  <!-- - [x] [SQLZoo](https://sqlzoo.net/wiki/SQL_Tutorial) <!-- https://velog.velcdn.com/images/zero__/post/71852f7f-bbd2-4f51-9025-590644dec95b/image.jpeg -->
- **Advanced:**
  - [ ] [Next-Level Database Techniques for Developers](https://sqlfordevs.com/ebook) <!-- https://sqlfordevs.com/build/assets/ebook.454b5368.png -->
  - [ ] 💲[SQL Antipatterns, Volume 1](https://pragprog.com/titles/bksap1/sql-antipatterns-volume-1/)
  - [ ] [Markus Winand - Use the Index, Luke!](https://use-the-index-luke.com/sql/preface)
  - [ ] 💲[Markus Winand - SQL Performance Explained](https://sql-performance-explained.com)
  - [ ] [Advanced Topics in SQL](https://www.edx.org/course/advanced-topics-in-sql) course from Stanford
- **PostgreSQL:**
  - [ ] [Postgres Playground](https://www.crunchydata.com/developers/tutorials)
  - [ ] [Yeah, Postgres can do that](https://dev.to/efertsch/series/20415)
  - [ ] 💲[High Performance PostgreSQL for Rails](https://pragprog.com/titles/aapsql/high-performance-postgresql-for-rails/)
  - [ ] Blog posts on Rails + Postgres: [lots on Paweł Urbanek's blog](https://pawelurbanek.com/blog), [this one at Honeybadger](https://www.honeybadger.io/blog/rails-postgresql-queries/), [this one at thoughtbot](https://thoughtbot.com/blog/advanced-postgres-performance-tips).
  - [ ] 💲[The Art of PostgreSQL](https://theartofpostgresql.com/)
  - [ ] 💲[PostgreSQL Query Optimization: The Ultimate Guide to Building Efficient Queries](https://link.springer.com/book/10.1007/978-1-4842-6885-8)
- **SQLite:**
  - [ ] 💲[SQLite on Rails](https://fractaledmind.gumroad.com/l/sqlite-on-rails)

### Git

- **Basics:**
  - [x] [Oh My Git!](https://ohmygit.org/) <!-- https://ohmygit.org/assets/images/oh-my-git.png -->
  - [x] [Oh Shit, Git!?!](https://ohshitgit.com/) <!-- https://upload.wikimedia.org/wikipedia/commons/5/50/Fxemoji_u2049.svg -->
  - [x] [Git Katas](https://github.com/eficode-academy/git-katas)
  - [x] [The Git Parable](https://youtube.com/watch?v=ANNboouhNHE) <!-- https://i.ytimg.com/vi/jm7QsI-nNjk/hqdefault.jpg -->
  - [x] [Git Flight Rules](https://github.com/k88hudson/git-flight-rules)
- **Advanced:**
  - [ ] [thoughtbot - Rebuilding Git in Ruby](https://thoughtbot.com/blog/rebuilding-git-in-ruby) <!-- https://avatars.githubusercontent.com/u/6183?s=400 -->
  - [ ] [Pro Git](https://git-scm.com/book)
  - [ ] 💲[Building Git](https://shop.jcoglan.com/building-git)

<!-- ### Linux / command line

- [ ] [Linux Journey](https://linuxjourney.com/)
- [ ] [Sundeep Agarwal - Linux Command Line Computing](https://learnbyexample.github.io/cli-computing/)
- [ ] [The Linux Command Line](https://linuxcommand.org/tlcl.php)
- [ ] [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
- [ ] [Sundeep Agarwal - "Linux CLI and shell scripting" list](https://learnbyexample.github.io/curated_resources/linux_cli_scripting.html)
- [ ] [Julia Evans - Your Linux Toolbox](https://jvns.ca/blog/2019/10/21/print-collection-of-my-first-7-zines/)
- [ ] 💲[Efficient Linux at the Command Line](https://www.oreilly.com/library/view/efficient-linux-at/9781098113391)
- [ ] 💲[How Linux Works](https://nostarch.com/howlinuxworks3)
- [ ] 💲[Julia Evans - Bite Size zine pack](https://wizardzines.com/zines/bite-size-pack/)
- [ ] 💲[Wicked Cool Shell Scripts](https://nostarch.com/wcss2) -->

## Advanced Ruby and Rails

See also [my GitHub star lists](https://github.com/fpsvogel?tab=stars) for handy Ruby gems.

### Advanced Ruby

- **Reference:**
  - [ ] [Victor Shepelev (zverok) - The Ruby Reference](https://rubyreferences.github.io/rubyref/) plus [Ruby Changes](https://rubyreferences.github.io/rubychanges/3.0.html) (covering Ruby 3+). [Ruby Evolution](https://rubyreferences.github.io/rubychanges/evolution.html) is also great.
  - [ ] [RuboCop performance rules](https://github.com/rubocop/rubocop-performance)
  - [ ] [RuboCop security rules](https://docs.rubocop.org/rubocop/cops.html#department-security)
- **Concurrency:**
  - [ ] [Jesse Storimer - Working with Ruby Threads](https://workingwithruby.com/wwrt/intro)
  - [ ] [Jesse Storimer - Working with Unix Processes](https://workingwithruby.com/wwup/intro)
  - [ ] [JP Camara - series on concurrency, parallelism and asynchronous programming in Ruby](https://jpcamara.com/2024/06/04/your-ruby-programs.html)
- **Ruby internals:**
  - [ ] 💲[Ruby Under a Microscope](https://patshaughnessy.net/2025/1/28/updating-ruby-under-a-microscope) (WIP)
  - [ ] 💲[Metaprogramming Ruby 2](https://pragprog.com/titles/ppmetr2/metaprogramming-ruby-2)
<!-- - **Misc.:** -->
  <!-- - [x] [Avdi Grimm - Confident Ruby](https://pragprog.com/titles/agcr/confident-ruby/) <!-- https://pragprog.com/titles/agcr/confident-ruby/agcr_hucf967c33f389130ab619766a81118218_436632_375x0_resize_q75_box.jpg -->
  <!-- - [ ] Property-based testing with [PropCheck](https://github.com/Qqwy/ruby-prop_check) and [PBT](https://github.com/ohbarye/pbt) -->

### Advanced Rails

- **Reference:**
  - [ ] 💲[The Rails 8 Way](https://leanpub.com/therails8way)
  - [ ] [Rails Guides](https://guides.rubyonrails.org/)
  - [ ] [Rails API docs](https://api.rubyonrails.org/)
- **Rails internals:**
  - [x] 💲[Rebuilding Rails](http://rebuilding-rails.com/) <!-- https://public-files.gumroad.com/84806cmcnanyrmtnxfxvruodap1n -->
  - [ ] 💲[The Rails Companion](https://courses.writesoftwarewell.com/p/rails-companion)
- **Architecture:**
  - [x] 💲[Layered Design for Ruby on Rails Applications](https://www.packtpub.com/product/layered-design-for-ruby-on-rails-applications/9781801813785) <!-- https://m.media-amazon.com/images/I/41MAUvi--4L.jpg -->
  - [ ] 💲[Maintainable Rails](https://leanpub.com/maintain-rails)
  - [ ] 💲[Gradual Modularization for Ruby and Rails](https://leanpub.com/package-based-rails-applications)
- **Performance:**
  - [ ] [BigBinary - Scaling Rails series](https://www.bigbinary.com/blog/scaling-rails-series)
  - [ ] 💲[Nate Berkopec - The Complete Guide to Rails Performance](https://www.railsspeed.com/)
  - [ ] 💲[Nate Berkopec - The Ruby on Rails Performance Apocrypha](https://www.speedshop.co/2021/01/14/announcing-apocrypha.html)
  - [ ] [Mature Optimization Handbook](https://carlos.bueno.org/optimization/) (not Rails-specific)
  - [ ] 💲[Rails Scales!](https://pragprog.com/titles/cprpo/rails-scales/)
- **Active Record:**
  - [ ] 💲[High Performance Active Record](https://impactahead.com/books/high-performance-active-record) (WIP)
- **Background jobs:**
  - [x] [Sidekiq wiki](https://github.com/sidekiq/sidekiq/wiki)
  - [ ] [How does Sidekiq work?](https://www.mikeperham.com/how-sidekiq-works/)
  - [x] 💲[Nate Berkopec - Sidekiq in Practice](https://nateberk.gumroad.com/l/sidekiqinpractice) <!-- https://public-files.gumroad.com/3x0fwqyo139zgcyn5bwcdsi9jas0 -->
- **Deployment:**
  - [ ] 💲[Josef Strzibny - Deployment from Scratch](https://deploymentfromscratch.com/)
  - [ ] 💲[Josef Strzibny - Kamal Handbook](https://kamalmanual.com/handbook/)
  - [ ] 💲[Julia Evans - How Containers Work](https://wizardzines.com/zines/containers/)
  - [ ] [Ruby on Whales: Dockerizing Ruby and Rails development](https://evilmartians.com/chronicles/ruby-on-whales-docker-for-ruby-rails-development)
  - [ ] 💲[The Docker Book](https://dockerbook.com/)
- **Misc.:**
  - [ ] [Perfecting Your Rails Forms](https://alexbarret.com/blog/2024/perfecting-your-rails-form-part-1/)
  - [ ] 💲[Frictionless Generators](https://garrettdimon.com/products/frictionless-generators)

## Front end

### HTML and CSS basics

- **HTML:**
  - [ ] [HTML for people](https://www.htmlforpeople.com/)
  - [ ] [MDN - Learn web development](https://developer.mozilla.org/en-US/docs/Learn_web_development)
  - [ ] [MDN - HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML)
  - [ ] [htmlreference.io](https://htmlreference.io/)
- **Forms:**
  - [ ] [MDN - Web forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)
  - [ ] [web.dev - Learn Forms](https://web.dev/learn/forms)
- **CSS:**
  - [ ] 💲[The Spicy Web - CSS Nouveau](https://www.spicyweb.dev/css-nouveau) <!-- https://www.spicyweb.dev/images/spicy-web-avatar-light.png -->
  - [ ] [MDN - CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
  - [ ] [cssreference.io](https://cssreference.io/)
  - [ ] [CSS Selectors: A Visual Guide & Reference](https://fffuel.co/css-selectors/)
  - [ ] [The Odin Project - Intermediate HTML and CSS](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/intermediate-html-and-css)
  - [ ] [The Odin Project - Advanced HTML and CSS](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/advanced-html-and-css)
  - [ ] [CUBE CSS](https://cube.fyi)
  - [ ] [Every Layout](https://every-layout.dev/)
  - [ ] [Magic of CSS](https://adamschwartz.co/magic-of-css/)
  - [ ] [Under-Engineered Patterns](https://adrianroselli.com/2023/05/under-engineered-patterns-for-wcbuf.html)
  - [ ] [Stephanie Eckles - Modern CSS Solutions](https://moderncss.dev/)
  - [ ] [Stephanie Eckles - SmolCSS](https://smolcss.dev/)
  - [ ] [CSS Naked Day](https://css-naked-day.github.io/)
  - [ ] 💲[Julia Evans - Hell Yes! CSS!](https://wizardzines.com/zines/css/)
  - [ ] [Modern Font Stacks](https://modernfontstacks.com/#font-stacks)
  - [ ] [Type Is Design: Fix Your UI with Better Typography and CSS](https://www.youtube.com/watch?v=1Pe7oGIKkqc)
  - [ ] [CSS games](#programming-games)
- **CSS games:**
  - [Flexbox Zombies](https://flexboxzombies.com/p/flexbox-zombies) <!-- https://d4.alternativeto.net/uJT4WbuIzPvczqpVa8ADBr1th9hAPeL1sdtaKNcqjc8/rs:fill:618:394:1/g:no:0:0/YWJzOi8vZGlzdC9zL2ZsZXhib3gtem9tYmllc18yMDAwMThfZnVsbC5qcGc.jpg -->
  - [Grid Critters](https://gridcritters.com/) <!-- https://process.fs.teachablecdn.com/ADNupMnWyR7kCWRvm76Laz/resize=width:705/https://www.filepicker.io/api/file/SaS7C1ZSeeZUEzvnAl2x -->
  - [CSS Diner](https://flukeout.github.io/) <!-- https://i.pinimg.com/736x/8a/b1/ad/8ab1ad8128508785f956eb6f58779b47.jpg -->
  - [Flexbox Froggy](https://flexboxfroggy.com/) <!-- https://flexboxfroggy.com/favicon.ico -->
  - [Flexbox Defense](http://www.flexboxdefense.com/) <!-- https://velog.velcdn.com/images%2Fdaymoon_%2Fpost%2F7b73b771-50e0-4728-99ec-0dc60f8b7153%2Fimage.png -->
  - [CSS Grid Garden](https://cssgridgarden.com/) <!-- https://cssgridgarden.com/favicon.ico -->
  - [CSSBattle](https://cssbattle.dev/) <!-- https://images.crunchbase.com/image/upload/c_pad,h_256,w_256,f_auto,q_auto:eco,dpr_1/ixvovaxpxyb0ma6w9f6y -->
  - [Coding Fantasy](https://codingfantasy.com/) <!-- https://pbs.twimg.com/profile_images/1396909500884529157/PdqFWViQ_400x400.jpg -->

### JavaScript

- **Basics:**
  - [x] [Exploring JavaScript](https://exploringjs.com/js/) or [MDN - JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) <!-- https://exploringjs.com/js/img/cover-homepage.jpg -->
  - [x] [Modern JavaScript Explained For Dinosaurs](https://peterxjang.com/blog/modern-javascript-explained-for-dinosaurs.html) plus [import maps](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script/type/importmap) <!-- https://process.fs.teachablecdn.com/ADNupMnWyR7kCWRvm76Laz/resize=width:705/https://www.filepicker.io/api/file/3k8M1zI3S9ePNURLZVBI -->
  - [x] [What the heck is the event loop anyway?](https://youtube.com/watch?v=8aGhZQkoFbQ) <!-- https://i.ytimg.com/vi/8aGhZQkoFbQ/maxresdefault.jpg -->
  - [x] [The Modern JavaScript Tutorial - Browser: Document, Events, Interfaces](https://javascript.info/ui) <!-- https://javascript.info/img/site_preview_en_512x512.png -->
  - [x] Build something in JS. Or for a more structured approach: [JavaScript30](https://javascript30.com/) and [solutions](https://github.com/search?q=javascript30&type=repositories), [freeCodeCamp's project-based JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/), [Frontend Mentor](https://www.frontendmentor.io/), [Frontend Practice](https://www.frontendpractice.com). You may also like JS coding exercises: [Exercism - JavaScript](https://exercism.org/tracks/javascript), [Advent of JavaScript](https://www.adventofjs.com/) and [solutions](https://github.com/search?q=%22advent+of+javascript%22+OR+%22advent+of+js%22&type=repositories), [Advent of Code](https://adventofcode.com/) with JS CLI runner ([1](https://github.com/caderek/aocrunner), [2](https://github.com/t-hugs/advent-of-code)) and solutions ([1](https://github.com/sguest/advent-of-code), [2](https://github.com/shahata/adventofcode-solver/tree/master/src), [3](https://github.com/leyanlo/advent-of-code), [4](https://github.com/niksimon/advent-of-code), [5](https://github.com/romellem/advent-of-code), [6 (TS)](https://github.com/T-Hugs/advent-of-code/tree/main/years), [7 (TS)](https://github.com/AlexAegis/advent-of-code/tree/master/solutions/typescript)); see also [programming games](#programming-games) below.
- **Going deeper:**
  - [ ] [Plain Vanilla](https://plainvanillaweb.com/index.html)
  - [x] [You Don't Know JS Yet](https://github.com/getify/You-Dont-Know-JS). Be sure to read the last three parts after they're finished. #TODO <!-- https://raw.githubusercontent.com/getify/You-Dont-Know-JS/2nd-ed/get-started/images/cover.png -->
  - [ ] [Deep JS](https://exploringjs.com/deep-js/toc.html)
  - [ ] [What the f*ck JavaScript?](https://github.com/denysdovhan/wtfjs)
- **TypeScript:**
  - [x] [Total TypeScript VS Code extension](https://www.totaltypescript.com/vscode-extension) <!-- https://mattpocock.gallerycdn.vsassets.io/extensions/mattpocock/ts-error-translator/0.10.1/1694612358825/Microsoft.VisualStudio.Services.Icons.Default -->
  - [x] [Total TypeScript essentials](https://www.totaltypescript.com/books/total-typescript-essentials/kickstart-your-typescript-setup) <!-- https://res.cloudinary.com/total-typescript/image/upload/v1676015688/core-volume_2x_wt7jnc.png -->
  - [ ] [The Concise TypeScript Book](https://gibbok.github.io/typescript-book/book/the-concise-typescript-book/)
  - [ ] [Execute Program - TypeScript courses](https://www.executeprogram.com/courses/typescript)
  - [ ] [Official docs](https://www.typescriptlang.org/)
  - [ ] [Tackling TypeScript](https://exploringjs.com/tackling-ts/index.html)
  - [ ] [Type Challenges](https://tsch.js.org/)
  - [ ] [TypeHero](https://typehero.dev/)
  - [ ] Type | Treat [2020](https://dev.to/typescript/type-treat-challenge-1-829), [2021](https://devblogs.microsoft.com/typescript/type-treat-2021-day-1/)
  - [ ] [Codeless Code - posts on TypeScript](https://code.lol/tags/typescript/) e.g. [Higher Kindred Types in TypeScript](https://code.lol/post/programming/higher-kinded-types/) and [Point-free Programming via HKTs](https://code.lol/post/programming/hkt-tacit/)
  - [ ] TypeScript libraries: [TS-Pattern](https://github.com/gvergnaud/ts-pattern), [Zod](https://github.com/colinhacks/zod), [type-fest](https://github.com/sindresorhus/type-fest)
  - [ ] 💲[TypeScript Cookbook](https://typescript-cookbook.com/)
  - [ ] 💲[Effective TypeScript](https://effectivetypescript.com/)
- **JavaScript/TypeScript games:**
  - [Kid.js](https://github.com/maissaninc/kidjs) <!-- https://kidjs.io/images/logo.svg -->
  - [Untrusted](https://untrustedgame.com/) <!-- https://letslearnruby.com/images/untrusted.png -->
  - [Screeps](https://screeps.com/) <!-- https://avatars.githubusercontent.com/u/9197419?s=400 -->
  - [BitBurner](https://bitburner-official.github.io/) <!-- https://steamuserimages-a.akamaihd.net/ugc/1816639486142926307/9B3DD06F3021AE6409C848B84052B885A0B287EB/ -->
  - [Elevator Saga](https://play.elevatorsaga.com/) <!-- https://i1.wp.com/www.404techsupport.com/wp-content/uploads/2015/01/elevator_visual.png -->

### UI and usability

- **Learning:**
  - [x] 💲[Don't Make Me Think](https://sensible.com/dont-make-me-think/) <!-- https://m.media-amazon.com/images/I/51sdCuqMwWL._AC_UF1000,1000_QL80_.jpg -->
  - [x] 💲[The Design of Everyday Things](https://www.nngroup.com/books/design-everyday-things-revised/) <!-- https://m.media-amazon.com/images/I/416Hql52NCL.jpg -->
  - [ ] [Growth.Design](https://growth.design/)
  - [ ] [Roast My Landing Page blog](https://blog.roastmylandingpage.com/)
  - [x] [Victor Ponamariov - UI/UX newsletter](https://vpon.me/newsletter) <!-- https://files.smashing.media/authors/viktor-ponamarev.jpg -->
  - [x] [Victor Ponamariov - 50 Tips to Improve User Interface](https://fifty.user-interface.io/50_ui_tips.pdf) <!-- https://fifty.user-interface.io/book.png -->
  - [ ] [Victor Ponamariov - How to design almost any UI element](https://user-interface.io/articles/how-to-design-almost-any-ui-element)
  - [ ] 💲[Victor Ponamariov - 100 UI/UX Tips & Tricks](https://akcium.gumroad.com/l/ui-ux-tips) (or on [the landing page](https://hundred.user-interface.io/))
  - [ ] 💲[Victor Ponamariov - Re:Form](https://reform.user-interface.io/)
  - [ ] 💲[Master UI Design](https://www.masteruibook.com/)
  - [ ] 💲[Refactoring UI](https://www.refactoringui.com/book)
  - [ ] 💲[User Interface Design: A Software Engineering Perspective](https://www.amazon.com/dp/0321181433)
- **Libraries:**
  - [Pico CSS](https://picocss.com/) <!-- https://picocss.com/build/_assets/pico-mark-dark-W5OEFAUA.svg -->
  - [Shoelace](https://shoelace.style/), soon to be superseded by [Web Awesome](https://www.kickstarter.com/projects/fontawesome/web-awesome). <!-- https://shoelace.style/assets/images/wordmark.svg -->

### Accessibility

- [ ] [MDN - Accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility)
- [ ] [Responsible Web Applications](https://responsibleweb.app/)
- [ ] [web.dev - Learn Accessibility](https://web.dev/learn/accessibility/) (among [their other courses](https://web.dev/learn/))
- [ ] In Rails: [Accessibility is a Requirement](https://www.youtube.com/watch?v=BF3D_IqOknk), [Accessible by Default](https://www.youtube.com/watch?v=4j2zlvE_Yj8)

### Hotwire

- **News:**
  - [Hotwire Weekly](https://hotwireweekly.com/) <!-- https://assets.buttondown.email/images/1bdac043-d137-4e4f-86ef-4df5c3b34029.png -->
- **Basics:**
  - [ ] [Turbo Rails Tutorial](https://www.hotrails.dev/)
  - [ ] [What is the difference between Turbo and Stimulus, and what exactly is Hotwire?](https://www.ducktypelabs.com/turbo-vs-stimulus/)
  - [ ] [Write Software, Well - articles tagged "Hotwire"](https://www.writesoftwarewell.com/tag/hotwire)
  - [ ] [30 days of Hotwire tips](https://twitter.com/ilrock__/status/1631315562390519809)
  - [ ] [Hotwire Cheatsheet](https://cheatsheetshero.com/user/igor-kasyanchuk/930-hotwire-for-ruby-on-rails-developers-cheatsheet?ref=shortruby.com#page-3609)
  - [ ] [Turbo 8 Cheatsheet](https://radanskoric.com/cheatsheet/)
  - [ ] 💲[GoRails - Learn Hotwire](https://learnhotwire.com/) (WIP)
  - [ ] 💲[Master Hotwire](https://masterhotwire.com/) (WIP)
- **Turbo 8:**
  - [ ] [Turbo 8 in 8 minutes](https://fly.io/ruby-dispatch/turbo-8-in-8-minutes)
  - [ ] [A happier happy path in Turbo with morphing](https://dev.37signals.com/a-happier-happy-path-in-turbo-with-morphing/)
  - [ ] [Turbo Music Drive](https://github.com/palkan/turbo-music-drive) app demonstrating upcoming features of Turbo 8, along with accompanying blog posts (pt. 1 [on morphing](https://evilmartians.com/chronicles/the-future-of-full-stack-rails-turbo-morph-drive), pt. 2 [on view transitions](https://evilmartians.com/chronicles/the-future-of-full-stack-rails-turbo-view-transitions))
- **Reference:**
  - [Hotwire.io](https://hotwire.io) (more extensive than [the official docs](https://hotwired.dev/)) <!-- https://hotwire.io/apple-touch-icon.png -->
  - [turbo-rails "Usage" README section](https://github.com/hotwired/turbo-rails#usage)
  - [thoughtbot - Hotwire examples](https://github.com/thoughtbot/hotwire-example-template/branches/all) <!-- https://avatars.githubusercontent.com/u/6183?s=400 -->
  - [Betterstimulus](https://www.betterstimulus.com) <!-- https://raw.githubusercontent.com/github/explore/b0f7ffc5ee5bc1b6dfc1bbc4d75dd2587a243c14/topics/stimulus/stimulus.png -->
  - [Stimulus-Use](https://stimulus-use.github.io/stimulus-use) <!-- https://avatars.githubusercontent.com/u/65528542?s=400 -->
  - [Stimulus Components](https://www.stimulus-components.com/) <!-- https://avatars.githubusercontent.com/u/72915408?s=400 -->

## Ruby beyond web developement

- **Mentoring:**
  - [x] [Exercism](https://exercism.org/mentoring) <!-- https://avatars.githubusercontent.com/u/5624255?s=400 -->
  - [ ] [First Ruby Friend](https://firstrubyfriend.org/mentors)
- **Game programming:**
  - 💲[DragonRuby Game Toolkit](https://dragonruby.itch.io/dragonruby-gtk) has the largest community, e.g. [on Discord](discord.dragonruby.org), [Dragon Riders Community](https://www.dragonriders.community/),  <!-- https://img.itch.zone/aW1nLzIzNjU2MzQucG5n/original/WFWBHQ.png -->
  - Other game libraries: [Gosu](https://www.libgosu.org/), [Raylib Ruby](https://www.raylib-ruby.com/), [MiniGL](https://github.com/victords/minigl), [Ruby 2D](https://www.ruby2d.com/), [Taylor](https://www.taylormadetech.dev) <!-- https://avatars.githubusercontent.com/u/6291058?s=400 -->
  - [Gamefic](https://gamefic.com/) for building text-based games and interactive fiction. See [Getting Started](https://gamefic.com/guides/getting-started) and [examples](https://github.com/castwide/gamefic-sdk/tree/master/examples). <!-- https://gamefic.com/assets/goony-6ea3e43a0283cf3bacced44d7f9e0486f27e845415b64350481592e2c1939abf.png -->
  <!-- Older text-based game libraries:
  <!--     https://github.com/jaywengrow/tuvi
  <!--     https://github.com/MikeTaylor/scottkit
  <!--     + https://github.com/MikeTaylor/scottkit/blob/master/docs/tutorial.md -->
- **Music:**
  - [ ] [Sonic Pi](https://sonic-pi.net/)
- **Text processing:** -->
  - [x] [Sundeep Agarwal - Ruby Regexp](https://learnbyexample.github.io/Ruby_Regexp) <!-- https://learnbyexample.github.io/Ruby_Regexp/images/ruby_regexp.png -->
  - [x] [Sundeep Agarwal - Ruby One-Liners Guide](https://learnbyexample.github.io/learn_ruby_oneliners/) <!-- https://learnbyexample.github.io/learn_ruby_oneliners/images/ruby_oneliners.png -->
  - [x] 💲[Text Processing with Ruby](https://pragprog.com/titles/rmtpruby/text-processing-with-ruby) <!-- https://m.media-amazon.com/images/I/91QfMPAeQZL._AC_UF1000,1000_QL80_.jpg -->
- **Ruby games:**
  - [SC2AI](https://sc2ai.pages.dev/) <!-- https://cdn.patchbot.io/games/14/starcraft_ii_sm.webp -->
  - [Ruby Warrior](https://github.com/ryanb/ruby-warrior) or [the online version](https://palkan.github.io/ruby-warrior/). <!-- https://html5gamedevelopment.com/wp-content/uploads//files/7b/3/323/spartacus.png -->

## Beyond Ruby

- **Career advancement:**
  - [x] [Engineering progression for humans](https://localghost.dev/blog/engineering-progression-for-humans/) <!-- https://localghost.dev/img/og-image.png -->
  - [ ] 💲[The Missing README: A Guide for the New Software Engineer](https://nostarch.com/missing-readme)
  - [ ] [Path to Senior Engineer handbook](https://github.com/jordan-cutler/path-to-senior-engineer-handbook)
  - [ ] [Staff engineer archetypes](https://staffeng.com/guides/staff-archetypes/)
  - [ ] 💲[The Software Engineer's Guidebook](https://www.engguidebook.com)
  - [ ] 💲[The Staff Engineer's Path](https://www.oreilly.com/library/view/the-staff-engineers/9781098118723/)
  - [ ] 💲[The Tech Resume Inside Out](https://thetechresume.com/)
- **Architecture:**
  - [ ] [The Architecture of Open Source Applications](https://aosabook.org/en/index.html)
  - [ ] [Software Design by Example](https://third-bit.com/sdxjs/)
  - [ ] 💲[Learning Domain-Driven Design](https://www.oreilly.com/library/view/learning-domain-driven-design/9781098100124/)
- **My other lists:**
  - [Learn Computer Science and Low-Level Programming](https://github.com/fpsvogel/learn-cs)
  - [Learn Roc](https://github.com/fpsvogel/learn-roc), a functional programming language.

<!-- ## Programming games

<!--- **API games (any language):**
<!--  - [SpaceTraders](https://spacetraders.io/) <!-- https://avatars.githubusercontent.com/u/76577835?s=400 -->
<!--  - [Artifacts](https://artifactsmmo.com/) <!-- https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1Rz35KdjPZ2vxmuwlITP5axOXOyx9mrbhHw&s -->
<!--  - [Battlesnake](https://play.battlesnake.com/) <!-- https://images.crunchbase.com/image/upload/c_pad,h_256,w_256,f_auto,q_auto:eco,dpr_1/d8p9mzhszirgd4avaqlf -->
<!--- **Other programming games:**
<!--  - [Swarm](https://swarm-game.github.io/) <!-- https://external-preview.redd.it/V2h0RvY_Z7-MPs6-34NQBH1oVS0speRWTWbVyIDZDr4.jpg?auto=webp&s=c7fee792a18e40e263026e691d91b2eb12d839bb -->

## Ruby media

### Chat / social media

- [r/ruby](https://www.reddit.com/r/ruby) and [r/rails](https://www.reddit.com/r/rails) <!-- https://letslearnruby.com/images/reddit.svg -->
- [Ruby (Discord)](https://discord.com/invite/ruby-518658712081268738) <!-- https://cdn.prod.website-files.com/6257adef93867e50d84d30e2/636e0a6a49cf127bf92de1e2_icon_clyde_blurple_RGB.png -->
- [Ruby.social (Mastodon)](https://ruby.social) <!-- https://upload.wikimedia.org/wikipedia/commons/d/d5/Mastodon_logotype_%28simple%29_new_hue.svg -->
- [Ruby on Rails Link (Slack)](https://www.rubyonrails.link/) <!-- https://www.rubyonrails.link/assets/railslink-icon-10c1d749590f731efcb92fc4ffb599a6171cfd89e2eb2080b925d247060017db.png -->
- [Lobsters](https://lobste.rs/) is not Ruby-specific, but it's a way to widen your horizons and the discussions are of high quality. It's like Hacker News but smaller and more focused on programming. <!-- https://letslearnruby.com/images/lobsters.png -->

### Newsletters

- [Short Ruby](https://newsletter.shortruby.com/) <!-- https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F1a71f846-50a2-435b-b824-ecfe2525557c_727x727.png -->
- [Ruby Weekly](https://rubyweekly.com/) <!-- https://letslearnruby.com/images/ruby-weekly.png -->
- [Ruby Radar](https://rubyradar.dev/) <!-- https://letslearnruby.com/images/ruby-radar.png -->

### Blogs

There are lots more out there; these are just my favorites.

<!-- maybe add later: https://newsletter.rubycademy.com -->
- [Code with Jason](https://www.codewithjason.com/articles/) <!-- https://www.codewithjason.com/wp-content/uploads/2023/01/jason-300x300.jpeg -->
- [Fly.io - The Ruby Dispatch](https://fly.io/ruby-dispatch/) <!-- https://fly.io/static/images/brand/brandmark.svg -->
- [Fullstack Ruby](https://www.fullstackruby.dev/) <!-- https://www.fullstackruby.dev/images/fullstack_ruby_icon.png -->
- [Noel Rappin's Blog](https://noelrappin.com/blog/) <!-- https://letslearnruby.com/images/noel-rappin.jpg -->
- [One Ruby Question](https://buttondown.email/bhumi/archive/) <!-- https://assets.buttondown.email/images/0375126a-cf71-4d05-baca-c5d2ee0da1d7.png -->
- [Write Software, Well](https://www.writesoftwarewell.com/) <!-- https://letslearnruby.com/images/akshay-khot.jpg -->
- [zverok on lucid code and open data](https://zverok.substack.com/) <!-- https://avatars.githubusercontent.com/u/129656 -->

### "Let's build" screencasts

These are series using at least Rails 7.

- [CJ Avilla - CreatorPlatform.xyz](https://www.youtube.com/watch?v=uuHtuR2FFS4&list=PLS6F722u-R6IJfBrIRx3a2SBkAL4vUp2p) <!-- https://i.ytimg.com/vi/uuHtuR2FFS4/maxresdefault.jpg -->
- [Conner Jensen - learning management system](https://www.youtube.com/watch?v=HDA9QiHgrsI) <!-- https://i.ytimg.com/vi/HDA9QiHgrsI/maxresdefault.jpg -->
- [Conner Jensen - ecommerce app](https://www.youtube.com/watch?v=HDA9QiHgrsI) <!-- https://i.ytimg.com/vi/hURUMwdCWuI/maxresdefault.jpg -->
- [Ken Greeff - Luxury Stays (accommodation directory)](https://www.youtube.com/playlist?list=PLCWWDssV3NgzmIO6DBIjA7j8Th-vVMsnI) <!-- https://i.ytimg.com/vi/_S_BqFjpI30/hqdefault.jpg -->
- [TypeFast - Tinysale (Gumroad clone)](https://www.youtube.com/playlist?list=PLCawOXF4xaJLcYMsWPqEKoOCDsr-xLv5J) <!-- https://i.ytimg.com/vi/SevRvvTkY78/hqdefault.jpg -->
- [TypeFast - Airbnb clone](https://www.youtube.com/playlist?list=PLCawOXF4xaJK1_-KVgXyREULRVy_W_1pe) <!-- https://i.ytimg.com/vi/D889P37r3bc/hqdefault.jpg -->
- [TypeFast - Trello clone](https://www.youtube.com/playlist?list=PLCawOXF4xaJLgAlweneIHqQTUMiVquXaD) <!-- https://i.ytimg.com/vi/vcBdu3zkeV8/hqdefault.jpg -->
- [TypeFast - Twitter clone](https://www.youtube.com/playlist?list=PLCawOXF4xaJLb9HwPWiizGBNupJszY6bR) <!-- https://i.ytimg.com/vi/XxuPlSW4t6M/hqdefault.jpg -->
- [TypeFast - Instagram clone](https://www.youtube.com/playlist?list=PLCawOXF4xaJIzmh3y8xxzGGYog9r3npOE) <!-- https://i.ytimg.com/vi/0ghpv0XZ4ZY/hqdefault.jpg -->
- [Webcrunch - supplement sharing app](https://www.youtube.com/playlist?list=PL01nNIgQ4uxOhHYZd6THGIFVBALJZCcpM) <!-- https://i.ytimg.com/vi/uef6vBXyY0M/hqdefault.jpg -->

### Topical screencasts

<!-- - [Rapid Ruby ](https://www.youtube.com/@rapid-ruby/videos) --> <!-- not very active -->
<!-- - [Indigo Tech Tutorials](https://www.youtube.com/@indigotechtutorials/videos) --> <!-- maybe add in the future -->
- [Code with Jason Meetup](https://www.youtube.com/@codewithjason/videos) <!-- https://i.ytimg.com/vi/mWUpIH6wqaI/maxresdefault.jpg -->
- [Deanin](https://www.youtube.com/@Deanin/videos) <!-- https://yt3.googleusercontent.com/ahPK-LBcDFhQplh2FMWvsXegGUUzoSofq3TWKk42vwO-rR8KZNptp8i6D2eEWjPeHsV7S2e-EAQ=s176-c-k-c0x00ffffff-no-rj -->
- 💲[Destroy All Software](https://www.destroyallsoftware.com/screencasts/catalog) <!-- https://letslearnruby.com/images/destroy-all-software.png -->
- 💲[Drifting Ruby](https://www.driftingruby.com) <!-- https://letslearnruby.com/images/drifting-ruby.jpg -->
- 💲[GoRails](https://gorails.com) <!-- https://letslearnruby.com/images/gorails.jpg -->
- [Ruby & Beyond](https://www.youtube.com/@RubyAndBeyond) <!-- https://yt3.googleusercontent.com/GN8RZ5dTfwVs_gMGkOkkpLizoD39WJTewaS1JbCouEPyMdOUo4FH97vvjMaX2uUjlqx4lw5LVg=s160-c-k-c0x00ffffff-no-rj -->
- [SupeRails](https://www.youtube.com/@SupeRails/videos) <!-- https://i.ytimg.com/vi/csvaYIaBYpw/maxresdefault.jpg -->
- [Webcrunch](https://www.youtube.com/@Webcrunch/videos) <!-- https://letslearnruby.com/images/webcrunch.svg -->

### Streams

- [AmirRajan](https://www.twitch.tv/amirrajan) <!-- https://avatars.githubusercontent.com/u/517055?s=400 -->
- [ChaelCodes](https://www.twitch.tv/ChaelCodes) <!-- https://static-cdn.jtvnw.net/jtv_user_pictures/7d0747d3-6b95-495e-866f-8b7203a29554-profile_image-300x300.png -->
- [CodingWithCaleb](https://www.twitch.tv/codingwithcaleb)  <!-- https://static-cdn.jtvnw.net/jtv_user_pictures/06d54031-97e7-4a0a-bd4c-4f1331ec1650-profile_image-300x300.png -->
- [fractaledmind](https://www.youtube.com/@fractaledmind/streams) <!-- https://avatars.githubusercontent.com/u/5077225?s=400 -->
- [FullStackLive](https://www.twitch.tv/fullstacklive) <!-- https://static-cdn.jtvnw.net/jtv_user_pictures/7aa31c3b-54b0-4c44-a9ed-babdc6e5ca30-profile_image-300x300.png -->
- [jardonamron](https://m.twitch.tv/jardonamron) <!-- https://static-cdn.jtvnw.net/jtv_user_pictures/7fecac18-9377-4611-b57e-34fedf3a4a73-profile_image-300x300.png -->
- [jhawthorn](https://www.twitch.tv/jhawthorn) <!-- https://static-cdn.jtvnw.net/jtv_user_pictures/947d3620-e9a6-46e9-9837-917e4ceafc5b-profile_image-300x300.jpeg -->
- [purplelf](https://m.twitch.tv/purplelf) <!-- https://static-cdn.jtvnw.net/jtv_user_pictures/e0d78f1f-6ed9-4dc7-b96d-ccada52887ee-profile_image-300x300.png -->
- [TenderlovesCoolStuff](https://www.youtube.com/@TenderlovesCoolStuff/streams) <!-- https://avatars.githubusercontent.com/u/3124?s=400 -->
- [thoughtbot on YouTube](https://www.youtube.com/@thoughtbot/streams) <!-- https://avatars.githubusercontent.com/u/6183?s=400 -->
- [thoughtbot on Twitch](https://www.twitch.tv/thoughtbot) <!-- https://avatars.githubusercontent.com/u/6183?s=400 -->
- [YakAndShears](https://www.twitch.tv/yakandshears) <!-- https://yt3.googleusercontent.com/Bk18JI7d5n7lzVYz_IxY23Ps4lZnrb0pKGCnGErnelalBdGEjkGfKnurVExxvM1RqjZEptL1OA=s160-c-k-c0x00ffffff-no-rj -->
- [yesthatelise](https://www.twitch.tv/yesthatelise) <!-- https://static-cdn.jtvnw.net/jtv_user_pictures/78a1fa7a-7277-45c4-93b2-4bd7b5023ab8-profile_image-300x300.png -->

### Podcasts

- [Bike Shed](https://www.bikeshed.fm/) <!-- https://assets.fireside.fm/file/fireside-images/podcasts/images/1/167c01a1-0eb9-4640-b488-c2f6d6866650/cover_small.jpg -->
- [Code and the Coding Coders who Code it](https://podcast.drbragg.dev/) <!-- https://podcast.drbragg.dev/images/podcast.jpeg -->
- [Code with Jason](https://www.codewithjason.com/podcast) <!-- https://www.codewithjason.com/wp-content/uploads/2023/01/jason-300x300.jpeg -->
- [Friendly Show](https://www.friendly.show/) <!-- https://storage.buzzsprout.com/zhyzuuam1vptl88kzpj22qnk8naa -->
- [Fullstack Ruby](https://www.fullstackruby.dev/topics/podcast) <!-- https://www.fullstackruby.dev/images/fullstack_ruby_icon.png -->
- [IndieRails](https://www.indierails.com/) <!-- https://images.transistor.fm/images/show/38529/medium_1675794047-artwork.jpg -->
- [Maintainable](https://maintainable.fm/) <!-- https://maintainable.fm/images/maintainable-cover-robby-mid.jpg -->
- [Rails Changelog](https://www.railschangelog.com/) <!-- https://images.transistor.fm/images/show/39552/medium_1680188330-artwork.jpg -->
- [Remote Ruby](https://www.remoteruby.com/) <!-- https://storage.buzzsprout.com/variants/y355ibk4nfqsqu37yrvz8a6o63z1/b49cbe86cb411762753e730c58953bb88ad958a9d657212c074729b6f04e5463.jpg -->
- [Rooftop Ruby](https://www.rooftopruby.com) <!-- https://storage.buzzsprout.com/variants/4ln9kmgzd7365e01mek8zsnnoyc7/b49cbe86cb411762753e730c58953bb88ad958a9d657212c074729b6f04e5463.jpg -->
- [Rubber Duck Dev Show](https://www.rubberduckdevshow.com/) <!-- https://i.ytimg.com/vi/HIuyzkeWLdQ/maxresdefault.jpg -->
- [Ruby for All](https://www.rubyforall.com/) <!-- https://images.transistor.fm/images/show/32763/medium_1661990746-artwork.jpg -->
- [Ruby on Rails Podcast](https://www.therubyonrailspodcast.com/), especially starting at [episode 372](https://www.therubyonrailspodcast.com/372) went they went independent, brought on co-hosts, and hired an editor. <!-- https://assets.fireside.fm/file/fireside-images/podcasts/images/e/ed4e373f-21b4-44bb-a2f3-630a56c17f71/cover_small.jpg -->
- [Ruby Rogues](https://topenddevs.com/podcasts/ruby-rogues) <!-- https://topenddevs.us-southeast-1.linodeobjects.com/7tb1xhkypftrpf3dwr83ztyccwte -->
- [Tightly Coupled Book Club](https://rss.com/podcasts/tightly-coupled-book-club/) <!-- https://img.rss.com/tightly-coupled-book-club/400/20230320_080352_39a56ab7cb62348b7e033fd90746e2ff.jpg -->
- [YAGNI](https://yagni.fm/) <!-- https://images.transistor.fm/images/show/32802/medium_1659401516-artwork.jpg -->

## Rails codebases to study

I've chosen the codebases below based on a these criteria:

* Is active, with recent commits.
* Does not use a JS framework on the front end, though I made exceptions.
* Is well-known *or* solves a problem that's interesting to me.

If you want to explore more widely, here are other places to find open-source Ruby projects:

* [OpenSourceRails](https://opensourcerails.org/)
* [Ruby projects on CodeTriage](https://www.codetriage.com/?language=Ruby), though not all of them are Rails apps
* [Real World Rails](https://github.com/eliotsykes/real-world-rails) (and [how to search through it](https://www.hexdevs.com/posts/massive-list-of-open-source-ruby-on-rails-applications-you-can-use-as-a-reference/))
* [Awesome Ruby and Rails Open Source Apps](https://github.com/asyraffff/Open-Source-Ruby-and-Rails-Apps)

Without further ado…

- **Small codebases:** Less than 50k lines of Ruby code.
  - [github.com/onerinas/whatwentwelltoday](https://github.com/onerinas/whatwentwelltoday). <1k lines. *An app to share daily positivity.*
  - [github.com/krschacht/37signals-rails-code](https://github.com/krschacht/37signals-rails-code). <2k lines. *Extracts from the Basecamp and Hey codebases.*
  - [github.com/nshki/naisho](https://github.com/nshki/naisho). <2k lines. *Send personal data deletion request emails to hundreds of data brokers at once.*
  - [github.com/carsoncole/workypad](https://github.com/carsoncole/workypad). 2k lines. *App for managing job prospecting.*
  - [once.com/writebook](https://once.com/writebook). 3k lines. *App for publishing books to the web.* <!-- https://once.com/assets/images/logo-writebook.png -->
  - [github.com/ChaelCodes/MeetAnotherDay](https://github.com/ChaelCodes/MeetAnotherDay). 4k lines. *Helps you find and meet up with your friends at conferences.*
  - [github.com/SpinaCMS/Spina](https://github.com/SpinaCMS/Spina). 6k lines. *CMS (Content Management System).*
  - [github.com/eigenfocus/eigenfocus](https://github.com/eigenfocus/eigenfocus/). 5k lines. *Self-hosted project/time management app.*
  - [github.com/codetriage/codetriage](https://github.com/codetriage/codetriage). 6k lines. *Issue tracker for open-source projects.*
  - [github.com/demingfactor/calagator](https://github.com/demingfactor/calagator). 9k lines. *Community calendar platform.*
  - [github.com/lookbook-hq/lookbook](https://github.com/lookbook-hq/lookbook). 11k lines. *UI development environment for Rails apps.*
  - [github.com/thoughtbot/upcase](https://github.com/thoughtbot/upcase). 14k lines. *Learning platform for developers.*
  - [github.com/joemasilotti/railsdevs.com](https://github.com/joemasilotti/railsdevs.com). 14k lines. *The reverse job board for Ruby on Rails developers.*
  - [github.com/houndci/hound](https://github.com/houndci/hound). 14k lines. *Automated code review for GitHub PRs.*
  - [github.com/galahq/gala](https://github.com/galahq/gala). 15k lines. *Collaborative learning platform.*
  - [github.com/CircuitVerse/CircuitVerse](https://github.com/CircuitVerse/CircuitVerse). 15k lines. *Digital logic circuit simulator. Has a Vue.js front end.*
  - [github.com/docusealco/docuseal](https://github.com/docusealco/docuseal). 15k lines. *Open source DocuSign alternative.*
  - [github.com/rubyforgood/homeward-tails](https://github.com/rubyforgood/homeward-tails). 15k lines. *Connects adopters/fosters with pets.*
  - [github.com/TheOdinProject/theodinproject](https://github.com/TheOdinProject/theodinproject). 16k lines. *Main website for The Odin Project web development learning platform.*
  - [github.com/AllYourBot/hostedgpt](https://github.com/AllYourBot/hostedgpt). 16k lines. *Self-hosted ChatGPT alternative.*
  - [github.com/RailsEventStore/ecommerce](https://github.com/RailsEventStore/ecommerce). 17k lines. *Example app showing DDD (Domain-Driven Design), CQRS, and Event Sourcing.*
  - [github.com/lobsters/lobsters](https://github.com/lobsters/lobsters). 18k lines. *Hacker News clone.*
  - [github.com/maybe-finance/maybe](https://github.com/maybe-finance/maybe). 19k lines. *Personal finance app.*
  - [github.com/rauversion/rauversion](https://github.com/rauversion/rauversion). 20k lines. *Music platform.*
  - [github.com/ifmeorg/ifme](https://github.com/ifmeorg/ifme). 21k lines. *Mental health communication web app to share experiences with loved ones.*
  - [github.com/openSUSE/osem](https://github.com/openSUSE/osem). 24k lines. *Event management tool tailored to Free and Open Source Software conferences.*
  - [github.com/chicago-tool-library/circulate](https://github.com/chicago-tool-library/circulate). 26k lines. *A lending library management system.*
  - [github.com/feedbin/feedbin](https://github.com/feedbin/feedbin). 31k lines. *RSS reader.*
  - [github.com/AlchemyCMS/alchemy_cms](https://github.com/AlchemyCMS/alchemy_cms). 37k lines. *CMS (Content Management System).*
  - [github.com/huginn/huginn](https://github.com/huginn/huginn). 37k lines. *Web task automation.*
  - [github.com/rubyforgood/casa](https://github.com/rubyforgood/casa). 44k lines. *Volunteer management system for the nonprofit CASA.*
  - [github.com/rubyforgood/human-essentials](https://github.com/rubyforgood/human-essentials). 47k lines. *An inventory management system for essentials supply banks.*
  - [github.com/SumOfUs/Champaign](https://github.com/SumOfUs/Champaign). 39k lines. *Digital campaigning platform. A Rails app generator.*
- **Larger codebases:** More than 50k lines of Ruby code.
  - [github.com/rubygems/rubygems.org](https://github.com/rubygems/rubygems.org). 56k lines. *Where Ruby gems are hosted.*
  - [github.com/WikiEducationFoundation/WikiEduDashboard](https://github.com/WikiEducationFoundation/WikiEduDashboard). 59k lines. *Wikipedia course dashboard system. Has a React front end.*
  - [github.com/chatwoot/chatwoot](https://github.com/chatwoot/chatwoot). 74k lines. *Customer engagement suite. Has a Vue.js front end.*
  - [github.com/solidusio/solidus](https://github.com/solidusio/solidus). 98k lines. *E-commerce platform.*
  - [github.com/alphagov/whitehall](https://github.com/alphagov/whitehall). 110k lines. *Publishes government content on [gov.uk](https://www.gov.uk/).*
  - [github.com/mastodon/mastodon](https://github.com/mastodon/mastodon). 117k lines. *Like Twitter but self-hosted and federated.*
  - [github.com/redmine/redmine](https://github.com/redmine/redmine). 118k lines. *Project management app.*
  - [github.com/campsite/campsite](https://github.com/campsite/campsite). 119k lines. *Self-hosted Slack alternative.*
  - [github.com/forem/forem](https://github.com/forem/forem). 126k lines. *Powers the blogging site [dev.to](https://dev.to/). Uses Preact on the front end.*
  - [github.com/openfoodfoundation/openfoodnetwork](https://github.com/openfoodfoundation/openfoodnetwork). 129k lines. *An online marketplace for local food.*
  - [github.com/decidim/decidim](https://github.com/decidim/decidim). 294k lines. *The participatory democracy framework.*
  - [github.com/zammad/zammad](https://github.com/zammad/zammad). 299k lines. *Helpdesk/customer support system.*
  - [github.com/antiwork/gumroad](https://github.com/antiwork/gumroad). 323k lines. *E-commerce platform.*
  - [github.com/opf/openproject](https://github.com/opf/openproject). 479k lines. *Project management software.*
  - [github.com/discourse/discourse](https://github.com/discourse/discourse). 514k lines. *Discussion forum platform. Has an Ember.js front end.*
  - [github.com/instructure/canvas-lms](https://github.com/instructure/canvas-lms). 891k lines. *A popular LMS (learning management system).*
  - [gitlab.com/gitlab-org/gitlab](https://gitlab.com/gitlab-org/gitlab). 3 million lines. *Like GitHub but with CI/CD and DevOps features built in. Uses Vue.js on the front end. Has [docs on architecture](https://docs.gitlab.com/ee/development/architecture.html).* <!-- https://letslearnruby.com/images/gitlab.png -->
