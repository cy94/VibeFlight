# VibeFlight

A basic browser flight sim (Three.js, single `index.html`, no build step).

**Play:** open `index.html` in a desktop browser (needs internet for the Three.js CDN), or serve the folder with any static server.

- 5 jets: F-16C, F/A-18C, A-10C, Boeing 737-800, Learjet 45
- Simplified but physical flight model: lift/drag curves, stall, ground effect, thrust lapse, afterburner, G/AoA limits, wheel friction and brakes
- Gear, flaps, speed brake, nav/beacon/strobe/landing lights
- Weather: clear, scattered, overcast, rain, thunderstorm, fog, snow; wind and turbulence; dawn/midday/sunset/night
- Procedural island with hills, mountains, lake, farmland, forests, a city, a town, wind turbines, two airports with runway lights, approach lights and PAPI
- Six-pack instruments (airspeed, attitude + ILS, altimeter, turn coordinator, heading + bearing pointer, vertical speed), systems panel, minimap, cockpit HUD

Mission: take off from Hillcrest (HLC) and land on runway 36 at Lakeside (LKS), 12 km north (~2 min).
Press **F1** in game for the controls.
