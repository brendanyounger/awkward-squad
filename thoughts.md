# The Awkward Squad (IO, errors, distributed computation, etc.)

This talk is all about how we might write programs that are easier to understand, easier to extend, and more robust than those we usually write today.  With the rise of computing on demand and scaling everything to "web-scale", there are a lot proposals out there for how to manage the coordination and intermittent faults that accompany these larger systems.  I've found what I think is the best answer at the moment, and I want to share my thoughts on it.

As a teaser, I'd like to share some of the best papers, videos, and slides I've come across relating to the topics I'll be discussing.  There is no need to read them all beforehand, but you might peruse them to get in the right mindset.  I will have an extensive annotated bibliography prepared for the talk if you'd like to dig deeper into any of these.

    * [Tackling the Awkward Squad](http://research.microsoft.com/en-us/um/people/simonpj/papers/marktoberdorf/mark.pdf) is a great introduction the history of handling IO actions and effects in Haskell.  Very readable.

    * [Datomic database values](http://www.infoq.com/presentations/Datomic-Database-Value) explains exactly why never deleting data is actually a great idea.

    * The [Elm language](http://elm-lang.org/) and [ReactiveML](http://rml.lri.fr/) are excellent implementations of Functional Reactive Programming which allows computation to occur whenever new inputs are ready.

    * [The declarative imperative](http://www.eecs.berkeley.edu/Pubs/TechRpts/2010/EECS-2010-90.pdf) and [Consistency analysis in Bloom](http://db.cs.berkeley.edu/papers/cidr11-bloom.pdf) make a good case for designing distributed systems in such a way that computation can always be retried and everything will be eventually consistent.

    * [Babbage](http://thecomputersarewinning.com/post/Explaining-Babbage/) and the [Storm project](http://storm-project.net/) are frameworks for splitting up computation and handling it piecemeal.

I'll be presenting with HTML slides, so if you'd like to follow along, try out some of the links, etc. bring your own laptop to the meeting.

See you there,
Brendan Younger

[Awkward squad](http://en.wikipedia.org/wiki/Awkward_Squad)

[Tackling the Awkward Squad](http://research.microsoft.com/en-us/um/people/simonpj/papers/marktoberdorf/mark.pdf)
[How to Declare an Imperative](https://wiki.ittc.ku.edu/lambda/images/3/3b/Wadler_-_How_to_Declare_an_Imperative.pdf)

[Elm language](http://elm-lang.org/)
[Bacon.js](https://github.com/raimohanska/bacon.js)
[ReactiveML](http://rml.lri.fr/)

[BOOM](http://boom.cs.berkeley.edu/)
[The declarative imperative](http://www.eecs.berkeley.edu/Pubs/TechRpts/2010/EECS-2010-90.pdf)
[The declarative imperative slides](http://db.cs.berkeley.edu/jmh/talks/podskeynote10.pdf)
[Consistency analysis in Bloom](http://db.cs.berkeley.edu/papers/cidr11-bloom.pdf)

[What goes around comes around overview](http://web.eecs.umich.edu/~klefevre/eecs584/Handouts/Stonebraker-Hellerstein.pdf)
[Datomic database values](http://www.infoq.com/presentations/Datomic-Database-Value)

[PaxosLease](http://arxiv.org/pdf/1209.4187.pdf)
[Paxos made live](http://www.cs.utexas.edu/~lorenzo/corsi/cs380d/papers/paper2-1.pdf)

[Babbage](http://thecomputersarewinning.com/post/Explaining-Babbage/)
[Prismatic graph library](http://blog.getprismatic.com/blog/2012/10/1/prismatics-graph-at-strange-loop.html)
[Storm project](http://storm-project.net/)

[Total functional programming](http://www.jucs.org/jucs_10_7/total_functional_programming/jucs_10_07_0751_0768_turner.pdf)

## Bio

Brendan, currently a programmer at Roomkey.com, enjoys playing around with new ideas in CS and programming languages.  This talk is an amalgamation of the papers and projects he's been reviewing in his spare time.
