# Gloamgate

A top-down maze game played by flashlight. Every maze is procedurally generated and split into sealed sections. Colored gates connect the sections in pairs: step into a rim and you come out at its twin somewhere else. Find the brass key, then take the stairs down to the next depth.

Something hunts you in the dark. It spots your light from far away and hears you move nearby. With your light off and your feet still, it cannot find you.

## Play

Open `index.html` in a browser. It is a single file with no build step. With GitHub Pages turned on, it is playable at https://markerobinson.github.io/gloamgate/.

## Controls

| Action | Keyboard and mouse | Phone |
| --- | --- | --- |
| Walk | WASD or arrow keys | Drag anywhere |
| Sprint | Hold Shift | Hold the Run button |
| Aim the flashlight | Mouse | Follows your movement |
| Flashlight on or off | F or Space | Light button |
| Pause | P or Esc | Pause button |

## Rules

- The flashlight starts off. A full battery gives 75 seconds of light, and each spare battery adds 20%.
- Sprinting drains stamina (4 seconds from full). It refills slowly while walking and faster while standing still. Run it dry and you cannot sprint again until it is back to 30%.
- The hunter is faster than you walk and slower than you sprint. Sprinting is louder, so it can hear you through walls from farther away.
- More hunters appear as you go deeper: one at depths 1 and 2, two at depths 3 to 5, three after that.

## Maze codes

Each maze has a code such as `3-2FF7DF` (depth, a dash, then six characters). Enter a code from the Code button to play that exact maze, with the same gates, batteries and hunter starting spots. Any word also works as a code.
