---
layout: post
title: A Code Horror Story
---

"The whole code was littered with constructor calls that don’t store the returned new object. What’s the point in constructing another instance if you throw it away in the next moment, without ever using it? After examining these constructors, it became apparent that they only exist to perform side effects each. The new object is registered with the global data model while it’s still under construction. ..."

I normally don't like horror stories, but I couldn't stop reading this one. It scared the hell out of me.

[A Tale of Scrap Metal Code](http://schneide.wordpress.com/2011/01/24/a-tale-of-scrap-metal-code-part-ii/)
