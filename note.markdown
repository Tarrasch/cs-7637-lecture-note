% Arash Rouhani
% Lecture notes from Knowledge based AI (7th September, 2012)

# Frames

When reading a text from a story, say about the earthquake in Slabovia,
we remarkably understand the content immediately. With frames, we know
what we are looking for when we read it. There are slots for all "expected
values", we precisely know where to store these expected values. For
instance, when reading "the death toll reached 25 persons", we have a
slot to fill already. Because we already know that an earthquake should
have a death toll number.

The "template" that we fill in when we read about an earthquake is
a *stereotype*. Reading about a subject where we lack a stereotype, we
need to create a new frame which will work as a stereotype when we read
about the same subject the next time. This will all be stored in our
long term memory. We have stereotypes for all kinds of concepts,
like "how a professor looks like", "what happens when somebody is drunk"
etc.

## Frames relation to Semantic Networks

A series of frames with relations to other frames like *a kind of* can
be seen as a Semantic Network (chapter 2 in Winston).  Instead of frames
and relations, we have nodes and edges. The book (chapter 9 part 1)
have figures illustrating this equivalency.

## Curiosity, creativity, expectations and surprise

We become *surprised* when we encounter something that we don't have a
stereotype frame for, we say that that encountering didn't meet our
*expectations*.

We will become *curious* when we have a almost matching template that
don't completely fit. Consider this example, a world-unaware person
reads about earthquakes and they mention that "25 people died and 100
got injured", the person first becomes surprised because he's only
associate earthquakes with number of deaths, not a number of injuries.
Curiosity is when he starts googling for why people get injured during
earthquakes.

*Creativity* is when we get surprised by a completely new concept that
need a whole new frame.

# Artificial Intelligence contra Machine Learning

In machine learning, agents start with no knowledge and are supposed to
learn how everything works. That isn't how human cognition works, we
learn by making new frames from having plentiful of existing ones. The
elementary school teachers assume at least *some* knowledge of their
pupils, even at the first day of class. Knowledge Based AI is more like
the learning we encounter on a daily basis.

# Common sense

In the 10th chapter of the book they introduce the concept of common
sense. What is common sense and why is it good? Imagine that you give
order to a futuristic domestic robot to fetch you some coffee.
Distinguishing for a robot with common sense is that it can find a way
around the fact that there are no cups left, it should for example bring
the coffee in a glass.

A model for common sense should be able to make use of context. An
example of this is that "Ashok takes aspirin" and "Ashok is taken by
surprise" are very alike sentences with different meanings. It is part
of common sense to able to distinguish between these using context.

The next lecture should cover more about common sense.

---

For feedback, please patch this document by pull requesting in [my github
repo][repo]. If your uncomfortable with github, you can email me at
<rarash@gatech.edu>.

[repo]: https://github.com/Tarrasch/cs-7637-lecture-note
