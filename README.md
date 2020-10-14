# PROCESS

## BRAINSTORMING

### Expansion Phase

- The _brainstorming_ process started with the _expansion_ phase.
- The objective was to come up with a twist on the classic shoot em up genre.
- In this phase, I jotted down almost anything that made enough sense to be put up on paper and made a chart of my ideas.
- It finally came down to looking like this:

<center>
<img align="center" src="chart.png" alt="chart" width="200"/>
</center>

## Collection and Collison Phase

- I shortlisted a few final ideas(or themes) from the previous phase.
- Then, I thought of ways in which the themes could be combined to create interesting game ideas.

### Results:

#### **Time-loop/ Inversion/ Space shooter:**

- A game that is played once forward in time and once backwards.
- In the second half, you catch the bullets that you had earlier shot. The bullets glow when they are ready to catch, you need to move to the line of sight such that the enemy is in the path to kill them.
- You end the game where you began.
- (Slightly inspired from the film Tenet and it’s temporal pincer movement)

#### **Thor/ Tower defense/ Ricochet:**

- A game where Thor has to protect the Infinity stones from Thanos and his army.
- A top-down view, Bullet Hell game.
- Thor’s hammer ricochets between enemies.
- As his health decreases, it ricochets off more enemies and deals damage.
- (You could refuse to pick up a health powerup in order to deal more damage)

#### **Thor Platformer/ ability switch:**

- A Thor platformer, ShootEmUp.
  You can throw the hammer to hit long range enemies.
- When you don't have the hammer, you cannot jump high enough. But you deal more close range fist damage(Lightning punches?).
- The idea is to strategically switch between 2 modes based on the situation.

## FINAL IDEA DISCUSSION:

- The final game idea was decided to be a top-down shooter with a level based progression.
- The core mechanic of the game was that the player's weapon has different abilities at different healths.
- For example, the bullets would have a larger spreads or there might be more powerful laser projectiles or say missiles/ricochet etc
- This idea of tradeoffs would make the player take risks and and avoid picking up healthpacks in order to clear out the enemies faster.

## MIDPOINT RETROSPECTION:

- Upon play testing, the controls seemed a bit constrained and very restricted. So I decided to change the control scheme from only keyboard to keyboard and mouse.
- The level based progression and fixed enemies didn't feel like the right way to go as I felt that in such a game structure, some kind of puzzle element is the only thing that can make it interesting.
- So I decided to completely scrape the game and do an endless shooter style top down game with random enemy spawns.
- I also added a critical health power where the gun does massive damage to get out of tight corners.

## Final Game and Issues:

- I was planning on getting several weapon types that have various fire modes, but could implement only the main weapon with three fire modes.
- The "Scatter-shot" effect of the gun was difficult to implement as the force added to the bullets with offsets seemed to be the only thing that worked close to how I wanted it to. (Other methods included having a bullet spread prefab that did not seem to work)
- Could not get the enemies to face the player, move towards and converge around him. I included the script to do this but for some reason, Unity wouldn't allow me to add the 'Player' object to the enemyscript. (Struggled with this for a day.) I could however manage this by adding the code to the EnemyManager script but that did not seem to be working quite right, so for now, the enemies are stationary and fire downwards.

## Future updates:

- To include more weapons that have complex fire modes like chaining in between enemies, ricochets etc.
- Make enemy ai move towards player and around objects(NavMesh?) and fire more intelligently.
- Try converting the game back into Level based progression with some puzzle elements and Boss battles.
