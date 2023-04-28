# RTOSFinalProjectWeek5

CHANGES:

Added status bar for magnitude of platform velocity & loss condition for moving too fast
Added status bar for foundation health 
Added victory condition for evacuation after hitting the foundation enough times or the castle directly once
Added negative impulse imparted onto platform by railgun shot
Added shield functionality
Removed shield because it didn't fit the parameters of project. Proper implementation will come shortly.
Attempted to add scaling to display task - may be working, needs more testing
Fixed collision detection being optimized out
Polished castle drawing

PROJECT COMPLETION: (19.65) + 7.25 hrs / 36.75 = 73.1% finished.

ANALYSIS OF TIME ESTIMATES VS LOGS Satchel based on position: Estimated time - .5 hrs | Real time - 1.5 hrs | 3x Environment variable tweeking : Estimated time - 2hrs | Real time- .5 hrs | .25x Platform based on position: Estimated time - 3 hrs | Real time - 1 hr (Nearly complete) | .33x Weekly upkeep: Estimated time - .70 hrs | Real time - .5 | 0.7x

Shield: Estimated time - 3 hrs | Real time - 2 hrs | 0.66x
Castle and state machine: Estimated time - 2 hours | Real time - 2 hrs| 1.0x
A lot of time was spent on fixing various things and tweaking stuff | Real time - 3 hrs | 1.0x
Weekly upkeep - .7 hrs | Real time - 0.5 hrs | 0.7x


STATUS: This week consisted of a lot of work with graphics and making the statemachine for the game. The graphics were fun to implement because I enjoyed the process of getting coords from a pixel art drawing and turning it into code. The statemachine was relatively straightforward because I could get away with stalling once the victory or loss conditions were met, and having the SM do very little until that point. I will put in a few more hours polishing over the weekend but the game is in a playable state and I am very happy with my results thus far. With enough work this weekend I am confident that I will be done either on time for demo on Wednesday or earlier (Prefer earlier so I can start studying for finals)
