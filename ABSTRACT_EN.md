# Talk Abstract

Explanations of categorical abstractions often go something like "this is Option. It's a Functor. Also, all of the other things".

In this talk, we try the opposite approach, building types that are some of the things, but not all of the things, to make it clearer what each of the things does.


# Talk Description
When learning things, I find it useful to have concrete example to help build an intuition.

The problem with this approach when explaining categorical abstractions is that a lot of types most developers are used to working with are Monads, and thus, all of the other things as well. Not having concrete examples of things that are, say, a Functor but not an Applicative, makes it harder to build an intuition of the difference between the two.

This talk is an experiment to see whether such examples are, in fact, useful. We will carefully build examples of common abstractions, see what makes them work, and attempt to break that. The hope is that understanding what needs to happen for a Functor to also be an Applicative will make it clearer what those two things are, what they share and, more importantly, what distinguishes them.

# Notes

I'll be completely honest: I'm not sure this talk is *useful*. I do think it's quite fun however, for an admittedly novel definition of the word _fun_.

This approach works for me, and preparing this talk has definitely led to some new insights. The types we build along the way *are* useful, and so are the notions  we end up manipulating. But, as stated in the description: most types developers work with on a daily basis are either none or the things, or all of the things. Understanding the distinction between and Applicative and a Monad might not be critical when most things you're likely to work with are both.

I do believe building these intuitions is useful as a sort of mental scaffolding, and as a matter of culture. It's also fun to take things that work and carefully change the minimum possible amount to break them in _just_ the right way, so that the properties we don't need stop holding, but none of the others do.

And, well, let's face it. We're engineers. We like breaking things to see what makes them tick just as much as we like building them.
