# Pac-Man
This is a software engineering course project, and my team and I will try to make a Pac-Man game from scratch


Software architecture

1.	Main software components and their functions:
    •	Game engine component: responsible for handling the logic and process control of the game, including handling player input, controlling the movement of the game objects, calculating scores and the end of the game.
    •	Game elements: including Pac-man, beans, obstacles, enemies, etc., are encapsulated as classes, and have their own attributes and methods.
    •	User interface: including menu, scoring board, timer, prompt, game screen, etc., used to interact with users and display the game status.
    •	Input / output module: responsible for reading player input, saving game status and reading game configuration files, etc.
    •	Sound module: used to play the game sound, sound effects and music.
    
2.	Specifies the interface between the components:
    •	Game engines and game elements: Game engines invoke game elements to process game logic and render game elements.
    •	Game engine and sound module: The game engine plays the game sound, sound effects and music through the sound module.
    •	User interface and input-output module: The user interface reads and saves the game status and configuration files through the input-output module.
    •	Game engine and sound module: The game engine plays the game sound, sound effects and music through the sound module.
    
3.	Data stored by the system, and how to store it:
    The system needs to store the following data:
    •	The status and attributes of the game elements, including the location of Pac-man, the location of beans, the location and status of enemies, etc.
    •	Game status, including the current level, score, health, time, etc.
    •	Game configuration, including sound effects, difficulty, graphics, etc.
    Data can be stored in a local file so that the player can save and restore the game status. If you need to synchronize the game status between multiple devices, you can store your data on a cloud server. If you need faster read and write data, you can use relational or non-relational databases.
    The advanced database schema is as follows:
    •	Table of game elements: store the location and attributes of the game elements.
    •	Game status table: store the game status, including the current level, score, health value, time, etc.
    •	Game configuration table: store the game configuration, including sound effects, difficulty, graphics, etc.
    
4.	As hypothesized, we can determine that the following underpins our chosen architecture：
    •	Object-oriented programming: We assume that we use object-oriented programming to implement games, so we need to design classes of game elements and organize and manage code through the encapsulation of the class.
    •	C + + Programming Language: We assume that C + + is used as the primary programming language, which is because C + + is a high-performance programming language that provides excellent game performance and flexibility.
    •	OpenGL and SDL libraries: We assume that the OpenGL and SDL libraries are used to implement game graphics and sound effects, because they are widely used game development libraries that provide cross-platform support.
    •	Graphics design software: We assume to use graphic design software to design game graphical interfaces, such as Adobe Photoshop or GIMP.
    •	Visual Studio Development environment: We assume to use Visual Studio as a development environment, because it is a powerful IDE, can provide many development tools and plug-ins, can improve development efficiency.
    •	Git versioning: We assume that versioning and collaborative development use Git, because Git is a popular versioning system that can effectively manage code and collaborative development.
    
5.	For each of two decisions, identify and briefly describe an alternative. For each of the two alternatives, discuss its pros and cons compared to your choice:
    Choose to use the C + + programming language, the OpenGL graphics library, and the SDL game development library to implement the game
    • Alternatives: Use other programming languages and game engines to implement games, such as Unity engines and C # programming languages.
    •	Advantages: Using other game engines and programming languages may be easier to achieve some advanced features, such as physics engines, special effects, multi-platform support, etc. In addition, using an off-the-shelf game engine can greatly reduce the development time and workload.
    •	Cons: Using other game engines and programming languages may result in reduced code portability and maintainability. At the same time, it takes extra time and effort to learn new programming languages and game engines.
    

