The Helios Complex

A first-person stealth-parkour game built solo in Unreal Engine 5 for my Advanced Game Development course. Navigate the facility by moving through the shadows, managing your exposure to light, and using parkour to reach each checkpoint.

Engine: Unreal Engine 5.6 (Blueprints) · Status: Completed course project (solo)

*I need to add a gameplay screenshot*

Core mechanics
Light-based exposure: the player's exposure is calculated from nearby light sources, and warm and cold lights affect it differently
Exposure meter UI: a real-time HUD meter shows how exposed the player is, so the light challenge is readable at a glance
First-person parkour: jumping and traversal routes through the environment
Checkpoint system: progress saves at checkpoints, and the player respawns there on failure
Interact/switch logic: reusable interaction Blueprints drive doors, light switches and objectives

Technical highlights
Exposure logic evaluates the light sources affecting the player and produces a single exposure value that drives the HUD and fail state
Warm and cold lights are handled as separate light types, so level design can mix safe and dangerous light
Interaction uses a shared Blueprint interface, so any actor can become interactable without one-off code

Running the project
Install Unreal Engine 5.6 through the Epic Games Launcher.
Clone this repo and open the .uproject file.
Press Play in the editor.

Controls
Move | WASD
Look | Mouse
Jump | Space
Pause | Esc

Author
Jacob Davis · GitHub
