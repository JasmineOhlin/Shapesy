# Shapesy
 
## **Idea** 
Small puzzle game inspired by Towers of Hanoi.  

#### *Game* 
Rods with stacked badges containing a symbol.  
Below the rods a vertical pattern of symbols are shown, for example heart, star, circle.  
The badges needs to match up with the patterned showed. When all badges on all rods are sorted according to the pattern below each rod the level is completed.  
The badges will have extra space (height) to allow more stacked badges.


#### *Rules* 
Only the top badge of each rod can be moved.  
Badges can only be stacked on top of eachother while there's room on the rod.  
All rods need the correctly sorted badges for the level to be cleared.  
Only one badge can be moved at the time.  


#### *Limitations* 
No level will be unsolvable.  
There won't be any outside changes to the initial or current state.  
All information is given to the player/AI at the start.  


## **Problems**  
#### *For Player/AI* 
The first problem the Player/AI will face is unsorted symbols with the goal of having them sorted.  
The second problem is how to move the badges in the most effecient way to reach the goal.  
For Players a third problem would be to redo moves when realizing that the wrong path was chosen.  


#### *For Programmer* 
Setting up a playable prototype.  
Finding an algorithm that can look at the current state and the final state and solve the problem with the best possible path.  
Lack of art/3D models. May lead to having to switch the visual representation of the game. For example single coloured spheres instead of badges with symbols.  


## **Goals** 
To create a puzzle game that has a best solution.  
To create an AI/algorithm that finds the best solution.  
To create a calm and slow paced game, it should not be fast or unpredictable.  

