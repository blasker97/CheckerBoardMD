Checkerboard.md

### Question 1

Functionally my checkboard program operated to the standards that were defined in the assignment, but some noticeable efficiency differences are apparent from my code to the solution.
When creating a checkerboard with specific colors my code differs in the way it is created.  In my code I reassign every field as if I would for a default board.
In the solution using the default construct is used to create the board and the "this operator" is only used for the colors chosen.  This helps with code readability and length and I can
see why it is more affective to format the construction this way.  Also in my Build() function I do no create the anchor pane but rather I do it on construction.  I believe that does not effect
anything behind the scenes except just differing in code organization.  When looking at the algorithm to color the pieces both codes are almost symmetrical, and the same thought process was used.
Many differences are used for the state change in the view.  In my code I have multiple action events with different responsibilities where as in the solution a switch statement is used to
shorten the code and make it more readable for all the options. Plus, in this way you only need 1 action event. What I found hard was use an anonymous inner class to track when the window
became bigger or smaller.  After much thought I came up with a solution that closely resembles the solution.


### Question 2

I understood all the concepts to a solid conceptual level.  I’m not 100% sure if I could have written this code from scratch without notes and guidance.  The part that troubled me a lot
was resizing the board since anonymous inner classes still feel foreign to me and I need more practice.


### Question 3

I believe I met all requirements for the challenge.

### Question 4

My solution matches closely to the solution besides some code organization.  The major difference is the handling of action events where in my solution I am redundant and repeat a lot of code
where I could have saved time by reusing an action event element and just have different choices through the implementation of a switch statement.


### Question 5

Going forward I need to read over my code as if I was a person who have no idea what is going on.  I do a lot of things that make sense in my head but would be hard to interpret if you tried to read
the code with no prior knowledge.  I understand everything that was required for the challenge but defiantly need to get more comfortable with anonymous inner classes and decrypting lambda functions.



	
