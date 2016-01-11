![logo](https://github.com/Myasis/BeamNES/blob/BeamNES/img/logo.png)

** Disclaimer: There are NO ROMs or Emulators included with this package **


** Beam Plays NES Games **

You have to download an emulator like: Nestopia.  You can find it on Google, not hard to find.
You will also need the ROM file for the game you want to run.

** Setup **
These are the steps you have to complete to get it to work.

0. Make sure to have Python 2.7.11 installed
1. Get yourself [Nodejs](http://Nodejs.org) and Java
2. Download this project as a zip file
3. Unzip it.
4. Open a terminal/cmd in its folder
5. Write a config file in config/ called default.json follow the default.sample.json for a guide.
6. Open up your emulator and go to the keymapping!

We use 'I', 'J', 'K', 'L' for directions. '[' for start, ']' for select. The 'A' & 'B' buttons will be 'A' & 'B'.
If you want to type things, you will have to stop it completely with CTRL-C

** Beam plays NES: **
Setup the emulator mapping like this:

![player controlls](https://github.com/Myasis/BeamNES/blob/BeamNES/img/BeamNES-Controls.png)

** Use **

1. Launch the rom on the emulator.
2. Set Beam to Interactive mode etc. (TODO: Once site is live)
3. Run the command prompt and move to your BeamNES directory. Run the bot with `node index.js` or your Operating system's equivelant. 
4. If you see 'Connected to beam' you're all good and can start playing.
5. If you see any messages or errors your setup may be incomplete or your config file may be missing or misconfigured. Refer to the default.sample.json config file to see how one should be layed out. (in the /config folder)
6. Leave the window open and it'll report button state changes.
7. Make sure the emulator is in focus, which means, click on it so it is the active window. If anything else is active, the keystrokes will go there instead.

** Games Tested **
Final Fantasy I
Dragon Warrior