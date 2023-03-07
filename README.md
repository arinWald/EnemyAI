# EnemyAI
![R](https://user-images.githubusercontent.com/99820809/223563084-eb3e7480-8bfa-46fc-9500-b902ed6b288f.jpg)

## What is an AI?
An AI (Artificial Intelligence) is a computer program or system that can perform tasks that normally require human intelligence, such as recognizing speech, identifying images, making decisions, and learning from experience. AI systems use algorithms and statistical models to analyze data, identify patterns, and make predictions or decisions based on that data.
![AI](https://user-images.githubusercontent.com/99820809/223563165-fd90a7c3-1233-4f4a-850b-de9733404cef.jpg)

There are different types of AI, such as:
* **Rule-based systems**: these use a set of predefined rules to make decisions or perform tasks.
* Machine learning
* Deep learning

### Some examples of AI... or not AI?
Alexa --> Yes
Self-Driving car --> Yes
Youtube recommendations algorithm --> Yes
Calculator --> No
Programmable coffee maker that can brew coffee on a schedule --> No
Thermostat --> Yes!

#### Why the thermostat?

A thermostat is an example of AI because it can perform a task that would normally require human intelligence (regulating temperature) without human intervention.

In general, any system that can sense its environment, make decisions based on that information, and perform a task without human intervention can be considered an AI, regardless of how simple or complex its algorithms may be.

## Why do we need an AI for videogames?

AI has transformed the gaming experience by allowing developers to create smarter and more realistic non-player characters (NPCs), which can interact with players in more sophisticated ways. AI can be used to create more personalized gaming experiences by analyzing player data and providing tailored content.

Basically: create more engaging and enjoyable gaming experiences. Good AI in video games is about creating believability and immersion rather than just creating a challenging opponent.

### Quick look to the past
#### Space Invaders - 1978
Stored patterns to simulate arbitrary enemy movement. Space Invaders, 1978, was one of the first games to make use of this and kickstarted the evolution of AI in gaming.

[Space Invaders Gameplay](https://www.youtube.com/watch?v=MU4psw3ccUI&feature=youtu.be&ab_channel=GameArchive-NoCommentaryGameplay)

#### Pac-Man - 1980
In 1980, Pac-Man also hit the arcades, bringing AI into a complex maze game, allowing the colorful characters involved to exhibit different personality traits.

![pacman_500px](https://user-images.githubusercontent.com/99820809/223563383-9bdbb45e-18ac-4c39-ad80-ac7eba1e204b.jpg)

#### The Sims - 2000
Heavy reliance on AI allowed the player to assume the role of an omnipotent being from the comfort of their own home, able to watch their characters live their own independent lives with minimal required input.

![R](https://user-images.githubusercontent.com/99820809/223563467-50d40ba5-0756-4f0e-bcb4-4ea901cbd907.png)

### **More complicated and unpredictable player behavior:**

#### Grand Theft Auto
Seemingly thousands of individual NPCs going around about their business in the beautiful Los Santos, existing in their day-to-day lives regardless of player presence, with their reactions to the player, and all the inevitable destruction, designed to be as realistic as possible.

#### Alien Isolation 2014
Adaptive AI and unpredictable. Evolves and learns during the game. The AI system creates a sense of tension and fear in the game and is widely regarded as a remarkable achievement in video game design.

[Smart Xenomorph Move](https://www.youtube.com/watch?v=lOedyccpBuw&ab_channel=Ghaddy)

[How Xenomorph learns throught the game](https://www.youtube.com/watch?v=xS_I9yOmtjE&ab_channel=MelodicMizeryPs3Vids)

## Why do we need an AI for our RPG’s?
Turn-Based RPG's are not the most exciting games because of their combat system. To make this interesting, a good enemy behaviour is the key. Challenges the player in many ways and forces it to use all the resources it has.

[We don’t want this kind of battles (Dragon Quest VIII)](https://youtu.be/R6rYzl_BUog?t=292) where the player only attacks and the enemy attacks and nothing else.

[Here’s a different example (the first boss is a good example)](https://www.youtube.com/watch?v=0gvW2sIQ7po&ab_channel=FelipeNascimento). This Final Fantasy VII Boss has more variation. It has an ability that targets one single enemy to attack (Search Scope) and the most exciting thing here is that suddently his tail elevates. When this happens, the player should not attack him; otherwise it will get counterattacked. 
This adds more complexity layers and makes a more interesting battle.

![Advance_Wars-58b981f84e38e](https://user-images.githubusercontent.com/99820809/223563691-94b32498-2cfc-44f8-a60c-042af6b2690c.jpg)

Not only you can focus on attack but in the defense too. In advance wars, you can win the game by either killing the enemies or destroying their base, the one the enemies should defend.

### Scaling difficulty of the RPG trough enemy AI
A simple way to scale difficulty is through the enemy stats, and thats ok, but boring.
Just by giving them more attack, more health and so is not the best way to improve the difficulty. However, we can be more creative.Another way is to improve their AI, here are some ideas.
* Focus on the healer first
* Use positioning strategies like surrounding
* Use items by itself or use some buffs
* Focus on the weakest character
* Defend their own allies or heal them
* And many more possibilities…

### Tactical RPGs - Things to take into account
![final-fantasy-tactics-advance-13 big](https://user-images.githubusercontent.com/99820809/223564238-a11af8db-8c36-471b-aae8-30d7f6379cfc.jpg)
* Enemies have to know the player’s position
* Know if the terrain is “cheap” of “expensive” and decide the best way to travel (pathfinding). 
* Does the terrain have any advantages that modifies the gameplay?
* Know the stats of themselves and the characters’
* Is Melee: prioritizes closing the distance to the target
* Is Manged: prioritizes keeping a distance from the target

### Tactical RPGs - Things to take into account
* Everyone’s stats (enemies and allies)
* Timing (FF vs DQ)
* Position --> [Chrono Trigger has a system where the enemy positioning is important](https://youtu.be/083D9MO6Ths?t=1959)
* Items available to use
* Buffs and debuffs
* Turns economy (if the enemy or the allies can attack twice, or once, or none etc...)

**The key is to design with a purpose in mind (applied to every kind of design) Think what we want the player to do or thing during the battle**

---

Let’s imagine that we want an enemy that is strong but slow. _Makes an attack every 2 turns and frequently his attack is critical._ **What we want the player to do?** 
* Think carefully what to do in those turns and take risky decisions. 
* Try to focus more on defense rather than attack.

Different strategies:
* Use first turn to attack and second to defend?
* Attack two times but risk of insta-kill an ally?
* Use both turns to save strength, get attacked, strength again and then huge attack?

Another example: _a ranged enemy that is always far from you and you cannot attack ranged._ **What we want the player to do?** 
** Surround the enemy to the map limit and do not let it move.

Strategies:
* Move all your units for only one enemy
* Having to move from one point to another
* Surround it

[Dragon Quest VIII dragon boss example](https://youtu.be/fJqr027sgPw?t=292)
Here the dragon has the hability to remove the party buffs. It also has two turns.

[Mario And Rabbids: Kingdom Battle - Rabbid behaviour example looking for coverage](https://youtu.be/vuMnHPNaqh0?t=12560)
In this example, the enemy always looks for the nearest coverage before doing anything else. The player can take advantage from this by predicting the next enemy move.
[Same happens here](https://youtu.be/vuMnHPNaqh0?t=11423)
This enemy always moves towards the nearest player or the one who has attacked him.

# How to build an enemy AI
## The Monte Carlo Search Tree Algorithm

AI can function in many different ways, but on the whole, and in gaming in particular, it all comes down to decision making. Usually based on the probability of success from the outcome.

Before making a move against a human opponent, the computer builds out a tree that predicts the likelihood of success of each potential move thereafter. 
For example, if a computer needs to decide whether to defend, build technology, or attack, it will create a tree diagram to simulate each potential outcome. In this instance, attack has a higher probability of reward than the other variables, so that's what it decides to do. Once the computer has attacked and the player has chosen their next move, the computer will start building the tree once again.

![monte-carlo-search-tree-algorithm](https://user-images.githubusercontent.com/99820809/223564885-8f716f4f-0947-4fb1-93eb-cfdc646a5caa.png)

**Possible uses of this algorithm**

* Create the perfect enemy
* Maximum difficulty

---

## How a Flow Chart Works
A Flow Chart is a visual representation of a behavior or an algorithm. With AI, it can be used to represent the decision flow that the AI makes based on different inputs and situations.

>The Monte Carlo Search Tree can be applied into a Flow Chart.

![Captura de pantalla 2023-03-07 231039](https://user-images.githubusercontent.com/99820809/223565088-1f93a332-26fc-4a87-a2f7-132e7b482aa0.png)

In general, there are a few types of blocks:

* Start and End (defines the beginning and end)
* Step (what happens or what action is performed)
* ??? (conditional block)
* Comment

**In the end, a flow chart can be translated into If, else, for’s, whiles, etc in a programming language.**

Recommended tools:

[Gojs](https://gojs.net/latest/samples/flowchart.html)

[Smartdraw](https://cloud.smartdraw.com/?nsu=1)

# Let's create an enemy (from the presentation)
## Previous ranged enemy flow charts
> The following images are placeholders. They will we changed for the ones done in the class presentation

### Ranged enemy (tactical rpg)
![image6](https://user-images.githubusercontent.com/99820809/223565296-4853a9d2-f876-4a1c-b5e4-18a0c3ec9a1f.png)

### Strong slow melee enemy (turn-based rpg)
![image3](https://user-images.githubusercontent.com/99820809/223565342-b4a13d4e-b6c8-4453-8c7c-4942a73c931b.png)


## Conclusions
**Always Remember:**
* Make it fun and interesting
* Have a clear purpose when designing
* Use a state diagram first
* **_“I strongly encourage people to think more of "interesting behaviors" than "AI". You want units that move in interesting ways, perform memorable activities, and present unique challenges that require different approaches than other units.”_**  By Reddit User TheMaster42LoL

## Webgraphy and interesting websites to expand knowledge

[Google Slides Presentation Link (Please acces with the UPC mail)](https://docs.google.com/presentation/d/1aJIVstgZRtikvVOLOiIABWozvTRzPAmTMc7HX_8zWjo/edit?usp=sharing)

[Enemy AI Design - RPG Maker Forums](https://forums.rpgmakerweb.com/index.php?threads/enemy-ai-design.124200/)

[Enemy Design - MegaCatStudios](https://megacatstudios.com/blogs/retro-development/enemy-design-101-apeels-court)

[ChatGPT - OpenAI](https://chat.openai.com/)

[Artificial Intelligence in video games - Novatech](https://www.novatech.co.uk/blog/business/artificial-intelligence-in-video-games/)

[Importance of artificial Intelligence in gaming - Coolsmartphone](https://www.coolsmartphone.com/2020/07/17/importance-of-artificial-intelligence-in-gaming/)

[The importance of articifial intelligence of gaming - GND-Tech](https://gnd-tech.com/2021/10/the-importance-of-artificial-intelligence-in-gaming/)

[The perfect organistm the AI of Alien Isolation - GameDeveloper](https://www.gamedeveloper.com/design/the-perfect-organism-the-ai-of-alien-isolation)

[How does the AI in turn based RPGs Work - Reddit](https://www.reddit.com/r/gamedev/comments/enabqz/how_does_the_ai_in_turn_based_rpgs_work/)

