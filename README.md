Download Link: https://assignmentchef.com/product/solved-csce693-gameobject_02
<br>
<ul>

 <li>Complete the following tasks associated with the “gameobject_02” project using the “sol” template library:

  <ol>

   <li>(15) Create a static member variable in Game class that stores a sol::state for the Lua interpreter. This state should be initialized (i.e., libraries should be opened) in the constructor.  Initialization also includes reading and processing the “config.lua” script.  If the script fails, throw an exception!  Catch the exception (if thrown) in the main() function – the program should exit if this happens.</li>

   <li>(15) Modify the Chopper, Tank and Pacman classes so they create their own texture for what is to be drawn. In other words, remove the code associated with passing a filename to the constructor that specify a particular image location.  The signature for all 3 constructors should be (const float xpos, const float ypos, const float xvel, const float yvel).</li>

   <li>(70) Modify the Game::load_level() method so that it reads and creates all the game objects defined in the “config.lua” script. In other words, it iterates over the gameobjs list (as discussed in class) and creates the game objects defined.</li>

  </ol></li>

</ul>


