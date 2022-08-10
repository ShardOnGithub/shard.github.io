# Welcome to my tutorial on how to edit my Friday Night Funkin' Scratch Test Engine!

You're probably here because you didn't understand or needed help with my recently published Friday Night Funkin' Test Engine. Look no further, you've come to the right place. Also, this tutorial is mainly focused on people who have probably never used Scratch before.

### The Link to the Original Scratch Project (you may follow along with this tutorial)

https://scratch.mit.edu/projects/720611318/

Click "see inside"!

### Sprites

Sprites are objects in the game that play a role in letting us see how the game functions. In this case, Boyfriend.
![image](https://user-images.githubusercontent.com/110993906/183939759-46c0c688-8602-4f1c-b9e0-fd1901d9a5d6.png)

You are free to change the sprites (because it's a test engine, why wouldn't you be?), and edit the code to make sure they work. To change the sprite, first grab these two pieces of code:

![image](https://user-images.githubusercontent.com/110993906/183940518-df99af8d-71e5-4230-aec1-b55eb4a40df1.png)
![image](https://user-images.githubusercontent.com/110993906/183940551-f865565f-0cc0-429f-875c-8b2e0ec973e4.png)

Open the backpack by clicking on it, then put the scripts in (it's at the bottom of the screen)

![image](https://user-images.githubusercontent.com/110993906/183941034-493b341c-08e9-4cc0-84c7-5c4ce17fb06d.png)

Now, delete the "Boyfriend" sprite. Go to the "sprites" pane on the right, and click Boyfriend's sprite (if not already clicked) and a trash can icon should appear. Click it and Boyfriend is gone.

![image](https://user-images.githubusercontent.com/110993906/183942627-3eb067a8-ef71-43b8-a64e-dfa777f1326e.png)

If you want to draw your own sprites, do that and skip this, but if you want sprites from another mod, go to the Funkipedia Mods Wiki. Once you're there, go to the mod the character's from. When you reach the character page, be sure to click on the image, and wait for the image viewer to appear. Right-click (or double-tap the mousepad) the image and click "Save image as..." Name it anything you want. I'm not responsible for that.

An example of the image viewer:

![image](https://user-images.githubusercontent.com/110993906/183944676-d0b6ce09-9245-457e-8b70-984a534bea18.png)

Note that for some people, the file may come out as a ".webp" file, which Scratch does not support. Try to find a converter online (I recommend ezgif.com)

#### Importing the Sprites
It's not difficult to import sprites. Once you're back at the Scratch project, look at the bottom right. You should see these two buttons:

![image](https://user-images.githubusercontent.com/110993906/183945953-c5847910-16b7-4e82-95ea-b043523465e6.png)

The one to the left is for sprites, and the other for backgrounds (we'll get to those later). Hover over the button, and find this icon:

![image](https://user-images.githubusercontent.com/110993906/183947180-a49c0ed2-6f09-4c91-bd8c-bb177c5342ab.png)

Find your character .gif in the folder you downloaded it in, select it, and press "Enter". Loading text that says, "Importing" should pop up. Once it's done, it will take you to the sprite's costumes, meaning every frame of the gif will show up in separate pngs. If they are not in order, order them by the number at the end of your costume name. If you want it to be a bit smoother, change the image to "Vector" (bottom left of screen).

#### Editing the Code

Remember the scripts you put in your backpack? Open the backpack and drag them onto the coding grid. Once that's done, go to variables. (Left hand side of window)

![image](https://user-images.githubusercontent.com/110993906/183953921-87e2152f-c659-4e55-a6a3-f84d75edd3c2.png)

Rename the "Timer" and "NextBeatTime" variables to your character's name. For example, if I did Disability Dave, the name would be "Timer (Disability Dave)" and "NextBeatTime (Disability Dave)".

##### Editing Keybinds

The second script you should've dragged is the poses script. Basically if you press the key that is on the "when _ key pressed" block, it plays an animation. Change it to whatever keybind you prefer. Next, go to the "repeat until _ " block, and change the "key _ pressed" input to the keybind on top. Remember to duplicate the scripts and edit them to make them enact the desired animation.

### Backdrops

Basically the background of a song. It's just like getting sprites.

### Importing .mp3 files

Find the .mp3 file for your song. (I recommend this site: https://downloads.khinsider.com/friday-night-funkin) Remember the sprites button? Next to it, is a backdrops button, and the backdrops _pane_ is above it. Click it, then go to "Sounds" on the top left. Hover over the bottom left button, and find an upload icon. Your mp3 should be in it once done! (Remember to change the "start sound" block's output and the bpm (block labeled "set tempo to _ "))
