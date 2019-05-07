## Difference Between QA and QC
QA(Quality Assurance)  and QC(Quality Control) are two different things, although QC usually is a part of QA.

QA is the whole proactive process addressed to help our videogames to reach the quality we expect from them. It makes sure we do the right things in the right way.
QC is the testing processes make when the product is complete(in the case of video games, every build would count), that have the quality we planned and, if it’s not the case, stop the production to fix this problems.

So, the difference is clear, QA is centered in the process to assure the quality, while QC is centered in control that the quality it’s what we aimed.

![image](https://github.com/VictorSegura99/Professional-Balance-and-Testing-Research/blob/master/docs/QA_QC.jpg?raw=true)

The difference between QA and QC is largely one of power and control. QC is usually as service provided to development and is responsible for providing that service. QA expects development to provide services to it and is not responsible for any result.

## Professional Videogame Balance Methods:

Videogame Balance is obviously very important, but there’s not a flawless way to accomplish this, and lot of times come to designers guessing. To avoid this, there’s methods to try to getting as close as possible to a balanced game.

**Power curve**

This method solves the problem of different elements affecting the same thing.
In this method, it’s all about have similar effect per investment ratio. This means that the first step would be identify what have to invest the player in our games.
After this, we should measure what effect have each element we should consider in order to balance our game. For example, in an action game, could be damage, movement, etc.
With this, we can make a graphic and see all the different elements and how they scale with the investment. For example, with weapons we can measure DPS(damage per second).

**Triple Tapping**

The most probable is that on our first iteration, the game will be still very unbalanced, so following the method above, we would re estimate the cost or the power of the element at where it should be, right?
Actually, you’ll probably keep the element in the wrong state in the same direction. What expert developers advice is to over change the direction to triangulate the actual ideal cost and each iteration be closer.
To put it on an example: if a weapon doing 300 DPS is overpowered by a lot, don’t put the damage per second in 250 if you think it will be correct, because probably will still be overpowered and you’ll not gain much information. Put it on 200 or even 150, where the weapon should be under powered, but now you have completely correct margins to work with.

**How our players see the game**

The most powerful tool designers have to balance their game is their proper players. 
In order to balance some aspect of our game, it’s correct to ask to our players, in our particular case, during the playtests. As the Termi Law says, an average of a lot of not close estimations by different people will result on a very exact estimation of the ideal result, so if we ask a lot of players, even if they don’t have a great knowledge of the game, and do an average of their estimations, we’ll be closer to a perfect estimation of how the perfect balance would be.

## How do companies organize testing?

**Roles:**

_Producers_: they work with the marketing and quality assurance team to organize test and to establish deadlines.

_QA/test lead_: manages QA staff. Responsible of bug lists. Tracks bug reports and ensures they’re fixed. Coordinates all QA teams. They are usually responsible of submitting to regulatory bodies such as ESRB and PEGI.

_Testers_: they write accurate reports on bugs, and ensure that the game is fun and works correctly.

_SDET(Software Development Engineer in Test)_: they test game performance and security. They are usually experts in computer science rather than in video games.

**Testing process:**
Identification: find the bug.

Reporting: the bug is reported to the developers in an accurate report which includes how to reproduce the bug and priority.
Analysis: Developer in charge of the area in which the bug has appeared checks the malfunction.
Verification: the testers check that the bug has been fixed.

**6 Steps:**

  1. Plan and outline the test.

  2. Set up the test.

  3. Play out the test.

  4. Report the outcomes.

  5. Repair the bug.

  6. Come back to 1 and retest.

**Factors:**

Bug Tracking Framework: Each time a bug is discovered the game tester needs to make another object of some sort (or “ticket”) in a bug tracking system.

Test Case: Establish what your are going to test and how. It should have a description, steps and finally an expected outcome.

Test Suite: a test suite or checklist is a collection of Test Cases set up together on account of a particular objective. This objective needs to do with approval of the game’s localization (translation of content and voice), physic engine, and so forth.

Aptitudes, Experience and Thoroughness: To be a committed game tester, one needs to utilize these aptitudes legitimately, have the capacity to write relating test cases, sort out steady test suites and make precisely clear bug records.

**Types of testing:**

The tests can be done automatically, where they are previously programed to run certain case scenarios and search for bugs, memory leaks, crashes… or they can be done manually, with a tester in front of the screen playing the game.

Functionality: generic test that searches for stability issues, mechanics issues, and game asset integrity.

Compliance: test that checks technical requirements in different platforms. Also ESRB and PEGI rating.

Compatibility: test to ensure that the game works fine with different combinations of hardware and software in PC.

Localization: testers make sure that the game is well translated in their own language and there aren’t any mistakes in the text edition part.

Soak: leaving the game for a prolonged period of time in different screens and actions. Checks for crashes and memory leaks.

Alpha and Beta: tests performed during the alpha and beta stages of the game. It can be done with testers from the company or it can be a public beta, where the players are the testers. It is a global check.

Regression: test performed when a bug has been fixed in order to ensure that it has definitely been solved and it hasn’t produced other ugs.

Load/Stress: test how much load of something the game is able to support, for example: active sprites in screen, players in mmo games, number of particles, polygons…

Multiplayer: testers ensure that all connectivity methods (modem, LAN, Internet) are working.

Mobile game: includes many of the previous test, but now in a mobile phone platform.

**Bug reports format:**

Part 1: Title and overview
Overview of what, where, why, when and how the bug is generated and how does it affect the game.

Part 2: Classification
In depth analysis of the characteristics of the bug and some contemplations. Here you have to put everything regarding the bug. You also classify the bug depending on how it affects the game and its priority compared to other bugs.

Part 3: Generation
A comprehensive and easy to understand guide on how to replicate the bug.

Part 4: Extra information
Any data you think would be useful regarding the bug, you put it in here. You can also write your opinion on how to solve the issue.


## Bibliography

http://wiki.c2.com/?QualityAssurance

http://wiki.c2.com/?QualityControl

http://wiki.c2.com/?QualityAssuranceIsNotQualityControll

http://www.gamasutra.com/blogs/DanFelder/20151012/251443/Design_101_Balancing_Games.php


https://en.wikipedia.org/wiki/Game_testing
https://www.testbytes.net/blog/game-testing-tutorial/
https://www.t-plan.com/game-test-automation/
https://www.usertesting.com/blog/user-testing-games/
https://gameanalytics.com/blog/how-to-do-a-game-test.html



