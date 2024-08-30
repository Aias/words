# a living language

A quick outline of a process for maintaining design systems at scale, which allows for the democratic evolution of the system and a gentle decline of the old and unnecessary.

This is implemented in Figma, and is generally how we’ve structured things at Genospace. The system was designed to fit into the 2-week release flow of an agile software company, but could be pretty easily adapted to work with slower or less regular release cycles.

### a brief intro to figma

*If you’re already a seasoned user of Figma, feel free to skip this section, but I realized even I didn’t understand it intuitively until I wrote it down.*

In Figma, each Team (which can be a part of an Organization) can have a number of Projects, and each Project can have multiple Files. Then files in turn have their own Pages, and Pages have Frames, which can contain other Frames, at which point the hierarchy ends infinitely and recursively.

If that was confusing, maybe this won’t be.

```
Organizations
  ↳ Teams
    ↳ Projects
      ↳ Files
        ↳ Pages
          ↳ Frames
            ↳ Frames...  
```

Since Components are basically Frames, they “live” (are created and maintained) at same level as Frames, but are unique in that they can be included in Libraries. Libraries are a File-level concept which can be imported by other Files, to make Components more flexible.

And here I’m going to stop referring to all of these concepts with capital letters.

### team organization

Our design system is managed within a single project under our team home. The project is organized as follows:

1. Design
   1. *__Design System__*
      1. Colors
	  2. Typography
	  3. Icons
	  4. Components
   2. *Brand*
      1. Colors
	  2. Graphics
   3. *Shared Application UI*
      1. Components

At level two, all three *italic* items indicate that the components in these files are published in their own libraries. The __bold__ Design System is additionally published as a default library for every file in the team.

### the design system

Note that, while icons do get their own page, we make no distinction between the atoms and molecules you may be familiar with from other design systems.

**Application UI**
- App frame and shared UI (in Atomic Design, this would be a getting towards the Organisms level and above)
- Sub-app A (Templates)
- Sub-app B (Templates)
- Sub-app C (Templates)

### documentation

Use description field for every style and every component to document the following information:

For Colors...TODO

For Typography...TODO

For Components...TODO

### evolving the system

> “Once people share a language, the language will begin evolving of its own accord. The language will evolve, because it can evolve piecemeal, one pattern at a time. As people exchange ideas about the environment, and exchange patterns, the overall inventory of patterns in the pattern pool keeps changing.
>
> Of course, this evolution will never end.”
>
> Christopher Alexander, *The Timeless Way of Building*

The Components page is actually a group of 3 related pages, organized as follows:
- Components
- Components / Proposed
- Components / Retired

The base page represents the largest and most stable subset of the system. It is the language itself.
But the system also recognizes that needs change, and new problems need to be solved, and other things will get built.
If we cannot embrace change and adapt the system to evolving needs, we will fail.
And so we have a page for Proposed components.
Anyone can add a component to Proposed. With commenting and shared editing, the whole team can collaborate on the component in-place. Potential use cases should be outlined and discussed.
If it finds general use, the team may vote to move into Current.
And then there is the opposite case: a component which has been replaced by something more generic, or more specific, or more useful. Or maybe it hasn’t been replaced at all. Maybe it’s just no longer needed.
As we have a page for Proposals, so do we have a page for Retired components.
When a component retires, it gets moved to this page permanently (unless it someday comes out of retirement), and (since this is implemented in Figma) it is unpublished from the shared library.
In this way the system evolves through the combined effort of an entire team. It is not under control of any one person, and it strikes a balance between maintaining a stable core and responding to change.
The system reflects the way any real design language is evolved and refined.
Simple, but effective.