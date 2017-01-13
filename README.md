# Dota-2-Game-Regression-Model

#Introduction
The dataset that I picked for this experiment is something related to a game called DoTA2. DoTA2 is a massively multiplayer online role playing game(MMORPG). 
During the game, 10 players are split into two teams of five and the main objective of the game is to defend your base and the same time take down the enemy's base.
Each player is represented by a hero, or "champion", to carry out the objective. During the game, players can have various of methods to collect gold, or money, 
so that along the way they can purchase upgrades that boost their heroes. For example, every one minute mark there will be a wave of smaller unit, or soldiers, 
that will march out both bases and help their heores on their objective, respectively. So, hero that killed these units will get an amount of gold, and this is called last hit. 
The more last hit a hero gets, the more gold it will earn (more units killed = more gold). Players can also collect gold from killing another hero unit or destroying a building that 
is defending the enemy base. Therefore, at the end of the game, the system will calculate the gold that a hero unit earned during the game per minute. We called it gold per minute(GPM). 
Currently in the game, there are 113 unique hero units that players can choose from. One of the hero is called Anti-Mage, and it is one of the most picked heros in the game. So, my experiment 
here is to predict the GPM for Anti-Mage based on some given attributes.
