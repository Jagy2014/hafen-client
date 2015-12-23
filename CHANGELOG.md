Last update:

v8.4.2
-added Quest log
-Loftar fixes
 
Hotkeys:
F1 - Equipment window (Ctrl+E)
F2 - Character Sheet (Ctrl+T)
F3 - Kith & Kin window (Ctrl+B)
F4 - Options window (Ctrl+O)
F5 - Drop seeds placed into inventory.
F12 - Take screenshot

CTRL + LMB - Drop(to the ground) single item.
CTRL + ALT + LMB - Drop(to the ground) identical items.
SHIFT + LMB - Transfer single item between inventory and container.
Shit + ALT + LMB - Transfer identical items between inventory and container. ?
CTRL + N - Toggle nightvision.
SHIFT + Point with mouse over an object on the ground - shows its resource name.
CTRL + Q - Open timers window.
CTRL + G - Show grid overlay.
Shft + Q/W/E/R - Change speed.
CTRL + P - Show crops and trees stages.
SHIFT + C - Change between bad and ortho cameras.
CTRL + D - Show mine support/beehive radius.
SHIFT + RMB on stockpile window(NOT on stockpile itself!) - Transfer everything to the inventory.
SHIFT + ALT + LMB or ALT + RMB on item in inventory - Transfer all identical items to stockpile.
Take item on cursor and SHIFT + RMB - Transfer all similar items from inventory to stockpile.
ALT + RMB - Transfer identical items between inventory and container(Will be sorted DESC).
CTRL + RMB - Transfer identical items between inventory and container(Will be sorted ASC).
ALT + Scroll UP - Transfer identical items between inventory and container(Will be sorted DESC).
ALT + Scroll DOWN - Transfer identical items between inventory and container(Will be sorted DESC).
ALT + CTRL + Scroll UP - Transfer identical items between inventory and container(Will be sorted ASC).
ALT + CTRL + Scroll DOWN - Transfer identical items between inventory and container(Will be sorted ASC).
ALT + S - Opens separate study window
CTRL+H - Hide item on cursor (Needed to plant tree into center of tail)
SHIFT+H - Hide trees
ALT+C - Craft search menu
ALT+B - Build search menu

Full Change Log:
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