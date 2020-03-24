# Godot Airconsole
A Godot node plugin for AirConsole API

Copy/clone the folder godot-airconsole to your addons folder in your godot project.

Now you can:
- Add AirConsole.gd as a singleton
- Or add AirConsole as a node into your main scene (should be available from the Add Node menu)

Connect the Airconsole signal to your scripts. Look at the method and signals available in `AirConsole.gd` file. 
Look at the [AirConsole API documentation](https://developers.airconsole.com/api/api-1-7-0/AirConsole.html).

After exporting your godot project to HTML. rename the .html file to `screen.html` for the game 
and `controller.html` if you use a godot project to make the controller.

### /!\ You'll also need to add this to your .html export.
`<script type="text/javascript" src="https://www.airconsole.com/api/airconsole-1.7.0.js"></script>`
