# MP2 design process

I designed my levels to have 4 stages. The first one is an island of pursuers. I designed this stage like this with the strategy of having to run away from the pursuers because although it is possible to kill all the pursuers, there is much risk at hand because one hit could potentially kill you because of stun lock.

The second stage is an island of mortars. The level should normally be easy because (if you walk in a straight line) it is not very likely that the projectiles will land on you. However, I mitigated that by adding a lot of collectibles this stage in order to increase the likelihood that you would be hit by a projectile.

The third stage is an island of chargers (my custom enemy that rotates until it finds you and runs at you). This stage, similar to the first one, is designed with the strategy of having to run away from the chargers instead of killing them.

The fourth stage is a mini-boss stage where the mini-boss is larger than normal. Because of the mini-boss's size, it is impossible to jump on its head and kill it by jumping normally. I implemented a collectible that gives you a temporary jump boost that spawns when you kill an enemy on the fourth stage. There is also a jump boost to get from the middle island to the fourth stage.

I made the game so the finish line only drops when the boss is dead. However, you can only complete the game if you collected all the collectibles, which I implemented in order to frustrate the player a little bit. If the player does not have any enemies left on the fourth stage, they have no choice but to die and start over from stage 1.

I also chose not to respawn all the enemies and collectibles upon dying (aside from the jump boost to get to the fourth stage). I did this because, while testing, the boss stage was a little abnormally hard, so I thought it would not be fair if the player had to start over all the way from the beginning every time they died. This would definitely be very frustrating and I think not respawning all enemies/collectibles was the right choice for the player's sanity.

There are three kinds of collectibles: score collectibles, health collectibles, and jump boost collectibles. These are all pretty self-explanatory, but the jump boost collectibles are a little extra I added to the game in order to complement the boss stage.
