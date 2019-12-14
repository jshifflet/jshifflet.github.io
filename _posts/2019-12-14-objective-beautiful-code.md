---
title: Is beautiful code possible? 

Does beautiful code have higher quality?

Thoughts from Alexander, Gabriel, and Dexter
---

I have recently be working on relearning software design patterns. This has included reading: "Head First Design Patterns" and Richard P. Gabriel's "Patterns of Software". In addition, I have been thinking and reading about aesthetics in software code. In particular, the paper "On the Embodied Aesthetics of Code" by Scott Dexter et. al. All this reading and coding at my day job has me thinking:) 

* Can the judgment of beauty be extended to other observers beyond myself - i.e. can beauty be objective?

* Is beautiful code better than ugly code?

* If so, then what is beautiful code?

According to Gabriel, beautiful code would be code that has what Christopher Alexander calls "the quality without a name". This quality is something shared by all beautiful objects. These objects can be cities, houses, streets, or possibly as raised by Gabriel, software code. Alexander attempts to realign facts with value, instead of splitting them apart as has been in vogue since the 1800s. 

A beautiful system is one with a whole that stems from its small parts. It is a system that has a stable dynamic harmony between its parts. It is living, being adapted, and modified by its inhabitants. Above all, its inhabitants feel the systems is habitable and beautiful.

The article "On the Embodied Aesthetics of Code" by Scott Dexter et. al. points out that in research studies, ugly code is more often attributed to code with bugs, and that one can pick out ugly code faster than one can judge some piece of code beautiful. 

So if Alexander, Gabriel, and and Dexter are correct, then beauty can be objective and applied to code, for the purpose of helping to determine quality.

So, then what if we want beautiful code?

* What attributes would such code embody?

This is were pattern languages can come in to play. Gabriel uses his entire book to explore the overlap of Christopher Alexander's work and that of software development. Through this he tries to define what attributes beautiful code should have.

He explains in his first few essays, which is as far as I have reached so far, that beautiful code must have Alexander's "quality without a name". This quality stems from: not over using abstractions, building from small components, and the use of pattern languages. Above all beautiful code is understandable to the point of allowing future extension and modification.

Abstractions are almost always touted as the goal of good software engineering. However, Gabriel points out, I believe correctly, that abstraction works as "compression". By compression, here, he means, that each part of the abstraction is actually greater than its local meaning. This means that abstractions work because they are a type of analogy. Their meaning is derived from some prior knowledge. 

Gabriel uses the common "stack" pattern as an example. Every CS major knows what a stack is and that if they see the word "stack" in a variable name, then they probably can assume that the author was referring to the common data structure. 

Abstraction can fail for several reasons though:

* The knowledge regarding the abstraction is not held by the current software editor.

* The abstraction is too large, leaving room for ambiguity in its scope and side effects.

The first reason can be solved through education and the building of common pattern libraries. Hence the need for relearning design patterns.

Secondly, though, large abstractions are more dangerous and deserve more attention.

If an abstraction is large, it is probably not general enough to be in a common pattern language library.

Also, since no common knowledge exists, assumptions will be made or the code editor will have to read and understand the entire abstraction to use it.

This last point negates the entire purpose of an abstraction. Good abstractions can be extended and re-worked to save later coders time and reduce the risk of software bugs since the prior abstraction author should have already tested the component.

Whether your program resembles a "web" or a "pyramid", small abstractions are essential.

They have smaller scope, therefore are easier to test and communicate.

As QA Engineer I care about quality. 

The idea that beauty can be an objective way to spot bugs in software is interesting to me.

Also, that pattern libraries can help to increase code habitability through creating beautiful software with the attribute of Alexander's "quality without a name" is enticing.

In the end, if the judging of elegant code can be objective, then it can be taught, be a goal, and help to increase software quality.

With the help of common pattern languages, code can be better understood, leading to safer maintenance, and less bugs. 

My current understanding is that beautiful code is habitable code, and habitable code, is code whose nuances and side-effects are easily seen and understood through the use of small common patterns.

# Sources:

1. [Richard P. Gabriel "Patterns of Software"](http://dreamsongs.com/Files/PatternsOfSoftware.pdf)

2. [Scott Dexter, Melissa Dolese,
Angelika Seidel, and Aaron Kozbelt "On the Embodied Aesthetics of Code"](https://culturemachine.net/wp-content/uploads/2019/01/8-Embodied-438-895-1-PB.pdf)
