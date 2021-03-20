# DualStickCombatControl

Description:  
The game camera will be similar to how it is in Arms (directly behind the player). The left stick will be used for general movement as well as providing a directional input for attacks. The right stick will be used for performing attacks. Different attacks can be performed by moving the stick in certain ways (e.g. a 360 degree movement can allow the player to perform a spin attack. Paired with the left stick, the player can move in a desired direction while performing a moving variant of the spin attack). Right stick movements will be evaluated after the right stick has approximately remained in the end position for a quick duration or has gone back to a neutral position. The end position of a stick movement will have a stick angle threshold to determine if the end position has been held long enough. Players can cancel right stick movements with the press of a shoulder button. Players must return the stick to neutral if they wish to perform a different right stick action.

More Examples:  
1) Holding the left stick towards the left or right direction will call for a walk
2) Holding the left stick upwards puts the character in a jumpsquat animation  
a) Returning the left stick to neutral will call for a jump if the command does not change into a walk
3) Double tap with left stick calls for a burst movement option in the desired direction
4) There is no burst option downwards
5) Downwards input from the left stick calls for a crouch
6) Flicking the right stick calls for a fast attack that aims at the desired direction  
a) A slash attack will travel in the same, or at the least a similar, angle as the angle at which the player flicked the right stick  
b) A projectile will be aimed at an enemy’s direction-side  

Ideas:  
- Compound right stick movements  
  - Kind of like hunting horn where there are different combos for songs
  - Perform the compound movement by pressing a button after the movements have been performed
  - Vertical movement -> Horizontal movement (and vice versa) = Plus movement
- Visual Interface for player to see what right stick command they’ll be inputting
