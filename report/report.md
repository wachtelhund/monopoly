# Report

## Are there any classes missing in your design, why/why not?

In my original design I was missing a class so handle console inputs as well as separation of human players and bots. The reason for missing the more specific types of players is that i didn't see a need for it in the initial design. I didn't handle the console inputs, because during the initial design phase it was unclear how the players were going to control their ingame players.

## Did you have any extra classes in your design, why/why not?

I didn't have any extra classes since if I'd split for example the board into board sections the initial design would have been bloated.
 
## Are there differences in naming the classes? How should classes be named?

The classes are similarly named, the only real difference between the names are the Tile subclasses. A class name should be descriptive of what the class represent preferably in a real life context.

## Are there differences in the relations between the classes?

There are lots of differences in the relations between classes. Mainly with the lack of dependency in my design but the associations differ as well.

## Did you connect the objects using dependency/association or did you use id-connections?

I connected my objects using association.

## Did you manage to divide the complexity/behavior into different classes or do you have one central class having most of the code?

The complexity was fairly divided however I used the game class for handling the classes.

## What differences are there for the object diagram?

In the object diagram i was missing the consoleUI and the the HumanPlayer was simply a player. I didn't properly link the tiles but see that the tiles should have been linked via associations.

## What differences are there for the sequence diagram?

All of it, the correct sequence diagram goes into a lot more detail and is able to use a lot more operations since it was most likely built somewhat in parallel with the implementation of the methods.

## Do you think you made a good job in your initial design, why/why not?

The classes looked somewhat alright however the rest of it was pretty bad. The reason for this was probably because it was my first ever diagrams and I was not able to create them in parallel with writing the code itself or adjust it according to what turned out to be crucial parts of the full design.

## What is the most important thing you learned by designing first?

You should keep the initial design as simple as possible with only the crucial classes and operations and then refine it as you're implementing the design. The process of creating a good design should be done in parallel with the implementation. 