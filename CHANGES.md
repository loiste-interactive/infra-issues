# Upcoming

## reserve2

* Removed catwalk color settings

## watertreatment

* Added labels to water sample analyzer switches
* Added barrels to make it look that the area is not accessible (issue [#714] (https://github.com/loiste-interactive/infra-issues/issues/714))
* Fixed watertreatment global
* Fixed doors (issue [#717] (https://github.com/loiste-interactive/infra-issues/issues/717))
* Fixed kebab highlights (issue [#723] (https://github.com/loiste-interactive/infra-issues/issues/723))
* Fixed grit classifier signs (issue [#740] (https://github.com/loiste-interactive/infra-issues/issues/740))

## metro

* Added a working speedometer to the maintenance tram
* Added working instrument lights to the maintenance tram
* Added a working horn to the maintenance tram
* Added proper sound for the maintenance tram diesel engine
* Changed the tram handling - acceleration and deceleration are a bit more smooth
* Fixed nodraw being visible (issue [#778] (https://github.com/loiste-interactive/infra-issues/issues/778))
* Fixed the maintenance tram headlights missing sprites
* Fixed the maintenance tram brake lever not rotating enough
* Fixed the maintenance tram throttle lever not rotating properly

## metroride

* Added new camera target locations
* Added a working speedometer to the maintenance tram
* Added working instrument lights to the maintenance tram
* Added a working horn to the maintenance tram
* Added proper sound for the maintenance tram diesel engine
* Changed the tram handling - acceleration and deceleration are a bit more smooth
* Fixed the collapse camera targets having too short range (issue [#782] (https://github.com/loiste-interactive/infra-issues/issues/782))
* Fixed the maintenance tram headlights missing sprites
* Fixed the maintenance tram brake lever not rotating enough
* Fixed the maintenance tram throttle lever not rotating properly

## waterplant

* Added camera target (issue [#783] (https://github.com/loiste-interactive/infra-issues/issues/783))
* Fixed corruption document not being photographable (issue [#775] (https://github.com/loiste-interactive/infra-issues/issues/775))
* Fixed television reflections (issue [#776] (https://github.com/loiste-interactive/infra-issues/issues/776))
* Removed one blue screen (issue [#761] (https://github.com/loiste-interactive/infra-issues/issues/761))

## central

* Fixed misplaced sprites for the ceiling lights

## bunker

* Added mushroom teddybear
* Added lights to bodyroom and laboratory door
* Changed breaker switch to control room button
* Changed hatch locked sound
* Fixed centrifuge room corruption targets (issue [#777] 
(https://github.com/loiste-interactive/infra-issues/issues/777))

# Next Update

* Fixed viewmodels shaking like crazy when standing on certain kind of slopes
* Fixed being unable to equip the camera with mouse wheel down
* Fixed the camera getting unequipped on its own on level transitions
* Fixed a rare issue where the crosshair would get stuck on-screen after a level transition
* Fixed the crosshair fading in too late after a screen fade in
* Fixed unuseable radiophones receiving use highlights
* Fixed a possible issue with unuseable boots receiving use highlights
* Fixed cardboard_box_001 collision

## tunnel2

* Changed Mark's line when pulling the fire alarm from "shit" to "shit, that wasn't the lights" (issue [#593] (https://github.com/loiste-interactive/infra-issues/issues/593))

## furnace

* Changed Mark's line "is that gas that I smell?" to "smells like there's a gas leak in here"

## central

* Removed the smeared text from the door code hint

## servicetunnel

* Fixed bunker codes text
* Fixed an issue with the level transition to `skyscraper` (issue [#796] (https://github.com/loiste-interactive/infra-issues/issues/796))

## bunker

* Fixed documents misplaced text
* Fixed gas sensors sign (issue [#793] (https://github.com/loiste-interactive/infra-issues/issues/793))

# September 30th 2016 (Version 2.0.5)

* Fixed a regression where players couldn't to bring up the phone in the `office` meeting anymore

# September 29th 2016 (Version 2.0.4)

* Fixed crouching while on a ladder not working properly
* Fixed an issue with viewmodel bobbing that was causing it to be a bit unresponsive
* Fixed a rare issue where players could get stuck on computer screens (issue [#758] 
(https://github.com/loiste-interactive/infra-issues/issues/758))

# September 27th 2016 (Version 2.0.3)

## bunker

* Fixed documents misplaced text
* Fixed an issue where it was possible to exit the crane while it was still moving (issue [#768] 
(https://github.com/loiste-interactive/infra-issues/issues/768))
* Fixed the crane not moving sideways when playing with a controller (issue [#769] 
(https://github.com/loiste-interactive/infra-issues/issues/769))

# September 26th 2016 (Version 2.0.2)

* Fixed incompatible saves not showing up in the main menu
* Fixed a crash in some cases when entering deep water
* Fixed a possible black screen when loading a save
* Fixed INFRA: Part 1 decisions not reflecting in INFRA: Part 2 in some cases (issue [#747] 
(https://github.com/loiste-interactive/infra-issues/issues/747))

## metro

* Fixed missing maintenance tram and random black screen in some cases (issue [#749] 
(https://github.com/loiste-interactive/infra-issues/issues/749))

## central

* Changed the texture for the door code hint

## cistern

* Fixed level transition from `stormdrain` to `cistern` booting you to the main menu in some cases

# September 25th 2016 (Version 2.0.1)

## tunnel4

* Fixed the raft breaking immediately on level start

## metro

* Fixed the maintenance tram failing to appear (issue [#729] 
(https://github.com/loiste-interactive/infra-issues/issues/729))

# September 25th 2016 (Version 2.0.0)

* Added new levels
* Added LODs for NPCs
* Added more eye textures for NPCs
* Added a backlight to the camera screen
* Added new pain sounds for Mark
* Added crouched death animations (issue [#465] 
(https://github.com/loiste-interactive/infra-issues/issues/465))
* Changed vehicle textures to look more realistic
* Changed the camera battery indicator to be more accurate
* Changed font rendering to generate mipmaps for certain fonts – drastically improves icon quality for the camera screen and text quality for in-game computers
* Changed game content to be loaded from pack files – drastically lowers loading times (we were seeing a 52% improvement on HDDs and 63% on SSDs)
* Changed the appearance of the pause menu
* Changed the default position of the developer console
* Changed use selection outlines to be hidden while in the menu
* Changed document view to also be exitable with the ESC key
* Changed NPCs to be less likely to wear certain colors
* Changed NPCs to be less likely to wear certain clothes
* Changed the game to not be pausable when the credits are about to roll
* Changed the death and hurt post-processing effect durations
* Changed vertex weights of NPC skins
* Fixed the game not automatically flushing content from memory on level changes when low on memory – this might help if you were experiencing crashes on a low-memory system
* Fixed occasional delays in Mark's battery monologue
* Fixed NPCs using wrong colors for collared shirts
* Fixed ponytail position on the female office worker model
* Fixed a hitch when equipping the camera for the first time
* Fixed player being unable to crouch after respawn if he died while crouched on a level that had no saved games
* Fixed fall damage sounds for light and medium damage being the wrong way around
* Fixed fall death sound not always playing
* Fixed player hurt post-processing effect not playing in quick succession
* Fixed the "coughing" closed caption not staying on-screen for long enough
* Fixed doors being able to block each other from opening or closing
* Fixed grainy saved game screenshots in the main menu
* Fixed delayed animation for saved game screenshots in the main menu
* Fixed player coughs and grunts using the wrong sound channel, occasionally causing them to overlap with player monologue or causing them to be cut off by other sounds
* Fixed crosshair not following the same rules as use selection outlines, causing crosshair to appear on objects that can't be used
* Fixed prop color not being used with static props where the model has use highlights (issue [#56] 
(https://github.com/loiste-interactive/infra-issues/issues/56))
* Fixed gaps in character models (issue [#268] 
(https://github.com/loiste-interactive/infra-playtest-issues/issues/268))
* Fixed clipping issues with ties (issue [#517] 
(https://github.com/loiste-interactive/infra-issues/issues/517))
* Fixed off-center multiline hints (issue [#675] 
(https://github.com/loiste-interactive/infra-issues/issues/675))
* Fixed the player being able to flush himself down certain toilets (issue [#698] 
(https://github.com/loiste-interactive/infra-issues/issues/698))
* Fixed certain doors playing the locked animation and sound when opened (issue [#701] 
(https://github.com/loiste-interactive/infra-issues/issues/701))
* Removed collisions from the green mushrooms

## office

* Fixed the hallway conversation starting before the player has even seen who's speaking
* Fixed one of the door windows being detached from the door itself (issue [#681] 
(https://github.com/loiste-interactive/infra-issues/issues/681))
* Fixed receptionist subtitles turning white when you interact with her after she has played the scripted scenes (issue [#683] 
(https://github.com/loiste-interactive/infra-issues/issues/683))
* Fixed a crash when "restarting from last save" in the meeting if no saved games exist (issue [#699] 
(https://github.com/loiste-interactive/infra-issues/issues/699))
* Fixed skybridge missing faces (issue [#722] 
(https://github.com/loiste-interactive/infra-issues/issues/722))
* Changed Mark's line "so I heard I get to visit a dam too" to "looks like I get to visit a dam too"

## reserve2

* Added a phone call for repairing the dam

## reserve3

* Added a phone call to the corpse room
* Fixed the secret stash counting as two separate corruption targets, even though it only awarded one
* Fixed the broken railing being photographable from very far away
* Fixed the secret stash being difficult to photograph (issue [#690] 
(https://github.com/loiste-interactive/infra-issues/issues/690))

## tunnel

* Removed the second alarm panel code and added a hint

## tunnel3

* Changed Mark's line "who builds an outhouse in a fresh water tunnel?" to "who's shitting in everybody's drinking water?"
* Fixed Mark's line "moonshine" preventing other lines from playing for a short while after it
* Removed Mark's line for looking at the raft

## tower

* Changed contents of the phone call when descending the tower

## sewer

* Fixed the fuel canisters not colliding with each other on the shelf
* Fixed delay in the crane switch sounds
* Fixed an unobtainable camera target
* Fixed sparks from the broken transformer clipping through walls
* Fixed the barrel being detachable from the crane (issue [#693] 
(https://github.com/loiste-interactive/infra-issues/issues/693))

## sewer2

* Changed one of the dynamic lights to make better use of it
* Fixed an invisible wall where a pillar had collapsed
* Fixed the player getting stuck on the wall when walking up the stairs to the chained gate
* Fixed the player getting stuck on some of the debris near the openable flood door
* Fixed performance issues (issue [#691] 
(https://github.com/loiste-interactive/infra-issues/issues/691))

# July 30th 2016 (Version 1.1.5)

* Added footstep sounds for puddles
* Added use selection outlines to objects that don't have use highlights (glass bottles, clutter, etc.)
* Added a hint for the use key
* Added keyboard/gamepad support to the options menu – completes Full Controller Support (issue [#117] 
(https://github.com/loiste-interactive/infra-issues/issues/117))
* Changed flashlight hints not to be shown while the player view is being controlled
* Changed the "show hints" label in the options menu to say "tutorial messages" instead
* Changed the "spot repaired" and "corruption uncovered" sounds to be the same as the "successful photo" sound
* Changed Mark to always say something after taking a photo of a document
* Changed Mark to always say something after repairing a spot
* Changed the main menu camera movement to be faster
* Changed the options menu to use submenus instead of tabs
* Changed the options menu slider tick sound
* Changed the mouse cursor to be hidden in the main menu when using the keyboard or a controller
* Changed Mark's deep water warning monologue
* Changed all subtitles to italic where the person is speaking through a speaker
* Changed Mark's jacket sleeves to glow better in the dark
* Changed the developer console size
* Changed options menu sliders to be thinner
* Changed all lines of subtitles to be centered, instead of just the whole subtitle item
* Changed options menu scrollbars to be draggable with the mouse
* Changed certain lower priority subtitles (such as the hallway conversations at the office) to be hidden while important subtitles (such as the receptionist dialogue at the office) are visible (issue [#599] 
(https://github.com/loiste-interactive/infra-issues/issues/599))
* Fixed fallback fonts – fixes rendering issues with Japanese, Chinese and Korean characters
* Fixed sounds playing quieter than usual when the player view is being controlled (raft ride, document view, climbing, etc.)
* Fixed pause menu and main menu mouse focus issues
* Fixed certain elevator LED screen having a regular font instead of a LED font
* Fixed numerous issues with use highlights
* Fixed numerous issues with use selection outlines
* Fixed numerous issues with the crosshair appearing on objects that can't be used
* Fixed numerous issues with objects being hard to use unless directly looking at them
* Fixed numerous issues with being able to use objects through walls
* Fixed the options menu slider tick sound playing too often when dragging sliders
* Fixed slight input lag in equipping the camera
* Fixed Mark warning himself about deep water even when the water isn't that deep
* Fixed a crash when clicking the play button when not signed into Steam – now displays an error message instead
* Fixed breakable prop gibs not floating on water
* Fixed Tab key behaviour in the main menu
* Fixed issues in the main menu and on in-game computers when the cursor is dragged outside the computer screen
* Fixed subtitle shadows getting cut off in some cases
* Fixed hint text shadow being a bit too intense
* Fixed subtitles being slightly off-center
* Fixed quickload bind being useable in the main menu
* Fixed gamepad getting stuck if you try binding keys in the options menu
* Fixed use highlights causing performance issues
* Fixed invisible useable valves (issue [#590] 
(https://github.com/loiste-interactive/infra-issues/issues/590))
* Fixed some voices missing spatialization, appearing to be too loud (issue [#597] 
(https://github.com/loiste-interactive/infra-issues/issues/597))
* Fixed player being able to pick up breakable prop gibs (issue [#645] 
(https://github.com/loiste-interactive/infra-issues/issues/645))
* Fixed subtitles not disappearing immediately if the sound is stopped (issue [#649] 
(https://github.com/loiste-interactive/infra-issues/issues/649))
* Fixed the camera screen being off when equipped for the first time after dying in a map with no saved game (issue [#653] 
(https://github.com/loiste-interactive/infra-issues/issues/653))

## office

* Added a confirmation prompt for skipping the meeting (issue [#600] 
(https://github.com/loiste-interactive/infra-issues/issues/600))
* Changed the text for the keycard reader hint
* Changed the slides used in the meeting
* Changed the receptionist's subtitle color to purple
* Changed sound mixing so that the receptionist dialogue ducks other dialogue
* Changed the hint for using the keycard reader not to show up until the player interacts with the door (issue [#598] 
(https://github.com/loiste-interactive/infra-issues/issues/598))
* Changed the text of the keycard reader note (issue [#644] 
(https://github.com/loiste-interactive/infra-issues/issues/644))
* Fixed poor timings in the meeting scene
* Fixed some subtitles in the meeting scene fading out too early
* Fixed a missing comma from a certain subtitle in the meeting scene
* Fixed a minor timing issue with the hallway conversation
* Fixed leaving the meeting not interrupting currently playing lines (issue [#553] 
(https://github.com/loiste-interactive/infra-issues/issues/553))
* Fixed player being able to climb the railing in the third floor (issue [#578] 
(https://github.com/loiste-interactive/infra-issues/issues/578))
* Fixed the key prompts not using localized text (issue [#601] 
(https://github.com/loiste-interactive/infra-issues/issues/601))
* Fixed certain door frame being usable (issue [#615] 
(https://github.com/loiste-interactive/infra-issues/issues/615))
* Fixed elevator lights staying on when it goes dark the second time (issue [#650] 
(https://github.com/loiste-interactive/infra-issues/issues/650))
* Fixed office main doors getting stuck open (issue [#651] 
(https://github.com/loiste-interactive/infra-issues/issues/651))
* Fixed sauna toilet missing flush particle (issue [#652] 
(https://github.com/loiste-interactive/infra-issues/issues/652))
* Fixed sauna missing drains (issue [#654] 
(https://github.com/loiste-interactive/infra-issues/issues/654))
* Fixed cubemap issues with the elevator blackout scene (issue [#660] 
(https://github.com/loiste-interactive/infra-issues/issues/660))
* Removed out of place gestures from the meeting scene

## reserve1

* Changed the position of the first geocache (issue [#610] 
(https://github.com/loiste-interactive/infra-issues/issues/610))
* Fixed lighting issues on certain rocks
* Fixed the cottage doors missing use highlights (issue [#257] 
(https://github.com/loiste-interactive/infra-issues/issues/257))
* Fixed player being able to climb on top of his car (issue [#609] 
(https://github.com/loiste-interactive/infra-issues/issues/609))
* Fixed the signal box repair target never triggering (issue [#621] 
(https://github.com/loiste-interactive/infra-issues/issues/621))
* Fixed padlocks retaining use highlights after use (issue [#642] 
(https://github.com/loiste-interactive/infra-issues/issues/642))

## reserve2

* Fixed the lab door note floating in mid-air (issue [#579] 
(https://github.com/loiste-interactive/infra-issues/issues/579))
* Fixed a typo on one of the info boards (issue [#589] 
(https://github.com/loiste-interactive/infra-issues/issues/589))
* Fixed certain autosaves triggering constantly when standing on them (issue [#608] 
(https://github.com/loiste-interactive/infra-issues/issues/608))
* Fixed issues with transition to `reserve3` (issue [#626] 
(https://github.com/loiste-interactive/infra-issues/issues/626))
* Fixed the dam camera target counting towards the total twice – once in `reserve1` and once in `reserve2` (issue [#641] 
(https://github.com/loiste-interactive/infra-issues/issues/641))
* Fixed the sawmill padlock retaining use highlights after use (issue [#642] 
(https://github.com/loiste-interactive/infra-issues/issues/642))

## reserve3

* Fixed player getting stuck behind a certain tree (issue [#602] 
(https://github.com/loiste-interactive/infra-issues/issues/602))
* Fixed the hidden stash missing use highlights (issue [#603] 
(https://github.com/loiste-interactive/infra-issues/issues/603))
* Fixed the cliff near the end of the level being finicky to walk (issue [#604] 
(https://github.com/loiste-interactive/infra-issues/issues/604) and [#605] 
(https://github.com/loiste-interactive/infra-issues/issues/605))
* Fixed the tunnel entrance camera target being photographable from weird angles (issue [#613] 
(https://github.com/loiste-interactive/infra-issues/issues/613))
* Fixed issues with transition to `reserve2` (issue [#626] 
(https://github.com/loiste-interactive/infra-issues/issues/626))

## tunnel1

* Added missing flood door labels
* Added missing camera target (issue [#606] 
(https://github.com/loiste-interactive/infra-issues/issues/606))
* Added missing flood door player clip (issue [#607] 
(https://github.com/loiste-interactive/infra-issues/issues/607))
* Fixed the pipe room flood door valve getting stuck (issue [#620] 
(https://github.com/loiste-interactive/infra-issues/issues/620))

## tunnel2

* Added camera target for the broken wall of the chlorine tank building
* Added camera target for the broken fence (issue [#630] 
(https://github.com/loiste-interactive/infra-issues/issues/630))
* Added working meter and sound for the chlorine tank (issue [#631] 
(https://github.com/loiste-interactive/infra-issues/issues/631))
* Changed the monitors to use localized text
* Changed the elevation of the red pipe by the cliff (issue [#646] 
(https://github.com/loiste-interactive/infra-issues/issues/646))
* Fixed player not being able to climb to the other three pools of water
* Fixed the water in the pools not acting like water
* Fixed player getting stuck behind certain railing (issue [#580] 
(https://github.com/loiste-interactive/infra-issues/issues/580))
* Fixed player getting stuck to the exit pipe (issue [#584] 
(https://github.com/loiste-interactive/infra-issues/issues/584))
* Fixed player blocking the toiler seat cover (issue [#591] 
(https://github.com/loiste-interactive/infra-issues/issues/591))
* Fixed the keycard pickup spot being useable after pickup (issue [#623] 
(https://github.com/loiste-interactive/infra-issues/issues/623))
* Fixed player getting stuck near the cliff face (issue [#629] 
(https://github.com/loiste-interactive/infra-issues/issues/629))
* Fixed indoor cables being affected by the wind (issue [#636] 
(https://github.com/loiste-interactive/infra-issues/issues/636))
* Fixed incorrect door status light (issue [#637] 
(https://github.com/loiste-interactive/infra-issues/issues/637))
* Fixed player being able to stand on a certain window sill (issue [#647] 
(https://github.com/loiste-interactive/infra-issues/issues/647))
* Fixed certain gates being unusable (issue [#657] 
(https://github.com/loiste-interactive/infra-issues/issues/657))

## tunnel3

* Added camera targets for the raft ride (issue [#429] 
(https://github.com/loiste-interactive/infra-issues/issues/429))
* Changed the raft to rotate a bit in the direction it's being steered in
* Fixed the raft model clipping with the water surface
* Fixed player getting stuck when transitioning from `tunnel2` (issue [#596] 
(https://github.com/loiste-interactive/infra-issues/issues/596))

## tunnel4

* Added camera targets for the raft ride (issue [#429] 
(https://github.com/loiste-interactive/infra-issues/issues/429))
* Fixed Mark warning himself about deep water after the raft breaks, as if it wasn't obvious (issue [#628] 
(https://github.com/loiste-interactive/infra-issues/issues/628))

## furnace

* Changed certain button to a more relevant lever (issue [#404] 
(https://github.com/loiste-interactive/infra-issues/issues/404))
* Fixed the ladle control switch being usable after the initial use despite not doing anything (issue [#575] 
(https://github.com/loiste-interactive/infra-issues/issues/575))
* Fixed out of bounds issues (issue [#581] 
(https://github.com/loiste-interactive/infra-issues/issues/581) and [#582] 
(https://github.com/loiste-interactive/infra-issues/issues/582))
* Fixed the control room key pickup spot being useable after pickup (issue [#625] 
(https://github.com/loiste-interactive/infra-issues/issues/625))
* Removed certain crate which could be used to get stuck (issue [#576] 
(https://github.com/loiste-interactive/infra-issues/issues/576))

## tower

* Changed certain switches to be less confusing (issue [#577] 
(https://github.com/loiste-interactive/infra-issues/issues/577))
* Fixed the busy tone for a certain phone number playing while the call tone was still playing
* Fixed out of bounds issues (issue [#526] 
(https://github.com/loiste-interactive/infra-issues/issues/526) and [#530] 
(https://github.com/loiste-interactive/infra-issues/issues/530))
* Fixed the ladder padlock retaining use highlights after use (issue [#642] 
(https://github.com/loiste-interactive/infra-issues/issues/642))

## watertreatment

* Fixed being able to turn on the secondary clarifier when the selected grit classifier is off
* Fixed some mistakes in the email content on the computer
* Fixed out of bounds issue (issue [#574] 
(https://github.com/loiste-interactive/infra-issues/issues/574))
* Fixed a certain floating rack (issue [#585] 
(https://github.com/loiste-interactive/infra-issues/issues/585))
* Fixed player getting stuck on a certain cardboard box (issue [#586] 
(https://github.com/loiste-interactive/infra-issues/issues/586))
* Fixed player blocking the toiler seat cover (issue [#595] 
(https://github.com/loiste-interactive/infra-issues/issues/595))

## sewer

* Added signs to the remote controlled gates to clarify their function (issue [#568] 
(https://github.com/loiste-interactive/infra-issues/issues/568))
* Fixed certain trees missing collisions
* Fixed weird climbing spot in front of the forklift (issue [#566] 
(https://github.com/loiste-interactive/infra-issues/issues/566))
* Fixed a certain door getting stuck open (issue [#611] 
(https://github.com/loiste-interactive/infra-issues/issues/611))
* Fixed player getting stuck to debris at the pump station (issue [#612] 
(https://github.com/loiste-interactive/infra-issues/issues/612))
* Fixed a certain door being useable from the wrong side (issue [#618] 
(https://github.com/loiste-interactive/infra-issues/issues/618))
* Fixed hacker den windows missing collisions (issue [#619] 
(https://github.com/loiste-interactive/infra-issues/issues/619))
* Fixed a repair spot that was impossible to obtain (issue [#622] (https://github.com/loiste-interactive/infra-issues/issues/622))
* Fixed an invisible floating button in front of the forklift (issue [#624] (https://github.com/loiste-interactive/infra-issues/issues/624))
* Fixed unusual behaviour with certain faulty button (issue [#627] (https://github.com/loiste-interactive/infra-issues/issues/627))
* Fixed forklift ignition key being usable after startup (issue [#639] (https://github.com/loiste-interactive/infra-issues/issues/639))
* Fixed the padlock retaining use highlights after use (issue [#642] 
(https://github.com/loiste-interactive/infra-issues/issues/642))

## sewer2

* Fixed the bolt cutter use highlights reappearing if the gate is closed (issue [#643] (https://github.com/loiste-interactive/infra-issues/issues/643))

# May 14th 2016 (Version 1.1.4)

* Added autosaves to be loadable from the pause menu
* Added a subtle red tint to the player hurt effect – on lower settings this is displayed instead of the post-processing effect, but on higher graphics settings this is displayed in addition to the post-processing effect
* Added demo recording back (issue [#124] 
(https://github.com/loiste-interactive/infra-issues/issues/124))
* Changed "restart from checkpoint" pause menu option to read "restart from last save"
* Changed the player hurt effect to be also played for the killing blow
* Fixed a case where triggers could cause 0 damage to the player (i.e. screen would shake, but no damage effects would appear and no damage would be actually taken)
* Fixed the main menu focusing multiple menu options at once in some cases after a video mode change
* Fixed the pause menu being briefly visible during level loading
* Fixed a case where the player could receive 0 fall damage if near the fall damage velocity threshold (i.e. screen would shake, but no damage effects would appear and no damage would be actually taken)
* Fixed frame rate drop when taking a photo (or repairing a spot, etc.) for the first time
* Fixed demo recording issue where the game would crash when the player died (issue [#124] 
(https://github.com/loiste-interactive/infra-issues/issues/124))
* Fixed demo playback ending when the player dies (issue [#124] 
(https://github.com/loiste-interactive/infra-issues/issues/124))
* Fixed demo playback issue where the electrified water death sound was still playing after the player had respawned (issue [#124] 
(https://github.com/loiste-interactive/infra-issues/issues/124))

## office

* Changed the intro sequence so that the player view is less restricted

# May 3rd 2016 (Version 1.1.3)

* Fixed a crash on equipping the camera when hints are disabled (issue [#573] 
(https://github.com/loiste-interactive/infra-issues/issues/573))

## watertreatment

* Fixed the player's "where is everybody" line triggering multiple times
* Fixed issues with the contents of the emails

# May 3rd 2016 (Version 1.1.2)

* Added a hint for throwing held objects
* Added a fade in & fade out to level transitions
* Added a fade out when loading a saved game or starting a new game from the main menu
* Added a fade in after the loading screen when starting a new game
* Added information about the saved games to the load game and save game menus (chapter and time played)
* Added "use selection outline" to the options menu (it's now separate from use highlights)
* Added a dialog to the main menu that will prompt you to restart the level if you try to load an incompatible saved game
* Added full Steam Cloud support for saved games (previously only unlocked chapters and level stats were synced)
* Added generic dialogue for the female office workers
* Changed some of the various notes to be properly handwritten with better language
* Changed saved games so that it's no longer possible to load old incompatible saved games
* Changed saved games so that saved games in the same level are now loaded much faster
* Changed the loading screen (removed the spinner and added a progress bar instead)
* Changed load games to use a different fade in instead of the respawn effect
* Changed the water splash sound to have a bit more variation
* Changed the respawn effect
* Changed use highlights and selection outlines to be hidden when the camera is being controlled
* Changed the camera to only register a single camera target per picture – the one closest to the center of the screen
* Changed closed doors to be useable from further away if they are not locked
* Changed the flashlight equip hint not to be shown if the player has already equipped his flashlight at least once
* Changed the camera equip hint not to be shown if the player has already equipped his camera at least once
* Changed the camera focus indicator hint to be shown until the player takes a successful photo
* Changed the document view so that it zooms in closer with certain documents (issue [#494] 
(https://github.com/loiste-interactive/infra-issues/issues/494))
* Changed the player not to collide with small physics props (issue [#570] 
(https://github.com/loiste-interactive/infra-issues/issues/570))
* Fixed the player character being able to talk while dead
* Fixed camera targets, etc. not always saving their state properly
* Fixed film grain affecting screen fades
* Fixed color correction affecting screen fades
* Fixed closed captions not being affected by screen fades
* Fixed minor memory leaks
* Fixed being able to quick save while in the main menu
* Fixed a crash when trying to start a game on a map that no longer exists
* Fixed incorrect subtitles for the first geocache line
* Fixed input lag when VSync is enabled
* Fixed glitchy respawn sound fade
* Fixed use highlights for several objects
* Fixed a rare issue where the player could no longer equip his camera after dying
* Fixed chapter titles not being affected by screen fades
* Fixed being able to climb on held objects
* Fixed attenuation for some dialogue
* Fixed an issue where the player could get stuck crouching if the game was saved while the view was being controlled
* Fixed weird white lines appearing on NPCs on low graphics settings
* Fixed NPCs drawing incorrectly on low graphics settings
* Fixed held objects glitching out if you pick up another object while still holding the other one
* Fixed misaligned document view for a certain model
* Fixed being able to use entities while the view is being controlled – was especially a problem with the various in-game computers
* Fixed scaffolding model lighting
* Fixed corruption targets not counting as a successful photo for the camera hints
* Fixed a crash when saving the game on resolutions smaller than 512 × 512
* Fixed saved game screenshot aspect ratios
* Fixed the player moving faster while crouching diagonally
* Fixed the player moving faster on ladders diagonally
* Fixed finicky crate physics (issue [#93] 
(https://github.com/loiste-interactive/infra-issues/issues/93))
* Fixed flashlight sometimes coming up without animation after respawn (issue [#121] 
(https://github.com/loiste-interactive/infra-issues/issues/121))
* Fixed unused models and materials not getting unloaded on level changes, leading to out of memory crashes (issue [#289] 
(https://github.com/loiste-interactive/infra-issues/issues/289))
* Fixed water reflections on low graphics settings (issue [#293] 
(https://github.com/loiste-interactive/infra-issues/issues/293))
* Fixed finicky climbing (issue [#310] 
(https://github.com/loiste-interactive/infra-issues/issues/310))
* Fixed closed captions sometimes disappearing for a while after dying (issue [#319] 
(https://github.com/loiste-interactive/infra-issues/issues/319))
* Fixed soundscapes stopping playing after the player dies until the player moves to a new soundscape (issue [#373] 
(https://github.com/loiste-interactive/infra-issues/issues/373))
* Fixed crouched player no longer crouching after exiting the document view (issue [#382] 
(https://github.com/loiste-interactive/infra-issues/issues/382))
* Fixed zoomed in player no longer being zoomed in after exiting the document view (issue [#416] 
(https://github.com/loiste-interactive/infra-issues/issues/416))
* Fixed camera screen sometimes not focusing after dying (issue [#422] 
(https://github.com/loiste-interactive/infra-issues/issues/422))
* Fixed camera screen sometimes staying off after picking up props when equipped (issue [#432] 
(https://github.com/loiste-interactive/infra-issues/issues/432))
* Fixed missing localization tokens for "autosave" and "quicksave" in the main menu (issue [#512] 
(https://github.com/loiste-interactive/infra-issues/issues/512))
* Removed a certain climb foley sound
* Removed demo recording (issue [#124] 
(https://github.com/loiste-interactive/infra-issues/issues/124))

## office

* Added detail to certain areas
* Added autosave to when picking up the letter from the reception
* Added use highlights to the toilet in the sauna (issue [#536]
(https://github.com/loiste-interactive/infra-issues/issues/536))
* Added footsteps to the parking garage cutscene (issue [#556]
(https://github.com/loiste-interactive/infra-issues/issues/556))
* Added footsteps to the starting scene (issue [#557]
(https://github.com/loiste-interactive/infra-issues/issues/557))
* Changed the location of the geocache slightly
* Fixed reflection issues in the kithen
* Fixed being able to jump down the lobby without dying
* Fixed the receptionist scene continuing even if the player has left the immediate area
* Fixed the walking NPC in the lobby disapperearing visibly
* Fixed zoom hint appearing at wrong times (issue [#314]
(https://github.com/loiste-interactive/infra-issues/issues/314))
* Fixed car driver door being solid red if use highlights are turned off (issue [#324]
(https://github.com/loiste-interactive/infra-issues/issues/324))
* Fixed certain office worker staring at a black screen (issue [#343]
(https://github.com/loiste-interactive/infra-issues/issues/343))
* Fixed the key envelope being usable after it's taken (issue [#346]
(https://github.com/loiste-interactive/infra-issues/issues/346))
* Fixed being able to jump down the lobby without dying (issue [#347]
(https://github.com/loiste-interactive/infra-issues/issues/347))
* Fixed being able to get stuck behind certain ladder (issue [#502]
(https://github.com/loiste-interactive/infra-issues/issues/502))
* Fixed being able to see a card corridor too clearly (issue [#503]
(https://github.com/loiste-interactive/infra-issues/issues/503))
* Fixed cutscenes not working properly (issue [#533]
(https://github.com/loiste-interactive/infra-issues/issues/533) and [#534]
(https://github.com/loiste-interactive/infra-issues/issues/534))
* Fixed a small reflection issue near the server room (issue [#539]
(https://github.com/loiste-interactive/infra-issues/issues/539))
* Fixed various lighting issues (issue [#555]
(https://github.com/loiste-interactive/infra-issues/issues/555))

## reserve1

* Added new autosaves
* Added corruption camera target for the logging zone map
* Fixed train horn playing after the train has already arrived
* Fixed the dam crack achievement being hard to trigger
* Fixed certain static barrels being physics objects
* Fixed out of bounds issues
* Fixed chapter title never being displayed at the start of the map (issue [#320] 
(https://github.com/loiste-interactive/infra-issues/issues/320))
* Fixed player's head clipping through the bridge (issue [#516] 
(https://github.com/loiste-interactive/infra-issues/issues/516))
* Fixed being able to use the water flow monitor instruments through the door (issue [#551] 
(https://github.com/loiste-interactive/infra-issues/issues/551))

## reserve2

* Added new autosaves
* Added a new route to the turbine hall to make backtracking less of a hassle
* Added a new corruption document
* Added a mistake target to when turning on the turbine hall power
   * Can be untriggered by turning the power off
* Added a camera target for the tree growing on the concrete
* Added player clips to certain places (issue [#559] 
(https://github.com/loiste-interactive/infra-issues/issues/559))
* Changed the cabin keyholder to be less confusing
* Fixed player being able to climb out of the elevator
* Fixed weird behaviour with certain locked door handles
* Fixed the switchyard fire causing performance issues
* Fixed synchroscopes being off-center when synched
* Fixed flickering water in the generator room when looking out of the window in a certain angle (issue [#495]
(https://github.com/loiste-interactive/infra-issues/issues/495))
* Fixed the lab door note being parented to the door (issue [#498]
(https://github.com/loiste-interactive/infra-issues/issues/498))
* Fixed issues with dam areaportals (issue [#499]
(https://github.com/loiste-interactive/infra-issues/issues/499))
* Fixed one of the synchroscopes being unuseable after the generators are turned off and on again (issue [#514]
(https://github.com/loiste-interactive/infra-issues/issues/514))
* Fixed the valve at the lab missing sounds (issue [#515]
(https://github.com/loiste-interactive/infra-issues/issues/515))
* Fixed player getting stuck to the small rocks near the cottage (issue [#542]
(https://github.com/loiste-interactive/infra-issues/issues/542))
* Fixed screen jumping up an down when walking on the sawmill generator room floor(issue [#543]
(https://github.com/loiste-interactive/infra-issues/issues/543))
* Fixed the entrance elevator being finicky to climb out (issue [#545]
(https://github.com/loiste-interactive/infra-issues/issues/545))

## reserve3

* Added camera target for the broken railing at the Bergmann tunnel
* Fixed certain static barrels being physics objects
* Fixed the office door lighting
* Fixed the tunnel railing lighting
* Fixed the cliff face being difficult to climb
* Fixed the concrete barrier player clip (issue [#541] 
(https://github.com/loiste-interactive/infra-issues/issues/541))

## tunnel1

* Changed the pipe room fuse to affect the pipe room (issue [#513]
(https://github.com/loiste-interactive/infra-issues/issues/513))
* Fixed timing issue with the "shouldn't have jinxed it" line
* Fixed the A2 pipe lights (issue [#513]
(https://github.com/loiste-interactive/infra-issues/issues/513))
* Fixed the heavy door lights (issue [#508]
(https://github.com/loiste-interactive/infra-issues/issues/508))
* Fixed visual artifacts with the collapsing ceiling (issue [#386]
(https://github.com/loiste-interactive/infra-issues/issues/386))

## tunnel3

* Fixed the player's camera screen disappearing when entering the raft with the camera equipped
* Fixed being able to use the water flow monitor instruments through the door (issue [#552] 
(https://github.com/loiste-interactive/infra-issues/issues/552))

## tunnel4

* Added a new camera target to the changed route at the power plant under construction
* Added player clips to certain places
* Changed the climbing part on the power plant under construction
* Changed the dynamite explosion kill radius to be smaller
* Changed the office lighting to be dimmer
* Changed the flooded electrified hallway door opening direction (issue [#548] 
(https://github.com/loiste-interactive/infra-issues/issues/548))
* Changed the flooded electrified hallway crate to smaller crate (issue [#550] 
(https://github.com/loiste-interactive/infra-issues/issues/550))
* Fixed some mining area lighting issues
* Fixed certain notes being unusable
* Fixed the key box (issue [#395] 
(https://github.com/loiste-interactive/infra-issues/issues/395))
* Fixed an alternative route door unlocking when it shouldn't (issue [#500] 
(https://github.com/loiste-interactive/infra-issues/issues/500))
* Fixed light switch highlights (issue [#521] 
(https://github.com/loiste-interactive/infra-issues/issues/521))
* Fixed being able to use the water flow monitor instruments through the door (issue [#547] 
(https://github.com/loiste-interactive/infra-issues/issues/547))
* Fixed button highlights (issue [#549] 
(https://github.com/loiste-interactive/infra-issues/issues/549))

## furnace

* Fixed incorrect subtitles and timing issues with VO
* Fixed attenuation for the recorded announcements
* Fixed illogical behaviour with the minitrain controls (issue [#501]
(https://github.com/loiste-interactive/infra-issues/issues/501))

## tower

* Fixed power lines in the skybox moving in the wind
* Fixed certain doors missing sounds (issue [#520] 
(https://github.com/loiste-interactive/infra-issues/issues/520))

## watertreatment

* Added detail to the office (issue [#572]
(https://github.com/loiste-interactive/infra-issues/issues/572))
* Changed the pipes at the sludge building to affect the conveyor belt sludge
* Fixed reflection issues
* Fixed flickering debris
* Fixed installation CD insertion behavior
* Fixed some models being too bright
* Fixed a player's line getting cut off in the phone call to his boss if he has turned on some of the water flow meters
* Fixed a player's line missing subtitles in the phone call to his boss if he has turned on all of the water flow meters (issue [#442]
(https://github.com/loiste-interactive/infra-issues/issues/442))
* Fixed being able to get out of the playable area (issue [#529]
(https://github.com/loiste-interactive/infra-issues/issues/529))
* Removed a water sample on the floor near the test machine (issue [#543]
(https://github.com/loiste-interactive/infra-issues/issues/532))

## sewer

* Added missing player clips (issue [#540]
(https://github.com/loiste-interactive/infra-issues/issues/540))
* Added a camera target for the broken stairs (issue [#567]
(https://github.com/loiste-interactive/infra-issues/issues/567))
* Fixed hacker den windows being non-solid
* Fixed being able to get out of the playable area (issue [#527]
(https://github.com/loiste-interactive/infra-issues/issues/527))
* Fixed being able to lose the diesel canister to the elevator shaft (issue [#562]
(https://github.com/loiste-interactive/infra-issues/issues/562))
* Fixed sewer entrance door not being closeable (issue [#565]
(https://github.com/loiste-interactive/infra-issues/issues/565))
* Removed trigger_push (issue [#544]
(https://github.com/loiste-interactive/infra-issues/issues/544))

## sewer2

* Changed the hint for throwing held objects to reappear in this level since it's essential to progress
* Fixed notes on the map being difficult to interact with
* Fixed leaking pipe camera target not triggering when close
* Removed "the Bergmann tunnel underneath has collapsed" line

# March 17th 2016 (Version 1.1.1)

* Fixed credits not rolling
* Fixed Unicode not displaying properly in subtitles or credits

## office

* Changed one of the nag monologue subtitles when the player doesn't go get his stuff
* Fixed missing subtitles from the player's greeting at the meeting

## watertreatment

* Added poison building label

# March 15th 2016 (Version 1.1.0)

* Added use highlights to toilets (issue [#258]
(https://github.com/loiste-interactive/infra-issues/issues/258))
* Changed player's voice
* Changed the sound effect for "spot repaired" and "corruption uncovered" to be louder
* Fixed a certain gate model texture (issue [#399]
(https://github.com/loiste-interactive/infra-issues/issues/399))
* Fixed a large amount of dustmotes causing very noticeable visual artifacts when viewed at a distance (issue [#493] 
(https://github.com/loiste-interactive/infra-issues/issues/493))
  * Noticeable in `office` and `reserve2`

## office

* Added new player VO
    * Added to when loitering for too long in the hallways
    * Added to when trying to use the locked gate in the fire escape
    * Added to when grabbing all the required gear from the player's office
* Added corruption targets to both of the newspapers
    * Triggered when the papers are read
* Changed lighting of some office rooms
* Changed the randomization of the generic office workers
  * Their hair texture and normal map are now randomized instead of simply tinting the hair
  * Their skin texture and normal map are now randomized instead of simply tinting the skin
* Changed Amit's character to use another model in the intro scene
* Changed face textures and materials for all character models
* Changed head models for most of the characters
* Fixed the boss's eyes sometimes randomly changing color
* Fixed being able to pick up items through the cabinet door

## reserve1

* Added new autosaves
   * Added to when fixing the water flow meter
   * Added to when picking up the bolt cutters
   * Added to when cutting the chain with the bolt cutters
   * Added to when photographing the Morning Wood office document
* Added a new hidden achievement
* Added detail and clutter to the start area
* Added detail to the logging zone
* Added a camera target to the wooden bridge
* Changed one of the cliff faces to be more realistic
* Changed the transformer camera target to stay enabled
* Changed certain model (issue [#477] 
(https://github.com/loiste-interactive/infra-issues/issues/477))
* Fixed overlapping subtitles in the phone call to boss
* Fixed the timing of a specific subtitle in the phone call to boss
* Fixed map monologue interrupting corruption monologue
* Fixed illogical train breaking sound (issue [#259] 
(https://github.com/loiste-interactive/infra-issues/issues/259))
* Fixed train signal global not triggering (issue [#372] 
(https://github.com/loiste-interactive/infra-issues/issues/372))
* Fixed certain geocache being finicky to pick up (issue [#384] 
(https://github.com/loiste-interactive/infra-issues/issues/384))
* Fixed some issues with the cable raft (issue [#419] 
(https://github.com/loiste-interactive/infra-issues/issues/419))
* Fixed certain invisible walls (issue [#420] 
(https://github.com/loiste-interactive/infra-issues/issues/420))
* Fixed props having incorrect lighting (issue [#475] 
(https://github.com/loiste-interactive/infra-issues/issues/475))
* Fixed out of bounds issue (issue [#492] 
(https://github.com/loiste-interactive/infra-issues/issues/492))

## reserve2

* Added new autosaves
   * Added to when exiting the elevator
   * Added to when turning on the generator hall power
* Added a hint for the climb button to the elevator part
* Added new rooms to the dam
   * A security checkpoint next to the elevator exit, houses new puzzle elements
   * A collapsed tunnel leading from the control room
   * A laboratory to the Western side of the dam
* Added a new door control mechanism to the dam
* Added new camera targets to the dam
* Added new particles to the switchyard
* Added a new room to the sawmill
* Added a newspaper to the sawmill
* Added a new repailable spot to the dam
* Added a new achievement when fixing the dam
* Added missing camera targets (issue [#426] 
(https://github.com/loiste-interactive/infra-issues/issues/426) and issue [#469] 
(https://github.com/loiste-interactive/infra-issues/issues/469))
* Changed the sawmill generator room power to be toggleable
   * Also added a mistake target which is fired when the power is turned on, but unfired if the power is turned off
* Changed the murkiness of the water in the generator hall
* Changed the textures of the info signs
* Changed the room before Hartman's office to a secretary's office / waiting space
   * Moved the secretary's note from the western wing to here
* Changed the dam to be fully repairable
   * Changed the way the switchyard breaker works
   * Moved the sluice gate control panel to the control room
     * Changed the way the panel functions
* Changed the layout of the western side of the dam
* Changed the sawmill lighting to be more realistic
* Fixed the elevator teleporting down a bit when freefalling
* Fixed the achievement `Step and Jump` being unlockable even when the power was off
* Fixed tree fading out noticeably (issue [#262] 
(https://github.com/loiste-interactive/infra-issues/issues/262))
* Fixed problem with certain locked door (issue [#299] 
(https://github.com/loiste-interactive/infra-issues/issues/299))
* Fixed player getting stuck under the sawmill log collection platform (issue [#303] 
(https://github.com/loiste-interactive/infra-issues/issues/303))
* Fixed certain camera target having too short range (issue [#337] 
(https://github.com/loiste-interactive/infra-issues/issues/337))
* Fixed low res reflections on the puddles (issue [#348] 
(https://github.com/loiste-interactive/infra-issues/issues/348))
* Fixed models being too bright (issue [#423] 
(https://github.com/loiste-interactive/infra-issues/issues/423) and issue [#475] 
(https://github.com/loiste-interactive/infra-issues/issues/475))
* Fixed broken areaportal at the dam (issue [#308] 
(https://github.com/loiste-interactive/infra-issues/issues/308) and issue [#424] 
(https://github.com/loiste-interactive/infra-issues/issues/424))
* Fixed the broken wires being unphotographable when too close (issue [#425] 
(https://github.com/loiste-interactive/infra-issues/issues/425))
* Fixed the crow sitting on the bird watching tower sometimes not flying away (issue [#427] 
(https://github.com/loiste-interactive/infra-issues/issues/427))
* Fixed water particles clipping throught the wall (issue [#428] 
(https://github.com/loiste-interactive/infra-issues/issues/428))
* Fixed the rock ramp at the end of the level being finicky to climb back up (issue [#447] 
(https://github.com/loiste-interactive/infra-issues/issues/447))
* Fixed the note on the exit gate interupting the gate opreation (issue [#467] 
(https://github.com/loiste-interactive/infra-issues/issues/467))
* Fixed player getting stuck between the rocks near the forest guard's cabin (issue [#473] 
(https://github.com/loiste-interactive/infra-issues/issues/473))
* Fixed bunch of floating objects (issue [#474] 
(https://github.com/loiste-interactive/infra-issues/issues/474) and issue [#476] 
(https://github.com/loiste-interactive/infra-issues/issues/476))
* Removed unnecessary crates from the sawmill

## reserve3

* Added missing camera targets
* Added playerclip to concrete barrier(issue [#385]
(https://github.com/loiste-interactive/infra-issues/issues/385))
* Added more playerclips to the cliff path (issue [#482]
(https://github.com/loiste-interactive/infra-issues/issues/482))
* Added a camera target for the fallen ladder (issue [#496]
(https://github.com/loiste-interactive/infra-issues/issues/496))
* Changed the flood door to slide down(issue [#457]
(https://github.com/loiste-interactive/infra-issues/issues/457))
* Fixed props having incorrect lighting
* Fixed the broken window collision model (issue [#481]
(https://github.com/loiste-interactive/infra-issues/issues/481))

## tunnel

* Added more valve spots (issue [#444]
(https://github.com/loiste-interactive/infra-issues/issues/444))
* Added button sounds to alarm keypad when it's off (issue [#471] 
(https://github.com/loiste-interactive/infra-issues/issues/471))
* Changed keypad screen to be off when there is no power (issue [#450]
(https://github.com/loiste-interactive/infra-issue/450))
* Fixed some misaligned models
* Fixed lighting glitch (issue [#161]
(https://github.com/loiste-interactive/infra-issues/issues/161))
* Fixed the elevator monologue (issue [#387]
(https://github.com/loiste-interactive/infra-issues/issues/387))
* Fixed certain camera target having too small range (issue [#445]
(https://github.com/loiste-interactive/infra-issues/issues/445))
* Fixed misaligned digit on the keypad screen (issue [#446]
(https://github.com/loiste-interactive/infra-issues/issues/446))
* Fixed missing autosave (issue [#490] 
(https://github.com/loiste-interactive/infra-issues/issues/490))

## tunnel2

* Added camera target to the newspaper (issue [#483] 
(https://github.com/loiste-interactive/infra-issues/issues/483))
* Fixed the door magically locks behind the player at the start of map (issue [#458] 
(https://github.com/loiste-interactive/infra-issues/issues/458))

## tunnel3

* Added an autosave to corruption document (issue [#390] 
(https://github.com/loiste-interactive/infra-issues/issues/390))
* Fixed the catwalk camera target having too large range (issue [#389]
(https://github.com/loiste-interactive/infra-issues/issues/389))
* Fixed three different documents count as one camera target (issue [#488]
(https://github.com/loiste-interactive/infra-issues/issues/488))

## tunnel4

* Added functional light switch to office (issue [#394] 
(https://github.com/loiste-interactive/infra-issues/issues/394))
* Added button sounds to alarm keypad when it's off (issue [#470] 
(https://github.com/loiste-interactive/infra-issues/issues/470))
* Fixed raft emitting particles after it breaks (issue [#392] 
(https://github.com/loiste-interactive/infra-issues/issues/392))
* Fixed the junk collisions near water (issue [#393] 
(https://github.com/loiste-interactive/infra-issues/issues/393))
* Fixed a lever sound (issue [#400] 
(https://github.com/loiste-interactive/infra-issues/issues/400))
* Removed red indicator light (issue [#454] 
(https://github.com/loiste-interactive/infra-issues/issues/454))

## furnace

* Fixed ending event being skipable
* Removed finicly ladder near planks

## tower

* Changed the floor crap (issue [#405] 
(https://github.com/loiste-interactive/infra-issues/issues/405))
* Fixed wrong door sounds (issue [#339] 
(https://github.com/loiste-interactive/infra-issues/issues/339))
* Fixed sparks from fuses clipping through several levels (issue [#357] 
(https://github.com/loiste-interactive/infra-issues/issues/357))
* Fixed a certain floating door (issue [#407] 
(https://github.com/loiste-interactive/infra-issues/issues/407))

## watertreatment

* Added new grit classifier puzzle
* Added a new hidden achievement (issue [#361] 
(https://github.com/loiste-interactive/infra-issues/issues/361))
* Added a new red keycard
* Added a valve to old grit classifier room
* Added a valve to sewer pipe building
* Added a camera target to the broken window (issue [#433] 
(https://github.com/loiste-interactive/infra-issues/issues/433))
* Added a camera target to the broken secondary clarifier (issue [#437]
(https://github.com/loiste-interactive/infra-issues/issues/437))
* Added a camera target to the tablet (issue [#486]
(https://github.com/loiste-interactive/infra-issues/issues/486))
* Changed the blower building route
* Changed the white keycard location (issue [#460]
(https://github.com/loiste-interactive/infra-issues/issues/460))
* Fixed a door turning static when transitioning from `tower` (issue [#408] 
(https://github.com/loiste-interactive/infra-issues/issues/408))
* Fixed the missing valves(issue [#409] 
(https://github.com/loiste-interactive/infra-issues/issues/409))
* Fixed the sample report being finicky (issue [#410] 
(https://github.com/loiste-interactive/infra-issues/issues/410))
* Fixed the blue screen computer not being usable (issue [#411] 
(https://github.com/loiste-interactive/infra-issues/issues/411))
* Fixed the gate being ajar to the wrong side (issue [#412] 
(https://github.com/loiste-interactive/infra-issues/issues/412))
* Fixed blue tint in doorway (issue [#436] 
(https://github.com/loiste-interactive/infra-issues/issues/436))
* Fixed the glowing mushrooms camera target having too small range (issue [#438] 
(https://github.com/loiste-interactive/infra-issues/issues/438))
* Fixed the light on alarm staying green when disarmed (issue [#439] 
(https://github.com/loiste-interactive/infra-issues/issues/439))
* Fixed too bright watertreatment log (issue [#440] 
(https://github.com/loiste-interactive/infra-issues/issues/440))
* Fixed the water sampler use highlights (issue [#453] 
(https://github.com/loiste-interactive/infra-issues/issues/453))
* Fixed a floating prop (issue [#479] 
(https://github.com/loiste-interactive/infra-issues/issues/479))
* Fixed illogical keycard coloring scheme (issue [#489]
(https://github.com/loiste-interactive/infra-issues/issues/489))

## sewer

* Added missing corruption target to the other tablet
* Added missing camera targets
* Added trigger_hurt to a certain broken pipe
* Fixed the debris collisions at the start of sewer (issue [#381] 
(https://github.com/loiste-interactive/infra-issues/issues/381))
* Fixed player complains about deep water just before the end (issue [#370] 
(https://github.com/loiste-interactive/infra-issues/issues/370))

## sewer2

* Added player monologue when triggering the event

# February 15th 2016 (Version 1.0.11)

* Added a hint explaining the camera focus rectangle
* Added a hint explaining the camera successful picture sound
* Added a different death sound for dying in water
* Added a different death sound for dying in electrified water
* Added dynamic lighting of the water impact particle effects
* Added quick save and quick load to the controls in the options menu
* Changed the break sound of a certain glass bottle model
* Changed the impact sound of the brick model
* Changed the default binding for quick load from F7 to F9
* Changed the default binding for crouch to also include right control
* Changed the default binding for sprint to also include right shift
* Changed the hint display to not display the control and shift keys twice if also bound to right control and right shift
* Changed the amount of characters that the developer console can hold from 65536 to 131072
* Fixed multiline captions for hints
* Fixed electrical glow particles clipping through nearby geometry
* Fixed the down arrow and right arrow icons being the wrong way around in the options menu
* Fixed the options menu not binding the right shift and right control keys along with the left shift and left control keys
* Fixed a certain glass bottle model not floating on water
* Fixed water impact effects almost never occurring with physics props
* Fixed a missing texture on the spark particle effect when the player dies of electrocution
* Fixed flickering water splash particles (issue [#240] 
(https://github.com/loiste-interactive/infra-issues/issues/240))
* Fixed the female arms crossed animation partially (issue [#377] 
(https://github.com/loiste-interactive/infra-issues/issues/377))

# February 5th 2016 (Version 1.0.10)

* Fixed erroneously shipping debug versions of certain binaries

# February 3rd 2016 (Version 1.0.9)

* Changed the player landing sound threshold so that it plays more often
* Changed the player landing sound volume to be twice as loud
  * Was almost inaudible previously
  * Doesn't affect "rough landings" where the volume was okay
* Changed batteries to use a bloated hitbox to make them easier to pick up from drawers
* Changed the amount of lines shown by default in `developer` mode at the upper left corner from 8 to 32
* Fixed a possible crash when transitioning from `office` to `reserve1` on low memory systems
* Fixed the "Hartman's Speech" track erroneously titled as "Hartmann's Speech" on the soundtrack
* Fixed several important documents and screens being blurry on the lowest graphics settings
* Fixed a rare crash when transitioning from `reserve1` to `reserve2` after playing for an extended period of time (issue [#417] 
(https://github.com/loiste-interactive/infra-issues/issues/417))
* Fixed a rare crash when transitioning from `tower` to `watertreatment` after playing for an extended period of time (issue [#431] 
(https://github.com/loiste-interactive/infra-issues/issues/431))

## office

* Fixed erroneous word on a certain newspaper (issue [#449] 
(https://github.com/loiste-interactive/infra-issues/issues/449))

## reserve2

* Changed the texture of the note in the flooded sawmill basement
  * Better text and handwritten now
* Changed the texture of the switchyard breaker note
  * Better text and handwritten now

## reserve3

* Changed the texture of the note in the caves
  * Better text and handwritten now
* Changed the texture of Erik's note in the control building
  * Better text and handwritten now
* Fixed misaligned text on the stash note
* Fixed stash & stash note lighting error (issue [#418] 
(https://github.com/loiste-interactive/infra-issues/issues/418))

## tunnel

* Changed the texture of the map
  * Better text and handwritten now
* Fixed misaligned text on Hartman's note to Kleinmann
* Fixed misaligned text on Erik's note to Robin

## tunnel2

* Changed the texture of the polluted water note
  * Better text and handwritten now
* Changed the texture of the note near the pools
  * Better text and handwritten now
* Fixed misaligned text on Erik's note about Robin

## tunnel3

* Fixed misaligned text on Erik's note to Robin

## tunnel4

* Changed the texture of the maintenance log
  * Better text and handwritten now
* Changed the texture of the generator G2 note
  * Better text and handwritten now
* Changed the paint on the keypad (issue [#396]
(https://github.com/loiste-interactive/infra-issues/issues/396))
* Fixed misaligned text on Erik's note to Robin about the mushrooms
* Fixed misaligned text on Kleinmann's note about the dynamite

## tower

* Changed the texture of the binder in the tower
  * Better text and handwritten now
* Changed the texture of the "upper fuses" note
  * Better text and handwritten now

## watertreatment

* Changed the texture of the maintenance log
  * Better text and handwritten now
* Changed the texture of the grit classifier note
  * Better text and handwritten now
* Fixed spelling errors on the newspaper (issue [#459]
(https://github.com/loiste-interactive/infra-issues/issues/459))

## sewer

* Changed the texture of the tablets in the Hacker Den
  * Improved text
* Fixed an issue with the computer screens that was introduced in the last update

## sewer2

* Fixed misaligned text on the override button note

# January 31st 2016 (Version 1.0.8)

* Added "controller sensitivity" slider to the options menu
* Added "invert controller look" option to the options menu (issue [#331] (https://github.com/loiste-interactive/infra-issues/issues/331))
* Added album art for the soundtrack
* Added a hint for equipping the flashlight when first entering a really dark area
* Added sounds for crouching
* Added reslists and map sound manifests
  * Should improve load times and reduce the chance of audio hitching
* Changed the power consumption of taking a picture with the camera from 5% to 4% per picture
* Changed the power consumption of the camera screen from 0.5% per second to 0.33% per second (issue [#323] (https://github.com/loiste-interactive/infra-issues/issues/323))
* Changed the sprint button on Xbox 360 controllers to be a toggle
  * Reset to default controls to apply
* Changed the crouch button on Xbox 360 controllers from B to the right stick
  * Reset to default controls to apply
* Changed the default sensitivity of Xbox 360 controllers from 2.0 to 0.6
* Changed the in-game computers to be usable with a Xbox 360 controller (issue [#317] (https://github.com/loiste-interactive/infra-issues/issues/317))
* Changed timings on the geocache monologues so that the box open sound can be heard more clearly
* Changed the spacebar hint icon to be a bit smaller
* Changed the key icons in the options menu to use their own, smaller texture
  * They previously used the same texture as the in-game hints, but it was downscaled so much that the edges turned really thin
* Fixed main menu skipping the chapter selection and going straight to the game if you have unlocked chapters but no saved games
* Fixed main menu accepting input while transitioning between screens
  * This was especially an issue with Xbox 360 controllers where you would get stuck between the load game menu and the main menu since the button press would register on both screens
* Fixed the pause menu still accepting keyboard input after returning to the main menu
* Fixed the credits remaining rolling after restarting from checkpoint during the credits (issue [#369] (https://github.com/loiste-interactive/infra-issues/issues/369))
* Fixed compression artifacts on some of the hint icons
* Fixed being able to save the game while the credits are rolling (issue [#371](https://github.com/loiste-interactive/infra-issues/issues/371))
* Fixed the hint display fonts breaking after a resolution change (issue [#374](https://github.com/loiste-interactive/infra-issues/issues/374))
* Fixed hints for the shift key not using the shift key icon
* Fixed black edges appearing on some hint icons with lower resolutions
* Fixed main menu music stopping playing after switching speaker type in the options menu (issue [#375](https://github.com/loiste-interactive/infra-issues/issues/375))
* Fixed level transitions erroneously clearing previous map state (issue [#376](https://github.com/loiste-interactive/infra-issues/issues/376))
* Fixed a rare crash when playing for an extended period of time

## office

* Changed the generic office workers to look at the player when talking to him
* Fixed position of the eyes for the female office worker model
* Fixed the position of the right eye for some of the female faces
* Fixed the position of the right eye for some of the male faces
* Fixed the female office worker model hand clipping through her clothes occasionally (issue [#342](https://github.com/loiste-interactive/infra-issues/issues/342))

## reserve1

* Changed timings of the monologue when picking up the bolt cutters early
* Fixed small cave entrance (issue [#326] 
(https://github.com/loiste-interactive/infra-issues/issues/326))
* Fixed the range of a certain camera target (issue [#336] 
(https://github.com/loiste-interactive/infra-issues/issues/336))
* Fixed the monologues interrupting the phone call (issue [#340] 
(https://github.com/loiste-interactive/infra-issues/issues/340), also fixed elsewhere)

## reserve2

* Changed the texture for the folder in the forest guard's cabin
  * Better text and handwritten now
* Changed the texture for Hartman's noticeboard
  * Better text and handwritten now
* Fixed the "train track cleanup" line cutting short in the phone call to boss

## reserve3

* Changed the corpse monologue so that the player will attempt a phone call
* Changed the interior ambient lighting to be a bit brighter (issue [#330](https://github.com/loiste-interactive/infra-issues/issues/330))
* Changed the texture for Hartman's stash note
  * Better text and handwritten now
* Fixed fade distance on some objects with low graphics settings (issue [#294] 
(https://github.com/loiste-interactive/infra-issues/issues/294))
* Fixed the range of a certain camera target (issue [#333] 
(https://github.com/loiste-interactive/infra-issues/issues/333))

## tunnel

* Changed the texture for the folder in the water sensor puzzle path
  * Better text and handwritten now
* Changed the texture for Erik's note about Hartman
  * Better text and handwritten now
* Changed the texture for Lukas' note about the keypad door
  * Better text and handwritten now
* Fixed the range of a certain camera target (issue [#332] 
(https://github.com/loiste-interactive/infra-issues/issues/332))
* Fixed the elevator button having two separate spots where it could be used and the other one doing nothing (issue [#316] 
(https://github.com/loiste-interactive/infra-issues/issues/316))

## tunnel2

* Changed the texture for Erik's note about Robin
  * Better text and handwritten now
* Changed the texture for the note addressed to Marko
  * Better text and handwritten now
* Changed the exit pipe indicator to be functional even if the valve isn't attached (issue [#388] 
(https://github.com/loiste-interactive/infra-issues/issues/388))
* Changed certain green mushrooms to damage the player (issue [#351] 
(https://github.com/loiste-interactive/infra-issues/issues/351))
* Fixed stopping the facility triggering the wrong global (issue [#414] 
(https://github.com/loiste-interactive/infra-issues/issues/414))
* Fixed pumps being able to be closed when water is flowing, preventing blocking progress
* Fixed a certain door not closing once opened

## tunnel3

* Added a camera target to the map (issue [#352] 
(https://github.com/loiste-interactive/infra-issues/issues/352))
* Added a camera target to the catwalk
* Changed the raft not to break immediately when touching a wall
* Changed the texture for Erik's note to Robin
  * Better text and handwritten now

## tunnel4

* Added a camera target to the maintenance log (issue [#353] 
(https://github.com/loiste-interactive/infra-issues/issues/353))
* Changed the raft not to break immediately when touching a wall
* Changed the texture for the corruption folder
  * Fixed grammar and spelling mistakes
* Changed the texture for Kleinmann's note about the dynamite and stuff
  * Better text and handwritten now
* Changed the texture for Erik's note to Robin about the mushrooms
  * Better text and handwritten now
* Fixed a couple of spots where the player could get stuck (issue [#321] 
(https://github.com/loiste-interactive/infra-issues/issues/321), [#354] 
(https://github.com/loiste-interactive/infra-issues/issues/354))
* Fixed the range of a certain camera target (issue [#401] 
(https://github.com/loiste-interactive/infra-issues/issues/401))
* Fixed the water flow meter triggering the wrong global (issue [#413] 
(https://github.com/loiste-interactive/infra-issues/issues/413))
* Fixed an unusable ladder (issue [#397] 
(https://github.com/loiste-interactive/infra-issues/issues/397))

## furnace

* Changed the interior ambient lighting to be a bit brighter (issue [#325] 
(https://github.com/loiste-interactive/infra-issues/issues/325))
* Changed the entrance to the third fuse room
* Fixed missing use highlights on the blue screen computer (issue [#256] 
(https://github.com/loiste-interactive/infra-issues/issues/256))
* Fixed the player being able to run through certain steam without dying (issue [#379] 
(https://github.com/loiste-interactive/infra-issues/issues/379))
* Fixed it being possible to skip a certain gas fire (issue [#356] 
(https://github.com/loiste-interactive/infra-issues/issues/356))

## tower

* Fixed the phone foley sound playing before the disconnect tone in the phone call to boss

## watertreatment

* Changed the texture for the "alarm code" note
  * Better text and handwritten now
* Changed the texture for the note hidden in the control building
  * Better text and handwritten now
* Fixed out of bounds error (issue [#283] 
(https://github.com/loiste-interactive/infra-issues/issues/283))
* Fixed possibility to skip most of the puzzles (issue [#296] 
(https://github.com/loiste-interactive/infra-issues/issues/296))
* Fixed missing door animations (issue [#297] 
(https://github.com/loiste-interactive/infra-issues/issues/297))
* Fixed disappearing valves (issue [#304] 
(https://github.com/loiste-interactive/infra-issues/issues/304))
* Fixed lighting color error (issue [#305] 
(https://github.com/loiste-interactive/infra-issues/issues/305))
* Fixed screens displaying incorrect information (issue [#358] 
(https://github.com/loiste-interactive/infra-issues/issues/358))
* Fixed door stuck open (issue [#362] 
(https://github.com/loiste-interactive/infra-issues/issues/362))
* Fixed door card reader staying on (issue [#360] 
(https://github.com/loiste-interactive/infra-issues/issues/360))
* Fixed missing use highlights on the sample report
* Fixed floppy disks having use highlights (issue [#341] 
(https://github.com/loiste-interactive/infra-issues/issues/341))

## sewer

* Changed the texture for the mushroom machine instruction table
  * Better text and handwritten now

## sewer2

* Added some delay before the ending button becomes pressable
* Added a new camera target
* Added a light to the floodgate power switch
* Changed the climbing part
* Changed the textures for Hartman's notes
  * Better text and handwritten now
* Changed the texture for Robin's note about the override button
  * Better text and handwritten now
* Fixed hints being visible during the credits (issue [#367] 
(https://github.com/loiste-interactive/infra-issues/issues/367))
* Fixed the player saying "last batteries" just before the credits roll (issue [#366] (https://github.com/loiste-interactive/infra-issues/issues/366))
* Fixed the player dying from the collapse in the safe area (issue [#365] (https://github.com/loiste-interactive/infra-issues/issues/365))

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
* Fixed missing music from the Hartman tape scene

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
* Changed the Hartman tapes and the `furnace` announcements and the `tower` payphone calls to sound distorted
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
