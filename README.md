# MG6

1. the entire for loop must complete before Update can advance to the next frame, making the game lag as it has to take an extremely long time to execute a single frame.
2. since code simply turns off the player's collider when the player is moving upwards, it allows the player to pass through any object with a collider, not just platforms. 
