<!-- omit in toc -->
# Learn Ruby: a resource list

Hi! This road map has helped me as a second-career developer who didn't do a bootcamp. I hope it helps you too.

Notice a broken link? [Open an issue!](https://github.com/fpsvogel/learn-ruby/issues/new)

<!-- omit in toc -->
## Table of contents

- [Preliminaries](#preliminaries)
- [Basics](#basics)
  - [Front-end basics](#front-end-basics)
  - [Ruby basics](#ruby-basics)
  - [Rails basics](#rails-basics)
  - [Getting hired](#getting-hired)
- [Foundations](#foundations)
  - [SQL and databases](#sql-and-databases)
  - [Git](#git)
- [Front end](#front-end)
  - [CSS](#css)
  - [JavaScript](#javascript)
  - [Usability](#usability)
  - [Accessibility](#accessibility)
  - [Web standards](#web-standards)
  - [Hotwire](#hotwire)
- [Advanced Ruby and Rails](#advanced-ruby-and-rails)
  - [Advanced Ruby](#advanced-ruby)
  - [Advanced Rails](#advanced-rails)
- [Beyond web development](#beyond-web-development)
- [Ruby media](#ruby-media)
  - [Chat / social media](#chat--social-media)
  - [Blogs and newsletters](#blogs-and-newsletters)
  - [Podcasts](#podcasts)
  - ["Let's build" screencasts](#lets-build-screencasts)
  - [Topical screencasts](#topical-screencasts)
- [Rails codebases to study](#rails-codebases-to-study)

## Preliminaries

- **If you want to keep it simple** and use just *one* resource that can take you from zero to hireable, I suggest the free [Odin Project](https://www.theodinproject.com/paths). If you want more variety and more depth on certain topics, keep reading!
- **Why did I chose Ruby?** At first I went for full-stack JS, but the JS ecosystem was confusing to me as a solo learner. Ruby was a lot more straightforward enjoyable.
- **Make sure your day job is conducive to part-time studying** if you're a working adult looking to switch careers. I used to be a teacher and spent many of my evenings and weekends grading assignments, which would have made it difficult to learn programming. So I switched to a remote customer support job to free up my schedule.
- **Take care of yourself!** Exercise and get plenty of sleep, and you'll better retain what you learn. If you develop wrist pain from heavy computer use, get an ergonomic keyboard, [do daily wrist stretches](https://youtube.com/watch?v=fdD7CgN5FGg), and try a break app such as [Stretchly](https://hovancik.net/stretchly).

Resources below marked with a dollar sign (💲) cost money. You may be able to find books for free (from your local library, interlibrary loan, or more dubious sources) but buy them if/when you can, to support the authors.

## Basics

### Front-end basics

- [x] Learn some HTML, CSS, and JS: [The Odin Project - Foundations path](https://www.theodinproject.com/paths/foundations/courses/foundations) or [MDN - Learn web development](https://developer.mozilla.org/en-US/docs/Learn_web_development) or [web.dev - Learn web development](https://web.dev/learn/). <!-- https://avatars.githubusercontent.com/u/4441966?s=400 -->
- [x] Build a blog from scratch. [GitHub Pages](https://pages.github.com) is an accessible way to do this. (Choose the option "Project site", then "Start from scratch".) <!-- https://letslearnruby.com/images/html-blog.png -->

### Ruby basics

- **Basics:**
  - [x] [The Odin Project - Ruby](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/ruby) <!-- https://avatars.githubusercontent.com/u/4441966?s=400 -->
  - [x] [GoRails - Ruby for Beginners](https://gorails.com/series/ruby-for-beginners) if you prefer videos. <!-- https://letslearnruby.com/images/gorails.jpg -->
  - [x] [Try Ruby](https://try.ruby-lang.org/) and [BigBinary Academy](https://academy.bigbinary.com/learn-ruby), if you like an interactive approach. <!-- https://www.globalnerdy.com/wordpress/wp-content/uploads/2009/08/chunky_bacon.jpg -->
  - [ ] [Eloquent Ruby, 2nd ed.](https://www.linkedin.com/posts/russolsen_im-thrilled-to-announce-that-brandon-weaver-activity-7310320740807888897-_w2f/?rcm=ACoAACJ6fHUBRp5BOTO2HiDVkkL1scMPO998sVA) (WIP)
  - [ ] [Ruby Alchemy](https://alchemists.io/books/ruby_alchemy) (WIP)
- **Guided practice:**
  - [x] [Exercism - Ruby](https://exercism.org/tracks/ruby) <!-- https://avatars.githubusercontent.com/u/5624255?s=400 -->
  - [x] [Advent of Code](https://adventofcode.com) with other people's Ruby solutions to compare yours to. One way to do this is [my Advent of Ruby gem](https://github.com/fpsvogel/advent_of_ruby). <!-- https://letslearnruby.com/images/aoc.png -->
- **OOP (object-oriented programming):**
  - [x] 💲[Sandi Metz - Practical Object-Oriented Design](https://www.poodr.com) <!-- https://images.squarespace-cdn.com/content/v1/5527cdbae4b0ee7b897c2111/1530279450483-K5BJ5TZGMYSWYA3QQA63/POODR_2e_cover_low_res.jpg -->
  - [x] 💲[Sandi Metz & Katrina Owen - 99 Bottles of OOP](https://sandimetz.com/99bottles-sample-ruby) <!-- https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1477514056i/31183020.jpg -->
- **Build stuff with Ruby.** Here are some ideas:
  - A CLI (command-line interface) app. I made [one that gives statistics on a reading log](https://fpsvogel.com/posts/2021/my-first-ruby-app-lessons-learned). <!-- https://miro.medium.com/v2/resize:fit:774/1*PGxvXulYR1Zp3TPx7FjMsQ.png -->
  - A game. A text-based game is the most straightforward option, but [there are Ruby game engines](#beyond-web-development) for graphical games. <!-- https://letslearnruby.com/images/game.svg -->
  - A static site with [Bridgetown](https://github.com/bridgetownrb/bridgetown), which is simpler than building a web app with Rails. Maybe rebuild your blog? Be sure to [join the Bridgetown Discord server](https://discord.gg/Cugms94QFM). <!-- https://www.bridgetownrb.com/images/bridgetown-avatar.png -->
- **Reference:**
  - [x] [Ruby API](https://rubyapi.org). Since its search uses a query param, you can [add a search keyword to your browser](https://nedbatchelder.com/blog/202205/custom_search_keywords.html) so that you can quickly search from the address bar, for example `rb partition` would take you to [https://rubyapi.org/3.4/o/s?q=partition](https://rubyapi.org/3.4/o/s?q=partition) <!-- https://upload.wikimedia.org/wikipedia/commons/7/73/Ruby_logo.svg -->

### Rails basics

Only books and courses are listed below, but be sure to *build things* as you learn. I found it most helpful to build a bunch of little throwaway apps ([1](https://fpsvogel.com/posts/2021/gpt3-ai-story-writer), [2](https://fpsvogel.com/posts/2021/wiki-stumble-wikipedia-explorer), [3](https://fpsvogel.com/posts/2021/pass-the-story-collaborative-writing-game), [4](https://fpsvogel.com/posts/2022/doctor-lookup-health-provider-search-tool)).

- **Basics:**
  - [x] [Getting started with Rails](https://rails-tutorial.evilmartians.io/), an interactive quick start. <!-- https://avatars.githubusercontent.com/u/46581?s=400 -->
  - [x] [typecraft - Rails New](https://www.youtube.com/playlist?list=PLHFP2OPUpCeZcPutT9yn4-e0bMmrn5Gd1) and/or [GoRails - Build a Blog with Rails 7](https://gorails.com/series/build-a-blog-with-rails-7) if you like videos. <!-- https://i.ytimg.com/vi/_lRlOGS8Bgo/hqdefault.jpg -->
  - [x] [The Odin Project - Rails](https://www.theodinproject.com/paths/full-stack-ruby-on-rails) <!-- https://avatars.githubusercontent.com/u/4441966?s=400 -->
- **Testing:**
  - [x] [thoughtbot - Testing Rails](https://github.com/thoughtbot/testing-rails) or [the summary blog post](https://thoughtbot.com/blog/how-we-test-rails-applications). (In the book, ignore controller specs because [they have been superseded by request specs](https://stackoverflow.com/a/46500842).) <!-- https://public-files.gumroad.com/g2f7k3fkbdgvubnh1b2cmsdcsenc -->
  - [x] 💲[Effective Testing with RSpec 3](https://pragprog.com/titles/rspec3/effective-testing-with-rspec-3/) <!-- https://pragprog.com/titles/rspec3/effective-testing-with-rspec-3/rspec3.jpg -->
  - [ ] 💲[Everyday Rails Testing with RSpec](https://leanpub.com/everydayrailsrspec)
  - [ ] 💲[Professional Rails Testing: Tools and Principles](https://www.amazon.com/Professional-Rails-Testing-Tools-Principles/dp/B0DJRLK93M)
  <!-- minitest:
  - https://chriskottom.com/minitestcookbook
  - https://testdrivingrails.com
  -->
- **Miscellaneous:**
  - [x] [Beginners Guide to Ruby on Rails Performance](https://henry.bearblog.dev/beginners-guide-to-ruby-on-rails-performance-part-1) <!-- https://bear-images.sfo2.cdn.digitaloceanspaces.com/henry/performance.webp -->
  - [x] [Style guides](https://ruby.style/) for Ruby, Rails, and RSpec <!-- https://avatars.githubusercontent.com/u/10871348?s=400 -->

### Getting hired

- **Get real-world experience to put on your resume:**
  - Contribute to open-source projects. I've written [a short guide on how to get started](https://fpsvogel.com/posts/2021/how-to-contribute-to-open-source-ruby-rails). <!-- https://imgs.xkcd.com/comics/dependency_2x.png -->
  - [Ruby Central - Scholars and Guides Program](https://rubycentral.org/scholars_guides_program/) <!-- https://rubycentral.org/content/images/size/w256h256/format/png/2022/11/Ruby-Central-logo.svg -->
- **Mentorship:**
  - [First Ruby Friend](https://firstrubyfriend.org) where aspiring and first-year developers are connected with a mentor. <!-- https://firstrubyfriend.org/images/ruby-plus-one.svg -->
  - [r/rails](https://www.reddit.com/r/rails). Examples: [1](https://www.reddit.com/r/rails/comments/rvs7f2/rails_mentoring/), [2](https://www.reddit.com/r/rails/comments/lvwn41/finding_a_mentor/). <!-- https://letslearnruby.com/images/reddit.svg -->
- **The job search:**
  - [RubyOnRemote](https://rubyonremote.com) <!-- https://styles.redditmedia.com/t5_7xqhrm/styles/communityIcon_pjfyocxjx1ja1.png -->
  - [Welcome to the Jungle](https://www.welcometothejungle.com) <!-- https://letslearnruby.com/images/welcome-to-the-jungle.jpg -->
  <!-- Of unverified usefulness:
  - https://railshotwirejobs.com
  - https://weworkremotely.com/remote-jobs/search?term=ruby
  - https://remoteok.com/remote-ruby-jobs?order_by=date
  - for behavioral and system interview prep: https://www.hellointerview.com
  -->

## Foundations

In addition to the topics below, it's also good to know the basic workings of the Internet and the Web. Resources for that are listed in [my "Learn Computer Science" list](https://github.com/fpsvogel/learn-cs#networking--the-web).

### SQL and databases

<!-- - [ ] [SQL Noir](https://www.sqlnoir.com/) (WIP, only 6 cases so far) -->
- [x] [SQL Teaching](https://www.sqlteaching.com) <!-- https://www.sqlteaching.com/database.png -->
- [x] [SQLBolt](https://sqlbolt.com) <!-- https://letslearnruby.com/images/sql-bolt.png -->
- [x] [Select Star SQL](https://selectstarsql.com) <!-- https://selectstarsql.com/imgs/favicon-256.png -->
- [x] [SQL Practice](https://www.sql-practice.com/) <!-- https://cdn-icons-png.flaticon.com/512/4299/4299956.png -->
- [x] [PostgreSQL Exercises](https://pgexercises.com/) <!-- https://opengraph.githubassets.com/5dc8f962a8ff3a00a68a35d74a38b117b653d05e8891b85360df152f6755b4b9/AlisdairO/pgexercises -->
- [x] [Next-Level Database Techniques for Developers](https://sqlfordevs.com/ebook) <!-- https://sqlfordevs.com/build/assets/ebook-BaM0l9I6.png -->
- [x] [Use the Index, Luke!](https://use-the-index-luke.com/sql/preface) <!-- https://use-the-index-luke.com/static/util_squirrel.og.fMeqdSQq.png -->
<!-- - [ ] [Advent of SQL](https://adventofsql.com/) (extra practice doesn't feel necessary at this point) <!-- https://letslearnruby.com/images/aoc.png -->

### Git

- [x] [Oh My Git!](https://ohmygit.org/) or [Learn Git Branching](https://learngitbranching.js.org/) <!-- https://ohmygit.org/assets/images/oh-my-git.png -->
- [x] [Oh Shit, Git!?!](https://ohshitgit.com/) or for more detail, [Git Flight Rules](https://github.com/k88hudson/git-flight-rules) <!-- https://upload.wikimedia.org/wikipedia/commons/5/50/Fxemoji_u2049.svg -->
- [x] [Git Katas](https://github.com/eficode-academy/git-katas)
- [x] [The Git Parable](https://youtube.com/watch?v=ANNboouhNHE) <!-- https://i.ytimg.com/vi/jm7QsI-nNjk/hqdefault.jpg -->
<!-- - **Git internals:**
  - [ ] [thoughtbot - Rebuilding Git in Ruby](https://thoughtbot.com/blog/rebuilding-git-in-ruby)
  - [ ] 💲[Building Git](https://shop.jcoglan.com/building-git)
  - [ ] ["Git Internals" chapter of Pro Git](https://git-scm.com/book/en/v2/Git-Internals-Plumbing-and-Porcelain) <!-- https://m.media-amazon.com/images/I/417jkTBWA3L._SX342_SY445_PQ78_.jpg -->

## Front end

### CSS

- [x] [CSS Nouveau](https://www.spicyweb.dev/css-nouveau/1-vanilla-has-never-tasted-so-hot/) <!-- https://letslearnruby.com/images/spicy-web.png -->
- [ ] 💲[Every Layout](https://every-layout.dev/)

### JavaScript

- **Basics:**
  - [x] [Exploring JavaScript](https://exploringjs.com/js/) or [MDN - JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) <!-- https://exploringjs.com/js/img/cover-homepage.jpg -->
  - [x] [Modern JavaScript Explained For Dinosaurs](https://peterxjang.com/blog/modern-javascript-explained-for-dinosaurs.html) plus [import maps](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script/type/importmap) <!-- https://peterxjang.com/img/1__H8PH__HaV43gZyBJz0mJHxA.png -->
  - [x] [What the heck is the event loop anyway?](https://youtube.com/watch?v=8aGhZQkoFbQ) <!-- https://i.ytimg.com/vi/8aGhZQkoFbQ/maxresdefault.jpg -->
  - [x] [The Modern JavaScript Tutorial - Browser: Document, Events, Interfaces](https://javascript.info/ui) <!-- https://javascript.info/img/site_preview_en_512x512.png -->
- **Web components:**
  - [ ] [Web Components at Work](https://thomaswilburn.github.io/wc-book/)
  - [x] [MDN - Web Components](https://developer.mozilla.org/en-US/docs/Web/API/Web_components) <!-- https://upload.wikimedia.org/wikipedia/commons/9/98/MDN_Web_Docs.svg -->
  - [ ] [Web Components: Working With Shadow DOM](https://www.smashingmagazine.com/2025/07/web-components-working-with-shadow-dom/) and [web.dev - Declarative Shadow DOM](https://web.dev/articles/declarative-shadow-dom)
  - [ ] [Heartml Reciprocate](https://thathtml.blog/2025/09/reciprocate-reactivity-for-html-web-components/)
  - [ ] [Lit docs](https://lit.dev/docs/)
  - [ ] [Lit - Learn](https://lit.dev/learn/)
  - [ ] [Open Web Components (Lit) - Codelabs](https://open-wc.org/guides/developing-components/codelabs/) and [Code Examples](https://open-wc.org/guides/developing-components/code-examples/)
  - [ ] [Google - From Web Component to Lit Element](https://codelabs.developers.google.com/codelabs/the-lit-path) and [Lit for React Developers](https://codelabs.developers.google.com/codelabs/lit-2-for-react-devs)
  - [ ] Explore source code of [QuietUI](https://quietui.org/), [Web Awesome](https://webawesome.com/)
- **Build your own front-end framework:**
  - [ ] General: [Let's learn how modern JavaScript frameworks work by building one](https://nolanlawson.com/2023/12/02/lets-learn-how-modern-javascript-frameworks-work-by-building-one/), [Frontend framework](https://mfrachet.github.io/create-frontend-framework/), 💲[Build a Frontend Web Framework](https://www.manning.com/books/build-a-frontend-web-framework-from-scratch)
  - [ ] React: [Implementing React From Scratch](https://www.rob.directory/blog/react-from-scratch), [Build your own React](https://pomb.us/build-your-own-react/), [Creating Our Own React From Scratch](https://itnext.io/creating-our-own-react-from-scratch-82dd6356676d), [Let's build a React from scratch](https://geekpaul.medium.com/lets-build-a-react-from-scratch-part-1-virtualdom-and-renderer-14f4f716de62)
  - [ ] Other frameworks: [Building AlpineJS](https://laracasts.com/series/building-alpinejs), [Create Your Own Vue.js From Scratch](https://dev.to/themarcba/coding-a-vue-js-like-framework-from-scratch-part-1-introduction-3nbf), [A Hands-on Introduction to Fine-Grained Reactivity](https://dev.to/ryansolid/a-hands-on-introduction-to-fine-grained-reactivity-3ndf) and [SolidJS: Reactivity to Rendering](https://angular.love/solidjs-reactivity-to-rendering), [Compile Svelte 5 in your head](https://lihautan.com/compile-svelte-5-in-your-head)
  <!-- maybe:
    <!-- -	incomplete: [Effectual JS](https://dttw.tech/posts/WPLtwgai6)
    <!-- - incomplete: [how to build your own JS framework](https://mikeguoynes.medium.com/part-1-build-your-own-js-framework-from-scratch-f4e35d0dffa6)
    <!-- - too basic: [Let's Build a Custom JavaScript Framework](https://medium.com/@lfoster49203/lets-build-a-custom-javascript-framework-97a01080d1bb)
    <!-- - too specific?: [Client Side Routing](https://jessedit.netlify.app/blog/client-side-routing), https://www.freecodecamp.org/news/learn-javascript-reactivity-build-signals-from-scratch, https://newsletter.unstacked.dev/p/dev-101-custom-javascript-signals
  -->
- **TypeScript:**
  - [x] [Total TypeScript VS Code extension](https://www.totaltypescript.com/vscode-extension) <!-- https://mattpocock.gallerycdn.vsassets.io/extensions/mattpocock/ts-error-translator/0.10.1/1694612358825/Microsoft.VisualStudio.Services.Icons.Default -->
  - [x] [Total TypeScript essentials](https://www.totaltypescript.com/books/total-typescript-essentials/kickstart-your-typescript-setup) <!-- https://res.cloudinary.com/total-typescript/image/upload/v1676015688/core-volume_2x_wt7jnc.png -->
  - [ ] [The TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
  - [ ] [The Concise TypeScript Book](https://gibbok.github.io/typescript-book/book/the-concise-typescript-book/)
  - [ ] [Execute Program - TypeScript courses](https://www.executeprogram.com/courses/typescript)
  - [ ] [Official docs](https://www.typescriptlang.org/)
  - [ ] [Tackling TypeScript](https://exploringjs.com/tackling-ts/index.html)
  - [ ] [Type Challenges](https://tsch.js.org/)
  - [ ] [TypeHero](https://typehero.dev/)
  - [ ] Type | Treat [2020](https://dev.to/typescript/type-treat-challenge-1-829), [2021](https://devblogs.microsoft.com/typescript/type-treat-2021-day-1/)
  - [ ] [Codeless Code - posts on TypeScript](https://code.lol/tags/typescript/) e.g. [Higher Kindred Types in TypeScript](https://code.lol/post/programming/higher-kinded-types/) and [Point-free Programming via HKTs](https://code.lol/post/programming/hkt-tacit/)
  - [ ] TypeScript libraries: [TS-Pattern](https://github.com/gvergnaud/ts-pattern), [Zod](https://github.com/colinhacks/zod), [type-fest](https://github.com/sindresorhus/type-fest), [Effect](https://effect.website/)
  - [ ] 💲[TypeScript Cookbook](https://typescript-cookbook.com/)
  - [ ] 💲[Effective TypeScript](https://effectivetypescript.com/)
  - [ ] [Google TypeScript Style Guide](https://google.github.io/styleguide/tsguide.html) and [TypeScript Style Guide](https://mkosir.github.io/typescript-style-guide/)
- **New web APIs:**
  - [View Transitions](https://developer.mozilla.org/en-US/docs/Web/API/View_Transition_API) <!-- https://upload.wikimedia.org/wikipedia/commons/9/98/MDN_Web_Docs.svg -->
  - [Speculation Rules](https://developer.mozilla.org/en-US/docs/Web/API/Speculation_Rules_API) <!-- https://upload.wikimedia.org/wikipedia/commons/9/98/MDN_Web_Docs.svg -->
  - [command and commandfor](https://developer.chrome.com/blog/command-and-commandfor) <!-- https://upload.wikimedia.org/wikipedia/commons/e/e1/Google_Chrome_icon_%28February_2022%29.svg -->
  - [Popover](https://developer.mozilla.org/en-US/docs/Web/API/Popover_API) <!-- https://upload.wikimedia.org/wikipedia/commons/9/98/MDN_Web_Docs.svg -->
  - [IntersecionObserver](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API) <!-- https://upload.wikimedia.org/wikipedia/commons/9/98/MDN_Web_Docs.svg -->

<!-- TypeScript curiosities:
  - https://www.learningtypescript.com/articles/extreme-explorations-of-typescripts-type-system
  - https://mattrickard.com/typescript-type-system-hacks
-->

### Usability

- [ ] [Vercel - Web Interface Guidelines](https://vercel.com/design/guidelines)
- [ ] [Laws of UX](https://lawsofux.com/articles/)
- [x] 💲[Don't Make Me Think](https://sensible.com/dont-make-me-think/) <!-- https://m.media-amazon.com/images/I/51sdCuqMwWL._AC_UF1000,1000_QL80_.jpg -->
- [x] 💲[The Design of Everyday Things](https://www.nngroup.com/books/design-everyday-things-revised/) <!-- https://m.media-amazon.com/images/I/416Hql52NCL.jpg -->
- [x] [Victor Ponamariov - 100 UI/UX Tips](https://vpon.me/hundred) <!-- https://optim.tildacdn.one/tild6639-3864-4563-a666-623739336438/-/resize/640x/-/format/webp/Group_18_Copy.png.webp -->
- [ ] 💲[User Interface Design: A Software Engineering Perspective](https://www.amazon.com/dp/0321181433)

### Accessibility

- [ ] [Accessibility Developer Guide](https://www.accessibility-developer-guide.com/)
- [ ] [MDN - Accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility) or [web.dev - Learn Accessibility](https://web.dev/learn/accessibility/)
- [ ] [Responsible Web Applications](https://responsibleweb.app/)
- [ ] 💲[Inclusive Components](https://book.inclusive-components.design/)
- [ ] [RailsConf talks on accessibility](https://www.youtube.com/results?search_query=railsconf+accessibility)
- [ ] Examples of accessible components: [Deque University Code Library](https://dequeuniversity.com/library/), [Scott O'Hara's Accessible Components](https://github.com/scottaohara/accessible_components)

### Web standards

References for when you want to stick to native Web technologies and patterns.

- [Plain Vanilla](https://plainvanillaweb.com/index.html) <!-- https://letslearnruby.com/images/plain-vanilla.png -->
- [Under-Engineered Patterns](https://adrianroselli.com/2023/05/under-engineered-patterns-for-wcbuf.html) <!-- https://adrianroselli.com/wp-content/uploads/2022/08/cthulhu-selfie-300x300.jpg -->
- [Stephanie Eckles - SmolCSS](https://smolcss.dev/) <!-- https://smolcss.dev/smolcss.png -->
- [Stephanie Eckles - Modern CSS Solutions](https://moderncss.dev/) <!-- https://moderncss.dev/img/social/home.jpeg -->

### Hotwire

- **News:**
  - [Hotwire Weekly](https://www.hotwireweekly.com) <!-- https://assets.buttondown.email/images/1bdac043-d137-4e4f-86ef-4df5c3b34029.png -->
- **Basics:**
  - [ ] 💲[Master Hotwire](https://masterhotwire.com/) <!-- https://letslearnruby.com/images/master-hotwire.png -->
  - [ ] [30 days of Hotwire tips](https://twitter.com/ilrock__/status/1631315562390519809)
  - [ ] [Hotwire Cheatsheet](https://cheatsheetshero.com/user/igor-kasyanchuk/930-hotwire-for-ruby-on-rails-developers-cheatsheet?ref=shortruby.com#page-3609)
  - [ ] [Turbo 8 Cheatsheet](https://radanskoric.com/cheatsheet/)
  - [ ] 💲[Hotwire Native for Rails Developers](https://pragprog.com/titles/jmnative/hotwire-native-for-rails-developers/) <!-- https://pragprog.com/titles/jmnative/hotwire-native-for-rails-developers/jmnative-500.jpg -->
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
  - [ ] Jesse Storimer - articles: [Threads, Not Just for Optimizations](https://web.archive.org/web/20171112112011/https://www.jstorimer.com/blogs/workingwithcode/7766063-threads-not-just-for-optimizations), [Matz is not a threading guy](https://web.archive.org/web/20180324184633/https://www.jstorimer.com/blogs/workingwithcode/7766069-matz-is-not-a-threading-guy), Nobody Understands the GIL (parts [1](https://web.archive.org/web/20170801134641/https://www.jstorimer.com/blogs/workingwithcode/8085491-nobody-understands-the-gil), [2](https://web.archive.org/web/20161024030142/http://www.jstorimer.com/blogs/workingwithcode/8100871-nobody-understands-the-gil-part-2-implementation), [3](https://web.archive.org/web/20160506090126/http://www.jstorimer.com/blogs/workingwithcode/8158971-nobody-understands-the-gil-part-3-thread-safety))
  - [ ] [Prateek Codes - series on concurrency and parallelism](https://www.prateekcodes.dev/ruby-threads-explained-simple-guide-part-1)
  - [ ] [JP Camara - series on concurrency, parallelism and asynchronous programming in Ruby](https://jpcamara.com/2024/06/04/your-ruby-programs.html)
  - [ ] [Ruby, Ractors, and Lock-Free Data Structures](https://iliabylich.github.io/ruby-ractors-and-lock-free-data-structures/intro.html)
  - [ ] Articles on threads and processes in Ruby: [1](https://mensfeld.pl/2024/02/the-art-of-forking-unlocking-scalability-in-ruby/), [2](https://thecodest.co/blog/forking-and-threading-in-ruby/), [3](https://www.toptal.com/ruby/ruby-concurrency-and-parallelism-a-practical-primer), [4](https://www.sitepoint.com/forking-ipc-ruby-part/), [5](https://thoughtbot.com/blog/untangling-ruby-threads)
  - [ ] [parallel gem](https://github.com/grosser/parallel)
  - [ ] [concurrent-ruby gem](https://github.com/ruby-concurrency/concurrent-ruby)
- **Ruby internals:**
  - [ ] 💲[Ruby Under a Microscope](https://patshaughnessy.net/2025/1/28/updating-ruby-under-a-microscope) (WIP)
  - [ ] [A Rubyist's Walk Along the C-side](https://blog.peterzhu.ca/ruby-c-ext/)
<!-- - **Miscellaneous:** -->
  <!-- - [x] [Avdi Grimm - Confident Ruby](https://pragprog.com/titles/agcr/confident-ruby/) <!-- https://pragprog.com/titles/agcr/confident-ruby/agcr_hucf967c33f389130ab619766a81118218_436632_375x0_resize_q75_box.jpg -->
  <!-- - [ ] Property-based testing with [PropCheck](https://github.com/Qqwy/ruby-prop_check) and [PBT](https://github.com/ohbarye/pbt) -->

### Advanced Rails

- **Reference:**
  - [ ] 💲[The Rails 8 Way](https://leanpub.com/therails8way)
  - [ ] [Rails Guides](https://guides.rubyonrails.org/)
  - [ ] [Rails API docs](https://api.rubyonrails.org/)
- **Rails internals:**
  - [ ] [The Rails Companion](https://books.writesoftwarewell.com/8/rails-companion)
  - [x] 💲[Noah Gibbs - Rebuilding Rails](https://noahgibbs.gumroad.com/l/rebuilding_rails) <!-- https://public-files.gumroad.com/84806cmcnanyrmtnxfxvruodap1n -->
- **Architecture:**
  - [x] 💲[Layered Design for Ruby on Rails Applications](https://www.packtpub.com/product/layered-design-for-ruby-on-rails-applications/9781801813785) <!-- https://m.media-amazon.com/images/I/41MAUvi--4L.jpg -->
  - [ ] 💲[Maintainable Rails](https://leanpub.com/maintain-rails)
  - [ ] 💲[Gradual Modularization for Ruby and Rails](https://leanpub.com/package-based-rails-applications) and [Gusto engineering blog posts on modularity](https://engineering.gusto.com/all?topic=modularization)
- **Background jobs:**
  - [x] [Sidekiq wiki](https://github.com/sidekiq/sidekiq/wiki)
  - [x] [How does Sidekiq work?](https://www.mikeperham.com/how-sidekiq-works) <!-- https://avatars.githubusercontent.com/u/124714131?s=400 -->
  - [x] 💲[Nate Berkopec - Sidekiq in Practice](https://nateberk.gumroad.com/l/sidekiqinpractice) <!-- https://public-files.gumroad.com/3x0fwqyo139zgcyn5bwcdsi9jas0 -->
- **Performance:**
  - [ ] [BigBinary - Scaling Rails series](https://www.bigbinary.com/blog/scaling-rails-series)
  - [ ] [RorVsWild blog](https://www.rorvswild.com/blog/) is largely about performance
  - [ ] 💲[Nate Berkopec - The Complete Guide to Rails Performance](https://www.railsspeed.com/)
  - [ ] 💲[Nate Berkopec - The Ruby on Rails Performance Apocrypha](https://www.speedshop.co/2021/01/14/announcing-apocrypha.html)
  - [ ] [Mature Optimization Handbook](https://carlos.bueno.org/optimization/) (not Rails-specific)
  - [ ] 💲[Rails Scales!](https://pragprog.com/titles/cprpo/rails-scales/)
- **PostgreSQL:**
  - [ ] [Postgres Playground](https://www.crunchydata.com/developers/tutorials)
  - [ ] [Yeah, Postgres can do that](https://dev.to/efertsch/series/20415)
  - [ ] 💲[High Performance PostgreSQL for Rails](https://pragprog.com/titles/aapsql/high-performance-postgresql-for-rails/)
  - [ ] Blog posts on Rails + Postgres: [lots on Paweł Urbanek's blog](https://pawelurbanek.com/blog), [this one at Honeybadger](https://www.honeybadger.io/blog/rails-postgresql-queries/), [this one at thoughtbot](https://thoughtbot.com/blog/advanced-postgres-performance-tips).
  - [ ] 💲[The Art of PostgreSQL](https://theartofpostgresql.com/)
  - [ ] 💲[PostgreSQL Query Optimization: The Ultimate Guide to Building Efficient Queries](https://link.springer.com/book/10.1007/978-1-4842-6885-8)
  - [ ] [PostgreSQL docs](https://www.postgresql.org/docs/current/)
- **SQLite:**
  - [ ] 💲[SQLite on Rails](https://fractaledmind.gumroad.com/l/sqlite-on-rails)
- **Deployment:**
  - [ ] 💲[Josef Strzibny - Deployment from Scratch](https://deploymentfromscratch.com/)
  - [ ] 💲[Julia Evans - How Containers Work](https://wizardzines.com/zines/containers/)
  - [ ] [Ruby on Whales: Dockerizing Ruby and Rails development](https://evilmartians.com/chronicles/ruby-on-whales-docker-for-ruby-rails-development)
  - [ ] 💲[The Docker Book](https://dockerbook.com/)
  - [ ] [Using Kamal 2.0 in Production](https://rubys.github.io/kamal-in-production/)
  - [ ] 💲[Josef Strzibny - Kamal Handbook](https://kamalmanual.com/handbook/)
- **Miscellaneous:**
  - [ ] [Perfecting Your Rails Forms](https://alexbarret.com/blog/2024/perfecting-your-rails-form-part-1/)
  - [ ] 💲[Frictionless Generators](https://garrettdimon.com/products/frictionless-generators)

## Beyond web development

- **Ruby that is not web development:**
  - 💲[DragonRuby Game Toolkit](https://dragonruby.itch.io/dragonruby-gtk) for game development. See [their Discord](https://discord.dragonruby.org/) and [community site](https://www.dragonriders.community/). Other Ruby game libraries: [Gosu](https://www.libgosu.org/), [Raylib Ruby](https://www.raylib-ruby.com/), [MiniGL](https://github.com/victords/minigl), [Ruby 2D](https://www.ruby2d.com/), [Taylor](https://www.taylormadetech.dev), [TIC-80](https://tic80.com/) <!-- https://img.itch.zone/aW1nLzIzNjU2MzQucG5n/original/WFWBHQ.png -->
  <!-- Keep an eye on https://github.com/hadashiA/MRubyCS because it could enable Ruby scripting in any game engine that supports C#, though there may be a wrinkle: https://news.ycombinator.com/item?id=43467382 -->
  - [Gamefic](https://gamefic.com/) for building text-based games and interactive fiction. See [Getting Started](https://gamefic.com/guides/getting-started) and [examples](https://github.com/castwide/gamefic-sdk/tree/master/examples). <!-- https://gamefic.com/assets/goony-6ea3e43a0283cf3bacced44d7f9e0486f27e845415b64350481592e2c1939abf.png -->
  <!-- Older text-based game libraries:
  <!--     https://github.com/jaywengrow/tuvi
  <!--     https://github.com/MikeTaylor/scottkit
  <!--     + https://github.com/MikeTaylor/scottkit/blob/master/docs/tutorial.md -->
  - [SC2AI](https://sc2ai.pages.dev/) for StarCraft II botting <!-- https://gitlab.com/uploads/-/system/project/avatar/60342720/logo.png?width=400 -->
  - [Sonic Pi](https://sonic-pi.net/) for live music coding <!-- https://avatars.githubusercontent.com/u/67760337 -->
  - [Ronin](https://ronin-rb.dev/) for security development <!-- https://ronin-rb.dev/images/logo.svg -->
  - Scripting and text processing: [Ruby One-Liners Guide](https://learnbyexample.github.io/learn_ruby_oneliners/), [Ruby Regexp](https://learnbyexample.github.io/Ruby_Regexp), 💲[Text Processing with Ruby](https://pragprog.com/titles/rmtpruby/text-processing-with-ruby) <!-- https://learnbyexample.github.io/learn_ruby_oneliners/images/ruby_oneliners.png -->
- **Mentoring:**
  - [x] [Exercism](https://exercism.org/mentoring) <!-- https://avatars.githubusercontent.com/u/5624255?s=400 -->
  - [ ] [First Ruby Friend](https://firstrubyfriend.org/mentors)
- **Software systems:**
  - [ ] 💲[Release It!](https://pragprog.com/titles/mnee2/release-it-second-edition/)
  - [ ] 💲[Foundations of Scalable Systems](https://www.oreilly.com/library/view/foundations-of-scalable/9781098106058/)
  - [ ] 💲[Designing Data-Intensive Applications, 2nd ed.](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781098119058/)
  - [ ] [Google SRE book](https://sre.google/sre-book/table-of-contents/) and [workbook](https://sre.google/workbook/table-of-contents/). Related: 💲[Establishing SRE Foundations](https://www.amazon.com/Establishing-Foundations-Step-Step-Organizations/dp/0137424604), 💲[Real-World SRE](https://www.packtpub.com/en-us/product/real-world-sre-9781788628884), 💲[Brendan Gregg's books](https://www.brendangregg.com/books.html)
  - [ ] [Quastor newsletter](https://blog.quastor.org/). See also [archives](https://blog.quastor.org/archive), [older archives](https://drive.google.com/file/d/1U7EchvgzCjTtF5JzGVVCFgjXC-qw7lIG), [case studies archive](https://quastor.substack.com/archive)
- **Computer science:**
  - [Learn Computer Science](https://github.com/fpsvogel/learn-cs), my other list.
- **Linux / command line:**
  - [ ] [The Command Line Murders](https://github.com/veltman/clmystery)
  - [ ] [Linux Journey](https://linuxjourney.com/)
  - [ ] [Sundeep Agarwal - Linux Command Line Computing](https://learnbyexample.github.io/cli-computing/)
  - [ ] [The Linux Command Line](https://linuxcommand.org/tlcl.php)
  - [ ] [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
  - [ ] [Sundeep Agarwal - "Linux CLI and shell scripting" list](https://learnbyexample.github.io/curated_resources/linux_cli_scripting.html)
  - [ ] [Julia Evans - Your Linux Toolbox](https://jvns.ca/blog/2019/10/21/print-collection-of-my-first-7-zines/)
  - [ ] 💲[Efficient Linux at the Command Line](https://www.oreilly.com/library/view/efficient-linux-at/9781098113391)
  - [ ] 💲[How Linux Works](https://nostarch.com/howlinuxworks3)
  - [ ] 💲[Julia Evans - Bite Size zine pack](https://wizardzines.com/zines/bite-size-pack/)
  - [ ] 💲[Wicked Cool Shell Scripts](https://nostarch.com/wcss2)

## Ruby media

### Chat / social media

- [r/ruby](https://www.reddit.com/r/ruby) and [r/rails](https://www.reddit.com/r/rails) <!-- https://letslearnruby.com/images/reddit.svg -->
- [Ruby (Discord)](https://discord.com/invite/ruby-518658712081268738) <!-- https://cdn.prod.website-files.com/6257adef93867e50d84d30e2/636e0a6a49cf127bf92de1e2_icon_clyde_blurple_RGB.png -->
- [Ruby.social (Mastodon)](https://ruby.social) <!-- https://upload.wikimedia.org/wikipedia/commons/d/d5/Mastodon_logotype_%28simple%29_new_hue.svg -->
- [Bluesky starter packs for Ruby developers](https://blueskystarterpack.com/ruby-developers) <!-- https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Bluesky_Logo.svg/543px-Bluesky_Logo.svg.png -->
- [Ruby on Rails Link (Slack)](https://www.rubyonrails.link/) <!-- https://www.rubyonrails.link/assets/railslink-icon-10c1d749590f731efcb92fc4ffb599a6171cfd89e2eb2080b925d247060017db.png -->
- [Lobsters](https://lobste.rs/) is not Ruby-specific, but it's a way to widen your horizons and the discussions are of high quality. It's like Hacker News but smaller and more focused on programming. <!-- https://letslearnruby.com/images/lobsters.png -->

### Blogs and newsletters

- [Awesome Ruby Blogs](https://github.com/Yegorov/awesome-ruby-blogs)

### Podcasts

- [Bike Shed](https://www.bikeshed.fm/) <!-- https://assets.fireside.fm/file/fireside-images/podcasts/images/1/167c01a1-0eb9-4640-b488-c2f6d6866650/cover_small.jpg -->
- [Code and the Coding Coders who Code it](https://podcast.drbragg.dev/) <!-- https://podcast.drbragg.dev/images/podcast.jpeg -->
- [Code with Jason](https://www.codewithjason.com/podcast) <!-- https://www.codewithjason.com/wp-content/uploads/2023/01/jason-300x300.jpeg -->
- [IndieRails](https://www.indierails.com/) <!-- https://letslearnruby.com/images/indie-rails.webp -->
- [Friendly Show](https://www.friendly.show/) <!-- https://storage.buzzsprout.com/zhyzuuam1vptl88kzpj22qnk8naa
- [Maintainable](https://maintainable.fm/) <!-- https://maintainable.fm/images/maintainable-cover-robby-mid.jpg -->
- [On Rails](https://onrails.buzzsprout.com/) <!-- https://storage.buzzsprout.com/78557u6tzo0eqjokvc5skiidkveo -->
- [Remote Ruby](https://www.remoteruby.com/) <!-- https://storage.buzzsprout.com/variants/y355ibk4nfqsqu37yrvz8a6o63z1/b49cbe86cb411762753e730c58953bb88ad958a9d657212c074729b6f04e5463.jpg -->
- [Rooftop Ruby](https://www.rooftopruby.com) <!-- https://storage.buzzsprout.com/variants/4ln9kmgzd7365e01mek8zsnnoyc7/b49cbe86cb411762753e730c58953bb88ad958a9d657212c074729b6f04e5463.jpg -->
- [Ruby on Rails Podcast](https://www.therubyonrailspodcast.com/), especially starting at [episode 372](https://www.therubyonrailspodcast.com/372) went they went independent, brought on co-hosts, and hired an editor. <!-- https://assets.fireside.fm/file/fireside-images/podcasts/images/e/ed4e373f-21b4-44bb-a2f3-630a56c17f71/cover_small.jpg -->
- [Ruby Rogues](https://topenddevs.com/podcasts/ruby-rogues) <!-- https://topenddevs.us-southeast-1.linodeobjects.com/7tb1xhkypftrpf3dwr83ztyccwte -->
- [The Ruby Gems Podcast](https://www.buzzsprout.com/2509083) <!-- https://storage.buzzsprout.com/tn40v00w9sd9tw6gpg2m7un3ml09 -->

### "Let's build" screencasts

These are series using at least Rails 7.

- [CJ Avilla - CreatorPlatform.xyz](https://www.youtube.com/watch?v=uuHtuR2FFS4&list=PLS6F722u-R6IJfBrIRx3a2SBkAL4vUp2p) <!-- https://i.ytimg.com/vi/uuHtuR2FFS4/maxresdefault.jpg -->
- [Conner Jensen - learning management system](https://www.youtube.com/watch?v=HDA9QiHgrsI) <!-- https://i.ytimg.com/vi/HDA9QiHgrsI/maxresdefault.jpg -->
- [Conner Jensen - ecommerce app](https://www.youtube.com/watch?v=HDA9QiHgrsI) <!-- https://i.ytimg.com/vi/hURUMwdCWuI/maxresdefault.jpg -->
- [HigherTheoryDev - Klipshow (streamer dashboard)](https://www.youtube.com/@HigherTheoryDev) <!-- https://yt3.googleusercontent.com/89gOKUS9a8QvQtNspIDjO2S1ORrsUpg7gmgFpKIiZscS102TCHnBRYSvCR1_qvuynoWg1Qhd=s160-c-k-c0x00ffffff-no-rj -->
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
<!-- - [thoughtbot on YouTube](https://www.youtube.com/@thoughtbot/streams) <!-- https://avatars.githubusercontent.com/u/6183?s=400 --> <!-- completely AI-focused for the past ~year -->
- [Code with Jason Meetup](https://www.youtube.com/@codewithjason/videos) <!-- https://i.ytimg.com/vi/mWUpIH6wqaI/hq720.jpg -->
- [Deanin](https://www.youtube.com/@Deanin/videos) <!-- https://i.ytimg.com/vi/YWjA6gR_Lr8/hq720.jpg -->
- 💲[Destroy All Software](https://www.destroyallsoftware.com/screencasts/catalog) <!-- https://letslearnruby.com/images/destroy-all-software.png -->
- 💲[Drifting Ruby](https://www.driftingruby.com) <!-- https://letslearnruby.com/images/drifting-ruby.jpg -->
- 💲[GoRails](https://gorails.com) <!-- https://letslearnruby.com/images/gorails.jpg -->
- [SupeRails](https://www.youtube.com/@SupeRails/videos) <!-- https://i.ytimg.com/vi/csvaYIaBYpw/maxresdefault.jpg -->
- [TenderlovesCoolStuff](https://www.youtube.com/@TenderlovesCoolStuff/streams) <!-- https://avatars.githubusercontent.com/u/3124?s=400 -->
- [Webcrunch](https://www.youtube.com/@Webcrunch/videos) <!-- https://i.ytimg.com/vi/Mc19pB784Us/maxresdefault.jpg -->

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
  - [github.com/nshki/naisho](https://github.com/nshki/naisho). <2k lines. *Send personal data deletion request emails to hundreds of data brokers at once.*
  - [github.com/carsoncole/workypad](https://github.com/carsoncole/workypad). 2k lines. *App for managing job prospecting.*
  - [once.com/writebook](https://once.com/writebook). 3k lines. *App for publishing books to the web.* <!-- https://once.com/assets/images/logo-writebook.png -->
  - [github.com/garyharan/fresh](https://github.com/garyharan/fresh) plus [github.com/garyharan/FreshAppIOS](https://github.com/garyharan/FreshAppIOS) and [github.com/garyharan/FreshAppAndroid](https://github.com/garyharan/FreshAppAndroid). 4k lines. *Dating app using Hotwire Native.*
  - [github.com/ChaelCodes/MeetAnotherDay](https://github.com/ChaelCodes/MeetAnotherDay). 4k lines. *Helps you find and meet up with your friends at conferences.*
  - [github.com/SpinaCMS/Spina](https://github.com/SpinaCMS/Spina). 6k lines. *CMS (Content Management System).*
  - [github.com/eigenfocus/eigenfocus](https://github.com/eigenfocus/eigenfocus/). 5k lines. *Self-hosted project/time management app.*
  - [github.com/basecamp/once-campfire](https://github.com/basecamp/once-campfire). 6k lines. *Self-hosted chat application similar to Slack.*
  - [github.com/codetriage/codetriage](https://github.com/codetriage/codetriage). 6k lines. *Issue tracker for open-source projects.*
  - [github.com/demingfactor/calagator](https://github.com/demingfactor/calagator). 9k lines. *Community calendar platform.*
  - [github.com/rubyevents/rubyevents](https://github.com/rubyevents/rubyevents). 11k lines. *Index of Ruby events and videos.*
  - [github.com/lookbook-hq/lookbook](https://github.com/lookbook-hq/lookbook). 11k lines. *UI development environment for Rails apps.*
  - [github.com/thoughtbot/upcase](https://github.com/thoughtbot/upcase). 14k lines. *Learning platform for developers.*
  - [github.com/joemasilotti/railsdevs.com](https://github.com/joemasilotti/railsdevs.com). 14k lines. *The reverse job board for Ruby on Rails developers.*
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
- **Larger codebases:** More than 50k lines of Ruby code.
  - [github.com/rubygems/rubygems.org](https://github.com/rubygems/rubygems.org). 56k lines. *Where Ruby gems are hosted.*
  - [github.com/WikiEducationFoundation/WikiEduDashboard](https://github.com/WikiEducationFoundation/WikiEduDashboard). 59k lines. *Wikipedia course dashboard system. Has a React front end.*
  - [github.com/chatwoot/chatwoot](https://github.com/chatwoot/chatwoot). 74k lines. *Customer engagement suite. Has a Vue.js front end.*
  - [github.com/solidusio/solidus](https://github.com/solidusio/solidus). 98k lines. *E-commerce platform.*
  - [github.com/alphagov/whitehall](https://github.com/alphagov/whitehall). 110k lines. *Publishes government content on [gov.uk](https://www.gov.uk/).*
  - [github.com/mastodon/mastodon](https://github.com/mastodon/mastodon). 117k lines. *Like Twitter but self-hosted and federated.*
  - [github.com/redmine/redmine](https://github.com/redmine/redmine). 118k lines. *Project management app.*
  - [github.com/forem/forem](https://github.com/forem/forem). 126k lines. *Powers the blogging site [dev.to](https://dev.to/). Uses Preact on the front end.*
  - [github.com/openfoodfoundation/openfoodnetwork](https://github.com/openfoodfoundation/openfoodnetwork). 129k lines. *An online marketplace for local food.*
  - [github.com/decidim/decidim](https://github.com/decidim/decidim). 294k lines. *The participatory democracy framework.*
  - [github.com/zammad/zammad](https://github.com/zammad/zammad). 299k lines. *Helpdesk/customer support system.*
  - [github.com/antiwork/gumroad](https://github.com/antiwork/gumroad). 323k lines. *E-commerce platform.*
  - [github.com/opf/openproject](https://github.com/opf/openproject). 479k lines. *Project management software.*
  - [github.com/discourse/discourse](https://github.com/discourse/discourse). 514k lines. *Discussion forum platform. Has an Ember.js front end.*
  - [github.com/instructure/canvas-lms](https://github.com/instructure/canvas-lms). 891k lines. *A popular LMS (learning management system).*
  - [gitlab.com/gitlab-org/gitlab](https://gitlab.com/gitlab-org/gitlab). 3 million lines. *Like GitHub but with CI/CD and DevOps features built in. Uses Vue.js on the front end. Has [docs on architecture](https://docs.gitlab.com/ee/development/architecture.html).* <!-- https://letslearnruby.com/images/gitlab.png -->
