---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: ''
datePublished: '2016-03-16T17:43:35.283Z'
dateModified: '2016-03-16T17:21:10.349Z'
title: Domain-Driven Design
author: []
sourcePath: _posts/2016-03-16-domain-driven-design.md
published: true
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
url: domain-driven-design/index.html
_type: Article

---
Ward Cunningham said of the book Domain-Driven Design, "If you don't think you are getting value from your investment in object-oriented programming, this book will tell you what you've forgotten to do."
My experiences directly relate to this observation. It is DDD that is giving me insight into improving my object-oriented analysis and design.
\*\*TL;DR links are at the bottom of the article.\*\*
\# A Brief Introduction
Domain-Driven Design (or DDD) is a software development approach that focuses on the domain model first. Techniques within DDD allow teams to separate various "domains" (related parts of the application) from one another with the resulting benefit of trading away generic models that hold the behavior for many contexts with models designed to a specific context.
DDD is linguistic, analytic, and strategic. It encompasses many areas of software design including interacting with clients and implementing design-patterns.
\# Tactical Patterns
At Laracon NYC, I gave a talk on command oriented interfaces and domain-events. These patterns are often utilized with DDD but are themselves not a core concept of DDD at all.
\[A UseCase Architecture by Shawn McCool\](https://www.youtube.com/watch?v=2\_380DKU93U)
As I mentioned during the talk, the talk was not about DDD. But rather, was inspired by the \*\*rich service layer movement\*\* that seems to be flowing from DDD through our community.
\[Models and Service Layers - Hemoglobin and Hobgoblins by Ross Tuck\](https://www.youtube.com/watch?v=3uV3ngl1Z8g)
I believe that many developers (like me) started to get a taste of the benefits that DDD has to offer and decided that they wanted more. 
But, what is DDD exactly?
\#\# Introduction to DDD
At first, DDD seems like a nebulous concept full of other nebulous concepts. However, during my pursuits I've started to nail down specific resources that I believe can give clarity to these ideas. 
Vaughn Vernon (the author of the red book --more info later--) gave two presentations at TechEd North America 2014 that are startlingly good introductions to DDD. The first covers the core concepts of DDD including the ubiquitous language, domains, bounded contexts, context mapping, and aggregation. 
\[How You Can Architect and Develop Enterprise Mission-Critical Applications with Domain-Driven Design\](https://www.youtube.com/watch?v=aieoAWXNjl0)
Vaughn's second session covers implementing aggregates and entities effectively. He utilizes .NET however the concepts hold true, so PHP developers don't be scared away.
\[How You Can Implement Aggregates and Domain Entities Effectively in Domain Models, with .NET\](https://www.youtube.com/watch?v=oFPbEi2463c)
So far, these are the best introductions to DDD that I have found. Once you have consumed these videos, you may have a desire to dig further. If you're like me, you're very interested in these strategies for understanding and developing enterprise applications.
\#\# Read the Source Material
When you're ready, it's probably time to grab the blue and red books.
The book \[\_Domain-Driven Design\_ by Eric Evans\](http://www.goodreads.com/book/show/179133.Domain\_Driven\_Design) is considered to be the seminal work. It's heavy on concepts and light on implementation. We're software engineers. We focus on code and design-patterns on a regular basis. It is my belief that while we study more design-patterns, techniques, and tools, we have not been growing as steadily in terms of strategic domain modeling. There is more than one side to the development coin and DDD is helping me to see how I can grow in ways separate from the object-oriented paradigm.
\[\_Implementing Domain-Driven Design\_ by Vaughn Vernon\](http://www.goodreads.com/book/show/15756865-implementing-domain-driven-design) (yes, the speaker mentioned earlier in this post) is an evolution of Eric Evan's book in that it provides additional explanations and ideas. However, it focuses much more heavily on implementation than the blue book. Implementing Domain-Driven Design discusses ideas about handling access control, implementing context maps, and many other code-focused topics. It is my personal opinion that this book is best digested after reading Evans' blue book.
Between these works, we have enough to begin mastering DDD.
\# Online Reading Resources
Aside from the books, we have a number of online resources to assist us. This list will be updated as I f ind more material.
- \[DDD Quickly\](http://www.infoq.com/minibooks/domain-driven-design-quickly) is a free short ebook that covers many of the ideas behind DDD and can serve as a good start. Of course, it can't compete with the blue or red books.
- \[Mathias Verraes' Blog\](http://verraes.net) is one such place. Mathias is a Belgian consultant who is considered premier in the space of DDD in PHP. His blog covers various related topics and I recommend reading each and every article as well as the comments on them.
- The \[DDD in PHP user group\](http://dddinphp.org) is a great place to ask questions and get answers. It may be worth your while to simply invest in reading the discussions a bit by bit each day until you're caught up. In reality, the total time spent doing such is a drop in the bucket for the amount of information available from this resource.
- \[Ross Tuck\](http://rosstuck.com) also discusses some topics on his blog. Again, do not skip over the comments as within exists quality information.
\# Video Resources
- \[How You Can Architect and Develop Enterprise Mission-Critical Applications with Domain-Driven Design\](https://www.youtube.com/watch?v=aieoAWXNjl0)
- \[How You Can Implement Aggregates and Domain Entities Effectively in Domain Models, with .NET\](https://www.youtube.com/watch?v=oFPbEi2463c)
- \[Implementing Domain-Driven Design Video Book Club\](https://www.youtube.com/channel/UChy\_3ir-ESf0Y5b5j95J61A) Jeff Carouth is leading a video book club for the red book. If you're reading the red book, you might watch the video for the chapter you just finished. This can help you further cement the ideas that you covered over that chapter.
- \[Mathias Verraes' LaraconEU 2014 Talk\](https://www.youtube.com/watch?v=QaIGN\_cTcc8) was over Decoupling the Model from the Framework and within he discusses domain-events as well.
And last but not least... The PHP Friends of DDD have compiled a massive \["State of the Union"\](https://github.com/PhpFriendsOfDdd) index of resources. 
I'll continue to add new resources to this list as I find them. Please feel free to comment if you find any gems.