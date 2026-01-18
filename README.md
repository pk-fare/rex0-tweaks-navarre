# Rex0 Tweaks: Navarre
A Tweak of the Moveset for Navarre in Super Smash Rex. Below you can find a Video detailing the changes done to Navarre in my Tweaks, as well as the exact changes done. There may be more of these kind of Edits to characters in the future, but this is the first of it's kind in my repetoire of creations. Feel free to use this at your leisure, and please credit if possible. If there is no credit that is also fine, but do NOT claim this as your own work please. 💖

# OVERVIEW VIDEO
[![ZeroFaultz Navarre Tweaks Overview Video](https://img.youtube.com/vi/6CTFHoGeDgo/0.jpg)](https://youtu.be/6CTFHoGeDgo?si=T2SjVpr7pzqlpE8E)

### Tweaks Synopsis

From my understanding of the character, Navarre is a highly oppressive character with Large amounts of potential for Mixups and Extensions using Side Special.
His frame data, attributes and damage output seems to indicate that as a sword fighter, navarre is meant to be solely focused on live reactionary punishes. Ones that decimate opponents in rapid speed as he applies a bit of pressure through tight spacing and movement. Something that other characters in his franchise seem to only do partially. 
Despite this, Navarre sometimes feels as though something is missing within his Kit to make him feel completely unique in how he handles opponents. As well as a glaring issue in terms of how Navarre functions.
Two problems I look to tackle personally here.

- Navarre's Attack Hitboxes and Range. Navarre has a large sword, and a significantly smaller dagger. Both of these tools are disjointed quite a bit, as well as surprisingly active. 
This can lead to characters being hit in positions where it does not seem correct.
This affects game feel rather extensively for both Navarre and his opponent. I'd like to retract some of that disjoint to promote a closer game of combat during gameplay. As well as provide a bit of leighway toward the opponent. Allowing for closer punishes even if by a short bit.

- Navarre's Movement Options. Not specifically his attributes, but his movement when using Side Special. On the ground and the Air the Special can feel a little stiff, more notably in the Air. Causing a bit of clunkiness when using this variant of the move 
specifically. I'd like to free up that clunkiness in the air, but also allow for more alterations on the ground that aid in navarre's potent mixup potential as well as giving him a tool or two that helps him stand out a bit more amongst the cast of characters in his type.

The content presented may change in the future. The changelog will also update when this is the case.
Hopefully these changes are something that can be enjoyed by all who like playing Navarre, as well as those who may have an interest in him.
With these changes, I hope to make Navarre a more interesting character who thrives on spacial awareness and movement mixups. While also rewarding precisely timed extensions and setups. As well as making him a bit more interesting to fight as well, as a core problem he does have as a moveset addition to me, seems to be his lack of variety in how he plays as well as how he is played against.

# Change-Log

<details><summary>Tweaks Update 1.0: Balance Adjustments and P+ Design Attempts</summary>

- Jab

Changed Damage from 4 to 5
Changed Jab Startup, used to be Frame 3 is Now Frame 5.
Changed IASA from Frame 25 to Frame 26
Changed Base Knockback from 60 to 35
Changed Knockback Growth from 60 to 55

- Dash Attack

Changed IASA from Frame 49 to Frame 52.

- Forward Tilt

Changed IASA from Frame 29 to Frame 32

- Up Tilt

Changed IASA from Frame 31 to Frame 34

- Down Tilt

Changed IASA from Frame 20 to Frame 24

- Forward Smash 2

Changed IASA from Frame 31 to Frame 40

- Down Smash 

Changed Second Hit Base Knockback from 76 to 58
Changed Second Hit Knockback Growth from 95 to 80
Changed IASA from Frame 46 to Frame 52

- Neutral Air

Reduced Knockback Growth from 122 to 116
Changed Landing Lag from 16(8) to 18(9)

- Back Air

Reduced Knockback Growth from 105 to 102

- Forward Throw

Changed Angle from 50 to 54
Changed Base Knockback from 60 to 90
Changed Knockback Growth from 60 to 68

- Back Throw

Changed Damage from 4 to 5
Changed Angle from 63 to 51
Changed Base Knockback from 70 to 80
Changed Knockback Growth from 60 to 70

- Up Throw

Changed Damage from 4 to 6
Changed Angle from 87 to 85
Changed Base Knockback from 60 to 75
Changed Knockback Growth from 130 to 110


- Down Throw

Changed Angle from 70 to 58
Changed Base Knockback from 65 to 85
Changed Knockback Growth from 110 to 90


- Side Special (Ground)
    ->  Side Special (Special Variation)

Secondary Attack changed IASA from Frame 31 to Frame 40
Secondary Attack changed Base Knockback from 82 to 78

- Up Special 2 (Descent)

Moved late Hitboxes to frame 27.
Added Middle hitboxes that send at angle 361 with 7 Damage, 96 Knockback Growth, and 70 Base Knockback at frame 24

- Up Special 3 (Landing) 

Adding Landing Hitbox that last for 5 frames starting at frame 1.
This hitbox being: 6 Damage, 80 Knockback Growth, 50 Base Knockback and 0.5 Hitlag Multiplier</details>

<details><summary>Tweakes Release: Hitbox Adjustments and Mechanical Additions. </summary>

- Jab 

Z-Offset for Hitbox ID 2 adjusted to 8.0 from 10.0

- Forward Tilt

Z-Offset for Hitbox ID 2 adjusted to 8.0 from 10.0
Adjusted startup for hitbox to frame 3.55 from frame 3.0
Adjusted hitbox termination timing of hitboxes to frame 5.25 from frame 5.0

- Up Tilt

Z-Offset for Hitbox ID 2 adjusted to 8.0 from 11.0
Startup changed to frame 4 from frame 3.
Changed synchronous timer for hitbox duration from 4 frames, to Asynchronous frame 7.

- Down Tilt

Z-Offset for Hitbox ID 2 adjusted to 8.0 from 9.0
Changed Synchronous timer for hitbox duration from 3 frames to Asynchronous frame 6.
Reduced recovery from frame 23 to frame 20.

- Neutral Air

Z-Offset for Hitbox ID 3 adjusted to 5.15 from 6.0
Z-Offset for Hitbox ID 4 adjusted to 6.0 from 10.0
Y-Offset for Hitbox ID 101 adjusted to 3.65 from 5.0

- Forward Air

Z-Offset for Hitbox ID 3 adjusted to 8.0 from 10.0

- Back Air

Z-Offset for Hitbox ID 3 adjusted to 8.0 from 10.0

- Up Air

Z-Offset for Hitbox ID 4 adjusted to 12.0 from 13.5
Removed Hitbox IDs 4,5 and 6 at frame 3 of the move.
Reduced the Knockback Growth of the move to 92 from 100. 

Down Air

Z-Offset for Hitbox ID 3 adjusted to 9.0 from 11.0

- Side Special (Ground)

Allowed Variation if Special Button is pressed at frame 9 or later.
Allowed Variation if Shield Button is pressed at frame 9 or later.

- Side Special (Shield Variation)

Added Dash Action, Provides 15 frames of intangibility after 5 frames of startup, as well as momentum.

- Side Special (Special Variation)

Frame Speed Modifier applied after Hitboxes have terminated.
Added Initial Attack Action, with same hitbox data as Forward Smash 1, omitting a raise in base knockback.
Initial Attack having a Frame Speed Modifier of 0.5 after hitboxes Terminate.


Frame Speed Modifier applied after Hitboxes have terminated.
Added Secondary Attack Action, with same hitbox data as Forward Smash 2, omitting a raise in base knockback. Initiated by Attack button press, during Initial Attack Action.
Initial Attack having a Frame Speed Modifier of 0.5 after hitboxes Terminate.

- Side Special (Ground) Down and Attack Variation

Changed the angle of the hitboxes to angle 114 from angle 30.

- Side Special (Air)

Allowed Specific Interrupt, Air Dodge at frame 4.0</details>
