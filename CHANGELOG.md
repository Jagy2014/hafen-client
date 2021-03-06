Last update:

v16.05.01
Add curio calculations based on study time (Learning points/hour/size, Learning points/hour/size/weight) on mouse over.

Not-So-Obvious Things:
Auto-miner. Click the mining action. Hold down shift to select an area to mine.
Hand slots can be moved by clicking empty space between them and dragging.
Chat can be horizontally resized by dragging the right border.
F-key toolbar - click on empty slot and drag to move. Shift + click to change orientation.
Craft/build history hotbelt - right click to move. Shift + right click to change orientation.

Hotkeys:
F1 - Equipment window (Ctrl+E)
F2 - Character Sheet (Ctrl+T)
F3 - Kith & Kin window (Ctrl+B)
F4 - Options window (Ctrl+O)

Ctrl + LMB - Drop single item.
Ctlr + Alt + LMB - Drop identical items.
Shift + LMB - Transfer single item between inventory and container.
Ctrl + LMB - Transfer identical items between inventory and container in ascending order.
Alt + LMB - Transfer identical items between inventory and container in descending order.
Ctrl + N - Toggle daylight/nightvision.
Shift + I - Toggles resource info when holding shift/shift+ctrl and pointing with the mouse.
Shift + Point with mouse over an object - shows its resource name (See Shift+I).
Shift + Ctrl + Point with mouse at a ground tile - shows its resource name (See Shift+I).
Ctrl + Q - Open timers window.
Ctrl + G - Show grid overlay.
Shift + Q/W/E/R - Change speed.
Ctrl + P - Show crop/tree stage.
Shift + C - Change between bad and ortho cameras.
Ctrl + D - Show mine support radius.
Shift + RMB on stockpile window - Transfer everything to the inventory.
Shift + Alt + LMB or Alt + RMB on item in inventory - Transfer all identical items to stockpile.
Alt + Z/X - Simulate left clicks on quickslots.
Ctrl + M - Show status widget.
Ctrl + Shift + LMB on an item in inventory - opens wiki page for that item.
Ctrl + Up/Right/Down/Left snaps ortho camera to N, E, S, W respectively.
Alt + LBM - Highlight object for other players.
Alt + S - Take screenshot.
Shift + H - Hide trees.
Ctrl + H - Hide item on cursor.
Ctrl + X - Perform right mouse clicks at the tile's center.
Tab - Aggro closest unknown/red player (works only if enabled from Combat Settings).
Shift + Z + RMB with an item on a structure - Automatically fill it similarly to pressing shift+rmb each time.
Shift + mouse wheel - rotate between combat opponents.
Shift + B - Show bounding boxes.
Ctrl + Z - Toggles path-finding (very experimental, use at your own risk).
Shift + D - Toggles beehives/trough radius.
` (back-quote/tilde) - Drink from any container located in the inventory.

Full Change Log:
v16.05.01
Add curio calculations based on study time (Learning points/hour/size, learning points/hour/size/weigth) on mouse over.

v16.04.27
Merged Vanilla changes.
Merged Amber changes.

v16.04.26
Fully rewrited client. I taked last edition of amber and added own features back.
Almost everything that was included in my client has been implemented back.

Please re-check all settings from Options window (Ctrl+O or F4).
Check Hotkeys! There is few differences from original Amber. And some new keys.

Build on current Amber version 1.32.6 (released 25.04.2016)

Enjoy!
 
v16.04.15
-New build numbering (yy.mm.dd)
-Don't show radius for dead animals
-All fixes that Loftar implemented in Vanilla (huge number of improvements)
 
v9.5.2
-Mammoths alarm and wheelbarrow icon
-Wagon icon
-Hearthfire (actually all types of fires - pow) icon (Green star)
-Leanto icon (Yellow start)
All icons could be hided from: F4 - Map Settings - Hide icons

v9.5.1
-Option to not drope mined ore
-Allow mining cave tiles in auto-miner
-Terminate autominer when troll appears
-Update curio data

-Fixed rare crash when teleporting
-Fixed null pointer dereference in GameUI.getmeter
-Removed unnecessary comparison
-Fixed Double.NaN test in partydraw
-Fixed glslver test
-Render grid underneath objects
-Fixed invalid cast
-Vanilla fixes

v9.5.0
-Sort button for cupboards (needs to be fixed)
-Last vanilla changes
-Improved Farm function

v9.4.0
-Made base attributes' buffs and debuffs always visible
-Changed ctrl+d to toggle only mine support radius and moved trough/beehive radius toggle to Display settings window
-Option to show animal radius
-Alarm on bluebells, flotsams, and edelweiss
-Slider for adjusting fireplace sound volume
-Draw icons for hostile animals on top
-Alarm onbears, lynx and boars
-Ignore loading exception when requesting overlay resource 
-Revorked menu, moved all custom msettings to Jaguar settings window
-Added Help menu

v9.3.0
-Set "Disable UI hiding with spacebar option" to enabled by default
-Select syslog on login
-Updated Calendar graphics
-Shift+lmb - transfer single item into stockpile

-Merged Paragon automations:
-Farming
-Dragonfly catcher

v9.2.0
-Option to highlight empty and finished drying frames
-Do not highlight in red drying frames with WWW

--Vanilla Chages:
--Work around apparent Intel GPU bug in MiscLib.olblend.
--Fixed quest-view bug.
--Bump protocol version.
--Reworked resattr support.
--Added support for decoding and managing resattr gob data.
--Publicize bonedb wrappings.
--Added toString method on MessageBuf.
--Added overlay-blending.
--Added support for an overlay texture.

v9.1.0
-Added auto mining: select mine, hold shift and select area to mine. Area should be to the right from your character.
-Show different sign for crops at the last growth stage
-Show distance from a party member
-Fixed movement vectors not showing for vehicles
-Added stalagmite to boulders list.
-Added option to disable UI hiding with space-bar
-Added store-hat equipment slot.
-Added drink function

v9.0.0
-Bump protocol version.
-Switched to new, more extensible, glob format.
-Show total softcap in craft window
-Fixed crash when using slings

v8.4.2
-added Quest log
-Loftar fixes

v8.4.1
-Alternative controls for minimap
-Aggro closest player on Tab key
-Aggro animals on minimap (using "t" hotkey)
-Replaced Blue squares by stumps when trees in hide mode. You can interract with stumps.
-Fixed crash on Barter stands

v8.4.0
Added latest Amber changes:
-Sound alarm when pony power drops below 10%
-Option to show buff icons when swimming/tracking/crime is active
-Fixed crime/track/swim toggles behaviour when switching chars and removed msg sfx on auto toggle
-Frog icon
-Allow picking up items with custom icons from minimap
-Fixed interaction with minimap icons when Config.iconsel is null
-Show contents quality for containers
-Cleanup in MinimapWnd

v8.3.2
-Loftar fixes

v8.3.1
-Fixed crash that can occur when hunger meter is not initialized fast enough

v8.3.0
-I already lost my, so added Boar Spear to minimap (red dot as arrows). Could be disabled in Map Settings - hide icons
-Prevent minimap flicker when changing locations
-Added option to draw background for quality numbers (Display settings)
-Added Hide trees hotkey (Shift+H)
-More fixes for minimap drawing
-Added Craft search menu (Alt+C)
-Added Build search menu (Alt+B)
-Added last crafted items into craft menu as tabs
-Removed remaining Fraktur font
-Added option to show lowest quality (as in Amber)
-Added option for arithmetic average (as in Amber) (check Display settings)
-Finally fixed sorting, now reflecting to selected arithmetic/quadratic quality options

v8.2.0
-removed zoom-out limit for normal camera (Tip: Use keyboard Home button to reset into default zoom position when needed)
-added static curio info based on config file
-added option to take curio from all opened cupboards (General settings)
-fixed separate curio window lock (ALT+S)

v8.1.0
-added option to show biome name on minimap. If mouse is over minimap it shows name of biome it is over, otherwise it shows biome player is in. (Ender)
-added changes for game update: Cuck-Hombre

v8.0.5
-Loftar fixes
-Amber cool button: Shift + Z + RMB with an item on a structure - Automatically fill it similarly to pressing shift+rmb each time.
-Fine tuning for Jorb quality model

v8.0.4
-Added mode to automatically transfer arrows from the quiver to the inventory:
 Put Quiver into your inventory, open it and take 1 arrow into inventory.
 Press Toggle Arrow Autoloader in Xtended menu.
 Quiver should stay open. Shoot. New arrow will be placed into inventory automatically.
-Add task for putting 11 coals into Ore smelter
-Fixed Mine support radius not showing when loading new areas

v8.0.3
-Show total damage that you did to opponent (Enable in Combat settings)
-Show total damage that opponent did to you (Enable in Combat settings)

v8.0.2
-Fix for window position

v8.0.1
-fixed crash when mass transfer items without any quality

v8.0.0
-Bunch of Loftar fixes.
-Updated to support update: Coat of Many Colors
-Added tasks for filling troughs, coops and tar kilns (can be found in extended menu)
-Added task for picking all nearby mussels (can be found in extended menu)
-Added yellow X on curio that you already studying. Red "INT" identify that you can study, but require more Intelligence that you have. (Should be enabled in General settings)
-Added Toggle Tracking on login (You need to enable it in General settings)
-Added screenshoot hotkey (F12) will save img in screenshoots directory.
-Added possibility to plant tree to center of tail. You will find Xtended menu (red plus sign). Hint how to do it is there(you will see it on mouse hover).
-Added possibility to drop any seed placed into inventory(F5) - enable when harvesting, disable when done. Made to avoid automixing seeds when harvesting. When you pickup seeds from ground - they not stack automatically.
Pickup seeds later by SHIFT+RMB (will pickup all automatically and not mix).
-CTRL+Home - Turns camera to North
-Probably something else was improved that I forgot to discribe...

7.7.2
-Added "Run on login" option
-Added option for automatically dropping seeds from inventory(You need to enable this only when harwest, to avoid auto mix seeds in inventory)
-Slider for adjusting Quern sound volume
-Attention meter fix (when loaded more than your int, bar will stay green, not red)

v7.7.1
-Added It's Dewy Mantle Time indicator and notification.
-Added following options for F1-F4 keys. Old bindings will also work.
	F1 - Equipment window (Ctrl+E)
	F2 - Character Sheet (Ctrl+T)
	F3 - Kith & Kin window (Ctrl+B)
	F4 - Options window (Ctrl+O)

v7.7.0
-Moved show arrows option to Maps settings-Hide icons-arrow. Arrows on minimap will be shown as red dot.
-Added milestones(red star) to minimap. Can be disabled in Maps settings-Hide icons-milestone.
-Added trees and bushes growth stages(1-99%). When tree/bush is ready then no pertentage shown on it, becouse it is treated as all normal trees(meaning not planted). So, you will not see 100%
-Option for automatically selecting harvest action
-NB! Fixed avg quality calculation (becouse formula is sqrt from all 3 qualities /3)
-Don't save map tiles for houses and cellars

v7.6.2
-Fixed curio messages
-Added separate study window (ALT+S)

v7.6.1
-Fixed crash in equipory when sprite hasn't finished constuctirng

v7.6.0
-Fixed crash on sorting when item has no quality (example: key)

v7.5.0
-Change cupboard size from Display menu (require client restart)

v7.4.0
-Scrolbar sorting ajusted for Farming (V->S->E)

v7.1.0
-Added movelines players and animals (enable in settings)

v7.0.0
-Auto curio
-Attention meter (bdew)
-Added curio remaining time info to Attention meter


v6.5.0
v6.4.0
v6.3.0
v6.2.0
v6.1.0
v6.0.0
v5.0.0
v4.0.0
v3.0.0
v2.0.0
v1.0.0

Notes:
2016.04.15
Loftar Commit 662efb6f3a079fc5bee7b27e7936210f241b1259 [662efb6]
Gob.java - not implemented