---
title: Richard Feynman and The Connection Machine
date: 2018-11-02 19:32:04
updated: 2018-11-02 19:47:02
source: http://blog.longnow.org/02017/02/08/richard-feynman-and-the-connection-machine/
tags:
  - compsci #compsci
  - explanation #explanation
  - interest #interest
  - life #life
  - management #management
  - science #science
  - understanding #understanding
---
Every great man that I have known has had a certain time and place in their life that they use as a reference point; a time when things worked as they were supposed to and great things were accomplished. For Richard, that time was at Los Alamos during the Manhattan Project. Whenever things got “cockeyed,” Richard would look back and try to understand how now was different than then.

### 2

What Hopfield had invented was a way of constructing an \[associative memory\], a device for remembering patterns. To use an associative memory, one trains it on a series of patterns, such as pictures of the letters of the alphabet. Later, when the memory is shown a new pattern it is able to recall a similar pattern that it has seen in the past. A new picture of the letter “A” will “remind” the memory of another “A” that it has seen previously. Hopfield had figured out how such a memory could be built from devices that were similar to biological neurons.

### 3

Concentrating on the algorithm for a basic arithmetic operation was typical of Richard’s approach. He loved the details. In studying the router, he paid attention to the action of each individual gate and in writing a program he insisted on understanding the implementation of every instruction. He distrusted abstractions that could not be directly related to the facts. When several years later I wrote a general interest article on the Connection Machine for \[Scientific American\], he was disappointed that it left out too many details. He asked, “How is anyone supposed to know that this isn’t just a bunch of crap?”

### 4

The game of Life is an example of a class of computations that interested Feynman called \[cellular automata\]. Like many physicists who had spent their lives going to successively lower and lower levels of atomic detail, Feynman often wondered what was at the bottom. One possible answer was a cellular automaton. The notion is that the “continuum” might, at its lowest levels, be discrete in both space and time, and that the laws of physics might simply be a macro-consequence of the average behavior of tiny cells. Each cell could be a simple automaton that obeys a small set of rules and communicates only with its nearest neighbors, like the lattice calculation for QCD. If the universe in fact worked this way, then it presumably would have testable consequences, such as an upper limit on the density of information per cubic meter of space.

### 5

> “We have noticed in nature that the behavior of a fluid depends very little on the nature of the individual particles in that fluid. For example, the flow of sand is very similar to the flow of water or the flow of a pile of ball bearings. We have therefore taken advantage of this fact to invent a type of imaginary particle that is especially simple for us to simulate. This particle is a perfect ball bearing that can move at a single speed in one of six directions. The flow of these particles on a large enough scale is very similar to the flow of natural fluids.”

This was a typical Richard Feynman explanation. On the one hand, it infuriated the experts who had worked on the problem because it neglected to even mention all of the clever problems that they had solved. On the other hand, it delighted the listeners since they could walk away from it with a real understanding of the phenomenon and how it was connected to physical reality.

### 6

I do not mean to imply that Richard was hesitant to do the “dirty work.” In fact, he was always volunteering for it. Many a visitor at Thinking Machines was shocked to see that we had a Nobel Laureate soldering circuit boards or painting walls. But what Richard hated, or at least pretended to hate, was being asked to give advice. So why were people always asking him for it? Because even when Richard didn’t understand, he always seemed to understand better than the rest of us. And whatever he understood, he could make others understand as well. Richard made people feel like a child does, when a grown-up first treats him as an adult. He was never afraid of telling the truth, and however foolish your question was, he never made you feel like a fool.

### 7

The last project that I worked on with Richard was in simulated evolution. I had written a program that simulated the evolution of populations of sexually reproducing creatures over hundreds of thousands of generations. The results were surprising in that the fitness of the population made progress in sudden leaps rather than by the expected steady improvement. The fossil record shows some evidence that real biological evolution might also exhibit such “punctuated equilibrium,” so Richard and I decided to look more closely at why it happened. He was feeling ill by that time, so I went out and spent the week with him in Pasadena, and we worked out a model of evolution of finite populations based on the Fokker Planck equations. When I got back to Boston I went to the library and discovered a book by Kimura on the subject, and much to my disappointment, all of our “discoveries” were covered in the first few pages. When I called back and told Richard what I had found, he was elated. “Hey, we got it right!” he said. “Not bad for amateurs.”

In retrospect I realize that in almost everything that we worked on together, we were both amateurs. In digital physics, neural networks, even parallel computing, we never really knew what we were doing. But the things that we studied were so new that no one else knew exactly what they were doing either. It was amateurs who made the progress.

### 8

Actually, I doubt that it was “progress” that most interested Richard. He was always searching for patterns, for connections, for a new way of looking at something, but I suspect his motivation was not so much to understand the world as it was to find new ideas to explain. The act of discovery was not complete for him until he had taught it to someone else.

I remember a conversation we had a year or so before his death, walking in the hills above Pasadena. We were exploring an unfamiliar trail and Richard, recovering from a major operation for the cancer, was walking more slowly than usual. He was telling a long and funny story about how he had been reading up on his disease and surprising his doctors by predicting their diagnosis and his chances of survival. I was hearing for the first time how far his cancer had progressed, so the jokes did not seem so funny. He must have noticed my mood, because he suddenly stopped the story and asked, “Hey, what’s the matter?”

I hesitated. “I’m sad because you’re going to die.”

“Yeah,” he sighed, “that bugs me sometimes too. But not so much as you think.” And after a few more steps, “When you get as old as I am, you start to realize that you’ve told most of the good stuff you know to other people anyway.”