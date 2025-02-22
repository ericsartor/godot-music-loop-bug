Godot project files at root level.

To reproduce, with Node and NPM installed, go into the "music-bug-test" folder, run `npm install` to install dependencies for the file server, then `npm run dev` to run the file server.

The behaviour is that the music only plays once, then never loops, depsite looping properly when opened and run in Godot engine directly.
