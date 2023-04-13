# Pac-Man
This is a software engineering course project, and my team and I will try to make a Pac-Man game from scratch

## Project profile
The idea of our project is to develop a C++ version of the Pac-Man game that will provide players with a classic Pac-Man experience and add some new features and challenges. Players will control Pac-Man to eat all the beans in a maze and avoid obstacles and enemy attacks. The game will consist of multiple levels, each with a different difficulty and challenge, and players will need to complete missions within the allotted time to advance to the next level.

## Vision and a competitive analysis
Our vision is to be a wildly popular Pac-Man game that provides players with an excellent gaming experience. We will focus on the following areas to achieve our vision:

**1.Interface design:** We will design a friendly, simple and beautiful game interface for players to easily get started.  

**2.Game Mechanics:** We will add some novel mechanics and elements to the game to enhance the playability and fun of the game.  

**3.Game balance:** We will set a reasonable difficulty for the game to make players feel challenged and accomplished.  

**4.User experience:** We will continuously collect user feedback to optimize the game experience and make players happy and happy.  

Competitive analysis shows that while Pac-Man games are popular in the market, most games have been developed in the last few decades and lack novel and innovative gameplay elements. We believe that by adding new game elements and a better graphical interface design, our games will be different and attract more players.  

## Technical approach
To realize our project idea, we plan to use the following system architectures, technologies, and tools:

**1.System architecture:** We'll use an object-oriented programming approach to encapsulate game elements such as Pac-Man, Beans, Obstacles, Enemies, etc. into classes to better organize and manage the code.

**2.Technology:** We will implement the game using the C++ programming language, the OpenGL graphics library, and the SDL game development library. We will also use graphic design software to design the game's graphical interface.

**3.Tool:** We will use Visual Studio as the development environment and Git for version control and collaborative development.  

## Challenges and risks：
When developing the C++ Pac-Man project on time, the most serious challenges or risks I foresaw were time management and team collaboration. Because the C++ Pac-Man project requires the implementation of many game elements and logic, such as map design, bean and obstacle generation, Pac-Man and enemy movement, score calculation, and so on, it requires a certain amount of time and effort. At the same time, if you need to collaborate as a team, you need to make sure that all members are on the same page and working together seamlessly.  

**In order to minimize or mitigate these risks, I will take the following actions:**  


Develop detailed project plans and timelines to ensure that all tasks and work are completed in a timely manner. At the same time, possible delays or problems need to be taken into account and countermeasures accordingly.  

Use simple, clear code structures and naming conventions whenever possible to make it easier for team members to communicate and collaborate. At the same time, to avoid conflicts and misunderstandings, it is also necessary to establish a unified code style and formatting specifications.  

Regularly check and evaluate the progress and quality of the work of team members, find and solve problems in a timely manner, and ensure the progress and quality of the project.  

Establish a good communication mechanism and workflow, including regular meetings, communication and collaboration, as well as the use of some project management tools and software, such as GitHub, Trello, etc., to facilitate team members to collaborate and track project progress.  


Through the above measures, I believe that the risks of time management and team collaboration can be minimized or reduced, and the project can be completed on time, and the quality and user experience can be obtained.  



## Software architecture

**1.	Main software components and their functions:**
    •	Game engine component: responsible for handling the logic and process control of the game, including handling player input, controlling the movement of the game objects, calculating scores and the end of the game.
    •	Game elements: including Pac-man, beans, obstacles, enemies, etc., are encapsulated as classes, and have their own attributes and methods.
    •	User interface: including menu, scoring board, timer, prompt, game screen, etc., used to interact with users and display the game status.
    •	Input / output module: responsible for reading player input, saving game status and reading game configuration files, etc.
    •	Sound module: used to play the game sound, sound effects and music.
    
**2.	Specifies the interface between the components:**
    •	Game engines and game elements: Game engines invoke game elements to process game logic and render game elements.
    •	Game engine and sound module: The game engine plays the game sound, sound effects and music through the sound module.
    •	User interface and input-output module: The user interface reads and saves the game status and configuration files through the input-output module.
    •	Game engine and sound module: The game engine plays the game sound, sound effects and music through the sound module.
    
**3.	Data stored by the system, and how to store it:**
    The system needs to store the following data:
    •	The status and attributes of the game elements, including the location of Pac-man, the location of beans, the location and status of enemies, etc.
    •	Game status, including the current level, score, health, time, etc.
    •	Game configuration, including sound effects, difficulty, graphics, etc.
    Data can be stored in a local file so that the player can save and restore the game status. If you need to synchronize the game status between multiple devices, you can store your data on a cloud server. If you need faster read and write data, you can use relational or non-relational databases.
    The advanced database schema is as follows:
    •	Table of game elements: store the location and attributes of the game elements.
    •	Game status table: store the game status, including the current level, score, health value, time, etc.
    •	Game configuration table: store the game configuration, including sound effects, difficulty, graphics, etc.
    
**4.	As hypothesized, we can determine that the following underpins our chosen architecture：**
    •	Object-oriented programming: We assume that we use object-oriented programming to implement games, so we need to design classes of game elements and organize and manage code through the encapsulation of the class.
    •	C + + Programming Language: We assume that C + + is used as the primary programming language, which is because C + + is a high-performance programming language that provides excellent game performance and flexibility.
    •	OpenGL and SDL libraries: We assume that the OpenGL and SDL libraries are used to implement game graphics and sound effects, because they are widely used game development libraries that provide cross-platform support.
    •	Graphics design software: We assume to use graphic design software to design game graphical interfaces, such as Adobe Photoshop or GIMP.
    •	Visual Studio Development environment: We assume to use Visual Studio as a development environment, because it is a powerful IDE, can provide many development tools and plug-ins, can improve development efficiency.
    •	Git versioning: We assume that versioning and collaborative development use Git, because Git is a popular versioning system that can effectively manage code and collaborative development.
    
**5.	For each of two decisions, identify and briefly describe an alternative. For each of the two alternatives, discuss its pros and cons compared to your choice:**
    Choose to use the C + + programming language, the OpenGL graphics library, and the SDL game development library to implement the game
    • Alternatives: Use other programming languages and game engines to implement games, such as Unity engines and C # programming languages.
    •	Advantages: Using other game engines and programming languages may be easier to achieve some advanced features, such as physics engines, special effects, multi-platform support, etc. In addition, using an off-the-shelf game engine can greatly reduce the development time and workload.
    •	Cons: Using other game engines and programming languages may result in reduced code portability and maintainability. At the same time, it takes extra time and effort to learn new programming languages and game engines.
    
## Software design  

The components involved in our program mainly include game engine, scene manager, input manager, interface manager, sound manager, archive manager, etc.  

Among them, the game engine is mainly written in C language and is responsible for processing core functions such as game logic and rendering images, and the scene manager is responsible for loading game scenes, managing game objects, and collision detection. The input manager is responsible for processing input from the user's keyboard and mouse. The interface manager is responsible for displaying the game screen, game UI, score, and game end interface. The Sound Manager is responsible for playing game sounds.  

The types that may be involved are: game loop abstract type, renderer class, input processor class, game object abstract type, collision detector abstract type, controller class, mover class, input event abstract class, input device abstract type, sound effect abstract type.  

## Coding guideline
For the programming languages used in our project, we chose the following coding specification guidelines:  

C++: Google C++ Style Guide ( https://google.github.io/styleguide/cppguide.html)
We plan to implement these guidelines in the following ways：Establish a code review system: Before each code submission, team members are required to conduct a code review to ensure that the code complies with the specification guidelines.  

## Process description (revisions)
### i. Risk assessment
Likelihood of occurring (high, medium, low).
    High  

Impact if it occurs (high, medium, low).
    Low  
   
Conduct user experience surveys, including aspects such as game graphics, sound effects, and operation methods, considering how to provide users with a pleasant experience in the game.  

Understand the existing similar small games in the market, including their advantages and disadvantages, user evaluations, player groups, etc. This can provide reference and improvement directions for product development. Develop marketing strategies, including how to attract players, promote the game, and improve the game's retention rate.  
Find more users of relevant age to experience the project and summarize their opinions to modify the game.  

#### Mitigation plan should it occur.
##### •	Identify the problem: Firstly, it is necessary to clarify what the problem with the game is. The nature and severity of the problem can be understood through testing and user feedback.
##### •	Prioritize: Based on the severity and scope of the problem, the work to fix the problem should be given the highest priority.
##### •	Teamwork: Let team members work together to solve the problem and improve the efficiency of problem-solving.
##### •	Replan: If the problem cannot be solved quickly, it is necessary to replan the project, reallocate resources and work priorities to ensure that the project can be completed on time.
##### •	Timely communication: Communicate timely and transparently when problems arise to avoid misunderstandings and delays. If necessary, seek external help, such as consulting other developers or professionals.
##### •	Allow buffer time: When planning, allocate buffer time for possible problems to prevent the plan from being delayed due to unexpected problems.

### ii. Team structure
•	Wei Zheyang--programmer: Responsible for translating the game designer's ideas into actual games. Programmers need to code Pac-Man to allow the game to run on a computer.  

•	Li Xiang--Game designer: Responsible for designing the game scene and characters, and determine the rules and difficulty level of the game.In Pac-Man, designers need to determine the number and location of beans, the rules of the ghost, the game score system, and more.  

•	Lu Zhenghang--Tester: Responsible for testing the game program, identifying and reporting on bugs and other issues, and ensuring the stability and quality of the game program.  

•	Gu Qian--Art designer: Responsible for drawing the game materials, including characters, maps, items, etc., as well as beautifying the game UI and visual effects.In Pac-Man, the graphic designers need to design the background of the maze, the images of beans and ghosts, and so on.  

•	Li Xinyu--Copy editor: Responsible for writing the game introduction, instructions, help documents, etc., as well as the text content needed in the game.  

### iii. Test plan & bugs
#### •	recovery testing  

As a system test, the recovery test mainly focuses on the various conditions that cause the software to fail, and verifies that the recovery process can be performed correctly. In particular cases, the system needs to be fault-tolerant. In addition, the system failure must be corrected within the specified time period, otherwise it will lead to serious economic losses.  

#### •	security testing   

Security tests are used to validate protection mechanisms within the system to prevent trespassing. In security tests, testers try to break into the system, using various ways to break through the line. Therefore, the criterion for system security design is to try to make the cost to invade the system more expensive.  

#### •	integration testing 
The program module is assembled with the appropriate integration strategy to test the correctness of the system interface and the function of the integration. The main purpose of the integration is to check whether the interface between the software units is correct.
#### •	Systematic testing
This includes testing the functionality, performance, and the software and hardware environments where the software runs. Most of the time is in the system test execution stage. Functional tests, regression tests, performance tests, and other non-functional tests are included.
#### •	reliability test 
The reliability of the software indicates the reliability to which a software system can perform its functions according to the requirements and objectives of the user design. In theory, reliable software systems should be correct, complete, consistent, and robust.
#### •	 unit testing 
Eliminate the logical and functional errors and defects in the local modules.

