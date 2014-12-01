---
layout: post
title: All Development 2014-KW48 
---

## Quotes from [High Scalability](http://highscalability.com/blog/2014/11/21/stuff-the-internet-says-on-scalability-for-november-21st-201.html)
> Prefer decoupling over duplication. Coupling will kill you before duplication does by @ICooper #buildstuffIt (@zhilvis)

> Optimisation maybe premature but measurement isn’t. (@RichardWarburto)

> Scaling is the process of decoupling load from latency. (Kiril Savino)

## Articles

### [How Nike thinks about app development: Lots of micro services](http://highscalability.com/blog/2014/11/21/stuff-the-internet-says-on-scalability-for-november-21st-201.html)
> Nike's plan: Build a series of services that do little things like checkout and reading data and then bring them together into larger apps that'll be easier to tweak in the future.


### [A Rare Peek Into The Massive Scale of AWS](http://www.enterprisetech.com/2014/11/14/rare-peek-massive-scale-aws/)
> An AWS datacenter is rated at 25 megawatts to 30 megawatts, which means at the 87 datacenters I am projecting in total for AWS at the moment, that is somewhere between 2.17 gigawatts and 2.6 gigawatts of total electric capacity.

>The AZs are usually under 1 millisecond apart in terms of latency and are always less than 2 milliseconds apart; this speed is what allows for synchronous data replication, since committing data to a solid state drive takes – wait for it – between 1 and 2 milliseconds.

### [Technical Dept Quadrant](http://martinfowler.com/bliki/TechnicalDebtQuadrant.html) by Martin Fowler

>The debt metaphor reminds us about the choices we can make with design flaws.

So technical debt is a metaphor to communicate design problems. Martin Fowler raises the question if there is only one kind of technical debt? He thinks technical debt has two characteristics. On the one hand a design choice is reckless or prudent. On the other hand a design choice is made either deliberate or inadvertent. In discussions about software design, libraries, etc. this classification gives us a schema to describe our reservations and hopefully to reduce the debt in the future.

### [2 years with Angular](http://www.fse.guru/2-years-with-angular)

[Make Any Framework Suck Less With These 10 Insightful Lessons](http://highscalability.com/blog/2014/11/26/make-any-framework-suck-less-with-these-10-insightful-lesson.html) directed me to the blog post from Alexey Migutsky. Just because AngularJS is backed by Google doesn't mean that everything is perfect. [2 years with Angular](http://www.fse.guru/2-years-with-angular) describes which obstacles one should be prepared for and ends with 10 lessons for framework developers:

> 1. You should have as small as possible number on abstractions.
> 2. You should name things consistent with your "thought domain".
> 3. Do not mix several responsibilities in your components. Make fine-grained abstractions with well-defined roles.
> 4. Always describe the intention for your decisions and trade-offs in your documentation.
> 5. Have a curated and updated reference project/examples.
> 6. You abstractions should scale "from bottom up".
>
>    Start with small items and then fit them to a Composite pattern. Do not start with the question "How do we override it globally?".
> 7. Global state is pure evil.
>
>    It's like darkness in the horror films - you never know what problems you will have when you tread into it...
> 8. The dataflow and data changes should be granular and localized to a single component.
> 9. Do not make things easy to use, make your components and abstractions simple to understand.
>
>    People should learn how to do stuff in a new and effective way, do not ADAPT to their comfort zone.
> 10. Encode all good things you know in the framework.
>
>     Make the "guiding rails" and throw warnings each time something is done incorrectly.

