---
layout: post
title:  "Mitigating Software Project Failure"
date:   2014-03-14 16:23:39
categories: blog 
---
## Introduction

Most software projects fail. 

According to the Standish group, the software project development failure rate has been [around 70% over the course of the last 20 years.][failurerate] This is a staggering statistic. There is no simple solution to ensure software development success, but a lot can be done to mitigate the failure rate.

Most software projects are [not the public web services we use everyday, and not shrink-wrapped software.][mostsoftware] Many of the projects that fail are custom software projects built for governments and corporations. The teams involved in these projects usually have little to no exposure to the Silicon Valley technology startup scene. Some of the greatest software successes have come out of the Silicon Valley, and I believe a lot of the problems that software projects encounter can be solved by following strategies that have become common-place in the Bay Area.

In 2011, __Eric Ries__, a Silicon Valley entrepreneur published a book called "The Lean Startup", describing a methodology for building businesses and products. Although there is no silver bullet, I believe that following this methodology can mitigate most important aspects of development failure and increase the success rate of all software projects, even when they have nothing to do with startups.

## Solving Problems with Lean Methods

One of the [most common problems in failing software projects][common] is the __lack of clear requirements and specifications.__ This is a problem startups face as well. It is often uncertain whether the market wants the product that the startup is building or whether the project will ultimately turn out to be unsuccessful. The lean startup methodology suggests using the __MVP__ (Minimum Viable Product) strategy to first test the market. A simple mock product is built with a very limited set of features, satisfying only the most important requirements, and shown to early adopters. Feedback is collected, and the potential of the product is then evaluated. Similarly, when the specifications are unclear for software projects, building a product akin to the MVP can be helpful in collecting early feedback from the clients, and then using the feedback to clarify the specifications.

Another common problem causing software project failure is the __lack of project status updates.__ Clients cannot easily find out how much progress the development team is making. This is because it often takes a long time before developers can show the first version of the project in a usable state to the client. Ideally developers should build upon the MVP, continuously improving the product and collecting feedback from the client. The lean method recommends that startups implement __continuous deployment__ to achieve this, immediately releasing a new version whenever any small change is made. In that way, any issues encountered by the client can then be taken into account as soon as they are noticed, rather than after the project is deemed finished.

Continuous deployment also allows the client to see how fast the project is developing. By measuring the pace of development, and taking note of which features still need to be implemented, it becomes easier to __set a realistic estimate__ for the project. Obviously this does not completely solve the problem, but any estimation method is better than pulling the deadline out of thin air.

The project requirements may be unclear, but if a software development team has a way to continuously collect feedback from the client, based on it, the team can decide whether to __pivot or persevere.__ As in, decide whether major changes need to be made to the 'MVP', or whether it is fine to develop the project further in the same direction. As long as the feedback from the client is taken into account, to some extent this shields the development team from the __politics involved in project planning and management:__ every change is being made in order to satisfy the client. Rather than following some manager's guidance on what feature to implement next, developers can decide on that simply by looking at the feedback: figuring out what clients complain about the most, what bugs they find the most annoying, and what features they demand the most.

Other common reasons for project failures are __poor project management__ and __sloppy development practices.__ If the management team is incompetent, there is not much developers can do about that, but at least when it comes to development practices, a lean methodology forces the development team to adopt agile development techniques. Surveys have shown that the usage of agile methods usually results in better software quality and productivity gains, hence, improving the chance of success for the project.

## Conclusion

Clearly the lean startup method is much more general than you would expect it to be, and it can also be applied to non-startup projects. The methodology is proven to work, as many successful companies such as [DropBox][dropbox] and [Intuit][intuit] were built upon it. The methodology ensures that the pace of development is fast and that client's feedback is taken into account from the very beginning of the project. There is hope that as time passes more and more software teams will become aware of the lean method, and that many software project failures will be avoided by adopting it.

_Originally published in [SAPM Blog.][original]_

[original]: http://blog.inf.ed.ac.uk/sapm/2014/03/14/mitigating-software-project-failure-using-lean-startup-techniques/
[failurerate]: http://www.inf.ed.ac.uk/teaching/courses/sapm/2013-2014/sapm-all.html#/547
[mostsoftware]: http://books.google.co.uk/books?id=UJlNAgAAQBAJ&lpg=PA105&ots=bLxkaZxKfr&dq=Eric%20Raymond%2C%20jobs%20custom%20software&pg=PA105#v=onepage&q&f=false
[common]: http://www.spinroot.com/spin/Doc/course/Standish_Survey.htm
[dropbox]: http://dropbox.com/
[intuit]: http://www.intuit.com/
