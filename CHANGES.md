# In the next update

* Added new map, Sewer, located after Watertreatment
* Added system to better read the various notes scattered around the game world. Use the highlighted notes to activate.
* Fixed issues with fov after loading a save
* Fixed problem with visibility check on the camera targets (Issue [#177] (https://github.com/loiste-interactive/infra-issues/issues/177))
* Fixed player being able to holster/equip his camera during computer camera transitions (Issue [#185] (https://github.com/loiste-interactive/infra-issues/issues/185))

## reserve1
* Added custscene when exiting the car
* Added particles to the raft
* Made the WW2 bomb explode when tampered with
* Fixed models with incorrect lighting (Issue [#200] (https://github.com/loiste-interactive/infra-issues/issues/200))

## reserve3
* Fixed fence missing backface again (Issue [#198] (https://github.com/loiste-interactive/infra-issues/issues/198))

## tunnel1
* Fixed use highlight of buttons showing throught the wall (Issue [#188] (https://github.com/loiste-interactive/infra-issues/issues/188))
* Fixed wrongly lit decal (Issue [#190] (https://github.com/loiste-interactive/infra-issues/issues/190))
* Fixed player getting stuck to the alarm panel's shutter (Issue [#192] (https://github.com/loiste-interactive/infra-issues/issues/192))
* Fixed player being able to jump on the small legde near the flood gates (Issue [#199] (https://github.com/loiste-interactive/infra-issues/issues/199))

## tunnel2
* Fixed issues with the control computer (Issue [#193] (https://github.com/loiste-interactive/infra-issues/issues/193))

## furnace
* Added more particles to the ending scene
* Fixed sprites showing through the wall (Issue [#201] (https://github.com/loiste-interactive/infra-issues/issues/201))

## tower
* Fixed border of level being too noticeable (Issue [#195] (https://github.com/loiste-interactive/infra-issues/issues/195))

## watertreatment
* Fixed computer with emails having missing textures (Issue [#10] (https://github.com/loiste-interactive/infra-issues/issues/10))
* Fixed the first tunnel having an invisible wall (Issue [#73] (https://github.com/loiste-interactive/infra-issues/issues/73))
* Fixed the strange lighting issues (Issue [#181] (https://github.com/loiste-interactive/infra-issues/issues/181))
* Fixed doors missing sounds (Issue [#182] (https://github.com/loiste-interactive/infra-issues/issues/182))
* Fixed broken keycard readers having highlights (Issue [#183] (https://github.com/loiste-interactive/infra-issues/issues/183))
* Fixed toilets not having tags (Issue [#194] (https://github.com/loiste-interactive/infra-issues/issues/194))
* Fixed bus having missing textures (Issue [#197] (https://github.com/loiste-interactive/infra-issues/issues/197))

# December 5th 2015

* Fixed missing normal maps from a certain ground material
* Fixed an issue where the player's camera tool would sometimes break after a camera ride
* Removed Shader Model 3 error from startup
  * Had too many false positives

# December 2nd 2015

* Added an error message to startup if Shader Model 3 is not available
* Added phong to certain metal objects
* Added hints
  * Added a hint for equipping the camera when looking at a photographable spot for half a second
  * Added hints for reloading the camera and the flashlight when they are at low battery and you have batteries with you
  * These hints are only displayed for a few times before they are marked as "learned"
* Added "restart from checkpoint" to the pause menu
* Added a background blur to the pause menu
* Added more player monologue
  * Added different lines for different battery types
  * Added a few lines about deep water when in water and there's really deep water nearby
  * Added more lines to when trying to pick up batteries but you already have the maximum amount you can carry
  * Turn on subtitles to see this placeholder player monologue
* Added persistent global state
  * When you reach a new level, the global state from the previous level is saved
  * When you later start a level from the main menu, the previous global state is restored
  * This avoids issues with saved games not being backwards compatible, but still allows progress to be saved
    * Note: the release version of the game will ship with save/load game functionality
  * The following things count as global state:
    * The amount of successful photographs
    * The amount of corruption found
    * The amount of mistakes made
    * The amount of geocaches found
    * The amount of spots repaired
    * Whether certain water flow meters are turned on or not
    * And others
* Added animations for certain door models that didn't have them
* Changed all normal mapped world materials to use self-shadowing normal maps
* Changed raft strafe speed from 40 to 50
* Changed music volume default to 100% instead of 33%
  * All music has been adjusted accordingly
  * If the music is too quiet, please set the slider to 100%!
* Fixed camera not acquiring targets through small obstacles such as railings
* Fixed use highlights for most objects that didn't have them
* Fixed finicky ladders (especially noticeable in tunnel3)
* Fixed utility light missing textures (issue [#33](https://github.com/loiste-interactive/infra-issues/issues/33))
* Fixed camera view model when zooming in on FOVs larger than 108 (issue [#131](https://github.com/loiste-interactive/infra-issues/issues/131))
* Fixed flashlight view model after restarting the level without a saved game
* Fixed the texture on a certain bush model (issue [#127](https://github.com/loiste-interactive/infra-issues/issues/127))
* Fixed missing shadow texture on the lowest settings (issue [#167](https://github.com/loiste-interactive/infra-issues/issues/167))
* Fixed computer screen textures being hard to read on the lowest settings
* Fixed currently playing music not being saved in saved games (issue [#34](https://github.com/loiste-interactive/infra-issues/issues/34))

## reserve1

* Added player monologue
  * Added to the bolt cutters and the door (issue [#27](https://github.com/loiste-interactive/infra-issues/issues/27))
  * Added to when the player first enters the old power plant
  * Added to when the player first enters the dam
  * Added to when spotting the fallen tree over the tracks
  * Added to certain photograph and "corruption" targets
  * Turn on subtitles to see this placeholder player monologue
* Fixed a spot where it's possible to get stuck between stairs and a rock (issue [#112](https://github.com/loiste-interactive/infra-issues/issues/112))
* Fixed train not showing up on certain approaches (issue [#79](https://github.com/loiste-interactive/infra-issues/issues/79))
* Fixed the map in the Morning Wood office being hard to interpret
* Fixed a skippable save trigger right after the old power plant (issue [#129](https://github.com/loiste-interactive/infra-issues/issues/129))
* Fixed generator switches being the wrong way around (issue [#100](https://github.com/loiste-interactive/infra-issues/issues/100))
* Fixed getting stuck inside the elevator (issue [#133](https://github.com/loiste-interactive/infra-issues/issues/133))
* Fixed lighting errors on some props inside the logging office (issue [#135](https://github.com/loiste-interactive/infra-issues/issues/135))
* Fixed some cars with a missing texture on the bridge (issue [#138](https://github.com/loiste-interactive/infra-issues/issues/138))

## reserve2

* Added player monologue
  * Added to when the elevator in the beginning breaks down
  * Added to when getting close to electrified water in generator room
  * Added to when entering forest guard cabin
  * Added to when funicular breaks down
  * Added to certain photograph and "corruption" targets
  * Turn on subtitles to see this placeholder player monologue
* Added forest guard cabin
* Added a locked gate to the cave entrance
  * Keys can be obtained from the forest guard cabin
* Added music to when the Hartman tape is playing
* Added a sound mixer to when the Hartman tape is playing
  * Boosts dialogue and music
  * Ducks ambient sounds
* Added a sound mixer to when the "Lookout" music is playing
* Changed the elevator breakdown sequence
* Changed sluice gate generator puzzle
  * Indicators and buttons are now at player's eye level
  * Indicators are larger and easier to read
* Changed generator room appearance
  * Now a lot brighter
  * Water is now dark green, more easily visible
* Changed the "garage door" next to the funicular to be open instead of closed
* Fixed broken funicular not being photographable (issue [#109](https://github.com/loiste-interactive/infra-issues/issues/109))
* Fixed sluice gate generator puzzle being passable with smaller rpm than intended (issue [#80](https://github.com/loiste-interactive/infra-issues/issues/80))
* Fixed Hartman tape subtitles being split into too long segments
* Fixed a spot where the player could get stuck at the sawmill (issue [#139](https://github.com/loiste-interactive/infra-issues/issues/139))
* Fixed another spot where the player could get stuck at the sawmill (issue [#142](https://github.com/loiste-interactive/infra-issues/issues/142))
* Fixed a spot where the player could get stuck near the funicular (issue [#104](https://github.com/loiste-interactive/infra-issues/issues/104))
* Fixed log chute not making much sense (issue [#100](https://github.com/loiste-interactive/infra-issues/issues/100))
* Fixed the Hartman tape dialogue being audible everywhere in the level (issue [#132](https://github.com/loiste-interactive/infra-issues/issues/132))
* Fixed a door opening to the inside of a wall (issue [#168](https://github.com/loiste-interactive/infra-issues/issues/178))
* Fixed a spot where the player could get stuck near the furnicular (issue [#169](https://github.com/loiste-interactive/infra-issues/issues/169))
* Fixed a spot where the player could get stuck on some rocks (issue [#169](https://github.com/loiste-interactive/infra-issues/issues/169))
* Fixed flickering water at the lower floor of the sawmill (issue [#4](https://github.com/loiste-interactive/infra-issues/issues/4))

## reserve3

* Added player monologue
  * Added to when entering the big cavern
  * Added to when using the locked gate
  * Added to when entering the first floor of the building
  * Added to when finding the body
  * Added to when walking on the fallen tree
  * Added to when getting close to the tunnel entrance
  * Added to certain photograph targets
  * Turn on subtitles to see this placeholder player monologue
* Added a mysterious stash
* Fixed a fence being invisible from the other side (issue [#134](https://github.com/loiste-interactive/infra-issues/issues/134))
* Fixed a spot where the player could get stuck between stones and a building (issue [#106](https://github.com/loiste-interactive/infra-issues/issues/106))
* Fixed it being easy to get stuck near the keys in the cave (issue [#170](https://github.com/loiste-interactive/infra-issues/issues/170), [#130](https://github.com/loiste-interactive/infra-issues/issues/130))
* Fixed several lighting errors (issue [#107](https://github.com/loiste-interactive/infra-issues/issues/107))
* Fixed gate and control room door not closing once opened (issue [#110](https://github.com/loiste-interactive/infra-issues/issues/110))
* Fixed gate not opening when fucking around with the yellow knobs in the control room (issue [#111](https://github.com/loiste-interactive/infra-issues/issues/111))

## tunnel1

* Added player monologue
  * Added to when the ceiling starts collapsing
  * Added to when player survives the collapse
  * Added to when player uses the exit elevator
  * Turn on subtitles to see this placeholder player monologue
* Added a sound mixer to when the finale music is playing
  * Boosts dialogue and music
  * Ducks ambient sounds
* Changed finale music to be louder
* Changed the water sensor puzzle to make more sense (issue [#89](https://github.com/loiste-interactive/infra-issues/issues/89))
* Fixed incorrectly labeled keys (issue [#100](https://github.com/loiste-interactive/infra-issues/issues/100))

## tunnel2

* Added a window that shows the pipe entrance from near the level start
* Added a map that shows both tunnel entrances
* Added an additional monitor to the pool room that shows the puzzle status
* Added new corruption notes
* Fixed an issue where the player could get stuck in settling tank #1 (issue [#85](https://github.com/loiste-interactive/infra-issues/issues/85))
* Fixed an out of bounds issue near the balcony (issue [#141](https://github.com/loiste-interactive/infra-issues/issues/141))
* Fixed inverted water basins (issue [#100](https://github.com/loiste-interactive/infra-issues/issues/100))
* Fixed certain pipes disappearing into the wall (issue [#162](https://github.com/loiste-interactive/infra-issues/issues/162))
* Fixed it being easy to get stuck in the pipe at the end (issue [#5](https://github.com/loiste-interactive/infra-issues/issues/5))
* Fixed a spot where the player could get stuck at the collapsed stairway (issue [#151](https://github.com/loiste-interactive/infra-issues/issues/151))

## tunnel3

* Added player monologue
  * Added to certain photograph and "corruption" targets
  * Turn on subtitles to see this placeholder player monologue
* Changed the tunnel to be a bit brighter
* Fixed white decals on the ground next to the water flow meter (issue [#92](https://github.com/loiste-interactive/infra-issues/issues/92))
* Fixed a spot where the player could get stuck in the broken tunnel  (issue [#144](https://github.com/loiste-interactive/infra-issues/issues/144))
* Fixed the player's head clipping through some rocks during the raft ride (issue [#38](https://github.com/loiste-interactive/infra-issues/issues/38))

## tunnel4

* Added an alternative route to the cave where you get to blow up stuff
* Changed the tunnel to be a bit brighter
* Fixed two doors being marked as "B2" (issue [#115](https://github.com/loiste-interactive/infra-issues/issues/115))
* Fixed a certain area portal (issue [#81](https://github.com/loiste-interactive/infra-issues/issues/81))
* Fixed light switch sounds playing on map start (issue [#36](https://github.com/loiste-interactive/infra-issues/issues/36))
* Fixed hallway with electrified water not having enough autosaves (issue [#31](https://github.com/loiste-interactive/infra-issues/issues/31))
* Fixed gate at the end of the map missing sounds (issue [#30](https://github.com/loiste-interactive/infra-issues/issues/30))
* Fixed gate at the end of the map opening in the wrong direction (issue [#30](https://github.com/loiste-interactive/infra-issues/issues/30))
* Fixed a z-fighting issue in the hallway with electrified water (issue [#27](https://github.com/loiste-interactive/infra-issues/issues/27))
* Fixed a spot that was finicky to climb up (issue [#19](https://github.com/loiste-interactive/infra-issues/issues/19))
* Fixed a spot where the player could get stuck on some pipes (issue [#18](https://github.com/loiste-interactive/infra-issues/issues/18))
* Fixed a spot where the player could get stuck on some railings on the floor (issue [#17](https://github.com/loiste-interactive/infra-issues/issues/17))
* Fixed main power switch animations when using it after the power is already on (issue [#20](https://github.com/loiste-interactive/infra-issues/issues/20))
* Fixed a spot where the player could get stuck in the generator room (issue [#104](https://github.com/loiste-interactive/infra-issues/issues/104))
* Fixed the raft light disappearing on level start (issue [#104](https://github.com/loiste-interactive/infra-issues/issues/39))
* Fixed an untextured brush face (issue [#154](https://github.com/loiste-interactive/infra-issues/issues/154))
* Removed a really weird alternative route involving opening the floodgates and riding the raft through them

## furnace

* Added player monologue
  * Added to when entering the cellar
  * Added to when entering the mushroom farm
  * Added to when photographing the mushroom farm
  * Added to when starting the finale
  * Added to when completing the finale
  * Added to when entering the exit elevator
  * Turn on subtitles to see this placeholder player monologue
* Added a new puzzle prior to the "finale"
* Added a sound mixer to when the finale music is playing
  * Boosts dialogue and music
  * Ducks ambient sounds
* Changed finale music to be louder
* Changed the location of the keys for the first door (near the old location, but should be easier to notice now)
* Changed the minitrain tracks to be more clearly marked
* Changed minitrain track control room door to one that has a rear lock
  * The key cabinet next to it has been removed
* Changed the minitrain track control room needing to be powered on before it can be used
* Fixed electrical box light sprites being visible through control room wall (issue [#125](https://github.com/loiste-interactive/infra-issues/issues/125))
* Fixed gate in the poison room being finicky to open from the other side (issue [#123](https://github.com/loiste-interactive/infra-issues/issues/123))
* Fixed not being able to close the gate in the poison room once opened (issue [#123](https://github.com/loiste-interactive/infra-issues/issues/123))
* Fixed a spot where the player could get stuck on a pipe (issue [#77](https://github.com/loiste-interactive/infra-issues/issues/77))
* Fixed not being able to pull elevator lever before closing the door (issue [#14](https://github.com/loiste-interactive/infra-issues/issues/14))
* Fixed control room door needing to be used in the exact right spot to be unlocked (issue [#13](https://github.com/loiste-interactive/infra-issues/issues/13))
* Fixed a spot where the edge of the skybox was too clearly visible to the player (issue [#1](https://github.com/loiste-interactive/infra-issues/issues/1))
* Fixed a spot where the player could get stuck between a catwalk and a machine (issue [#104](https://github.com/loiste-interactive/infra-issues/issues/104))
* Fixed chain collisions on the door that you need to use bolt cutters on (issue [#152](https://github.com/loiste-interactive/infra-issues/issues/152))
* Fixed it being possible to skip the last puzzle (issue [#155](https://github.com/loiste-interactive/infra-issues/issues/155))
* Fixed a spot where the player could get stuck on top of some pipes in the beginning (issue [#150](https://github.com/loiste-interactive/infra-issues/issues/150))
* Fixed a spot where the skybox was too visible when climbing on top of a lamp post (issue [#150](https://github.com/loiste-interactive/infra-issues/issues/150))

## tower

* Added player monologue
  * Added to when exiting the elevator
  * Added to when reaching the top
  * Added to when seeing the farm the first time
  * Turn on subtitles to see this placeholder player monologue
* Fixed a possible crash when turning on the fuses (issue [#95](https://github.com/loiste-interactive/infra-issues/issues/95))
* Fixed an invisible wall on certain stairs (issue [#91](https://github.com/loiste-interactive/infra-issues/issues/91))
* Fixed some skybox models not having mipmaps
* Fixed the outside roof of the steel factory not corresponding to the damaged roof on the inside (issue [#137](https://github.com/loiste-interactive/infra-issues/issues/137))
* Fixed some doors being static instead of interactable and locked (issue [#9](https://github.com/loiste-interactive/infra-issues/issues/9))
* Fixed a graffiti also being visible on the ground instead of just on the wall (issue [#149](https://github.com/loiste-interactive/infra-issues/issues/149))

## watertreatment

* Added a small new puzzle to the very beginning of the map
* Added a new sludge removal building with corruption and photography targets
* Changed the area in the beginning
* Changed the central area
* Changed the blower building
* Fixed an invisible wall on certain stairs (issue [#53](https://github.com/loiste-interactive/infra-issues/issues/53))
* Fixed a little missing texture on the ground in the poison room (issue [#148](https://github.com/loiste-interactive/infra-issues/issues/148))
* Fixed decal overflow (issue [#52](https://github.com/loiste-interactive/infra-issues/issues/52))
* Fixed the building flickering issues
* Fixed most of the performance issues
* Fixed turning on the clarifier not awarding a "spot repaired" (issue [#11](https://github.com/loiste-interactive/infra-issues/issues/11))
* Fixed it not being possible to pick up the keycard from the drawer (issue [#67](https://github.com/loiste-interactive/infra-issues/issues/67))
* Fixed some doors being static instead of interactable and locked (issue [#9](https://github.com/loiste-interactive/infra-issues/issues/9))
* Fixed laboratory doors not closing once opened (issue [#76](https://github.com/loiste-interactive/infra-issues/issues/76))
* Fixed a tree clipping through a wall (issue [#54](https://github.com/loiste-interactive/infra-issues/issues/54))
* Removed unused alternative route

# November 3rd 2015

* Added an option to disable motion blur (issue [#69](https://github.com/loiste-interactive/infra-issues/issues/69))
* Added all maps to the main menu (issue [#78](https://github.com/loiste-interactive/infra-issues/issues/78))
* Fixed sounds not playing when Steam language is not set to English (issue [#42](https://github.com/loiste-interactive/infra-issues/issues/42))
* Fixed localization issues when Steam language is not set to English (issue [#42](https://github.com/loiste-interactive/infra-issues/issues/42))
* Fixed resolution defaulting to 640x480 on certain graphics cards (issue [#22](https://github.com/loiste-interactive/infra-issues/issues/22))
* Fixed decals respawning over existing decals on player death (issue [#29](https://github.com/loiste-interactive/infra-issues/issues/29))
* Fixed water bottle reading "pring water" instead of "spring water" (issue [#40](https://github.com/loiste-interactive/infra-issues/issues/40))
* Fixed upside down text in a certain model (issue [#45](https://github.com/loiste-interactive/infra-issues/issues/45))
* Fixed extraneous "the" in a book's title (issue [#55](https://github.com/loiste-interactive/infra-issues/issues/55))
* Fixed use highlights on certain gate and valve models (issue [#57](https://github.com/loiste-interactive/infra-issues/issues/57))
* Fixed use highlights on a certain lever model

## reserve1

* Fixed a strange foam line on the water in the beginning (issue [#83](https://github.com/loiste-interactive/infra-issues/issues/83))
* Fixed a spot under the bridge where the player could get stuck (issue [#66](https://github.com/loiste-interactive/infra-issues/issues/66))
* Fixed some doors not closing once opened (issue [#23](https://github.com/loiste-interactive/infra-issues/issues/23))
* Fixed it being possible to "ride" along with the train without getting killed (issue [#2](https://github.com/loiste-interactive/infra-issues/issues/2))
* Fixed it being possible to use the "water meter" switches through the panel (issue [#47](https://github.com/loiste-interactive/infra-issues/issues/47))
* Fixed "raft" sounds sometimes not playing (issue [#44](https://github.com/loiste-interactive/infra-issues/issues/44))
* Fixed secret fuse achievement triggering under wrong conditions (issue [#41](https://github.com/loiste-interactive/infra-issues/issues/41))
* Fixed elevator sounds not restarting when turning it off and back on again (issue [#25](https://github.com/loiste-interactive/infra-issues/issues/25))
* Fixed camera fading in twice in the beginning (issue [#21](https://github.com/loiste-interactive/infra-issues/issues/21))
* Fixed being able to trigger the elevator while not in it (issue [#3](https://github.com/loiste-interactive/infra-issues/issues/3))
* Fixed not being able to turn the lights back on in the beginning if you turn them off
* Fixed light switch sounds in the beginning

## tunnel2

* Fixed doors not being locked (issue [#35](https://github.com/loiste-interactive/infra-issues/issues/35))

## tunnel3

* Fixed player getting stuck on certain debris (issue [#7](https://github.com/loiste-interactive/infra-issues/issues/7))

## tunnel3 & tunnel4

* Fixed player getting stuck in walls after the raft breaks (issue [#50](https://github.com/loiste-interactive/infra-issues/issues/50))
  * Still happens, but the player is killed if he gets stuck
  * Needs further tweaking
