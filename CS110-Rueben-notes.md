# CS110 — The Development Road

## Rueben

Personal record; not a submission receipt.

## Before the next challenge.

### My name
Rueben

### A question I want to resolve
How does one connect to their work like a bystander?

## Recall. Question. Recalibrate.

### What have I completed?
I have completed my notes on 11A.

### My explanation of classes, objects, data and actions
To be honest, I have no idea what to connect from my engine.

### My questions, answers and remaining uncertainty
How do I put code from Visual Studio into Unity?

### My personal GitHub repository URL
https://github.com/DemonicAssets/Week-11-Repository/tree/main/Action%2011B/New%20folder

### Readiness check
I ran Unity and saved a scene. 

## Replace Chapters with Pipelines
Attention First, Chapter 3, pp. 37–41.

### What I understand from this chapter
I understand how you have to have certain pipelines into your project for it to drawn audiences with your work more than how certain other classes do it.

### My opinion and reasons
I agree with how you have to create a story in order for your project to draw more attention. 

### A decision I can apply
I could talk about the setting of the game first, then later I would show the main character and what he's currently doing before telling their backstory afterwards.

### A question or next investigation
How can I expand my character's backstory?

Whiteboard: export CS110-Rueben-pipelines-board.png separately.
Concept of a shealth game.

## Design for the Attention Economy
Attention First, Chapter 6, pp. 53–58.

### What I understand from this chapter
I understand how people can not be interested with something if it doesn't fully get their attention.

### My opinion and reasons
I can agree how certain aspects of a game can be a reason for someone to get disinterested, like showing too much information, a dead opening, or no visible progression.

### A decision I can apply
I can make sure to add enough information to where it applies to my game, while also making sure it doesn't overload the story it is telling at hand.

### A question or next investigation
I could make sure to have each character to have enough backstory while also not being too much for the player.

## Identity and the Creator Loop
Attention First, Chapter 7, pp. 61–69.

### What I understand from this chapter
I understand that Identity can affect ones work and that it can help them with creating ideas.

### My opinion and reasons
I can agree that in order to to have an identity, you have to find it yourself.

### A decision I can apply
My response demonstrates that there's a way to find yourself by using your ideas and creating them on a canvas.

### A question or next investigation
I can find out more about myself by creating.

## Designing Your Teams and Tools
Attention First, Chapter 8, pp. 71–74.

### What I understand from this chapter
I understand that you have to communicate with your group in order for you to tell what your visions and ideas are in a different person's point of view.

### My opinion and reasons
I can agree that communicate is key to creating a project with a group.

### A decision I can apply
I can tell my group about what I came up with and they can give me feedback in return.

### A question or next investigation
I could show them examples of my vision and see what they can change or keep.

## The Human Operating System
Attention First, Chapter 11, pp. 93–103.

### What I understand from this chapter
Not recorded

### My opinion and reasons
Not recorded

### A decision I can apply
Not recorded

### A question or next investigation
Not recorded

## Bring something to the summit.

### The connection across the readings
Not recorded

### Evidence I am ready to show
Not recorded

### My board in words
Not recorded

## Choose where you want to go.

### My direction
Join a lead

### The mission I want to explore
It is for a group that I'm acquainted with.

### My pitch
Find what kind of idea we want to use - create storyboards for said idea - communicate on what to keep and what not to keep.

### Conversations and decisions
I can speak with the lead for any ideas that they have in mind.

## Agree on the work.

### Team name / solo mission
Humans System Check

### Agreed lead / my name if solo
Leah

### Accepted members and contributions
Lead - Team lead
Rueben - Art Lead
George - Coding Expert
Chris - Whiteboard Organizer
Andy - Image Editor
Caleb - Music
AI - Assisting in Coding and Organization

### How the literature strengthens this team
Chapter 7 explains that Identity develops through consistent actions, responsibility, and learning from mistakes. This encourages our team to take responsibility for our contributions. Chapter 8 explains that successful teams need people with different skills and  tools that serve a clear purpose. We can apply this by dividing responsibilities, communicating clearly, and helping each other develop our project. Chapter 11 also emphasizes the importance of human judgment when using technology, which reminds us to use AI as a helpful tool rather than letting it make every decision.

### Communication and check-in plan
Our team will communicate through a group chat and during class meetings. We will use Github to share our work and keep track of changes. We plan to check out progress weekly, discuss any problems, and make sure everyone understands their responsibilities. Leah will help coordinate the team, While George, Chris, Andy, and Caleb will contribute to the project and share updates on their progress.

### Team GitHub URL, or Working solo
https://github.com/DemonicAssets/Week-11-Repository

## Make the Attention Accord.

### Purpose and smallest playable result
Our goal is to create a video game where the player controls a character who catches criminals. The player will move around the environment, chase a criminal, and capture them. When the criminal is caught, they will disappear or stop moving, and the player&#39;s score will increase. Our first playable version will focus on movement, chasing, and capturing one criminal.

### My attention promise
Our main question is whether the player can successfully chase and capture a criminal. We will test this by creating a simple playable scene and recording whether movement, collision detection, and capturing work correctly. We will share screenshots, gameplay recordings, and test results with our team to identify problems and make improvements.

### Time and dependency plan
Our first step is to create the player character and basic movement controls in Unity. Next, we will add a criminal character, movement behavior, and a capture system. We will work on these features during class and outside of class, checking our progress weekly. If something does not work, we will simplify the feature, troubleshoot the code, and ask teammates for help before moving forward.

### Board explanation and contributors
Our mission board shows the sequence of our game: the player enters the environment, finds a criminal, chases them, and captures them to earn points. Each step depends on the previous one working correctly. Our team consists of Leah, George, Chris, Andy, and Caleb. We will collaborate on programming, gameplay mechanics, testing, and improving the game. Our board will help us organize responsibilities and track our progress.

## Translate the mission into code.

### My story-to-code map
Our main objects are the player and the criminal. In Unity, we will use GameObjects with C# scripts such as PlayerController and CriminalController. The player will have properties like movement speed, position, and score. Methods will control movement and capturing criminals. When the player presses movement keys, Unity&#39;s Update() method will detect the input and move the character. When the player touches a criminal, a collision or trigger event will activate the capture method. The criminal will disappear, and the player&#39;s score will increase.

### What I am borrowing and why
We will use Unity&#39;s built-in physics and collision detection features to help create our game. These features are provided by Unity Technologies and are part of the UnityEngine namespace. We will use components such as Rigidbody and Collider to detect when the player reaches a criminal. We will also use Unity&#39;s Transform component to control character positions. These built-in tools will save time because we will not need to program movement and collision detection completely from scratch. We will check our Unity version and use its official documentation.

### Object lifetime and responsibility
When the game starts, the player and criminal objects will be created in the scene. The player will remain active throughout the level, while criminals can be removed after being captured. New criminals may appear as the game continues. We will use Unity&#39;s Destroy() method to remove captured criminals or reuse objects if needed. We will test the game to make sure criminals disappear correctly, the score updates, and no unnecessary objects remain in the scene.

## Make one moment playable.

### What I expect to happen
When the player presses WASD or the arrow keys, the character will move around the environment. The player must chase and catch a criminal. When the player touches the criminal, the game will detect the collision and capture them. The criminal will disappear, and the player&#39;s score will increase. This creates a simple gameplay loop of moving, chasing, and catching criminals.

### What I built and where it lives
We are developing our game in Unity using C# scripts. Our project will contain a main scene with a player character, a criminal character, and a basic environment. We plan to create scripts called PlayerController.cs for movement, CriminalController.cs for criminal behavior, and GameManager.cs for scoring. These scripts will be stored in the project&#39;s Assets/Scripts folder. We will also save screenshots and gameplay recordings as evidence that the game works.

### A difficulty and my response
One difficulty we may encounter is getting the collision detection between the player and criminal to work correctly. We will investigate by checking the Collider and Rigidbody components in Unity and reviewing our C# scripts. We will adjust the collision settings and test the game again. Our goal is to make sure the criminal disappears and the score increases whenever the player successfully catches them.

## Test what you are claiming.

### My test record
We will test the player&#39;s movement using WASD and arrow keys to make sure the character moves correctly. Next, we will test what happens when the player tries to capture a criminal from too far away. We expect nothing to happen until the player gets close enough. When the player reaches the criminal, the capture should activate, the criminal should disappear, and the score should increase. We will also test repeated interactions to make sure the same criminal cannot be captured twice. We will record our results using screenshots and gameplay recordings.

### My improvement experiment
One improvement we want to test is making the criminal capture system more reliable. We predict that adjusting the collision detection and capture distance will make the gameplay smoother. We will experiment with different detection ranges and test whether the player can capture criminals consistently. We will compare the results before and after making changes to determine whether the improvement works.<

### Promised versus returned evidence
Our original goal was to create a playable game where the player can move around, chase criminals, and capture them. We plan to provide evidence through screenshots, gameplay recordings, and testing results. These will demonstrate whether movement, collision detection, and scoring work correctly. Our next steps are to fix any problems we discover, improve criminal movement, and make the gameplay more engaging. We will compare our progress with our original goals to make sure we are delivering what we promised.

## Return with work you can explain.

### My final access and file check
Our project is a Unity video game where the player chases and captures criminals. We plan to organize our Unity project files, C# scripts, screenshots, gameplay recordings, and mission board in GitHub. We will also download our personal reports and editable backups. Before submitting, we will check that all required files are included, the project opens correctly, and the GitHub links work. We will review our files to make sure we are only sharing appropriate project information.

### My next decision
After this mission, I want to continue improving our video game by adding better criminal movement, more challenging gameplay, and additional levels. I also want to improve my C# programming skills and learn more about Unity&#39;s features. Our next goal is to make the game more interactive by adding animations, sound effects, and a better scoring system. We will continue testing the game and fixing problems to create a more complete and enjoyable experience.
