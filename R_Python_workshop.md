# 0 Preamble
People should know how to:
 
 - Install softwares
 - Find paths on their machines
 - Working skills in R or python (or both!) or whatever other language (but we won't help much)
 - Install git, some kind of GUI for git, a devtool thing for your language (we propose suggestions for mac and windows and linux)

TODO:
[ ] -presentation: slides about what we're gonna do


# 1 Problem/question

If we go with card shuffling: do an intro where people solve the problem with pen and paper with 8 cards (give them real cards!)

Objectives:
 - Get the people to think about the problem
 - Get them to realise that you should do it with a computer (ask them the question for 100 cards!)

TODO:
[ ] -presentation: slides about the problem - TG

# 2 Split the problem

0. Overview of the engineering workflow

 - To solve a problem do this: what data are you working with, what do you want to do with it and how do you it in the computer
 - include coding and design strategies: **think before doing**

1. What data?

 - Cards. Easy

2. What do we want to do with it:

[talk about **separation of concerns**]

 - Apply functions:
     - function: make a deck [each time, on a board: write down the function definition: ask input/output definitions + preconditions (sanitizing) + output conditions + magic numbers!]
     - function: split a deck
     - function: shuffle a deck
     - function: examine the deck

3. How do we represent cards in a computer so you can use these functions

 - data structures?: how do you represent a card deck in your computer?
 - [get data structure decision tree from Sam's book]
 - Think about the output:
    -presentation
    -results display: what do you want the whole "software" to give you (in this case an integer: the number of shuffles)

At the end of this part: we need a chart of what:
 - the data looks like
 - the functions input/output are


TODO:
[ ] - slides about workflow + separation of concerns + data structure (part 0) - SP
[ ] - slides about data (part 1) - SP
[ ] - slides asking them to figure out functions - TG
[ ] - slides asking them to figure data structure - TG
[ ] - on white board: what the data looks like + what the functions i/o are

# 3 Implement the functions (and testing!)

DO YOUR RESEARCH ON ALGORITHMS: GOOGLE "SHUFFLE ALGORITHM"

For each group/person that picks a function has to do:

 - Write the test for function n+1 and pass it to the persons
 
Then do that:

 - Write the function documentation
 - Write the function


TODO:
[ ] - slides about how to write tests in general - TG
    [ ] - in python - SP 
    [ ] - in R - TG
[ ] - slides about how to write documentation - SP
    [ ] - in python - SP
    [ ] - in R - TG
[ ] - slides about how to write functions - SP



[talk about **flexibility** here: we're not doing it in this example but normally, you an figure out if something was wrongly decided in the previous step and correct then redo point 3 from scratch: don't be afraid to break everything and rebuild everything]

# 4 Combine everything

Talk about: version control

 - Making a gitHub repo
 - Get everyone to push their tasks
 - Pull the combined code
 - Run the tests (maybe edit the test)

Once tests are good, create a package/version (create a zipball and a release)

TODO:
[ ] - slides about version control - TG
[ ] - slides about CI: continuous integration (e.g. travis) - TG

# 5 Play with the software

Now run your question for 1000 cards!

[talk about: if it doesn't work, don't worry, go back to step 3 or even step 2]

# 6 Optimisation (it's always last!)

On a new function (e.g. n+1) 

[talk about optimisations]

 - Do benchmarking
 - Try optimise (if possible)
 - Re-run tests to see if you broke something
 
TODO:
[ ] - slides about benchmarking - SP
[ ] - slides about optimisation - SP










## How to deliver it

Powerpoints of the workflow step by step introducing the concepts
In the meantime, people advance on the problems on their machines

Both teaching and coding should advance at the same time.


## wish list for later

Including C!


