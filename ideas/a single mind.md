# a single mind

Had an experience at work recently where I spent basically a whole day writing up a new component for our design system, writing documentation, and opening up a pull request to get it added, only to come back in the next morning to see about 15 separate comments on the changes ultimately culminating in "I don't think we really need this in the design system right now."
I ended up declining my own pull request and deleting the branch myself.
And while it was a frustrating experience it did teach me a few things.
First is that I still suck at doing real development work. Objectively so much of what I wrote was problematic.
The second is always get feedback earlier before spending an entire afternoon on something only to have it thrown away. As a designer there's really no excuse for not following my own advice here.
But the third and most important thing I learned was about what happens when you start to have more than one person contributing to a thing that is then meant to be used by many others.
You very quickly start to run into the problem of consistency.

(Frederick Brooks quote)

If you take a wild west approach (a more positive term might be organic approach) (the cathedral and the bazaar) to maintaining a design system, where everyone can contribute anything at any time, then people who want to use that system have to adapt to the stylistic choices of as many minds as there are components in the system.
Every component has a different API, naming convention, implementation, etc. depending on who wrote it.
Some of these problems can be addressed by contribution standards, code style guides, or peer reviews, but ultimately it's impossible to completely erase the individuality and personality of those contributions.
Unless my coworker completely rewrote my new component from the ground up, there's no way to eliminate all the micro decisions that I made when I wrote it, and the sum of those micro decisions amounts to a non-trivial stylistic difference from the rest of the existing codebase.

If there's only one person in charge of the system, however, then everyone who uses that system only needs to adapt to the stylistic choices of one mind - the architect.
Even if the choice of who gets to be the architect is arbitrary, having a singular person with conceptual authority over the system means that the products of the system more often meet the expectations of the people who use it. It's predictable. Unsurprising.
And that's a good thing, because systems with this kind of conceptual integrity are quicker to learn.