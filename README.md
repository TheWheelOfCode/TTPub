# games
Please read these instructions first before asking for help.

Here’s how you get the sound pack up and running for you. The tt.tin file might also help you with any other muds you play. I is my global, used for all muds, tt file.
And without further ado…

Make sure You have Xcode installed before executing these steps.

Step 1: Install Homebrew
Go into terminal and type:

ruby -e " $(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install) " 

  If you have Mac big set or later, do this:

Nano ~/.zshrc

That’ll open or create a file. In that file, type:

export PATH=/opt/homebrew/bin:$PATH

Hit Control x to close the file and follow the prompts.

Step 2: install tt++

brew install tintin

Step 3: Install Sox

brew install sox

Step 4: Make a "games" folder in your home directory, and put everything in this route directory in that folder.

Step 5. Run the game

Go into terminal and type:

tt++ games/tt.tin
That will start up Tintin and load my global scripts for all muds.

Step 6. Connect to a game

Due to the tt.tin file that you should have already loaded and that Miriani is already set up for you, you just need to type “connect Miriani”, without the quotes.
If you want to add other worlds, type “add world without the quotes.  (Going to work on a blank .tin file being created in the worlds/world name-world url folder that is created upon world creation via the terminal client).
If you want to delete a world: delete world name. (Going to make it so that the folder to which the world belongs is deleted too, or maybe where you are given a prompt as to what you want done with it.)
If you want to see your world list, just type “connect”. 
And here are a few other notes:

F9 - Volume status:
Shows the current volume. Shows in the format of 0.x signifying a percentage.
Example 0.20 would be at 20 percent volume. You can go above 1.0 (100 percent)
but I wouldn't advise it. I also wouldn't advise goign or trying to go below
0.0 (0 percent), as that might break something on your system, and I am not responsible for
that.
F10 - Mute/unmute:
Toggles soundpack state - muted or unmuted. Simple enough.
F11 - Volume down:
Lowers the volume by 0.05, or 5 percent. Again, I am not responsible if you
attempt to lower it below 0.0 or 0 percent.
F12 - Volume up:
Raises the volume by 0.05, or 5 percent. Again, I am not responsible if you
raise it above 100 percent.
Option tab moves you through the multiple muds you may have up.
