# January 22nd 2016 (Version 1.0.7)

* Added "show hints" option to the options menu
* Added "invert mouse" option to the options menu with the ability to "invert X", "invert Y" or "invert X + Y" (issue [#274] (https://github.com/loiste-interactive/infra-issues/issues/274))
* Changed hints to use icons instead of text for mouse bindings
* Changed the camera hint to hide when no longer looking at a camera target
* Changed the camera hint not to be displayed after the player ignores it for a few times
* Changed keycard, zoom, unzoom and crouch hints to be only displayed once
* Changed player cell phone disconnect tone to be louder
* Changed the crouch button on Xbox 360 controllers to be a toggle
* Fixed hint display & success counts not being saved under certain circumstances
* Fixed achievement progress being overridden for "Photographist", "An Eye for Detail", "No Stone Unturned", "The Conspiracy Unfolds", "Structural Analyst Extraordinaire", "Restoring the Flow", and "TFTC" when starting a new game and making progress
  * Achievement progress is now only overridden if it's an improvement over the old value
* Fixed "Restoring the Flow" achievement (issue [#315](https://github.com/loiste-interactive/infra-issues/issues/315))
* Fixed the analogue sticks not working by default on the Xbox 360 controller
  * Reset to default controls for this to take effect
* Fixed missing hint icons for the Xbox 360 controller (issue [#307](https://github.com/loiste-interactive/infra-issues/issues/307))
* Fixed achievements not unlocking after loading a saved game from the main menu (issue [#276](https://github.com/loiste-interactive/infra-issues/issues/276))
* Fixed being able to get stuck on a black screen when something goes wrong (level transition errors, etc.)
  * The game will now always throw you into the main menu instead
* Fixed the "reset controls to defaults" button in the options menu also resetting the dropdown choices (but not to their defaults)
* Fixed a rare case where the player view control is never disabled (issue [#300] (https://github.com/loiste-interactive/infra-issues/issues/300))
  * Affects documents, climbing and "cutscenes"
* Fixed intro controls breaking if the game is saved and loaded in the middle of the intro (issue [#291] (https://github.com/loiste-interactive/infra-issues/issues/291))
* Fixed player view starting underground if the game is saved and loaded in the middle of the intro (issue [#291] (https://github.com/loiste-interactive/infra-issues/issues/291))
* Fixed the binding for skipping the intro missing from the options menu
* Fixed being able to rebind keys to a Xbox 360 controller in the options menu
  * The controls menu is intended for keyboard & mouse only
* Fixed the sprint button not being bound on the Xbox 360 controller
  * It's now bound to the left stick
* Fixed the reload button not being bound on the Xbox 360 controller
  * It's now bound to the Y button

## office

* Added conversations for the groups of three in the 7th floor corridor and in the atrium
* Added lipsyncing to the random office workers
* Added an additional voice for the male office workers
  * A voice is randomly picked for each office worker
* Added use highlights for the company car
* Changed the office worker voices a bit
  * Removed really high frequencies from certain voices
  * Adjusted the volume for certain voices
* Changed the timing of the reception scene a bit
* Fixed keycard reader hint not disappearing when the keycard reader is used (issue [#306]
(https://github.com/loiste-interactive/infra-issues/issues/306))
* Fixed crouch hint appearing when jumping from the 8th floor (issue [#318]
(https://github.com/loiste-interactive/infra-issues/issues/318))
* Fixed ghost subtitles when "using" a male office worker and then immediately "using" a female office worker

## reserve1

* Added a few extra batteries
* Added a camera target to the maintenance log in the power plant
* Changed train brake sounds (issue [#259]
(https://github.com/loiste-interactive/infra-issues/issues/259))
* Fixed player monologue and the phone call playing on top of each other
* Fixed leaking displacement (issue [#301]
(https://github.com/loiste-interactive/infra-issues/issues/301))

## tunnel

* Fixed a missing line from the player monologue when the ceiling starts to collapse

## tunnel4

* Fixed an area portal issue (issue [#295]
(https://github.com/loiste-interactive/infra-issues/issues/295))
* Fixed foliage building key being able to open gate in end of level
* Fixed raft water sound playing after raft ride
* Fixed a certain door missing animations (issue [#298]
(https://github.com/loiste-interactive/infra-issues/issues/298))
* Removed a player clip from the foliage building

## tower

* Fixed the player's voice coming from the phone speaker instead of the player in payphone calls

## watertreatment

* Fixed misleading grit classifier note

## sewer

* Fixed unreachable geocache location (issue [#311]
(https://github.com/loiste-interactive/infra-issues/issues/311))

## sewer2

* Added more bricks to the emergency bolt cutter part
* Changed crate locations in the climbing part
* Fixed missing metadata

# January 20th 2016 (Version 1.0.6)

* Fixed Xbox 360 controller not working out of the box
  * Reset to default controls from settings for this to take effect 
* Fixed camera equip hints never being displayed

## office

* Added hints to guide the player
   * Added use hint when getting close to the first passable door with a keycard reader
   * Added zoom hint when entering the atrium the first time
   * Added crouch hint when the elevator stops
* Added floor numbers near the elevators
* Added a few notes to help guide the player better
* Changed some doors to help guide the player better
* Changed the meeting sequence timings a bit
* Changed the textures of the whiteboard in the player's office

# January 19th 2016 (Version 1.0.5)

* Fixed a crash when transitioning from `watertreatment` to `sewer`
  * Caused by running out of memory
  * Solved by splitting `sewer` into two: `sewer` and `sewer2`
* Fixed dialogue and monologue stopping playing after a certain point (issue [#288] (https://github.com/loiste-interactive/infra-issues/issues/288))
* Fixed a rare crash when transitioning from `office` to `reserve1`
* Removed a bunch of Miles Sound System files that were shipped by mistake

## tunnel3

* Fixed player getting stuck inside the big pipe when transitioning from `tunnel2`

## furnace

* Fixed a missing subtitle from the first announcement

## tower

* Fixed incorrect subtitles in the phone call to boss
* Fixed missing subtitles from a certain payphone call

## watertreatment

* Fixed missing subtitles from the phone call

## sewer

* Fixed a missing door (issue [#285] (https://github.com/loiste-interactive/infra-issues/issues/285))

# January 18th 2016 (Version 1.0.4)

## office

* Fixed achievement `Bad Case of the Mondays` not triggering
* Fixed "skip the meeting" hint appearing after exiting the meeting room (issue [#281] (https://github.com/loiste-interactive/infra-issues/issues/281))

## reserve1

* Fixed random floating doors under the bridge when transitioning from `office` (issue [#280] (https://github.com/loiste-interactive/infra-issues/issues/280))

# January 17th 2016 (Version 1.0.3)

* Fixed a voice actor missing from the credits
* Fixed some visible seams in the character models
* Fixed the "continue" button in the main menu after starting a game and then returning to the menu

## reserve1

* Fixed player zoom 
* Fixed player spawning without his flashlight and camera (issue [#280] (https://github.com/loiste-interactive/infra-issues/issues/280))

# January 17th 2016 (Version 1.0.2)

## office

* Fixed parking garage cutscene not triggering if the garage was visited prior to picking up the keys from the reception
* Fixed a woman sitting in the atrium having broken animations
* Changed the "skip" option in the intro so that the hint message isn't displayed until later

## reserve1

* Fixed black screen on some systems when transitioning from `office` to `reserve1`

## reserve3

* Fixed the hidden stash firing wrong achievement when opened

## tunnel4

* Fixed a newspaper being unphotographable
* Fixed a corruption document in the small office being unphotographable
* Fixed certain missing subtitles

## tower

* Fixed certain missing subtitles
* Fixed black screen on some systems when transitioning from `furnace` to `tower` 

## watertreatment

* Fixed incorrect map texture in the lab (issue [#264] (https://github.com/loiste-interactive/infra-issues/issues/264))

## sewer

* Fixed "Sneaky" achievement being impossible to obtain without prior knowledge of the level

# January 16th 2016 (Version 1.0.1)

## reserve2

* Fixed problem with level change to `reserve3`
* Fixed missing music from the Hartmann tape scene

# January 15th 2016 (Release 1.0.0)

* Added pre-built sound caches (issue [#84] (https://github.com/loiste-interactive/infra-issues/issues/84))
* Added the rest of the voice acting
* Added new achievements
  * A Bad Case of the Mondays – at the office, jump down from the 8th or 7th floor
  * Better than Before – fix the problems at the pumping station and get back underground without disrupting the operation
  * Not So Fresh Water – analyze a water sample at the Pitheath Water Treatment Plant
  * Demolitionist – make your own tunnel in the Bergmann water tunnels
  * Sneaky – get through the hacker den without triggering any of the alarms
  * The End? – complete INFRA: Part 1
  * Also 6 secret achievements!
* Changed the Hartmann tapes and the `furnace` announcements and the `tower` payphone calls to sound distorted
* Changed the textures of all the newspapers
  * The articles have been rewritten from scratch
  * The dates on the newspapers have been fixed
  * The newspapers now have a distinct appearance depending on when the issue came out
* Changed all of the generic character models
  * They now use a single model for males and a single model for females
  * Facial features are randomized using flex animation
  * Lag spikes when NPCs spawn should be gone – randomization system no longer creates multiple `material_modify_control` entities for each NPC
  * Textures have been updated
* Fixed depth buffer related problem with a certain bulletin board model (issue [#238] (https://github.com/loiste-interactive/infra-issues/issues/238))
* Fixed player flashlight becoming enabled after death if it was previously disabled
  * Especially a problem in `office`
* Fixed camera flicker for one frame at the end of every "cutscene"
  * Affected both `office` and `reserve1`
* Fixed the shadows for hint messages and subtitles getting cut off from the bottom
* Fixed the player talking over himself
  * Monologue previously interrupted scripted scenes and other monologue
  * The player will now be quiet if he's in the middle of a scripted scene or if he's already speaking a monologue
* Fixed door animations breaking after player death (issue [#178] (https://github.com/loiste-interactive/infra-issues/issues/178))
* Fixed phone call scripts on `reserve2` and `watertreatment` breaking if restarting the level when there is no saved game
* Fixed the phone call scripts on `reserve2` and `watertreatment` breaking if dying prior to reaching them
* Fixed flashlight viewmodel sometimes not being set if restarting the level when there is no saved game
* Fixed crash if restarting the level without a saved game in the middle of deploying or holstering the camera

## office

* Added sound when picking up the flashlight
* Added textures to untextured models
* Changed the intro scene so that you can look around
* Changed Carla to be a woman
* Changed the brightness of some interior spaces to be brighter
* Changed some interior spaces to be more detailed 
* Changed the meeting room lighting to be better
* Fixed the one frame jump glitch on the cutscene when exiting the meeting room
* Fixed various door related issues (issue [#228] (https://github.com/loiste-interactive/infra-issues/issues/228) and [#230] (https://github.com/loiste-interactive/infra-issues/issues/230))
* Fixed cubemap issues (issue [#229] (https://github.com/loiste-interactive/infra-issues/issues/229))
* Fixed the strange lighting artifacts on the parking garage ramp (issue [#233] (https://github.com/loiste-interactive/infra-issues/issues/233))
* Fixed visible seam inside the elevators (issue [#237] (https://github.com/loiste-interactive/infra-issues/issues/237))
* Fixed areaportal error near the IT-services (issue [#239] (https://github.com/loiste-interactive/infra-issues/issues/239))
* Fixed player being able to clip through the elevator door if he gets in the way as it's closing (issue [#245] (https://github.com/loiste-interactive/infra-issues/issues/245))
* Fixed an out of bounds error (issue [#246] (https://github.com/loiste-interactive/infra-issues/issues/246))
* Fixed a missing player clip from certain stairs (issue [#247] (https://github.com/loiste-interactive/infra-issues/issues/247))
* Fixed bad soundscapes (issue [#263] (https://github.com/loiste-interactive/infra-issues/issues/263))

## reserve1

* Fixed the first document being hard to read since it was so dark (issue [#251] (https://github.com/loiste-interactive/infra-issues/issues/251))
* Fixed signal box playing click sound on use even when "block reserved" is active (issue [#250] (https://github.com/loiste-interactive/infra-issues/issues/250))
* Fixed a poor player clip on certain stairs (issue [#249] (https://github.com/loiste-interactive/infra-issues/issues/249))
* Fixed logging office door missing animations (issue [#248] (https://github.com/loiste-interactive/infra-issues/issues/248))

## reserve3

* Added working light switches to the control room
* Fixed computer missing use highlights (issue [#255] (https://github.com/loiste-interactive/infra-issues/issues/255))

## tunnel1

* Fixed corruption document being unphotographable (issue [#242] (https://github.com/loiste-interactive/infra-issues/issues/242))

## tunnel2

* Added working light switches to the control room
* Added a working fire alarm to the control room
* Changed the phone call to start once the player is inside the facility

## tunnel3

* Added more autosaves to the raft ride (issue [#260] (https://github.com/loiste-interactive/infra-issues/issues/260))

## tunnel4

* Added more autosaves to the raft ride (issue [#260] (https://github.com/loiste-interactive/infra-issues/issues/260))

## furnace

* Fixed a specific door not unlocking unless looking at a specific spot (issue [#252] (https://github.com/loiste-interactive/infra-issues/issues/252))
* Fixed some minor lighting issues (issue [#253] (https://github.com/loiste-interactive/infra-issues/issues/253))
* Fixed barrels being able to block the entrance to the fuse room (issue [#253] (https://github.com/loiste-interactive/infra-issues/issues/253))

## tower

* Fixed monologue about exiting Stalburg Steel being triggered too early (issue [#231] (https://github.com/loiste-interactive/infra-issues/issues/231))
* Fixed a certain payphone call missing a line from the beginning (issue [#234] (https://github.com/loiste-interactive/infra-issues/issues/234))
* Fixed payphone buttons not playing button sound when used fast twice in a row (issue [#235] (https://github.com/loiste-interactive/infra-issues/issues/235))
* Fixed payphone script error when trying to dial a phone number longer than 12 digits (issue [#236] (https://github.com/loiste-interactive/infra-issues/issues/236))

## watertreatment

* Added working light switches to the old office
* Added mistake target whean breaking the office glass
* Changed some interior spaces to be more detailed 
* Changed some of the never openeable doors to static props
* Fixed missing decals
* Fixed strange floating face on the edge of the secondary cralifier
* Fixed a flickering window when exiting the tunnel (issue [#261] (https://github.com/loiste-interactive/infra-issues/issues/261))

## sewer

* Changed the end of the level
* Fixed transformers having erroneous labels (issue [#232] (https://github.com/loiste-interactive/infra-issues/issues/232))

# January 8th 2016

* Added new map `office` to the beginning of the game
  * Mainly used to boot the story of the game
  * Character models are still being worked on
  * Carla is a man right now because why not
  * You can't look around in the intro scene, but it's being worked on
  * The intro scene controls are weird, we know
  * The "cutscenes" are work in progress
* Added voice acting for a bunch of characters
  * Office workers in `office`
  * Radio host in `office`
  * Factory manager in `furnace`
  * Worker trustee in `furnace`
  * Payphone calls in `tower`
  * VA for the boss and the player and the receptionist isn't in yet
  * Lipsyncing isn't in yet
* Added an option to the options menu to reset to the default controls (issue [#15] (https://github.com/loiste-interactive/infra-issues/issues/15))
* Added a new achievement for repairing all the water flow meters
* Added pickup, open and close sounds for geocaches
* Changed a bunch of monologue and dialogue
  * Changed deep water monologue #3 to be less terrible
  * Changed the monologue for geocaches
    * First three geocaches now have unique monologue
    * Sort of explains what the geocaches do (they are collectibles that don't really do anything)
  * Changed the remark on the falling elevator in `tunnel1`
  * Changed the signal monologue in `furnace`
    * Now mentions the cell transceiver up in the tower
    * The picture monologue has been moved to when the player enters Stalburg Steel
  * Changed the monologue of the fallen tree in `reserve1`
  * Changed the stash monologue in `reserve3`
  * Changed the poison room monologue in `furnace`
  * Changed the gas monologue in `furnace`
  * Changed the monologue when exiting the tunnel in `watertreatment`
  * Changed the monologue when eating the kebab in `watertreatment`
  * Changed the "metro maintenance access" monologue in `sewer`
  * Changed the phone call in `tunnel2` to be less terrible
  * Changed the phone call in `tower` to be less terrible
  * Changed the phone call in `watertreatment` to be less terrible
  * Changed the payphone calls in `tower` to be less terrible
  * Changed the logging office office monologue in `reserve1`
  * Fixed grammar error in the the bolt cutter door monologue in `reserve1`
  * Fixed the phone call timings in `reserve1`
  * Fixed the monologue for water flow meters not being unique for each meter
  * Fixed capitalization in the `reserve2` funicular scream monologue
  * Removed the snarky remark when in the elevator from `furnace`
  * Removed the view monologue from `tower`
* Changed the van model and its textures
* Changed the forklift textures
* Changed the subtitle font size from 20 to 22
* Changed the subtitle shadow to be a bit softer
* Changed the hint message font size from 20 to 22
* Changed the hard drop shadow used in the hint messages to a very soft shadow
  * Same as the one used in the subtitles
* Changed camera transitions to not automatically re-equip the camera and the flashlight afterwards if they were equipped prior to enabling the camera
* Changed the dust motes in the main menu
  * There are now dust motes everywhere the light hits, but more near the projector
  * The dust motes are a bit smaller and little less bright now
* Changed fall damage to be a bit more harsh
* Fixed cutscenes not transitioning to the proper FOV if the player has set his FOV to something else than 90
* Fixed changing the FOV setting after dying and respawning
* Fixed the player's collision bounds not updating after crouching
  * All triggers behaved as if the player was standing even if he was crouching
  * It's now possible to crouch under the smoke in the fire puzzle of `sewer` and not take any damage
* Fixed occasional incorrect camera angles in document view (issue [#213] (https://github.com/loiste-interactive/infra-issues/issues/213))
* Fixed important decals disappearing on lower shader detail levels (issue [#208] (https://github.com/loiste-interactive/infra-issues/issues/208))
* Fixed lighting issues on a certain electrical box model with lower LODs (issue [#225] (https://github.com/loiste-interactive/infra-issues/issues/225))
* Fixed the camera being in the wrong place for one frame when entering the raft (issue [#37] (https://github.com/loiste-interactive/infra-issues/issues/37))
* Fixed the `restart` console command not working properly in the main menu
* Fixed sharp edges on the key icons in the options menu
* Fixed flashlight shadow artifacts on objects with use highlights (issue [#58] (https://github.com/loiste-interactive/infra-issues/issues/58))
* Fixed flashlight shadow artifacts on dynamic props with a custom lighting origin
* Fixed the terrible bolt cutter sound

## reserve1

* Changed the speed of the elevator at the end of the level
* Fixed the player's car at the start of the level having placeholder textures (issue [#218] (https://github.com/loiste-interactive/infra-issues/issues/218), [#225] (https://github.com/loiste-interactive/infra-issues/issues/225))
* Fixed player getting stuck (issue [#222](https://github.com/loiste-interactive/infra-issues/issues/222))
* Fixed weird train behaviour when spamming the train signal while the train is approaching (issue [#219](https://github.com/loiste-interactive/infra-issues/issues/219))
* Fixed an area portal not triggering under specific conditions (issue [#225](https://github.com/loiste-interactive/infra-issues/issues/225))
* Fixed a couple of spots near the power plant where the player could get stuck (issue [#222](https://github.com/loiste-interactive/infra-issues/issues/222))
* Fixed water near the clog only being visible from a certain angle (issue [#43](https://github.com/loiste-interactive/infra-issues/issues/43))

## reserve2

* Added a placeholder phone call to the elevator at the start of the level
  * The dialogue changes depending on your findings in `reserve1`
* Changed the speed of the elevator at the start of the level

## reserve3

* Changed the puzzle for opening the gate
  * Mechanically still the same
  * Just looks a bit different

## tunnel2

* Added use highlights to the useable computer

## watertreatment

* Added use highlights to the useable computer
* Fixed screens showing incorrect info (issue [#223] (https://github.com/loiste-interactive/infra-issues/issues/223))

## sewer

* Added use highlights to useable computers
* Added a puzzle to the alternative route
* Added a possibility to either fix the smoking transformer or activate a fire alarm
* Added more checkpoints (issue [#224] (https://github.com/loiste-interactive/infra-issues/issues/224))
* Changed the end of the level
* Changed the entrance of the forklift puzzle room
* Changed some of the elements of the forklift puzzle
* Changed the toilet poison puzzle valve location (issue [#221] (https://github.com/loiste-interactive/infra-issues/issues/221))
* Changed the mushroom machine puzzle to be easier (issue [#224] (https://github.com/loiste-interactive/infra-issues/issues/224))
* Changed a misleading ladder to look more like it can't be climbed (issue [#224] (https://github.com/loiste-interactive/infra-issues/issues/224))
* Fixed some unrealistically dark places
* Fixed faulty door behavior (issue [#210] (https://github.com/loiste-interactive/infra-issues/issues/210))
* Fixed crane sounds cutting short (issue [#211] (https://github.com/loiste-interactive/infra-issues/issues/211))
* Fixed inconsistency with `watertreatment` (issue [#212] (https://github.com/loiste-interactive/infra-issues/issues/212))
* Fixed disappearing computer screens (issue [#214] (https://github.com/loiste-interactive/infra-issues/issues/214))
* Fixed a couple of spots where the player could get stuck (issue [#216] (https://github.com/loiste-interactive/infra-issues/issues/216), [#224] (https://github.com/loiste-interactive/infra-issues/issues/224))
* Fixed forklift penetrating ceiling (issue [#227] (https://github.com/loiste-interactive/infra-issues/issues/227))
* Fixed performance issues when operating the small crane (issue [#227] (https://github.com/loiste-interactive/infra-issues/issues/227))

# December 19th 2015

* Added a new map called `sewer`
  * Located after `watertreatment`
* Added camera transitions to notes to make them easier to read
  * Press use on the notes to activate
* Added water impact particles
* Added water impact sounds
* Added fire particles
* Added two new death animations where the player collapses forwards and backwards
  * If there's no space to collapse sideways, these animations will be used
  * Should fix issues with dying where the camera sometimes went through walls
* Added voice acting for the rest of the Hartman tapes
* Added placeholder player monologue for running out of camera batteries
* Changed the first Hartman tape recording to a better quality one
* Changed dialogue lines throughout the game
* Changed camera accuracy (regarding target acquisition) a bit
* Changed the big valve model to a more high quality one
* Fixed player field of view being stuck on the default value after loading a saved game
* Fixed an issue with the visibility check of camera targets (issue [#177] (https://github.com/loiste-interactive/infra-issues/issues/177))
* Fixed player being able to equip & holster his camera during camera transitions (issue [#185] (https://github.com/loiste-interactive/infra-issues/issues/185))
* Fixed player flashlight poking through walls in a certain angle
* Fixed camera transition progress not saving (broke saved games saved in the middle of a camera transition)
* Fixed player lethal water level monologue sometimes triggering when there isn't even deep water nearby
* Fixed Hartman tape corruption targets triggering even when the player is no longer nearby
* Fixed closed captions playing regardless of how far away the source is
* Fixed text drop shadow artifacts
  * Especially noticeable with the `con_drawnotify` notifications with `developer 1`
* Fixed incorrect use highlights in some cases 
  * Especially noticeable with keycards and batteries inside drawers
* Fixed player dropping carried items when scaling obstacles
* Fixed a certain locked door sound having a huge delay before it played

## reserve1

* Added a cutscene when exiting the car in the beginning
* Added particles to the raft
* Changed the WW2 bomb to explode when tampered with
* Changed the elevator to award a "spot repaired"
* Fixed certain models having incorrect lighting (issue [#200] (https://github.com/loiste-interactive/infra-issues/issues/200))

## reserve2

* Added an achievement for getting across the flooded generator room without moving any of the boxes
* Fixed a bunch of doors missing animations
* Fixed the Hartman tape breaking if you spam use on it

## reserve3

* Added a map of the area to the control room office
* Fixed fence missing backface again (issue [#198] (https://github.com/loiste-interactive/infra-issues/issues/198))

## tunnel1

* Added player monologue to when exiting the elevator
* Added a Hartman tape to the break room
* Added foam to the water
* Fixed the use highlight of certain buttons showing through walls (issue [#188] (https://github.com/loiste-interactive/infra-issues/issues/188))
* Fixed an incorrectly lit decal (issue [#190] (https://github.com/loiste-interactive/infra-issues/issues/190))
* Fixed player getting stuck in the alarm panel's shutter (issue [#192] (https://github.com/loiste-interactive/infra-issues/issues/192))
* Fixed player being able to jump on the small legde near the flood gates (issue [#199] (https://github.com/loiste-interactive/infra-issues/issues/199))

## tunnel2

* Fixed issues with the control computer (issue [#193] (https://github.com/loiste-interactive/infra-issues/issues/193))

## tunnel3

* Added particles to the raft ride section
* Added foam to the water

## tunnel4

* Added an alternative route to the latter half of the map
* Added particles to the raft ride section
* Added foam to the water

## furnace

* Added more particles to the finale
* Fixed certain sprites showing through walls (issue [#201] (https://github.com/loiste-interactive/infra-issues/issues/201))

## tower

* Added a Hartman tape to the foreman's office
* Changed the brightness of some interior spaces to be brighter
* Fixed the edge of the level being too noticeable (issue [#195] (https://github.com/loiste-interactive/infra-issues/issues/195))
* Removed the achievement for reaching the top of the tower

## watertreatment

* Fixed computer with emails having missing textures (issue [#10] (https://github.com/loiste-interactive/infra-issues/issues/10))
* Fixed an invisible wall at the start of the level (issue [#73] (https://github.com/loiste-interactive/infra-issues/issues/73))
* Fixed lighting issues (issue [#181] (https://github.com/loiste-interactive/infra-issues/issues/181))
* Fixed doors missing sounds (issue [#182] (https://github.com/loiste-interactive/infra-issues/issues/182))
* Fixed broken keycard readers having highlights (issue [#183] (https://github.com/loiste-interactive/infra-issues/issues/183))
* Fixed toilets not having tags (issue [#194] (https://github.com/loiste-interactive/infra-issues/issues/194))
* Fixed bus missing textures (issue [#197] (https://github.com/loiste-interactive/infra-issues/issues/197))

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
* Changed the elevator sequence so that the player has to climb out before it falls
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
