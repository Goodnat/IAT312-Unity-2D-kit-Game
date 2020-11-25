# IAT312-Unity-2D-kit-GameEach member’s work done on this iteration
Cynthia (Yuqing) Pan – Graphics, SFX, Slide  
Tianyi Shen –  Graphics, SFX, Slide  
Teng Pin (Eric) Pan – Programming 
Pengyu Li – Programming
Each members’ role in team

Cynthia (Yuqing) Pan          	- Audio & Graphics
Tianyi Shen                          	- Audio & Graphics 
Teng Pin (Eric) Pan             	- Programming
Pengyu Li                             	- Programming

Main Part: The Revised Game Design
        	Player description (No adjustments made)
Design Goal (Aesthetic) based on motivation and demographic variables
Target Audience
Players who are classified as Survivor according to the BrainHex gamer type. 
The ESRB rating for the game will be E (everyone).
Genre / Fun
Survival Strategy with Hard Fun and Challenging (from MDA) as the main source of entailment.
Storyboard
Added a main menu for difficulty selection and game instruction.

The game instruction page that tells the player how to play the game

	Depending on the game difficulty, map generation changes as well (eg. bigger map)


Design Questions
Q1 (Testing functional)  -  How should the change in game difficulty affect aspects such as enemy 'toughness' and spawn rate; amount of obstacles, and food spawn; as well as map generation?
Q2 (Testing functional)  -  Does the change of camera view size drastically affect the player’s decision making (in terms of making the game more challenging)?
Q3 (Balance of gameplay)  -  Does increasing map size, number of enemies, number of obstacles, and slight amount of food available for collecting increase the game difficulty?
Q4 (Balance of gameplay)  -  In terms of the current reward/punishment system for each (Easy, Normal, Hard) difficulty, does the risk, reward, and punishment formula for required food and energy gain/lost feel fair and balanced?
Q5 (Balance of gameplay)  -  Is it fair to force the player to make a play with more limited information presented on screen the harder the game difficulty is?
Q6 (Complete) -  Does the lowered density of food spawn locations by increasing map size motivate the player to make more cautious decision making?
Revised core, secondary mechanics, and features
	Core mechanic
No changes made to the core mechanic
Secondary mechanic
(Revised) - Amount of reward/punishment system varies depending on game difficulty rather than a static conclusion formula.
(Addressing Design Question Q4).
(Revised) - Updated character animation and SFX to enhance system feedback 
(Addressing the issue of poor feedback from Prototype 1).
(Revised) - Updated GUI of the game.
 (Addressing the issue of overwhelmed/overlooking information present on screen  from Prototype 1).
(New) -  Added an instruction option at the main menu before the game begins.
(Addressing the issue of the frustrations and confusions of how the game works from Prototype 1).
(New) - Changed variables affecting the map generation (size, amount of food, enemy, obstacles) will vary depending on game difficulty 
(Addressing Design Question Q1, Q3, and Q6).
(New) - Camera now follows the player rather than showing the entire map creating uncertainty to make the game more challenging.
(Addressing Design Question Q2 and Q5).
Play testing details
        	Setup 
8 sessions (each session is 1 play tester) - 4 through online voice chat/screen share, 4 in person.
Play testers:
Procedure:
1. Indicates that we are testing our game and not their (play testers) skill
2. Ask if they are comfortable with sharing their screen.
3. No introduction/instructions of the game including its game genre, how to play, and what to do is given (for the first few runs, it will be explained in the later run if needed).
4. Observe/Record play testing thoughts.
5. Interview them and ask for their more in depth thoughts.
Name:Celia Gu
Age: 22
Gender: Female
Gamer Type: Casual
Player Type: Socializer
Location: In person

 
Observation notes:
Easy Level:
- When she touches the enemy once, she will lose energy, however, there’s no change if she touches the enemy twice, and she will again lose energy if she touches the enemy the third time. 
Normal Level:
-text and text box are separate 
Hard Level: 
-map is too large? As the map is 24*24, energy is 100, there is not enough energy to walk the whole map around. 
Improve: 
-walking sound could be more obvious 
-in hard level, could add more energy? Shrink the map?or provide some props add energy 



Name: Tiko Lin
Age: 23
Gender: Female
Player Type: Achiever / Achiever-Mastermind
Gamer Type: Casual gamer
Location: Online voice chat
Observation notes:
- The hard level might be too challenging
-Would prefer to be able to see the whole map instead of only a part of it 

Name: Miko Li
Age: 29
Gender: Female
Player Type: Achiever-Conqueror
Gamer Type: Casual gamer
Location: Online voice chat
Observation notes:
She thinks the game is fun because you need to think of some strategies to survive as long as possible
She wanted to mute the sound but there is no way for her to do that
“Some days require her to obtain 5 foods but there are only 4 on the map?”
Cannot exit and restart 
She thinks how your energy would be calculate should be introduced to the player
She was overwhelmed before reading the instruction








Name: Yuxuan Cui
Age: 21
Gender: Female
Player Type: Achiever-Socializer
Gamer Type:
Casual gamer
Location:
In-person 

 
Observation notes:
Excited prior to playtesting 
She is glad there are different levels to choose 
She ignored the instructions 
Confused with the mechanics since she ignored the instructions
After she went through the instruction, everything is clear for her
She likes how the ant is being attacked (animation) which give her clear information that the enemy is dangerous
She is curious why she is awarded a lot of energy if she over-gains food but punishes a little if the expected amount is not achieved. 
She did not notice the information bar initially, she thinks it is better to have a notification of how many foods you have gained, for example, if required food has been gained, there should be something to indicate that.
She curious why the map is not centered

Name: Kenny Zhou
Age: 20
Gender: Male
Player Type: Survivor-Seeker
Gamer Type: Casual gamer
Location: In-person 


Observation notes:
He thinks the game is fun.
If there is a little storyline in the game, it will be better
Or to change a cute character, players are more accepted
It’s better if there are instant reward items

Name: Yindi Yang
Age: 21
Gender: Female
Player Type: Achiever-Seeker
Gamer Type: Hard core gamer
Location: In-person 
Observation notes:
She thinks the game is fun.
She didn't understand the game mechanics at first, but after seeing gameinfo, it becomes clear
She thinks it is too difficult to avoid the enemy
She believes that it needs to be marked, and players have to return to the cave every day to reach the next day.
  
Name: Joshua Nowakowski
Age: 23
Gender: Male
Gamer Type: Casual
Player Type: Seeker - Survivor
Location:
Online voice chat
Observation notes:
- Clear frustration (voice) when playing in hard difficulty
- Interested in the mechanics of food requirement affecting energy points (HP). But he thought the easy difficulty was too easy and hard was too hard.
- Would love to have a mini map.
- Felt the game has an interesting survival vibe to it.
Name: Kevin Chen
Age: 21
Gender: Male
Gamer Type:
Casual
Player Type:
Achiever
Location:
Online voice chat
 
Observation notes:
- Likes the fact that it requires the player to explore the map. Adds excitement.
- Wants more details for the game instructions.
Hard Level: 
- Feels that it was way too hard for someone playing the game for the first time.
 

Analysis of the testing results
 	Overall, the play testers enjoyed some of the changes to the game. However, the play testers also mentioned or demonstrated multiple issues the current version of the game has such as the difficulty balance, desire for specific features, and GUI effectiveness. For instance all the play testers felt that the ‘hard’ difficulty was way too hard, and some felt the ‘easy’ difficulty was way too easy. Moreover, due to the change of camera view and map size, the play tester recommended implementing a mini map feature for better player reference. Other improvements that need to be made in future iterations are GUI layouts, even better system feedback, and more alternative player options.
Reflection
        	If anything, by personally iterating through multiple prototypes, it allowed us to improve our game one step at a time. The biggest benefit of going through multiple iterations is that we were able to better divide up the work (either it’s implementing a new feature, debugging, or improving gameplay) and systematically solve each of the problems we encountered along the way efficiently (as the problem are typically small and more manageable due to small tasks). However, we also felt the pain of developing multiple prototypes and how expensive it is for creating these simplified versions of the final product. For instance, Prototype 1 took us (2 people) nearly 3 days to develop with certain degree of completeness and 90% bug free; Prototype 2 took us another 3 days to implement new mechanics/features, debugging errors and glitches, and polishing the game as much as possible prior to player testings. This process demonstrated why paper prototypes are often more favored than software prototypes in game developments (with exception of certain game genres).
	Playtesting on the other hand has allowed us to either find hidden bus, ask questions that need to be answered, playing the game in ways we haven’t thought of (or intended, and discover new ideas that can be implemented to make the game more fun etc. For instance, in the current version of the prototype, multiple play testers stated the need for a mini map as players can no longer see the entire map anymore. This was something that we wouldn't have thought of (or atleast, not until much later into development of the game) if we hadn’t done player testing in the first place. 
All in all, it should be clear that regardless of the kinds of games we are designing / developing, prototyping and player testing are essential for the game to be successful and fun.

 
Reference
Tutorial
Unity tutorial. Retired from https://learn.unity.com/project/2d-roguelike-tutorial
Graphics
Ant asset. Retired from http://pixelartmaker.com/art/0e138ed36dda51f
Rock1 asset. Retrieved from http://pixelartmaker.com/art/8fd9223acb89db4
Rock2 asset. Retrieved from http://pixelartmaker.com/art/3d079d40b6d7ac5
Grassland asset. Retrieved from http://pixelartmaker.com/art/db00a560c2afd56
Antlion asset. Retrieved from https://www.thelastantlion.com/forum
Fruit asset came from Unity asset store. https://assetstore.unity.com/packages/essentials/tutorial-projects/2d-roguelike-29825
Audio
Ant moving audio asset. Retrieved from https://freesound.org/people/raubana/sounds/82027/
BGM audio asset. Retrieved from https://m.tb.cn/h.VMm8OIk?sm=8da2a5
CollectFood. Retrieved from http://www.aigei.com/s?q=%E6%8B%BE%E5%8F%96&type=sound_game
HitWall. Retrieved from http://www.aigei.com/s?q=%E6%92%9E%E5%A2%99&type=sound&detailTab=file
Lizard attack audio asset. Retrieved from https://m.tb.cn/h.VMm8OIk?sm=8da2a5
Other audio asset came from Unity asset store. Retrieved from https://assetstore.unity.com/packages/essentials/tutorial-projects/2d-roguelike-29825
WalkingSound. Retrieved from http://www.aigei.com/s?q=%E8%B5%B0%E8%B7%AF&type=sound

Articles
8KindsOfFun.com:. (n.d.). Retrieved June 02, 2020, from http://algorithmancy.8kindsoffun.com/
Bartle, Richard A. (2009). Understanding the Limits of Theory. In Chris Bateman (ed.): Beyond Game Design: Nine Steps to Creating Better. Retrieved from Canvas
Ernest, A.(2014) Fundamentals of Game Design, 3rd Ed.. Retrieved from Canvas
Lazzaro, N. (2004). Why We Play Games: Four Keys to More Emotion Without Story. Retrieved from Canvas
Nacke, Lennart E., Bateman , Chris., L. Mandryk., Regan. (2011). BrainHex: Preliminary Results from a Neurobiological Gamer Typology Survey. Retrieved from Canvas
Salen, K., Zimmerman, E. (2003) Rules of Play: Game Design Fundamentals Retrieved from Canvas
Yee, N. Motivations for Play in Online Games. (2006). In Cyber pyschology & behavior, Vol. 9, No. 6. Retrieved from Canvas
 



