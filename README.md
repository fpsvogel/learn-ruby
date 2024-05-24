<!-- regex to find items with missing images: results should include only GitHub links -->
<!-- - \[x\] .+[^>\n]\n -->

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
  - [Ruby/Rails communities](#rubyrails-communities)
- [Foundational tools](#foundational-tools)
  - [SQL](#sql)
  - [Git](#git)
  - [How the Internet works](#how-the-internet-works)
  - [Linux / command line](#linux--command-line)
- [Advanced Ruby and Rails](#advanced-ruby-and-rails)
  - [Advanced Ruby](#advanced-ruby)
  - [Advanced Rails](#advanced-rails)
- [Front end](#front-end)
  - [HTML and CSS](#html-and-css)
  - [JS](#js)
  - [UI and usability](#ui-and-usability)
  - [Accessibility](#accessibility)
  - [Front-end practice](#front-end-practice)
  - [Hotwire](#hotwire)
- [Expanding my horizons](#expanding-my-horizons)
- [Games in Ruby](#games-in-ruby)
- [Ruby blogs, podcasts, screencasts](#ruby-blogs-podcasts-screencasts)
- [Rails codebases to study](#rails-codebases-to-study)

## Preliminaries

- **If you want to keep it simple** and use just *one* resource that can take you from zero to hireable, I suggest the free [Odin Project](https://www.theodinproject.com/paths). If you want more variety and more depth on certain topics, keep reading!
- **Why did I chose Ruby?** At first I went for full-stack JS, but the JS ecosystem was confusing to me as a beginner. So I tried some others, and found Ruby to be the most enjoyable.
- **Make sure your day job is conducive to part-time studying** if you're a working adult looking to switch careers. I used to be a teacher and spent hours grading in the evenings and on weekends, which would have made studying very difficult. So I switched to a remote customer support job to free up my schedule.
- **Take care of yourself!** Exercise and get plenty of sleep, and you'll better retain what you learn. If you develop wrist pain from heavy computer use, get an ergonomic keyboard (I use the [Keyboardio Atreus](https://fpsvogel.com/posts/2021/keyboardio-atreus), which has a learning curve, but I love it *and* it was affordable), [do daily wrist stretches](https://youtube.com/watch?v=fdD7CgN5FGg), and try a break app such as [Stretchly](https://hovancik.net/stretchly).

Resources marked with a dollar sign (💲) cost money. You may be able to find books for free (from your local library, interlibrary loan, or more dubious sources) but buy them if/when you can, to support the authors.

## Basics

### Front-end basics

- [x] Learn some HTML, CSS, and JS: [The Odin Project - Foundations path](https://www.theodinproject.com/paths/foundations/courses/foundations) or resources under ["Front end"](#front-end) below. <!-- https://avatars.githubusercontent.com/u/4441966?s=400 -->
- [x] Build a blog from scratch. [Here's the first iteration of my blog](https://fpsvogel-2020.netlify.app), and [here's how I built it](https://fpsvogel.com/posts/2020/zs). Building a blog is not only a good exercise in itself, but it might also give you extra motivation to write about what you learn. <!-- https://letslearnruby.com/images/blog-html.png -->

### Ruby basics

- **Basics:**
  - [x] [The Odin Project - Ruby](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/ruby) <!-- https://avatars.githubusercontent.com/u/4441966?s=400 -->
  - [x] [GoRails - Ruby for Beginners](https://gorails.com/series/ruby-for-beginners) if you prefer videos. <!-- https://letslearnruby.com/images/gorails.jpg -->
  - [x] [Try Ruby](https://try.ruby-lang.org/) and [BigBinary Academy](https://academy.bigbinary.com/learn-ruby). If you like an interactive approach. <!-- https://www.globalnerdy.com/wordpress/wp-content/uploads/2009/08/chunky_bacon.jpg -->
- **Guided practice:**
  - [x] [Exercism - Ruby](https://exercism.org/tracks/ruby). Be sure to take notes each time you learn something new in an exercise, and at the end you could write up your reflections ([here are mine](https://fpsvogel.com/posts/2020/exercism-ruby-practice)). <!-- https://avatars.githubusercontent.com/u/5624255?s=400 -->
- **OOP (object-oriented programming):**
  - [x] 💲[Sandi Metz - Practical Object-Oriented Design](https://www.poodr.com) <!-- https://images.squarespace-cdn.com/content/v1/5527cdbae4b0ee7b897c2111/1530279450483-K5BJ5TZGMYSWYA3QQA63/POODR_2e_cover_low_res.jpg -->
  - [x] 💲[Sandi Metz & Katrina Owen - 99 Bottles of OOP](https://sandimetz.com/99bottles-sample-ruby) <!-- https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1477514056i/31183020.jpg -->
- **Build stuff with Ruby.** Here are some ideas:
  - A CLI (command-line interface) app. I made [one that gives statistics on a reading log](https://fpsvogel.com/posts/2021/my-first-ruby-app-lessons-learned). <!-- https://miro.medium.com/v2/resize:fit:774/1*PGxvXulYR1Zp3TPx7FjMsQ.png -->
  - A game. A text-based game is a great exercise, but if you want something fancier see the [Games in Ruby](#games-in-ruby) section. <!-- https://img.itch.zone/aW1nLzIzNjU2MzQucG5n/original/WFWBHQ.png -->
  - A static site. [Bridgetown](https://github.com/bridgetownrb/bridgetown) is great for (among other things) building static sites, which are simpler than SSR (server-side rendered) sites à la Rails. Maybe [rebuild your blog](https://fpsvogel.com/posts/2021/build-a-blog-with-ruby-bridgetown)? Be sure to [join the Bridgetown Discord server](https://discord.gg/Cugms94QFM)—the maintainers are very welcoming and helpful to newbies. <!-- https://www.bridgetownrb.com/images/bridgetown-avatar.png -->
  - More ideas: [Coding Challenges](https://codingchallenges.fyi), [Build your own X](https://github.com/codecrafters-io/build-your-own-x), [Projectbook](https://projectbook.code.brettchalupa.com), [Project-based learning](https://github.com/practical-tutorials/project-based-learning#ruby) <!-- https://d31ezp3r8jwmks.cloudfront.net/2injd2hqjy28zry8i3khh7jauncy -->
- **Reference:**
  - [x] [Ruby API](https://rubyapi.org). Mentioning it up here because it's the best Ruby docs site but very little-known. Since its search uses a query param, you can add a search keyword to your browser to let you quickly search from the address bar, for example `rb partition` would take you to [https://rubyapi.org/3.2/o/s?q=partition](https://rubyapi.org/3.2/o/s?q=partition) <!-- https://upload.wikimedia.org/wikipedia/commons/7/73/Ruby_logo.svg -->

### Rails basics

Only books and courses are listed below, but be sure to *build things* as you learn. I myself [started building a large-ish Rails app](https://fpsvogel.com/posts/2021/first-rails-app-plain-reading) at first, but then I found it more helpful to build a series of small throwaway apps ([1](https://fpsvogel.com/posts/2021/gpt3-ai-story-writer), [2](https://fpsvogel.com/posts/2021/wikipedia-explorer-discover-articles-like-stumbleupon), [3](https://fpsvogel.com/posts/2021/pass-the-story-collaborative-writing-game), [4](https://fpsvogel.com/posts/2022/doctor-lookup-health-provider-search-tool)).

- **Basics:**
  - [x] [GoRails - Build a Blog with Rails 7](https://gorails.com/series/build-a-blog-with-rails-7) and if you want more along the same lines, [Rails 6 for Beginners](https://gorails.com/series/rails-6-for-beginners) <!-- https://letslearnruby.com/images/gorails.jpg -->
  - [x] [The Odin Project - Rails](https://www.theodinproject.com/paths/full-stack-ruby-on-rails) <!-- https://avatars.githubusercontent.com/u/4441966?s=400 -->
- **Testing:**
  - [x] 💲[Jason Swett - The Complete Guide to Rails Testing](https://www.codewithjason.com/complete-guide-to-rails-testing/) <!-- https://www.codewithjason.com/wp-content/uploads/2022/08/cgrt.png -->
  - [x] [thoughtbot - Testing Rails](https://github.com/thoughtbot/testing-rails) or [the summary blog post](https://thoughtbot.com/blog/how-we-test-rails-applications) <!-- https://public-files.gumroad.com/g2f7k3fkbdgvubnh1b2cmsdcsenc -->
  - [x] 💲[Effective Testing with RSpec 3](https://pragprog.com/titles/rspec3/effective-testing-with-rspec-3/) <!-- https://pragprog.com/titles/rspec3/effective-testing-with-rspec-3/rspec3.jpg -->
- **Polishing up:**
  - [x] [Style guides](https://ruby.style/) for Ruby, Rails, and RSpec <!-- https://avatars.githubusercontent.com/u/10871348?s=400 -->

### Getting hired

- **Get real-world experience to put on your resume:**
  - Contribute to open source projects. I've written [a short guide on how to get started](https://fpsvogel.com/posts/2021/how-to-contribute-to-open-source-ruby-rails). <!-- https://imgs.xkcd.com/comics/dependency_2x.png -->
  - [Ruby Central - Scholars and Guides Program](https://rubycentral.org/scholars_guides_program/) <!-- https://rubycentral.org/content/images/size/w256h256/format/png/2022/11/Ruby-Central-logo.svg -->
- **The job search:**
  - [Notes on my 2021-2022 job search](https://fpsvogel.com/posts/2022/how-to-find-ruby-rails-job) <!-- https://www.stockvault.net/data/2018/07/15/253106/preview16.jpg -->
  - [Notes on my 2023-2024 job search](https://fpsvogel.com/posts/2024/job-search-networking-for-engineers) <!-- https://letslearnruby.com/images/2023-job-search.jpg -->

### Ruby/Rails communities

Here are some places where you can learn with others or ask questions when you get stuck.

- **Communities:**
  - [Ruby.social Mastodon instance](https://ruby.social) <!-- https://upload.wikimedia.org/wikipedia/commons/d/d5/Mastodon_logotype_%28simple%29_new_hue.svg -->
  - [Ruby on Rails Link community on Slack](https://www.rubyonrails.link/) <!-- https://www.rubyonrails.link/assets/railslink-icon-10c1d749590f731efcb92fc4ffb599a6171cfd89e2eb2080b925d247060017db.png -->
- **Newsletters:**
  - [Short Ruby](https://newsletter.shortruby.com/) <!-- https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F1a71f846-50a2-435b-b824-ecfe2525557c_727x727.png -->
  - [Ruby Weekly](https://rubyweekly.com/) <!-- https://letslearnruby.com/images/ruby-weekly.png -->
  - [Ruby Radar](https://rubyradar.dev/) <!-- https://letslearnruby.com/images/ruby-radar.png -->
- **Mentorship:**
  - [First Ruby Friend](https://firstrubyfriend.org) where aspiring and first-year developers are connected with a mentor. <!-- https://firstrubyfriend.org/images/ruby-plus-one.svg -->
  - [r/rails](https://www.reddit.com/r/rails) is worth trying too. Examples: [1](https://www.reddit.com/r/rails/comments/rvs7f2/rails_mentoring/), [2](https://www.reddit.com/r/rails/comments/lvwn41/finding_a_mentor/). <!-- https://letslearnruby.com/images/reddit.svg -->

## Foundational tools

### SQL

- **Basics:**
  - [x] [SQL Teaching](https://www.sqlteaching.com) <!-- https://www.sqlteaching.com/database.png -->
  - [x] [SQLBolt](https://sqlbolt.com) <!-- https://letslearnruby.com/images/sql-bolt.png -->
  - [x] [Select Star SQL](https://selectstarsql.com) <!-- https://selectstarsql.com/imgs/favicon-256.png -->
  - [x] [SQL Murder Mystery](https://mystery.knightlab.com/) <!-- https://mystery.knightlab.com/174092-clue-illustration.png -->
  - [ ] [PostgreSQL Exercises](https://pgexercises.com/) and [single-page guide](https://ozencb.github.io/postgresql-exercises/) <!-- https://opengraph.githubassets.com/5dc8f962a8ff3a00a68a35d74a38b117b653d05e8891b85360df152f6755b4b9/AlisdairO/pgexercises -->
  - [x] [SQLZoo](https://sqlzoo.net/wiki/SQL_Tutorial) <!-- https://velog.velcdn.com/images/zero__/post/71852f7f-bbd2-4f51-9025-590644dec95b/image.jpeg -->
- **Advanced:**
  - [x] [Next-Level Database Techniques for Developers](https://sqlfordevs.com/ebook) <!-- https://sqlfordevs.com/build/assets/ebook.454b5368.png -->
  - [ ] 💲[SQL Antipatterns, Volume 1](https://pragprog.com/titles/bksap1/sql-antipatterns-volume-1/)
  - [ ] [Markus Winand - Use the Index, Luke!](https://use-the-index-luke.com/sql/preface)
  - [ ] 💲[Markus Winand - SQL Performance Explained](https://sql-performance-explained.com)
  - [ ] [Advanced Topics in SQL](https://www.edx.org/course/advanced-topics-in-sql) course from Stanford
- **Advanced (PostgreSQL):**
  - [ ] [Postgres Playground](https://www.crunchydata.com/developers/tutorials)
  - [ ] [Yeah, Postgres can do that](https://dev.to/efertsch/series/20415)
  - [ ] 💲[High Performance PostgreSQL for Rails](https://pragprog.com/titles/aapsql/high-performance-postgresql-for-rails/)
  - [ ] Blog posts on Rails + Postgres: [lots on Paweł Urbanek's blog](https://pawelurbanek.com/blog), [this one at Honeybadger](https://www.honeybadger.io/blog/rails-postgresql-queries/), [this one at thoughtbot](https://thoughtbot.com/blog/advanced-postgres-performance-tips).
  - [ ] 💲[The Art of PostgreSQL](https://theartofpostgresql.com/)
  - [ ] 💲[PostgreSQL Query Optimization: The Ultimate Guide to Building Efficient Queries](https://link.springer.com/book/10.1007/978-1-4842-6885-8)

### Git

- **Basics:**
  - [x] [Oh My Git!](https://ohmygit.org/) <!-- https://ohmygit.org/assets/images/oh-my-git.png -->
  - [x] [Oh Shit, Git!?!](https://ohshitgit.com/) <!-- https://upload.wikimedia.org/wikipedia/commons/5/50/Fxemoji_u2049.svg -->
  - [x] [Git Katas](https://github.com/eficode-academy/git-katas)
  - [x] [The Git Parable](https://youtube.com/watch?v=ANNboouhNHE) <!-- https://i.ytimg.com/vi/jm7QsI-nNjk/hqdefault.jpg -->
  - [x] [Git Flight Rules](https://github.com/k88hudson/git-flight-rules)
- **Advanced:**
  - [x] [thoughtbot - Rebuilding Git in Ruby](https://thoughtbot.com/blog/rebuilding-git-in-ruby) <!-- https://avatars.githubusercontent.com/u/6183?s=400 -->
  - [ ] [Pro Git](https://git-scm.com/book)
  - [ ] 💲[Building Git](https://shop.jcoglan.com/building-git)

### How the Internet works

- [x] 💲[Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/eighth.htm) <!-- https://m.media-amazon.com/images/I/517X347vzZL.jpg -->
- [ ] [Computer Networks from Scratch](https://www.networksfromscratch.com) (WIP, and possibly abandoned because Ch. 5 has been "coming soon" for a year now)
- [ ] [MDN Web Doc on HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)
- [ ] 💲[Web Security for Developers: Real Threats, Practical Defense](https://www.amazon.com/Web-Security-Developers-Malcolm-McDonald-ebook/dp/B07V78WH7V) and the accompanying site [Hacksplaining](https://www.hacksplaining.com/)
- [ ] [Jesse Storimer - Working with TCP Sockets](https://workingwithruby.com/wwtcps/intro)
- [ ] Build a web server from scratch. Here are Ruby resources: [Ruby HTTP server from the ground up](https://www.dmitry-ishkov.com/2021/07/ruby-http-server-from-ground-up.html), [How to Build a Web App with and without Rails Libraries](https://shopify.engineering/building-web-app-ruby-rails), and [a Reddit discussion with helpful comments](https://www.reddit.com/r/ruby/comments/vfc02l/newb_here_have_you_written_your_own_web_server)

### Linux / command line

- [x] Install and use Linux. [My post on switching to Linux](https://fpsvogel.com/posts/2023/switch-to-linux-from-windows) might give you some pointers. <!-- https://upload.wikimedia.org/wikipedia/commons/3/35/Tux.svg -->
- [ ] [Linux Journey](https://linuxjourney.com/)
- [ ] 💲[How Linux Works](https://nostarch.com/howlinuxworks3)
- [ ] [The Linux Command Line](https://linuxcommand.org/tlcl.php)
- [ ] [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
- [ ] [💲Efficient Linux at the Command Line](https://www.oreilly.com/library/view/efficient-linux-at/9781098113391)
- [ ] ["Linux CLI and shell scripting" list](https://learnbyexample.github.io/curated_resources/linux_cli_scripting.html)
- [ ] [Julia Evans - Your Linux Toolbox](https://jvns.ca/blog/2019/10/21/print-collection-of-my-first-7-zines/)
- [ ] 💲[Julia Evans - Bite Size zine pack](https://wizardzines.com/zines/bite-size-pack/)
- [ ] 💲[Julia Evans - How Containers Work](https://wizardzines.com/zines/containers/)
- [ ] 💲[Wicked Cool Shell Scripts](https://nostarch.com/wcss2)
- [ ] [Jesse Storimer - Working with Unix Processes](https://workingwithruby.com/wwup/intro)

## Advanced Ruby and Rails

### Advanced Ruby

- **Reference:**
  - [ ] [Victor Shepelev (zverok) - The Ruby Reference](https://rubyreferences.github.io/rubyref/) plus [Ruby Changes](https://rubyreferences.github.io/rubychanges/3.0.html) (covering Ruby 3+). [Ruby Evolution](https://rubyreferences.github.io/rubychanges/evolution.html) is also great.
  - [ ] [RuboCop performance rules](https://github.com/rubocop/rubocop-performance)
  - [ ] [RuboCop security rules](https://docs.rubocop.org/rubocop/cops.html#department-security)
- **Concurrency:**
  - [ ] [Jesse Storimer - Working with Ruby Threads](https://workingwithruby.com/wwrt/intro)
  - [ ] [Async Ruby](https://brunosutic.com/blog/async-ruby)
- **Text processing:**
  - [x] [Ruby Regexp](https://learnbyexample.github.io/Ruby_Regexp) <!-- https://learnbyexample.github.io/Ruby_Regexp/images/ruby_regexp.png -->
  - [x] [Ruby One-Liners Guide](https://learnbyexample.github.io/learn_ruby_oneliners/) <!-- https://learnbyexample.github.io/learn_ruby_oneliners/images/ruby_oneliners.png -->
  - [x] 💲[Text Processing with Ruby](https://pragprog.com/titles/rmtpruby/text-processing-with-ruby) <!-- https://m.media-amazon.com/images/I/91QfMPAeQZL._AC_UF1000,1000_QL80_.jpg -->
- **Misc.:**
  - [x] [Avdi Grimm - Confident Ruby](https://pragprog.com/titles/agcr/confident-ruby/) <!-- https://pragprog.com/titles/agcr/confident-ruby/agcr_hucf967c33f389130ab619766a81118218_436632_375x0_resize_q75_box.jpg -->

### Advanced Rails

- **Reference:**
  - [x] 💲[Rebuilding Rails](http://rebuilding-rails.com/) <!-- https://public-files.gumroad.com/84806cmcnanyrmtnxfxvruodap1n -->
  - [ ] [💲The Rails Companion](https://courses.writesoftwarewell.com/p/rails-companion)
  - [ ] 💲[The Rails 7 Way](https://leanpub.com/therails7way)
  - [ ] [Rails Guides](https://guides.rubyonrails.org/)
  - [ ] [Rails API docs](https://api.rubyonrails.org/)
- **Architecture:**
  - [x] [Volmer's Rails Guide](https://volmerius.com/rails/) <!-- https://volmerius.com/images/volmer.jpg -->
  - [x] 💲[Layered Design for Ruby on Rails Applications](https://www.packtpub.com/product/layered-design-for-ruby-on-rails-applications/9781801813785) <!-- https://m.media-amazon.com/images/I/41MAUvi--4L.jpg -->
  - [ ] [Develop Single-Machine Rails Applications with LiteStack](https://blog.appsignal.com/series/develop-single-machine-rails-applications-with-litestack.html)
  - [ ] 💲[Learning Domain-Driven Design](https://www.oreilly.com/library/view/learning-domain-driven-design/9781098100124/) (not Rails-specific)
  - [ ] 💲[Gradual Modularization for Ruby and Rails](https://leanpub.com/package-based-rails-applications)
- **Views:**
  - [ ] [Phlex](https://github.com/phlex-ruby) and tools based on it, such as [Superform](https://github.com/rubymonolith/superform).
  - [ ] [Glimmer](https://github.com/AndyObtiva/glimmer) for Opal and for Web. See [the RubyConf 2023 workshop](https://github.com/AndyObtiva/how-to-build-desktop-applications-in-ruby/tree/rubyconf2023) and [sample apps](https://github.com/AndyObtiva?tab=repositories&q=sample+glimmer+app).
- **Performance:**
  - [ ] 💲[Nate Berkopec - The Complete Guide to Rails Performance](https://www.railsspeed.com/)
  - [ ] 💲[Nate Berkopec - The Ruby on Rails Performance Apocrypha](https://www.speedshop.co/2021/01/14/announcing-apocrypha.html)
  - [ ] [Mature Optimization Handbook](https://carlos.bueno.org/optimization/) (not Rails-specific)
- **Background jobs:**
  - [ ] [Sidekiq wiki](https://github.com/sidekiq/sidekiq/wiki)
  - [ ] [How does Sidekiq work?](https://www.mikeperham.com/how-sidekiq-works/)
  - [ ] 💲[Ruby on Rails Background Jobs with Sidekiq](https://pragprog.com/titles/dcsidekiq/ruby-on-rails-background-jobs-with-sidekiq/)
  - [ ] 💲[Nate Berkopec - Sidekiq in Practice](https://nateberk.gumroad.com/l/sidekiqinpractice)
  - [ ] [AcidicJob](https://github.com/fractaledmind/acidic_job)
- **Deployment:**
  - [ ] 💲[Josef Strzibny - Deployment from Scratch](https://deploymentfromscratch.com/)
  - [ ] 💲[Josef Strzibny - Kamal Handbook](https://strzibny.gumroad.com/l/kamalbook)
  - [ ] [Ruby on Whales: Dockerizing Ruby and Rails development](https://evilmartians.com/chronicles/ruby-on-whales-docker-for-ruby-rails-development)
  - [ ] 💲[The Docker Book](https://dockerbook.com/)
- **Misc.:**
  - [ ] 💲[Frictionless Generators](https://garrettdimon.com/products/frictionless-generators)

## Front end

### HTML and CSS

- **Community:**
  - [The Spicy Web community on Discord](https://discord.com/invite/CUuYVH7Qa9) <!-- https://www.spicyweb.dev/images/spicy-web-avatar-light.png -->
- **HTML:**
  - [ ] [MDN - Getting started with the web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)
  - [ ] [MDN - HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML)
  - [ ] [htmlreference.io](https://htmlreference.io/)
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
- **CSS games:**
  - [ ] [Flexbox Zombies](https://flexboxzombies.com/p/flexbox-zombies)
  - [ ] [Grid Critters](https://gridcritters.com/)
  - [ ] [CSS Diner](https://flukeout.github.io/)
  - [ ] [Flexbox Froggy](https://flexboxfroggy.com/)
  - [ ] [CSS Grid Garden](https://cssgridgarden.com/)
  - [ ] [CSSBattle](https://cssbattle.dev/)

### JS

- **Basics:**
  - [x] [JavaScript for impatient programmers](https://exploringjs.com/impatient-js/) <!-- https://exploringjs.com/impatient-js/img-homepage/cover-homepage.jpg -->
  - [x] [Modern JavaScript Explained For Dinosaurs](https://peterxjang.com/blog/modern-javascript-explained-for-dinosaurs.html) <!-- https://process.fs.teachablecdn.com/ADNupMnWyR7kCWRvm76Laz/resize=width:705/https://www.filepicker.io/api/file/3k8M1zI3S9ePNURLZVBI -->
  - [x] [What the heck is the event loop anyway?](https://youtube.com/watch?v=8aGhZQkoFbQ) <!-- https://i.ytimg.com/vi/8aGhZQkoFbQ/maxresdefault.jpg -->
  - [x] [MDN - JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) <!-- https://upload.wikimedia.org/wikipedia/commons/9/98/MDN_Web_Docs.svg -->
- **Practice:**
  - [ ] [Exercism - JavaScript](https://exercism.org/tracks/javascript)
  - [ ] Build something in JS, or do [JavaScript30](https://javascript30.com/)
- **DOM, forms, and other Web APIs:**
  - [x] [The Modern JavaScript Tutorial - Browser: Document, Events, Interfaces](https://javascript.info/ui) <!-- https://javascript.info/img/site_preview_en_512x512.png -->
  - [ ] [MDN - Web forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)
  - [ ] [web.dev - Learn Forms](https://web.dev/learn/forms)
  - [ ] [MDN - Web APIs](https://developer.mozilla.org/en-US/docs/Web/API)
- **React:**
  - [x] [React "Learn" docs](https://react.dev/learn) <!-- https://upload.wikimedia.org/wikipedia/commons/3/30/React_Logo_SVG.svg -->
- **Going deeper:**
  - [x] [You Don't Know JS Yet](https://github.com/getify/You-Dont-Know-JS). Be sure to read the last three parts after they're finished. #TODO <!-- https://raw.githubusercontent.com/getify/You-Dont-Know-JS/2nd-ed/get-started/images/cover.png -->
  - [ ] [Deep JS](https://exploringjs.com/deep-js/toc.html)
  - [ ] [What the f*ck JavaScript?](https://github.com/denysdovhan/wtfjs)
- **Web components:**
  - [x] ["Hello Web Components"](https://eisenbergeffect.medium.com/hello-web-components-795ed1bd108e) <!-- https://miro.medium.com/v2/resize:fit:1050/1*aqIQ5pH0fhW7QBaqQ7PLeg.png -->
  - [x] [The Modern JavaScript Tutorial - Web Components](https://javascript.info/web-components) <!-- https://javascript.info/img/site_preview_en_512x512.png -->
  - [x] [MDN - Web Components](https://developer.mozilla.org/en-US/docs/Web/API/Web_components) <!-- https://upload.wikimedia.org/wikipedia/commons/9/98/MDN_Web_Docs.svg -->
  - [ ] [Lit "Learn" resources](https://lit.dev/learn/) and a few code labs ([1](https://codelabs.developers.google.com/codelabs/the-lit-path), [2](https://codelabs.developers.google.com/codelabs/lit-2-for-react-devs), [3](https://open-wc.org/codelabs/basics/lit-html), [4](https://open-wc.org/codelabs/intermediate/lit-html))
  - [ ] SSR web components in Ruby with the upcoming [Heartml](https://heartml-docs.onrender.com/) (see [this Spicy Web article](https://www.spicyweb.dev/web-components-ssr-node/) for context)

### UI and usability

- [x] 💲[Don't Make Me Think](https://sensible.com/dont-make-me-think/) <!-- https://m.media-amazon.com/images/I/51sdCuqMwWL._AC_UF1000,1000_QL80_.jpg -->
- [x] 💲[The Design of Everyday Things](https://www.nngroup.com/books/design-everyday-things-revised/) <!-- https://m.media-amazon.com/images/I/416Hql52NCL.jpg -->
- [ ] [Growth.Design](https://growth.design/)
- [ ] [Roast My Landing Page blog](https://blog.roastmylandingpage.com/)
- [x] [Victor Ponamariov - 50 Tips to Improve User Interface](https://fifty.user-interface.io/50_ui_tips.pdf) <!-- https://fifty.user-interface.io/book.png -->
- [ ] [Victor Ponamariov - How to design almost any UI element](https://user-interface.io/articles/how-to-design-almost-any-ui-element)
- [ ] 💲[Victor Ponamariov - 100 UI/UX Tips & Tricks](https://akcium.gumroad.com/l/ui-ux-tips) (or on [the landing page](https://hundred.user-interface.io/))
- [ ] 💲[Victor Ponamariov - Re:Form](https://reform.user-interface.io/)
- [ ] 💲[Master UI Design](https://www.masteruibook.com/)
- [ ] 💲[Refactoring UI](https://www.refactoringui.com/book)
- [ ] 💲[User Interface Design: A Software Engineering Perspective](https://www.amazon.com/dp/0321181433)

### Accessibility

- [ ] [MDN - Accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility)
- [ ] [Responsible Web Applications](https://responsibleweb.app/)
- [ ] [web.dev - Learn Accessibility](https://web.dev/learn/accessibility/) (among [their other courses](https://web.dev/learn/))
- [ ] In Rails: [Accessibility is a Requirement](https://www.youtube.com/watch?v=BF3D_IqOknk), [Accessible by Default](https://www.youtube.com/watch?v=4j2zlvE_Yj8)

### Front-end practice

- [ ] [Codewell](https://www.codewell.cc/)
- [ ] [Frontend Mentor](https://www.frontendmentor.io/)
- [ ] [Frontend Practice](https://www.frontendpractice.com/)

### Hotwire

- **Community and news:**
  - [StimulusReflex community on Discord](https://discord.com/invite/stimulus-reflex) <!-- https://avatars.githubusercontent.com/u/73479186?s=400 -->
  - [Joe Masilotti's newsletter](https://masilotti.com/hotwire/) <!-- https://masilotti.com/assets/images/joe-small.jpg -->
  - [Hotwire Weekly](https://hotwireweekly.com/) <!-- https://assets.buttondown.email/images/1bdac043-d137-4e4f-86ef-4df5c3b34029.png -->
  - [The Hotwire Club](https://hotwire.club/) <!-- https://letslearnruby.com/images/hotwire-club.png -->
  - [Hotwiring Rails](https://buttondown.email/davidcolby) <!-- https://buttondown.email/static/images/icons/icon-square@400.png -->
- **Basics:**
  - [ ] [What is the difference between Turbo and Stimulus, and what exactly is Hotwire?](https://www.ducktypelabs.com/turbo-vs-stimulus/)
  - [ ] [Hotwire.io](https://hotwire.io) (better than the official docs site)
  - [ ] [Write Software, Well - A Brief Introduction to Hotwire](https://www.writesoftwarewell.com/introduction-to-hotwire/)
  - [ ] [Write Software, Well - You Don't Need Rails to Start Using Hotwire](https://www.writesoftwarewell.com/using-hotwire-without-rails/)
  - [ ] [Write Software, Well - Turbo Streams: How They Work and Differ From Turbo Frames](https://www.writesoftwarewell.com/understanding-hotwire-turbo-streams/)
  - [ ] Evil Martians [talk](https://www.youtube.com/watch?v=sIxvxp7E0xg) and [blog post](https://evilmartians.com/chronicles/hotwire-reactive-rails-with-no-javascript)
  - [ ] [Turbo Rails Tutorial](https://www.hotrails.dev/)
  - [ ] [David Colby - Turbo Rails 101](https://www.colby.so/posts/turbo-rails-101-todo-list)
  - [ ] [Hotwire Handbook, Part 1](https://philreynolds.dev/posts/2022/hotwire-handbook-part-1), [Part 2](https://purpleriver.dev/posts/2023/hotwire-handbook-part-2-redux), [Part 3](https://purpleriver.dev/posts/2023/hotwire-handbook-part-3)
  - [ ] [30 days of Hotwire tips](https://twitter.com/ilrock__/status/1631315562390519809)
  - [ ] [Andrea Fomera - Learn Hotwire by Building a Forum](https://store.afomera.dev/learn-hotwire)
  - [ ] [David Colby - Hotwired ATS: Modern, full-stack Rails development](https://book.hotwiringrails.com/)
  - [ ] [Hotwire Cases](https://hotwiredcases.dev)
  - [ ] [Turbo Music Drive](https://github.com/palkan/turbo-music-drive) app demonstrating upcoming features of Turbo 8
  - [ ] [Turbo 8 in 8 minutes](https://fly.io/ruby-dispatch/turbo-8-in-8-minutes)
- **Screencasts and blogs:**
  - [ ] [Mix & Go screencasts on Hotwire](https://www.youtube.com/playlist?list=PLBhH0uX92r6oiwiLBjdE-3NNsyRqyLAV9)
  - [ ] [SupeRails screencasts on Hotwire](https://www.youtube.com/playlist?list=PLdTytUiloS16epXsqHswpCUMND_rksjr4)
  - [ ] [Rapid Ruby screencasts on Hotwire](https://www.youtube.com/playlist?list=PL2OcwqOUtdpCqddncOH61f0phQKtum3yQ)
  - [ ] [SupeRails blog](https://blog.corsego.com) which includes even more Hotwire tips.
  - [ ] [David Colby's blog](https://www.colby.so)
  - [ ] 💲[Andrea Fomera - Learn Hotwire by Building a Calendar](https://store.afomera.dev/learn-hotwire-by-building-a-calendar)
- **Examples and snippets:**
  - [ ] [Hotwire examples](https://github.com/thoughtbot/hotwire-example-template/branches/active) from Thoughtbot
  - [ ] [Better Stimulus](https://www.betterstimulus.com/)
  - [ ] [Stimulus-Use](https://stimulus-use.github.io/stimulus-use)
  - [ ] [Stimulus Components](https://www.stimulus-components.com/) for inspiration
- **Hotwire extensions:**
  - [ ] [TurboPower](https://github.com/marcoroth/turbo_power-rails)
  - [ ] [TurboBoost Commands](https://github.com/hopsoft/turbo_boost-commands)
  - [ ] [TurboBoost Streams](https://github.com/hopsoft/turbo_boost-streams)
  - [ ] [TurboBoost Elements](https://github.com/hopsoft/turbo_boost-elements)
- **Multi-platform:**
  - [ ] 💲[The Rails and Hotwire Codex](https://railsandhotwirecodex.com/)
- **Other similar libraries:**
  - [ ] [htmx](https://htmx.org/): read the book [Hypermedia Systems](https://hypermedia.systems) and/or watch [Carson Gross — Return To Hypermedia: Solving Javascript Fatigue Using Fundamental Web Architecture](https://youtube.com/watch?v=LRrrxQXWdhI).
  - [ ] [htmz](https://leanrada.com/htmz/): like htmx but simpler.

## Expanding my horizons

- **Be a mentor:**
  - [x] [Exercism](https://exercism.org/mentoring) <!-- https://avatars.githubusercontent.com/u/5624255?s=400 -->
  - [ ] [First Ruby Friend](https://firstrubyfriend.org/mentors)
- **Career advancement:**
  - [x] [Engineering progression for humans](https://localghost.dev/blog/engineering-progression-for-humans/) <!-- https://localghost.dev/img/og-image.png -->
  - [ ] [Path to Senior Engineer handbook](https://github.com/jordan-cutler/path-to-senior-engineer-handbook)
  - [ ] [Staff engineer archetypes](https://staffeng.com/guides/staff-archetypes/)
  - [ ] 💲[The Software Engineer's Guidebook](https://www.engguidebook.com)
  - [ ] 💲[The Staff Engineer's Path](https://www.oreilly.com/library/view/the-staff-engineers/9781098118723/)
  - [ ] 💲[The Tech Resume Inside Out](https://thetechresume.com/)
- **Computer science:**
  - [x] 💲[Code: The Hidden Language of Computer Hardware and Software](https://www.informit.com/store/code-the-hidden-language-of-computer-hardware-and-software-9780137909100) <!-- https://m.media-amazon.com/images/I/515myo2UtFL._AC_UF1000,1000_QL80_.jpg -->
  - [ ] [NandGame](https://nandgame.com)
  - [ ] [CircuitVerse](https://circuitverse.org/)
  - [x] From Nand to Tetris: [Part 1](https://www.coursera.org/learn/build-a-computer), [Part 2](https://www.coursera.org/learn/nand2tetris2) <!-- https://d3njjcbhbojbot.cloudfront.net/api/utilities/v1/imageproxy/https://d15cw65ipctsrr.cloudfront.net/32/effec0907511e4ba44bb6973b9260b/COURSE_IMAGE.png -->
  - [x] 💲[Data Structures and Algorithms in Java](https://www.amazon.com/Data-Structures-Algorithms-Java-2nd/dp/0672324539) <!-- https://m.media-amazon.com/images/I/91s8Z6lR87L._AC_UF1000,1000_QL80_.jpg -->
  - [ ] 💲[The Algorithm Design Manual](https://www.algorist.com/) plus [lecture videos](https://www3.cs.stonybrook.edu/~skiena/373/videos/)
  - [x] 💲[Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/) <!-- https://m.media-amazon.com/images/I/51lTsD-LGoL.jpg -->
  - [ ] 💲[Computer Systems: A Programmer's Perspective](https://csapp.cs.cmu.edu/)
  - [ ] [Crafting Interpreters](https://craftinginterpreters.com/)
- **Coding challenges:**
  - [ ] [Advent of Code](https://adventofcode.com)
- **Design patterns:**
  - [x] 💲[Head First Design Patterns](https://www.oreilly.com/library/view/head-first-design/9781492077992/) <!-- https://m.media-amazon.com/images/W/MEDIAX_849526-T3/images/I/91quawUTiVL._SY522_.jpg -->
  - [x] [Refactoring.Guru](https://refactoring.guru/) <!-- https://refactoring.guru/images/content-public/logos/logo-plain.png -->
  - [ ] [thoughtbot - Ruby Science](https://thoughtbot.com/ruby-science) (or [EPUB/PDF](https://thoughtbot.gumroad.com/l/ruby-science))
- **Monitoring:**
  - [ ] 💲[Practical Monitoring](https://www.oreilly.com/library/view/practical-monitoring/9781491957349/)
  - [ ] 💲[Observability Engineering](https://www.oreilly.com/library/view/observability-engineering/9781492076438/)
- **Documentation:**
  - [ ] [Divio Documentation System](https://documentation.divio.com/) (a.k.a. [Diataxis](https://diataxis.fr/))
- **Learn Crystal:** Whenever you need to make an isolated bit of Ruby code run faster than Ruby can run, porting it to Crystal is easy because they're so similar.
  - [ ] [Crystal for Rubyists (doc page)](https://crystal-lang.org/reference/1.9/crystal_for_rubyists/index.html)
  - [ ] [Crystal for Rubyists (book)](https://www.crystalforrubyists.com/)
  - [ ] [Exercism - Crystal](https://exercism.org/tracks/crystal)
  - [ ] [Crystal Koans](https://github.com/ilmanzo/crystal-koans)
  - [ ] Learn how to offload CPU-intensive tasks from a Ruby app into Crystal. There are several approaches ([1](https://github.com/contribsys/faktory), [2](https://github.com/hugopl/sidekiq.cr), [3](https://github.com/crimson-knight/fruit_juice), [4](https://www.youtube.com/watch?v=sTGfi98XXS4)).
  - [ ] Make a performance-intensive game/toy in Crystal using [Raylib](https://github.com/sol-vin/raylib-cr) or [SFML](https://github.com/oprypin/crsfml), possibly with the [Chipmunk](https://github.com/oprypin/crystal-chipmunk?tab=readme-ov-file) physics library.
- **Learn functional programming**
  - [My list "Learn functional programming"](https://github.com/fpsvogel/learn-functional-programming)

## Games in Ruby

- **Ruby game libraries:**
  - 💲[DragonRuby Game Toolkit](https://dragonruby.itch.io/dragonruby-gtk) is my recommendation because it has the liveliest community, and all the resources below are for DragonRuby. You may qualify for a free license (see "Free Unrestricted License" on the homepage), and the creators regularly give it away for free during game jams and other special occasions. <!-- https://img.itch.zone/aW1nLzIzNjU2MzQucG5n/original/WFWBHQ.png -->
  - [Gamefic](https://gamefic.com/) <!-- https://gamefic.com/assets/goony-6ea3e43a0283cf3bacced44d7f9e0486f27e845415b64350481592e2c1939abf.png --> is for building text-based adventure games and interactive fiction.
  - [Gosu](https://www.libgosu.org/) <!-- https://www.libgosu.org/website_header.png -->
  - [MiniGL](https://github.com/victords/minigl)
  - [Ruby 2D](https://www.ruby2d.com/) <!-- https://avatars.githubusercontent.com/u/6291058?s=400 -->
  - [Taylor](https://www.taylormadetech.dev) <!-- https://external-preview.redd.it/n2ZrKlYsFTDO-bAvYLtFWtnGikzGQcCKbejg0c9ftp4.jpg?auto=webp&s=08c876c76b0ef5490cfc7d72fbcbaded4dbe7e17 -->
- **DragonRuby tutorials:**
  - [Building Games with DragonRuby](https://book.dragonriders.community/) <!-- https://book.dragonriders.community/img/cover.jpg -->
  - [Let's make Tetris with DragonRuby Game Toolkit, Part 1](https://www.youtube.com/watch?v=xZMwRSbC4rY) and [Part 2](https://www.youtube.com/watch?v=C3LLzDUDgz4) <!-- https://i.ytimg.com/vi/xZMwRSbC4rY/sddefault.jpg -->
  - [Notes on DragonRuby Game Toolkit](https://dev.to/presidentbeef/series/16166) <!-- https://img.itch.zone/aW1nLzIzNjU2MzQucG5n/original/WFWBHQ.png -->
- **DragonRuby community, reference, tools:**
  - [Discord server](discord.dragonruby.org) <!-- https://img.itch.zone/aW1nLzIzNjU2MzQucG5n/original/WFWBHQ.png -->
  - [Docs](http://docs.dragonruby.org.s3-website-us-east-1.amazonaws.com/) <!-- https://img.itch.zone/aW1nLzIzNjU2MzQucG5n/original/WFWBHQ.png -->
  - [Zif](https://github.com/danhealy/dragonruby-zif)
  - [Dragon Riders Community](https://www.dragonriders.community) <!-- https://www.dragonriders.community/red-logo.png -->
  - [DragonRuby Treasure](https://itch.io/c/2785336/dragonruby-treasure), a collection of games made with DragonRuby. <!-- https://img.itch.zone/aW1nLzc3Mjc2ODYucG5n/315x250%23c/UBg9MK.png -->

## Ruby blogs, podcasts, screencasts

- **Blogs:** There are lots more out there; these are just my favorites.
  - [Code with Jason](https://www.codewithjason.com/articles/) <!-- https://www.codewithjason.com/wp-content/uploads/2023/01/jason-300x300.jpeg -->
  - [Fly.io - The Ruby Dispatch](https://fly.io/ruby-dispatch/) <!-- https://fly.io/static/images/brand/brandmark.svg -->
  - [Fullstack Ruby](https://www.fullstackruby.dev/) <!-- https://www.fullstackruby.dev/images/fullstack_ruby_icon.png -->
  - [Noel Rappin's Blog](https://noelrappin.com/blog/) <!-- https://letslearnruby.com/images/noel-rappin.jpg -->
  - [One Ruby Question](https://buttondown.email/bhumi/archive/) <!-- https://assets.buttondown.email/images/0375126a-cf71-4d05-baca-c5d2ee0da1d7.png -->
  - [Write Software, Well](https://www.writesoftwarewell.com/) <!-- https://letslearnruby.com/images/akshay-khot.jpg -->
  - [zverok on lucid code and open data](https://zverok.substack.com/) <!-- https://avatars.githubusercontent.com/u/129656 -->
- **"Let's build" screencasts:** These are channels that have at least one series that uses Rails 7.
  - [CJ Avilla](https://www.youtube.com/@cjav_dev/playlists) <!-- https://i.ytimg.com/vi/uuHtuR2FFS4/maxresdefault.jpg -->
  - [Conner Jensen](https://www.youtube.com/@connerjensen8170/videos) <!-- https://i.ytimg.com/vi/hURUMwdCWuI/maxresdefault.jpg -->
  - [Dr. Nic](https://www.youtube.com/@MocraVideos/playlists) <!-- https://i.ytimg.com/vi/XWfyffFWbDI/maxresdefault.jpg -->
  - [Justin Searls](https://www.youtube.com/@JustinSearls/playlists) <!-- https://i.ytimg.com/vi/HU4uBJ3UJPk/maxresdefault.jpg -->
  - [Kasper Timm Hansen with Jeremy Smith](https://www.youtube.com/@kaspth-final1-psd) <!-- https://yt3.googleusercontent.com/p24oO36GrH2nCXKBeno3xK2STfeszCBBEzBlDWRaJjiFDLvNOA4XUKFtVheltW5soE8j0DBN1w=s176-c-k-c0x00ffffff-no-rj -->
  - [Mix & Go](https://www.youtube.com/@mixandgo/playlists) <!-- view-source:https://i.ytimg.com/vi/dJ9CEkctKts/maxresdefault.jpg -->
  - [TypeFast](https://www.youtube.com/@typefastco/playlists) <!-- https://i.ytimg.com/vi/0ghpv0XZ4ZY/maxresdefault.jpg -->
  - [Web-Crunch](https://www.youtube.com/@Webcrunch/playlists) <!-- https://i.ytimg.com/vi/uef6vBXyY0M/maxresdefault.jpg -->
- **Topical screencasts:**
  - [SupeRails](https://www.youtube.com/@SupeRails/playlists) <!-- https://i.ytimg.com/vi/csvaYIaBYpw/maxresdefault.jpg -->
  - [Code with Jason Meetup](https://www.youtube.com/@codewithjason/videos) <!-- https://i.ytimg.com/vi/mWUpIH6wqaI/maxresdefault.jpg -->
  - [Deanin](https://www.youtube.com/@Deanin/videos) <!-- https://yt3.googleusercontent.com/ahPK-LBcDFhQplh2FMWvsXegGUUzoSofq3TWKk42vwO-rR8KZNptp8i6D2eEWjPeHsV7S2e-EAQ=s176-c-k-c0x00ffffff-no-rj -->
  - 💲[Drifting Ruby](https://www.driftingruby.com) <!-- https://letslearnruby.com/images/drifting-ruby.jpg -->
  - 💲[GoRails](https://gorails.com) <!-- https://letslearnruby.com/images/gorails.jpg -->
- **Streams:**
  - [ChaelCodes](https://www.twitch.tv/ChaelCodes) <!-- https://static-cdn.jtvnw.net/jtv_user_pictures/7d0747d3-6b95-495e-866f-8b7203a29554-profile_image-300x300.png -->
  - [CodingWithCaleb](https://www.twitch.tv/codingwithcaleb)  <!-- https://static-cdn.jtvnw.net/jtv_user_pictures/06d54031-97e7-4a0a-bd4c-4f1331ec1650-profile_image-300x300.png -->
  - [fractaledmind](https://www.youtube.com/@fractaledmind/streams) <!-- https://yt3.googleusercontent.com/GRH79JWqn6GEmoZxTcVAHFUFgqkw1P3adun8cVuSR2jH7-_TIaXH4yYAFRIsLjv92LxXkSW-Zg=s176-c-k-c0x00ffffff-no-rj -->
  - [FullStackLive](https://www.twitch.tv/fullstacklive) <!-- https://static-cdn.jtvnw.net/jtv_user_pictures/7aa31c3b-54b0-4c44-a9ed-babdc6e5ca30-profile_image-300x300.png -->
  - [jhawthorn](https://www.twitch.tv/jhawthorn) <!-- https://static-cdn.jtvnw.net/jtv_user_pictures/947d3620-e9a6-46e9-9837-917e4ceafc5b-profile_image-300x300.jpeg -->
  - [purplelf](https://m.twitch.tv/purplelf) <!-- https://static-cdn.jtvnw.net/jtv_user_pictures/e0d78f1f-6ed9-4dc7-b96d-ccada52887ee-profile_image-300x300.png -->
  - [TenderlovesCoolStuff](https://www.youtube.com/@TenderlovesCoolStuff/streams) <!-- https://yt3.googleusercontent.com/UHspKNgeDyA4xYuWNNHIRInoTl1goMH6qP-kUSJRf2RB4nX-HOdO-EpqK7EWcdJKcsbQoLI5=s160-c-k-c0x00ffffff-no-rj -->
  - [thoughtbot on YouTube](https://www.youtube.com/@thoughtbot/streams) <!-- https://avatars.githubusercontent.com/u/6183?s=400 -->
  - [thoughtbot on Twitch](https://www.twitch.tv/thoughtbot) <!-- https://avatars.githubusercontent.com/u/6183?s=400 -->
  - [YakAndShears](https://www.twitch.tv/yakandshears) <!-- https://yt3.googleusercontent.com/Bk18JI7d5n7lzVYz_IxY23Ps4lZnrb0pKGCnGErnelalBdGEjkGfKnurVExxvM1RqjZEptL1OA=s160-c-k-c0x00ffffff-no-rj -->
  - [yesthatelise](https://www.twitch.tv/yesthatelise) <!-- https://static-cdn.jtvnw.net/jtv_user_pictures/78a1fa7a-7277-45c4-93b2-4bd7b5023ab8-profile_image-300x300.png -->
- **Podcasts:**
  - [Bike Shed](https://www.bikeshed.fm/) <!-- https://assets.fireside.fm/file/fireside-images/podcasts/images/1/167c01a1-0eb9-4640-b488-c2f6d6866650/cover_small.jpg -->
  - [Code and the Coding Coders who Code it](https://podcast.drbragg.dev/) <!-- https://podcast.drbragg.dev/images/podcast.jpeg -->
  - [Code with Jason](https://www.codewithjason.com/podcast) <!-- https://www.codewithjason.com/wp-content/uploads/2023/01/jason-300x300.jpeg -->
  - [Friendly Show](https://www.friendly.show/) <!-- https://storage.buzzsprout.com/xg8v0bhdl3q0wyxro1ma4ym4j60w -->
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
  - [github.com/krschacht/37signals-rails-code](https://github.com/krschacht/37signals-rails-code). <2k lines. *Extracts from the Basecamp and Hey codebases.*
  - [github.com/carsoncole/workypad](https://github.com/carsoncole/workypad). 2k lines. *App for managing job prospecting.*
  - [github.com/ChaelCodes/MeetAnotherDay](https://github.com/ChaelCodes/MeetAnotherDay). 4k lines. *Helps you find and meet up with your friends at conferences.*
  - [github.com/SpinaCMS/Spina](https://github.com/SpinaCMS/Spina). 5k lines. *CMS (Content Management System).*
  - [github.com/docusealco/docuseal](https://github.com/docusealco/docuseal). 6k lines. *Open source DocuSign alternative.*
  - [github.com/codetriage/codetriage](https://github.com/codetriage/codetriage). 6k lines. *Issue tracker for open-source projects.*
  - [github.com/demingfactor/calagator](https://github.com/demingfactor/calagator). 9k lines. *Community calendar platform.*
  - [github.com/joemasilotti/railsdevs.com](https://github.com/joemasilotti/railsdevs.com). 12k lines. *The reverse job board for Ruby on Rails developers.*
  - [github.com/RailsEventStore/ecommerce](https://github.com/RailsEventStore/ecommerce). 12k lines. *Example app showing DDD (Domain-Driven Design), CQRS, and Event Sourcing.*
  - [github.com/TheOdinProject/theodinproject](https://github.com/TheOdinProject/theodinproject). 12k lines. *Main website for The Odin Project web development learning platform.*
  - [github.com/lobsters/lobsters](https://github.com/lobsters/lobsters). 13k lines. *Hacker News clone.*
  - [github.com/thoughtbot/upcase](https://github.com/thoughtbot/upcase). 14k lines. *Learning platform for developers.*
  - [github.com/CircuitVerse/CircuitVerse](https://github.com/CircuitVerse/CircuitVerse). 15k lines. *Digital logic circuit simulator. Has a Vue.js front end.*
  - [github.com/houndci/hound](https://github.com/houndci/hound). 14k lines. *Automated code review for GitHub PRs.*
  - [github.com/chicago-tool-library/circulate](https://github.com/chicago-tool-library/circulate). 17k lines. *A lending library management system.*
  - [github.com/rubyforgood/pet-rescue](https://github.com/rubyforgood/pet-rescue). 19k lines. *Connects adopters/fosters with pets.*
  - [github.com/ifmeorg/ifme](https://github.com/ifmeorg/ifme). 21k lines. *Mental health communication web app to share experiences with loved ones.*
  - [github.com/openSUSE/osem](https://github.com/openSUSE/osem). 25k lines. *Event management tool tailored to Free and Open Source Software conferences.*
  - [github.com/feedbin/feedbin](https://github.com/feedbin/feedbin). 25k lines. *RSS reader.*
  - [github.com/rubygems/rubygems.org](https://github.com/rubygems/rubygems.org). 26k lines. *Where Ruby gems are hosted.*
  - [github.com/huginn/huginn](https://github.com/huginn/huginn). 36k lines. *Web task automation.*
  - [github.com/AlchemyCMS/alchemy_cms](https://github.com/AlchemyCMS/alchemy_cms). 36k lines. *CMS (Content Management System).*
  - [github.com/rubyforgood/casa](https://github.com/rubyforgood/casa). 37k lines. *Volunteer management system for the nonprofit CASA.*
  - [github.com/rubyforgood/human-essentials](https://github.com/rubyforgood/human-essentials). 39k lines. *An inventory management system for essentials supply banks.*
  - [github.com/SumOfUs/Champaign](https://github.com/SumOfUs/Champaign). 39k lines. *Digital campaigning platform. A Rails app generator.*
- **Larger codebases:** More than 50k lines of Ruby code.
  - [github.com/WikiEducationFoundation/WikiEduDashboard](https://github.com/WikiEducationFoundation/WikiEduDashboard). 50k lines. *Wikipedia course dashboard system. Has a React front end.*
  - [github.com/chatwoot/chatwoot](https://github.com/chatwoot/chatwoot). 56k lines. *Customer engagement suite. Has a Vue.js front end.*
  - [github.com/solidusio/solidus](https://github.com/solidusio/solidus). 72k lines. *E-commerce platform.*
  - [github.com/mastodon/mastodon](https://github.com/mastodon/mastodon). 75k lines. *Like Twitter but self-hosted and federated.*
  - [github.com/openfoodfoundation/openfoodnetwork](https://github.com/openfoodfoundation/openfoodnetwork). 102k lines. *An online marketplace for local food.*
  - [github.com/forem/forem](https://github.com/forem/forem). 103k lines. *Powers the blogging site [dev.to](https://dev.to/). Uses Preact on the front end.*
  - [github.com/redmine/redmine](https://github.com/redmine/redmine). 117k lines. *Project management app.*
  - [github.com/alphagov/whitehall](https://github.com/alphagov/whitehall). 117k lines. *Publishes government content on [gov.uk](https://www.gov.uk/).*
  - [github.com/zammad/zammad](https://github.com/zammad/zammad). 250k lines. *Helpdesk/customer support system.*
  - [github.com/decidim/decidim](https://github.com/decidim/decidim). 288k lines. *The participatory democracy framework.*
  - [github.com/discourse/discourse](https://github.com/discourse/discourse). 322k lines. *Discussion forum platform. Has an Ember.js front end.*
  - [github.com/opf/openproject](https://github.com/opf/openproject). 368k lines. *Project management software.*
  - [github.com/instructure/canvas-lms](https://github.com/instructure/canvas-lms). 745k lines. *A popular LMS (learning management system).*
  - [gitlab.com/gitlab-org/gitlab](https://gitlab.com/gitlab-org/gitlab). 1.8 million lines. *Like GitHub but with CI/CD and DevOps features built in. Uses Vue.js on the front end. Has great [docs on architecture](https://docs.gitlab.com/ee/development/architecture.html).* <!-- https://letslearnruby.com/images/gitlab.png -->
