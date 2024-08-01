# How to be an effective engineer by Edmond Lau:
  1. Optimise for learning
  2. Invest in iteration speed
  3. Validate your ideas aggressively and iteratively
  4. Minimise operational burden
  5. Building a great engineering culture
  
## Tips from techlead:
  6. Create a design doc
  7. (in industry) add small diffs (code pull requests) in the codebase. Keep the diff sizes small
  8. see that your code ships in the end
  9. be effective and productive- instead of wasting time watching crap, read the codebase and study new things
  10. stay humble- dont end up like techlead

## Extra Tips
  - Plan your approach before you write a single line of code. Kinda like how you do programming challanges(Kattis, Leetcode)
Extend this even to when you are architecting a huge code base. Figure out all the requirements and interconnectivity between the routines you are about to write
  - When debugging, arguably the most important trait you can posess is calmness (and patience). Being frantic will not only confuse you more but also slow down the rate at which you solve the problem, or even worse cause you to give up.
  - Keep a devlog/ work journal \
*"The benefit of journaling is not just reentry, but that you begin to solidify the mental model into a concrete branching of possibilities that is tightly coupled to the specific problem. Your work becomes traversal and mutation of this tree. Several benefits accrue: you begin to see gaps in the tree, and can fill them in. You begin to have confidence in your mental model, recovering the time you used to spend going over the same nodes again and again in a haphazard way. In distributed systems in particular, the work is often detailed, manual, error prone and high latency - with a solid mental model you can get through a checklist of steps with minimum difficulty and high confidence that you didn't miss anything. This ability to take something abstract and make it more concrete on the fly is a critical skill."* \
*~comment from HN*
  - Rarely write error messages, instead figure out what to do and present users with solution messages (depends on the type of system of course.)
  - When building APIs, you should work from behind. Write the ideal API call first, and use it as if it existed. Then go and implement it
