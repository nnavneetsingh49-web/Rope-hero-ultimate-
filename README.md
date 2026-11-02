# B.S. Vice City — Test Project

This is a Godot 4 **feature prototype** intended for testing core gameplay ideas. It is not a finished commercial open-world game and has not been built or tested on Android in this environment.

## Included
- Procedural blockout 3D city, roads, beach/water, street lights and building window bands
- Third-person player and follow camera
- PC keyboard controls: WASD/arrows, Space jump, E enter/exit car, F action, J job, T shop, Tab inventory, M map, X exit car
- Mouse camera: right-click to capture mouse, move mouse to look; Esc releases it
- Mobile dual virtual joysticks (left movement, right camera look) and touch UI buttons
- Pedestrian NPCs that wander
- Traffic cars that move; enter a nearby car and drive
- Villain targets; action near them awards in-game cash and raises wanted stars
- Robot police pursue player while wanted level is active
- Jobs (delivery/taxi/patrol/race) using yellow city markers and cash reward
- Shop with armour, gadget and vehicle purchases
- Inventory/map panels, health, cash and wanted stars
- Hero/Robot/Armour visual mode switch

## Controls
### Mobile
Left joystick = movement / driving; right joystick = camera.
Touch buttons = JOB, SHOP, ACTION, CAR, MODE, BAG, MAP, JUMP.

### PC
WASD or arrow keys = move/drive; Space = jump; E = enter/exit nearest car; F = action;
J = job; T = shop; Tab = inventory; M = map; X = exit vehicle.
Right-click = capture mouse; mouse movement = camera; Esc = release mouse.

## Important limitations
- 3D people, buildings, police robots and cars are blockout meshes, not realistic finished models.
- Villain interaction is a simplified arcade placeholder, not a detailed combat system.
- Vehicle physics, NPC pathfinding, police AI, jobs, missions, save/load, weapons, full transformation rigs/animations and high-end graphics are not production complete.
- Mobile joystick UI and PC input are included in source, but need testing on actual devices.
- No APK/AAB is included. Android export requires Godot 4.x, export templates, Android SDK/JDK and signing configuration. AAB is for Play Store; APK is for direct installation.
- The project is not yet tested in Godot; if Godot reports an error, share a screenshot of the error and I can help fix it.

## Open in Godot
1. Install Godot 4.x.
2. Import `project.godot` from this folder.
3. Press Play (F6/F5 depending on editor state).
