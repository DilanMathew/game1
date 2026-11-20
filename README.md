# Harbor Heat

A top-down open-city crime game set in Port Cassidy, a harbor town ten blocks wide and ten blocks deep. It runs in the browser as a single HTML file and needs no build step or dependencies.

## Play

Open `index.html` in any modern browser. You can also serve the folder, for example with `python3 -m http.server`, and visit `http://localhost:8000`.

## Controls

| Key | Action |
| --- | --- |
| WASD / arrows | Walk, or drive (W gas, S brake/reverse, A/D steer) |
| Mouse + click | Aim and shoot |
| E (or F / Enter) | Get into or out of a car. Drivers get pulled out. |
| Space | Handbrake (drift) |
| Shift | Sprint |
| Q, 1-3, mouse wheel | Switch weapon (Pistol, SMG, Shotgun) |
| H | Horn |
| P / Esc | Pause |
| M | Mute |

On a touchscreen you get a virtual stick plus FIRE, CAR, BRAKE and GUN buttons, and aiming is automatic.

## What's in the city

- **Traffic and pedestrians.** AI cars keep to the right-hand lane and turn at intersections. Pedestrians walk the sidewalks and scatter when there's gunfire.
- **Car physics.** Each car has grip and drift, takes damage from crashes, smokes when hurt, then catches fire and explodes. There are seven car models.
- **Wanted level (five stars).** Crimes raise your heat. Patrol cruisers chase and ram you, and officers get out on foot to arrest you. At higher levels they shoot, and tactical vans join in. If you stay out of sight, the stars fade.
- **Jobs from the payphones (☎).** There are four kinds: courier runs against the clock, stealing a gold sports car and delivering it to the Dock Garage, a hit on a guarded target, and checkpoint races.
- **Spray & Pray.** Drive in while wanted and $250 buys a respray that clears your stars.
- **Pickups.** Cash, health, armor, SMG and shotgun ammo.
- **Day and night.** A full cycle takes about seven minutes, with headlights, streetlights and lit windows after dark.
- **Hospital and precinct.** If you go down, you wake up at St. Brigid's. If you're arrested, you're released from Precinct 9. Either way you lose 10% of your cash, and an arrest also costs you your weapons.

Your money and completed jobs are saved in the browser's local storage.
