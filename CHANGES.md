# Next Update (work in progress)

* Added an error message to startup if Shader Model 3 is not available
* Added phong to certain metal objects
* Added hints
  * Added a hint for equipping the camera when looking at a photographable spot for half a second
  * Added hints for reloading the camera and the flashlight when they are at low battery and you have batteries with you
  * These hints are only displayed for a few times before they are marked as "learned"
* Added "restart from checkpoint" to the pause menu
* Added a background blur to the pause menu
* Changed raft strafe speed from 40 to 50
* Fixed use highlights for most objects that didn't have them
* Fixed finicky ladders (especially noticeable in tunnel3)
* Fixed flashlight not playing draw animation sometimes after dying (issue [#121](https://github.com/loiste-interactive/infra-issues/issues/121))
* Fixed utility light missing textures (issue [#33](https://github.com/loiste-interactive/infra-issues/issues/33))
* Fixed camera view model when zooming in on FOVs larger than 108 (issue [#131](https://github.com/loiste-interactive/infra-issues/issues/131))
* Fixed flashlight view model after restarting the level without a saved game
* Fixed the texture on a certain bush model (issue [#127](https://github.com/loiste-interactive/infra-issues/issues/127))
* Fixed missing shadow texture on the lowest settings (issue [#167](https://github.com/loiste-interactive/infra-issues/issues/167))
* Fixed computer screen textures being hard to read on the lowest settings
* Fixed currently playing music not being saved in saved games (issue [#34](https://github.com/loiste-interactive/infra-issues/issues/34))

## reserve1

* Added placeholder player monologue
  * Added to bolt cutters and the door as discussed in issue [#27](https://github.com/loiste-interactive/infra-issues/issues/27)
  * Also added to other places
  * Turn on subtitles to see it for now
* Fixed a spot where it's possible to get stuck between stairs and a rock (issue [#112](https://github.com/loiste-interactive/infra-issues/issues/112))
* Fixed train not showing up on certain approaches (issue [#79](https://github.com/loiste-interactive/infra-issues/issues/79))
* Fixed the map in the Morning Wood office being hard to interpret
* Fixed a skippable save trigger right after the old power plant (issue [#129](https://github.com/loiste-interactive/infra-issues/issues/129))
* Fixed generator switches being the wrong way around (issue [#100](https://github.com/loiste-interactive/infra-issues/issues/100))
* Fixed water disappearing near the clog in the beginning when looking at it from a certain angle (issue [#43](https://github.com/loiste-interactive/infra-issues/issues/43))
* Fixed getting stuck inside the elevator (issue [#133](https://github.com/loiste-interactive/infra-issues/issues/133))
* Fixed lighting errors on some props inside the logging office (issue [#135](https://github.com/loiste-interactive/infra-issues/issues/135))
* Fixed some cars with a missing texture on the bridge (issue [#138](https://github.com/loiste-interactive/infra-issues/issues/138))

## reserve2

* Added forest guard cabin
* Changed sluice gate generator puzzle
  * Indicators and buttons are now at player's eye level
  * Indicators are larger and easier to read
* Changed generator room water to be more visible
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

## reserve3

* Fixed a fence being invisible from the other side (issue [#134](https://github.com/loiste-interactive/infra-issues/issues/134))
* Fixed a spot where the player could get stuck between stones and a building (issue [#106](https://github.com/loiste-interactive/infra-issues/issues/106))
* Fixed it being easy to get stuck near the keys in the cave (issue [#170](https://github.com/loiste-interactive/infra-issues/issues/170), [#130](https://github.com/loiste-interactive/infra-issues/issues/130))
* Fixed several lighting errors (issue [#107](https://github.com/loiste-interactive/infra-issues/issues/107))
* Fixed gate and control room door not closing once opened (issue [#110](https://github.com/loiste-interactive/infra-issues/issues/110))
* Fixed gate not opening when fucking around with the yellow knobs in the control room (issue [#111](https://github.com/loiste-interactive/infra-issues/issues/111))

## tunnel1

* Fixed incorrectly labeled keys (issue [#100](https://github.com/loiste-interactive/infra-issues/issues/100))

## tunnel2

* Fixed an issue where the player could get stuck in settling tank #1 (issue [#85](https://github.com/loiste-interactive/infra-issues/issues/85))
* Fixed an out of bounds issue near the balcony (issue [#141](https://github.com/loiste-interactive/infra-issues/issues/141))
* Fixed inverted water basins (issue [#100](https://github.com/loiste-interactive/infra-issues/issues/100))
* Fixed certain pipes disappearing into the wall (issue [#162](https://github.com/loiste-interactive/infra-issues/issues/162))
* Fixed it being easy to get stuck in the pipe at the end (issue [#5](https://github.com/loiste-interactive/infra-issues/issues/5))
* Fixed a spot where the player could get stuck at the collapsed stairway (issue [#151](https://github.com/loiste-interactive/infra-issues/issues/151))

## tunnel3

* Changed the tunnel to be a bit brighter
* Fixed white decals on the ground next to the water flow meter (issue [#92](https://github.com/loiste-interactive/infra-issues/issues/92))
* Fixed a spot where the player could get stuck in the broken tunnel  (issue [#144](https://github.com/loiste-interactive/infra-issues/issues/144))
* Fixed the player's head clipping through some rocks during the raft ride (issue [#38](https://github.com/loiste-interactive/infra-issues/issues/38))

## tunnel4

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

## furnace

* Added a new puzzle prior to the "finale"
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

## watertreatment

* Added a small new puzzle to the very beginning of the map
* Fixed an invisible wall on certain stairs (issue [#53](https://github.com/loiste-interactive/infra-issues/issues/53))
* Fixed a little missing texture on the ground in the poison room (issue [#148](https://github.com/loiste-interactive/infra-issues/issues/148))
* Fixed decal overflow (issue [#52](https://github.com/loiste-interactive/infra-issues/issues/52))
* Fixed some of the building flickering issues
* Fixed some of the performance issues
* Fixed turning on the clarifier not awarding a "spot repaired" (issue [#11](https://github.com/loiste-interactive/infra-issues/issues/11))
* Fixed it not being possible to pick up the keycard from the drawer (issue [#67](https://github.com/loiste-interactive/infra-issues/issues/67))
* Fixed some doors being static instead of interactable and locked (issue [#9](https://github.com/loiste-interactive/infra-issues/issues/9))
* Fixed laboratory doors not closing once opened (issue [#76](https://github.com/loiste-interactive/infra-issues/issues/76))
* Fixed a tree clipping through a wall (issue [#54](https://github.com/loiste-interactive/infra-issues/issues/54))

## tower

* Fixed a possible crash when turning on the fuses (issue [#95](https://github.com/loiste-interactive/infra-issues/issues/95))
* Fixed an invisible wall on certain stairs (issue [#91](https://github.com/loiste-interactive/infra-issues/issues/91))
* Fixed some skybox models not having mipmaps
* Fixed the outside roof of the steel factory not corresponding to the damaged roof on the inside (issue [#137](https://github.com/loiste-interactive/infra-issues/issues/137))
* Fixed some doors being static instead of interactable and locked (issue [#9](https://github.com/loiste-interactive/infra-issues/issues/9))
* Fixed a graffiti also being visible on the ground instead of just on the wall (issue [#149](https://github.com/loiste-interactive/infra-issues/issues/149))

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
