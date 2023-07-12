# PokemonJS
A Javascript version of Pokemon, which I will be building up slowly with Vanilla JS.

26 Jun
Began project.
Created outline of project.
Began working with audio.
Added both walking audio and battle audio.
Began adding grid for movement.

TO DO: Finish working on grid.
Add final win conditions.

27 Jun
Worked on Grid, both U/D and L/R movement works correctly.

TO DO: Plan final win conditions
Plan and create battle scene.
Formulate encounter rate.

29 Jun
Planned victory condition to be defeating trainer.
Created battle screen with two health amounts and two action options.
Created encounter counter and battle activation.
Need to be positioned next to trainer to activate final battle.

TO DO: Work out battle results and turns.
Continue working on battle scene.
Add experience bar and add levelling up.

30 Jun
Added Experience and Level divs, added experience and level growth.
Added attack and health values, which grow as level increases.
Reworked battle functions to be more logical.

TO DO:
Set enemy turn on and off.
Continue working on battle functions.
Add fightTrainer on and off variable with battleend fighting trainer allowing for Victory on win.

10 Jul:
Switching between battle and movement states via switching movementState on and off.
The battling system works, with pauses for victory and levelling up text.
FightTrainer state allows for selection of final trainer enemy when in front of trainer, and defeating trainer enables victory conditions with "trainer defeated" text.
Working on fadein/out CSS.
Added fadein/out on click.

Combined all DIV squares into 1.
Began converting to DIV graphics.
Player and Trainer are on the board as Divs, and player div moves correctly.

TO DO:
Work on switching battle background on and off when needed.
Add battle options to battle background.
Limit healings to 3.
Show healing quantity.
Convert music to on/off button with movement state shifting starting music.
Revert to Start Button at start.
Have extra layer in front to hide game before pressing start.

11 Jul:
Added transition to battle start and battle end.
Battle background changes z-index when needed, with correct transition delay.
Transition now cooperates with the fight and heal buttons.
Heals are limited to 3, when heals are reduced to 0 no more heals allowed.
Heal quantity is shown, with message when quantity is 0 and heal is attempted.

Background changed to be trees.
Trainer and enemy trainer changed to emoji faces instead of black sqaures.

TO DO: 
Have Fight Trainer button only appear when near to trainer, and hide when not near.
Convert music to on/off button with movement state shifting starting music.
Revert to Start Button at start.
Have extra layer in front to hide game before pressing start.
Clean up page and finish.

12 Jul:
Have fight button only appear when near to trainer.
Changed defeat div change to player emoji position change.
Reverted to Start Button at start.
Have extra layer hiding the game before pressing start.
Music is altered by both the movement state and by the push of either the play music or stop music buttons
Finished cleaning up.

COMPLETE.