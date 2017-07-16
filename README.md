# Welsyre

  My first attempt at making a multiplayer, browser-based game. I don't code with HTML + CSS often, because im more of a backend development kind of guy, so the aesthetics, I will admit, are complete shite. Also the fact that the only times I touch HTML or CSS is during a school project, should explain why the coding practices isn't up to standard :)
  
  
  This was supposed to just be a small project for me to learn about multiplayer programming using nodejs; Because of that, and the fact that a lot of its early code is made of spaghetti, its currently abandoned. It was a good learning process though, and now just something to show off.



  The game itself was coded with a data-oriented design in mind. So it uses an entity-component system(Its not perfect, this project was one of my earlier forays into DOD and ECS), which once in place, I could easily create components with various properties without editing the source files itself, but instead, adding a json object to the database.
  
It Uses:


-NodeJS as the server backend.

-SocketIO to connect the players to the server/ game session + matchmaking.

-Mongodb as the database.

-Passport for authentication

-Canvas for displaying the game.

-... and several others I might have forgotten.


===========================================


Features in place:

-Basic matchmaking

-Account creation + login system

-Database for logins, and sessions

-Database for basic components of the space ship.

-Very rough and basic gameplay (Extremely unoptimized code)

-Multiplayer (The whole game is multiplayer)

(Going to add more information later.)
