A digital 3D FPS level I worked on by myself in Unreal Engine 4 (October 2015 - December 2015, August 2016 - September 2016)
Due to the size restrictions of GitHub, I have not yet uploaded the actual level. In addition, an ongoing issue is preventing me from uploading the walkthrough videos. The level requires Unreal Engine 4 to run. The project is older, so UE version 4.10 is required to run the level, at least without tuning it post-download. It should be noted that the low frame rate and quality in the videos is just an artifact of the video capturing (OBS). The quality of the video was kept low to allow for easier uploading. The level runs at a consistent 60+ fps on the "Production" lighting setting, only dipping to about 55 fps once or twice when most of the particle effects are active and in frame. 

Hill 262 is a project I worked on to teach myself Unreal Engine 4. The project is an FPS level built in Unreal 4 using only the default provided assets, some downloaded and altered sound files, and one free pack of downloaded foliage models. These assets were combined to make something slightly more than a graybox level, but less than a finished product. By building a level and doing some programming using Unreal’s Blueprint system, I was able to teach myself the ins and outs of the game engine. Following the completion of my co-op at Mojo Game Studios, I returned to the level and improved it with the skills I had picked up over the previous eight months. The premise of the wider game this level would be in is that WWI took an extra ten or so years to end. As a result, the US underwent a communist revolution, taking it out of the war much like Russia in 1917. After the war ended, mainland Europe blamed the outside nations like the US and Russia for prolonging the war by staying out of it, and banded together under a fascist, racial community not unlike early, pre-war Nazism, though not specifically Anti-Semitic. The level is set in an alternate 1966 during WWII where a communist coalition of the US, Canada, Western Spain, and Russia has invaded mainland Europe to conquer the fascist alliance and its capital in Paris. In the level, the player plays as Henry Cunningham, a Captain in the Red Guards Company, similar to US Army Rangers. The character is upbeat and usually cheery and is a strong supporter of communism, as he grew up under it. The player is tasked with holding a strategic hill (Hill 262) from a counterattack by an elite armored division while the company awaits reinforcements. The player must strategically fall back up the hill to numerous phaselines to try and stall the enemy until the relive can arrive. The level takes inspiration from the old WWII-set Call of Duty games, specifically the Call of Duty 3 level, The Mace. The story is intended to generate a "feel-bad" narrative, where the protagonist's exposure to his ideological counterpart leads him to draw the nihilistic conclusion that all ideologies are essentially the same with only minor, superficial variants and that he and his company is not as heroic as he initially believed. This narrative is intended to be reinforced with the dialog, environmental storytelling, and the gameplay mechanics of how easily both enemies and allies can be killed.

This project was personal work that I was doing between school assignments, so I was responsible for the implementation of everything. I placed all of the assets and wrote all of the code. However, I did not make any of the sound or visual assets, instead using the provided material in Unreal or downloading them from sources like SoundBible.com (though I did alter most of the sounds in Audacity before using them). As this level was supposed to be essentially a graybox, I did not construct models or sounds, though I did make a few particle effects using Unreal 4’s editor.  Instead, I focused on the placement of assets, layout of the terrain and environment, and the flow of the gameplay. The gameplay of the level is supposed to mirror that of most modern shooters; i.e. light and fairly arcadey with lots of cover to utilize. Furthermore, I spent much of my time working on the tone of the level, adding in roughly seven pages of dialog, scripted triggers, and visual cues to drive the atmosphere home. The level has triggers sprinkled throughout to drive the narrative forward with either dialog or particle effects and sounds, or both. In addition, several of the triggers turn particle effects on or off to optimize the level as much as possible.

While the project was enjoyable and enlightening, it was not without its problems. Firstly, the Blueprint system in Unreal 4 was initially somewhat difficult to transition to from more traditional methods like MonoDevelop or Visual Studio. However, when returning to the level after working at Mojo (and using Blueprint for many months), working in Blueprint was considerably easier. The biggest issue I had with the level was implementing a simple AI waypoint following function. While I did get this implemented, the actor’s movement was very temperamental and would often get caught on the terrain, as well as random level geometry. In addition, the movement required a dynamic navmesh, which severely reduced the framerate. I had it working, but getting it to work properly would have taken a great deal of time and I wanted to finish up the level before starting job applications. As a result, I replaced the actual navigation with scripted matinee animations. If I were to go back and work on this level again, I would figure out how to implement the AI navigations properly without degrading the framerate too heavily. Furthermore, the level progression is currently entirely scripted; that is to say, the plot and visuals don’t progress until the player crosses a trigger. My final goal for the level is that the player would be forced to retreat up the hill due to enemy pressure and not scripted requirements. I would like it if it would be possible (but incredibly difficult) for the player to stay on a lower phaseline until the relief arrives and ends the level. While all the current enemy movement animations are uniform and all move at once, I would like increasingly stronger enemies to assault at different times, forcing the player to constantly run back, forth, and potentially behind to plug gaps. However, this would require functioning AI that could navigate, shoot at the player, and die upon being shot to work. I would like to implement these elements but, due to time, I decided to instead just use matinee animations to indicate the general movement paths of the enemies, as this was all that was needed for a graybox level. Another minor point is that the sound mixing could be better. I do not claim to be a sound designer, so it’s not that important, but some of the audio is too loud. Finally, while adding a skybox is not terribly difficult, I was unable to find a free one online that fit both the style and tone of the level, so I would like to either make or find one.
