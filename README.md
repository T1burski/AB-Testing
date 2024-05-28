# A/B Testing: User behaviour in game

![image](https://github.com/T1burski/AB-Testing/assets/100734219/c5399e16-c60a-4450-896c-d2f9fe1ea4af)

This is a hypothesis testing study focused on checking the implications of changing a feature within a game related to user retention and number of rounds played.

The notebook, developed using python, contains all the analyses and conclusions made. Take a look!

The game we are analyzing is called Cookie Cats, a famous mobile game.

In the game, as players progress through the levels, they will occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress.

The experiment made was to change the gates' positions level-wise. Initially the first gate was placed at level 30, but here we are testing the user's behaviour when changing the gate's position from level 30 to level 40. In particular, we will look at the impact on player retention and number of rounds played.

About the data:

The data is from 90,189 players that installed the game while the A/B-test was running. The variables are:

--userid - a unique number that identifies each player.

--version - whether the player was put in the control group (gate_30 - a gate at level 30) or the group with the moved gate (gate_40 - a gate at level 40). When a user installed the game, he or she was randomly assigned to either gate_30 or gate_40.

--sum_gamerounds - the number of game rounds played by the player during the first 14 days after install.

--retention_1 - did the player come back and play 1 day after installing?

--retention_7 - did the player come back and play 7 days after installing?

