**Working title**: Steal the honeycomb

Have draft version of doc ready by next Tuesday, Feb 17th.
https://bc.instructure.com/courses/2696556/pages/final-overview?module_item_id=100967134

Follow AI Agent in Unreal (tyrant)(bear)
**win** condition: Get honeycomb into house
**loss** condition: the tyrant collides with the player
Formal Elements
**Players**: 1 player
**Objective**: carry honeycomb to house
**Procedures**: Players can move, jump, and change direction (look). They need to navigate around boulders and trees
**Rules**: Can't move through other objects
**Resources**: collecting the honeycomb causes the door on the hut to disappear. Going in the hut causes win condition.
**Conflict**: Knocking over a log to create a bridge is required to get to the honeycomb. the bear is activated as soon as the honeycomb is collected.
Boundaries: Digital game using Windows PC monitor for output. Speakers for audio. keyboard and mouse input.

Dramatic Elements
**Challenge**: Low challenge. Someone with basic familiarity of WASD based games should be able to beat the game in 5 minutes.
**Premise**: The player wants honey in their oatmeal. They recall a beehive outside within walking distance.
**Character**: A hungry for honey flavored oatmeal robotic human
**Story**: Linear story
1. Talking bubble shows "This oatmeal needs honey. bad." over a small hut in the woods.
2. Humanoid comes out of the hut and controls show up on the screen.
3. Controls are dismissed as they are pressed by the player.
4. Humanoid collides with the log, knocking it over and creating a bridge over the creek.
5. Humanoid eventually collides with the honeycomb.
6. Humanoid either collides with home => win, or collides with bear => loses
7. UI comes up to replay the game
World Building (doesn't apply)
**Dramatic Tension**: Bear chases player

Bear: Intermediately charging.
Max Walk Speed: 500cm/s => 2500
Max Acceleration: 1500 => 2000
Braking Deceleration Walking: 2000 => 10
Ground Friction: 8 => 16
Rotation Rate (Yaw): 500 => 5 (this causes the movement to bug out. Likely going to ignore this setting instead of finding a fix)
Capsule Radius: 35 => 80 (This causes MoveTo to fail to A* to a path where it's collider can fit. Need to look into a fix)
