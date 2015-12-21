A digital 3D FPS level I worked on by myself from October 2015 to December 2015 (Work in Progress)

Hill 262 is a project I worked on to teach myself Unreal Engine 4. The project is an FPS level built in Unreal 4 using only the default 
provided assets, some downloaded and altered sound files, and one free pack of downloaded foliage models. These assets were combined to 
make something slightly more than a graybox level, but less than a finished product. By building a level and doing some programming 
using Unreal’s Blueprint system, I was able to teach myself the ins and outs of the game engine. The premise of the wider game this 
level would be in is that WWI took an extra ten or so years to end. As a result, the US underwent a communist revolution, taking it out 
of the war much like Russia in 1917. After the war ended, mainland Europe blamed the outside nations like the US and Russia for 
prolonging the war by staying out of it, and banded together under a fascist, racial community not unlike early, pre-war Nazism, though not 
specifically Anti-Semitic. The level is set in an alternate 1966 during WWII where a communist coalition of the US, Canada, Western 
Spain, and Russia has invaded mainland Europe to conquer the fascist alliance and its capital in Paris. In the level, the player plays
as Henry Cunningham, a Captain in the Red Guards Company, similar to US Army Rangers. The player is tasked with holding a strategic hill
(Hill 262) from a counterattack by an elite armored division while the company awaits reinforcements. The player must strategically fall
back up the hill to numerous phaselines to try and stall the enemy until the relive can arrive. The level takes inspiration from the old
WWII-set Call of Duty games, specifically the Call of Duty 3 level, The Mace.

This project was personal work that I was doing between school assignments, so I was responsible for the implementation of everything. 
I placed all of the assets and wrote all of the code. However, I did not make any of the sound or visual assets, instead using the 
provided material in Unreal or downloading them from sources like SoundBible.com (though I did alter most of the sounds in Audacity 
before using them). As this level was supposed to be essentially a graybox, I did not construct models or sounds, though I did make a 
few particle effects using Unreal 4’s editor.  Instead, I focused on the placement of assets, layout of the terrain and environment, and
the flow of the gameplay. The gamplay of the level is supposed to mirror that of most modern shooters; i.e. light and fairly arcadey 
with lots of cover to utilize. Furthermore, I spent much of my time working on the tone of the level, adding in roughly seven pages of 
dialog, scripted triggers, and visual cues to drive the atmosphere home. The level has triggers sprinkled throughout to drive the 
narrative forward with either dialog or particle effects and sounds, or both. In addition, several of the triggers turn particle effects
on or off to optimize the level as much as possible.

While the project was enjoyable and enlightening, it was not without its problems. Firstly and most importantly, the Blueprint system in 
Unreal 4 is somewhat difficult to transition to from more traditional methods like MonoDevelop or Visual Studio. While the node system 
is easy for simple things like adding or destroying actors or checking for collisions, I was unable to implement actor movement. I 
would have liked to create a simple waypoint to show general enemy paths. Furthermore, the level progression is currently entirely 
scripted; that is to say, the plot and visuals don’t progress until the player crosses a trigger. I would like to get actor movement 
to work (followed by actor collision with the player’s bullets) and try to implement a system where the player is able to stay wherever
he or she desires, with the level’s story progressing around him or her. My final goal for the level is that the player would be forced
to retreat up the hill due to enemy pressure and not scripted requirements. I would like it if it would be possible (but incredibly
difficult) for the player to stay on a lower phaseline until the relive arrives and ends the level. In addition, the default “FPS”
build for an Unreal level is problematic. The bullets’ collisions are too large, meaning that they catch on various bits of cover when 
they should be able to fly over. Finally, the player model is too small, making it very difficult to have cover that the player can see
over, but not jump over. I would like to refine both of these elements to have consistent cover that the player can fire over, but not 
jump over.
