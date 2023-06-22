# Release Notes Lite

## Version 1.8.7-Experimental Beta (To be released soon)

**General** 

- This build doesn't support Business Editions (Quest 1 is supported though)
- Spatial Anchors calibration beta for Quest
- Calibration should now reliably persist when the headsets are shut off or taken out of the playspace while still active. 
- Calibration should remain even after having to draw a new guardian. Only clearing guardian data would clear calibration. 
- When in the 4 ball calibration screen, the game now uses passthrough mode so you can easily see your playspace. 
- More clear instructions provided in the headset, with a diagram. 
- HUD:
    - added tooltip with player IP address and ping
    - shows ! icon if a headset needs calibration
- Calibration mode fixes:
    - now uses passthrough
    - in-game instructions clarified
    - you're now kicked out of calibration mode during certain situations where the virtual room moves (e.g. switching between time periods in Time Travel Paradox, changing rooms in the Pirates Plague temple ruins), which would previously cause unexpected results during calibration.
    - fix both Quick Calibrate and regular room calibration when in the Dragon Tower alchemy lab, when the room is flipped due to an inverto potion
- Game fixes:
    - Depths of Osiris - Temple Entrance: fix issue where taking the shell from the wall cubby which opens by pulling the middle piston, giving the shell to the crab, and pull the middle piston again would reveal an additional shell in the wall cubby.
    - Pirates Plague - Cabin: fix players getting stuck on their current costume if they try to grab their current costume (e.g. deck swabber tries to grab a deck swabber costume).
    - Pirates Plague - Cabin: now does a quick fade to black when changing costumes

## Version 1.8.6

**General** 
- Added new rooms to Space Station Tiberia and Depths of Osiris
- Extended all games to be 45 minutes by default
- Fixed the **"Restart Session Search"** button that appears when a headset does not find the server right away, should now actually restart the searching for session function
- Story intros for Space Station Tiberia, Depths of Osiris, and Dragon Tower now play in the first level of each game instead of the lobby. 
- Story intros can now be skipped by pressing **Shift + L** 
- Various small bug fixes for our other titles

**Space Station Tiberia**
- A new level added to the game to bring the game up to the length of our other titles: Space Shuttle
- Players have to restore power to their shuttle and dock with the space station
- Players will have to use zero gravity and inertia to their advantage to get their shuttle ready to dock
- Repairs on the space station start from the outside, players will have to fix the docking port before boarding
- New player avatar for Space Station Tiberia, giving the astronauts a torso and human hands 
- Space Station Tiberia story intro now plays inside the first level

**Depths of Osiris**
- New level added between the temple exterior and the temple interior: Ancient Airlock
- Players must figure out the connection with the mysterious ancient airlock and the bioluminescent shells
- Some shells float, while others sink, these differences are key to operating this perplexing contraption



## Version 1.8.2

**General**
- New game: Runaway Train
- Added Russian Language to all games
- Added a highlight to the currently selected game on the bottom left HUD
- Fixed an issue where keyboard shortcuts would get ignored after clicking a UI button
- Added icon in the player gear menu to reset players back to room center (only shown for players using teleport movement)
- New "Quick Calibrate" function (stand in the middle of the room, face the "forward" direction, and hold down "A" and "Y" controller buttons for 3 seconds)
- Fix teleport movement players entering the room at the wrong location
- Changed the icon shown when a player is removed from the game that is shown in the headset to move around so it does not burn into the screens. 
- Added "disableQuickCalibrate" .ini setting to turn off quick calibrate
- Update defalut game time to 45 minutes for all escape rooms
- Quick calibrate: fix being activated when all controller buttons were held down
    - Now only triggers if A and Y (without B or X) are held for 3 seconds
- Various small bug fixes for our other titles

**Runaway Train**
- Brand new VRCAVE escape adventure 
- Dr. Steem has escaped jail and is planning his revenge on the town that imprisoned him, Deputies need to work together to stop is runaway train from destroying the town and put an end to Dr. Steem's schemes 
- First players must catch up to DR. Steem's train, destroy his defense drones and board the train.
- Next players need to figure out how to use the forge to craft their way through the door to the engine room.
- Then players will need to equip a pistol and find a way to stop the train.
- Finally, the players will come face to face with Dr. Steem.

**Manor of Escape**
- Fixed an issue where the Tesla Coil would not show the electricity effect. 
- Added a keyboard shortcut to reset the water monster "R"

**Space Station Tiberia**
- Fixed an issue where interactable text was the same shade of blue as non interactable text instead of green


## Version 1.7.1 

**General**
- New game: Pirates Plague
- Added additional social media marketing images to the marketing folder (square and tall) for all games
- Various small bug fixes for our other releases

**Pirates Plague**
- Brand new escape exerience
- Your crew was stricken with a plague that will turn them into fish people, you must find the heart of a kraken to cure yourselves before it is too late! 
- First players must sink a ship of rabid fish folk looking for a fight, load and fire the ships cannons while fighting of boarders
- Then solve the mysterious kraken mural in the ruins, But don't get lost!
- Finally, Players face off against the fearsome kraken! 
- Sail the high seas with you crew, each member has a special skill they can use to help solve puzzles or wield new weapons 
- First game in the VRCAVE library to include player classes, each class has a unique outfit along with a special ability. 

**Manor of Escape**
- Final Boss fight will now add additional bows for each player.

**Time Travel Paradox**
- Fixed a bug where German translations would extend past the subtitle box. 

## Version 1.6.3
**General** 
- Manor of Escape has been released for Quest! See below for the details
- Fixed an issue where VRCave internal calibrations would be lost when the application is closed.
- Added a VRCAVE at home mode. Allows the use of vrcaveLibrary in non-roomscale or seated play. Players can use teleportation movement with the left stick and quick turn with the right stick. this can be accessed via the operators menu in the headset by pressing A B B A X Y X on the controllers and enabling vrcave at home. versions of the software with vrcave at home already enabled are available. 
- Various bug fixes across all escape room experiences. 

**Manor of Escape**
- The latest and spookiest escape experience is now available for Oculus Quest! 
- Escape from the Mad Count's terrifing manor as you uncover his experiments
- Sift through a flooded basement while something vicious swims just outside the cage, waiting to bite a reaching hand
- Don't make a sound in the lab, or the Hideoplast will hear you.
- Pick up a bow and fight against the Mad Count's ultimate creation! 

**Space Station Tiberia**
- Improved hint visuals for observation deck solar panel hint. 

**Dragon Tower**
- Fixed a bug that caused the game to crash when buring objects in the fire
- Fixed a bug that prevented players from seeing their achievements after a game
- Adjusted Dogs pathfinding to avoid vibrating near the cage

**Depths of Osiris**
- Improved hint visuals 

**Time Travel Paradox**
- Fixed a bug where some players were reflecting the lobby environment instead of the lab. 

**Laser Bots**
- Thief bots will now "launch" crystals into the playspace when destroyed outside of playspace



## Version 1.5.3

**General**
- Time Travel Paradox has been released for Quest! See below for details
- Server now displays battery levels for each headset
- Player Names can be displayed above their head by clicking the Aa icon in the player options menu on the server 
- Over 50 small bug fixes for existing games
- Finger pointing volumes now lock the hands into the pointing gesture and does not allow grabbing. this is to prevent the hand from pressing buttons the player didn't intend to press

**Time Travel Paradox**
- Our latest release is now available on Oculus Quest! 
- Players have to solve puzzles by using time travel mechanics
- Exciting boss battle against weapons from THE FUTURE!
- Player Avatars have a torso

**Space Station Tiberia**
- minor visual polish 


## Version 1.4.0

**Generel** 
- Initial Release of VRCAVELibrary for Oculus Quest
- comes with all 3 of our Escape Room games and our latest game Laser Bots
- Calibration can be done much faster with the Quest system
- Added Picture in Picture player perspective view option

**Space Station Tiberia** 
- Added a finger pointing gesture for computer screens. Hands will automatically point when placed near a button

**Depths of Osiris**
- Moved the Ancient Drone control buttons to one side to better accomidate Quest tracking
- Added a finger pointing gesture for the air lock glass

**Laser Bots**
- A brand new experience 10 minute action game aimed at kids filled with robots and lasers that's sure to be a blast.
- Team up with your buddies to reflect lasers and use your beam swords to cut through robots to destroy the giant robot to escape from the asteroid.
- Hardmode is more aimed at adults as many of the puzzles will require fast paced teamwork to complete the game in time.