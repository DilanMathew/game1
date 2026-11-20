# Neon Tide

An open-world crime game in 3D, set in Palmera Bay, a fictional 1980s coastal city. It runs in the browser from a single HTML file, using Three.js r128 loaded from cdnjs. There is no build step.

Danny Reyes is out after eight years inside. Lucía Marquez, owner of Club Paloma, wants the coast back from the Calloway brothers. Nine story missions take Danny from the bus depot to the top of the city.

## Play

Open `index.html` in a modern browser with WebGL. You need an internet connection the first time so Three.js and the fonts can load. You can also serve the folder with `python3 -m http.server` and visit `http://localhost:8000`.

## Controls

| Key | Action |
| --- | --- |
| WASD | Walk (relative to the camera) or drive |
| Mouse | Look around. Click once to lock the mouse. |
| Click | Shoot. Auto-aims at whoever is near the crosshair. Works from cars too. |
| E | Get into or out of a car. Drivers get pulled out. |
| Space | Handbrake, or skip a line of dialogue |
| Shift | Sprint |
| Q, 1-4, wheel | Pistol, SMG, Shotgun, Rifle |
| R | Change radio station while driving |
| H | Horn |
| P / Esc | Pause and stats |
| M | Mute |

Touch screens get a move stick on the left, a look area on the right, and FIRE, CAR, BRAKE, GUN and radio buttons.

## Story missions

1. **Home Sweet Palmera.** Get a car and meet Lucía at Club Paloma.
2. **Benny's Wishlist.** Steal a red Vanta GT for Benny's Garage. Damage cuts your pay.
3. **Boardwalk Pickup.** Grab a package from the lifeguard tower, then lose the police.
4. **Collections.** Visit three shops against the clock, then deal with the ambush.
5. **Special Delivery.** Chase and destroy a Calloway cash van.
6. **Midnight Grand Prix.** A street race against three rivals with a countdown and positions.
7. **Beach Bash.** Clear two waves of Calloway gunmen off the sand.
8. **Safe Passage.** Drive Hector in an armored sedan while gang cars chase you.
9. **Neon Tide.** Storm the Calloway mansion, kill Victor, escape four stars, and watch the credits.

Pink **L** markers start story missions, and the **B** marker means Benny has work.

## Also in the city

- **Side jobs** from payphones ☎, unlocked after mission 2: courier runs, car boosts, hits and sprints.
- **25 lost tapes** hidden around the map. Finding all of them pays a bonus.
- **Bullseye Guns.** Walk into a price tag to buy an SMG, shotgun, rifle or armor.
- **Spray & Pray.** A $250 respray clears your wanted level.
- **Five-star wanted system.** Cruisers ram you and officers arrest you on foot. At higher levels they shoot, tactical vans join, and a helicopter with a searchlight turns up at four stars.
- **Three radio stations**, generated live: WAVE 103 (synth pop), PALM 88.5 (late night soul) and KRANK 107 (heavy metal).
- **City.** Downtown towers, art-deco beachfront hotels with neon, a beach with palms and umbrellas, docks with a freighter, and a day/night cycle that takes about 12 minutes.
- **Saving.** Progress, money, weapons and tapes save to the browser automatically. Continue from the title screen.

The earlier top-down prototype is kept as `harbor-heat-2d.html`.
