# Architecture Options

Creating code that is well organised and easy to read, modify or expand upon is an important skill to have as a developer, especially when working in a team of developers. Using architecture is a good tool to do this. There are different architecture options suited to different video games and different development teams. We should aim to strike a balance between using architecture that the team is familiar with, while also ensuring it is the best option for the sort of game we are making.
Good architecture can save time in the long run, particularly as a project's code grows, but as a team we must not become overly focused on the architecture itself. Doing this would cost us a lot of the limited time we have to create the project.
All of these architecture options use modularity to abstract data so they do not need to know all of the code to change something. This also reduces errors, as the code does not 'know' about each other. Testing and debugging also becomes easier, as the error can be pinned down to a particular part of code much quicker.


## Interfaces

Interfaces are used by creating an Interface that can be used by other scripts with similar functions. This is useful for creating systems that will be used a lot throughout a game, like health or movement mechanics. This would be a good option for this stealth game, because mechanics like interacting with objects or being detected by enemies will be reused throughout the game. 

## Inheritance

Inheritance uses a 'parent' class that its 'child' classes inherit functionality from. This is used to cut down on repeat code, so a new child class would only have to contain any new code that differs from the parent class. Similar to Interfaces, this can be used to create repeat mechanics that are used by many different parts of the game. This could work for this project, but unlike Interfaces, a script can only inherit one parent class at a time. This could limit the flexibility of the code.

## Components

Using component architecture involves splitting up scripts to separate functions. This allows the developers to only work and understand on specific parts of the code, and helps reduce errors. Components are useful for games that involve repetitive objects, characters etc. Components could be useful in parts of this project, but is not the best fit for the primary architecture of this project. We will keep Components in mind and implement it if improves the structure of this project. 
