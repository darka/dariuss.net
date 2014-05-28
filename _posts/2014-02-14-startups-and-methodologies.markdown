---
layout: post
title:  "Startups and Development Methodologies"
date:   2014-02-14 12:31:01
categories: jekyll update
---

## Introduction

When it comes to early stage technology startups, software development is usually done in an ad-hoc way, without adhering to any specific rules. This is not surprising, considering startups usually have 2-3 co-founders, and not all of them are necessarily doing development. One of the co-founders is often non-technical, and handles the business side of the startup. Generally, you don't expect kids operating a company from a garage to thoroughly follow a software development methodology.

![Google](http://blog.inf.ed.ac.uk/sapm/files/2014/02/google-300x117.png)

Sergey and Larry were running Google from a garage and were lousy coders.
Fortunately they now have the resources to fix their code.

However, my experience working for a few startups, including one early stage startup, has shown that not adopting a software development methodology as early as possible causes a lot of headaches later. Despite the low number of people involved at the beginning, most startups develop both long-term and large-scale projects. Not adhering to any software development methodology when working on large projects leads to flaws in the implementation, buggy and poorly documented code, and loss of productive development time in the long run.

## Startup Problems

At a startup most of the code ends up being written in an ad-hoc manner due to lack of direction. Whenever a customer requires a new feature, and the architecture is found to be unsuitable for it, the developer usually ends up implementing the feature as a hack, rather than properly integrating it into the software. If this kind of development continues, and the number of hacks in the implementation increases, the code base becomes fairly hard to navigate.

As early stage startups usually do not have the resources needed to produce complete hand-written software documentation, they rely on automatic documentation generators (such as Doxygen) to at least document the APIs. However, multitudes of hacks greatly increase the complexity of the code base, such that the quality of documentation produced by the tools suffers. When a startup hires a new developer, it will take a lot of time for him or her to comprehend the code base.

![Facebook](http://blog.inf.ed.ac.uk/sapm/files/2014/02/fb1.png)

Facebook also suffered from code quality problems: it was written in PHP. They are still dealing with that.

Similar problems affect the testing side of startup software. Few test cases are written, so a lot of bugs are missed during development, and only encountered by the customer once the software is shipped. If such a bug is deemed critical (e.g. it may cause data loss to the customer), the developer has to rush to fix it, leading to even more hacks in the software code.

To some extent this can be avoided by having a dedicated tester on the startup team. Testers are usually cheaper to hire than developers, and can find some of the more critical bugs before customers encounter them, hopefully preventing dangerous code from being shipped. However, due to lack of funding, hiring even one tester may prove difficult for an early stage startup.

## Implementing a Development Methodology at a Startup

Now that we have established how the lack of a methodology leads to various problems during software development, we can look at what methodology suits a startup best.

Although still common in large corporations, the Waterfall methodology is too rigid to work in a startup environment. In lean startups, product specifications have to be revised constantly to adapt to changes in how customers perceive the product. If the viability of the product becomes questionable, the whole concept of the product may have to be changed. This is incompatible with Waterfall, as it is a sequential software development process.

The alternative to sequential development processes is agile methods. One such method is Extreme Programming (XP). Obviously, due to low head count in early stage startups, not all elements of XP can be implemented completely.

Planning in an agile way can usually be carried out without too many problems, as to some extent startups are aware of their potential customers, and hence, are able to produce the needed user stories. As one of the founders usually takes on more of a business-side role, he or she can be considered the "on-site customer", and able to consult the developers about software requirements.

Short release cycles can also be implemented. Startups often develop web apps, which can usually be shipped instantly. When it comes to mobile, Android market does not have a pre-approval process. Even for iOS, App Store approval time is about 6 days, which also allows for a relatively quick release cycle. This limits the scope of newly implemented features, encourages keeping the code base clean, and reduces the number of hacks in the code.

Regarding testing, software quality can be much improved by implementing test-driven development (i.e. writing test cases before implementing the needed functionality to make them pass). Designing a few manual test cases to be executed before major changes are shipped to ensure no major bugs are introduced, is also a good idea, as long as the test cases are kept simple enough so that developers (or testers) do not lose a lot of time while executing them.

Since early stage startup teams are so small, implementing Pair Programming and the 40 hour work week can be impractical. Human resources are already too scarce to limit the focus on code and restrict working hours. These agile methods can be implemented later, once the startup team becomes larger.

## Conclusion

Obviously, following agile practices during startup development slows down short-term progress due to some overhead. However, considering the number of problems which are eventually avoided, this is more than worth the effort. Unless you are building a startup you know is doomed to fail, adopting an agile development methodology early on will eventually save both time and money.
