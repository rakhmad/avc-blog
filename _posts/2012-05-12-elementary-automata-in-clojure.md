---
layout: post
category: 
tags : [clojure, math]
---

I've got a fun new project up on Github, [clj-automata](https://github.com/andrewvc/clj-automata), a short program that can be used to visualize an infinite sequence generated by a given [elementary cellular automataton](http://mathworld.wolfram.com/ElementaryCellularAutomaton.html). 

Automata are cool, but beyond that, the point of this project was to help people learn Clojure. To that end I spent a lot of time annotating the [source code](https://github.com/andrewvc/clj-automata/blob/master/src/clj_automata/core.clj). The code uses lazy-sequences heavily, but does a bit of imperative style code when it comes to interacting with the UI. This is something I've noticed quite a bit, graphical output seems to be less than amenable to FP. Given that clj-automata covers ground both in FP and imperative styles I thought it'd be a good learning project for those new to the language.

As an aside, I've been interested in [literate programming](http://en.wikipedia.org/wiki/Literate_programming) for quite some time. Literate programming was heavily promoted by Don Knuth, who wrote TeX as literate program.

You can see a snapshot of the running program (the actual code animates, scrolling down) below. Or, you can checkout and [run the source](https://github.com/andrewvc/clj-automata) yourself.

![automata-rule-22](/assets/images/automata-22.png)