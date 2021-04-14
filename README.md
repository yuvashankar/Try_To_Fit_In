# Try to fit in

Try to fit in is a farce of the modern corporate world. You play as an outsider who wants to improve the company, but must also try to fit into the hypoxic echelons of management.

# Development

I built this game in 7 days without having any prior knolwedge about Unreal Engine 4. It was an experiment to determine how quickly one could learn, develop, and ship a product on Unreal.

One of the key design tenants that I had to adopt was to "always have a product". Video Games are never complete, there is always something that the artist would like to add or remove from their work. 


Since I focued on constantly shipping a product, I would prioritize work making a complete product rather than making something that would improve the experience. For example, I focused on including a movie in the beginning of the game over learning about animations. While the animations are somewhat left to be desired in this experience, the game would be less enjoyable if the user didn't have the title movie to give any sort of general direction to the player. During the final day, when I was supposed to do the animations, I experienced a power outage at my house, which is very rare. Although it was unfortunate that I was unable to sneak in animations, at least I had a product that I could show. 


Another aspect that was woefully missing in this game was the lack of source control. Since I was moving quickly trying to learn about the unreal engine, I did not consider CI to be useful in such a small project. But as I came to learn, there were many examples where CI would have been vitally important. This game was rebuilt from the ground up 3 times during this week. Over the course of the week the following events occured which made me wish I had installed source control on the project to help me revert.

1. A power outage corrupted the main level
2. I accidentally deleted the floor collission, and my player character would fall through the environment every time they spawned
3. I somehow accidentally deleted the entire level when trying to work with the control rig plugin. 

In the future, no matter how small the project, I plan on learning and using source code control. The ability to roll back and revert any changes is invaluable. 

# Credits
I wasn't developing this project entirely in the dark. There are several resources that I used to get me started. 

1. The character class was created with the help of the [Unreal Engine FPS Game Tutorial](https://docs.unrealengine.com/en-US/ProgrammingAndScripting/ProgrammingWithCPP/CPPTutorials/FirstPersonShooter/index.html)

2. The Quick Time Event was nearly a direct copy from this [guide](https://www.youtube.com/watch?v=GKkZDXz-lOA&t=376s)

3. The environment is called "[Office Scene](https://unrealengine.com/marketplace/en-US/product/office-scene)" and was downloaded on the Unreal Engine Marketplace it was free to download at the time of writing. 