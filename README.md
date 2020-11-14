# MP_Pawn_Racing

> A prototype showcasing working multiplayer racing with custom raycast physics based vehicle pawns in UE4.

Gameplay clip: https://i.imgur.com/r3wbRZk.mp4

## Synopsis

This project encapsulates the basics of a multiplayer capable racing game built in UE4 using custom raycast physics based pawns with substepping.

Features:
* Singleplayer race mode
* Multiplayer race mode (listen-server with client-side physics)
* Basic main menu/pause menu/server browser/HUD
* Custom hover vehicle using raycasts (with substepping via MMT_Plugin)
* Coded entirely in blueprints (with decent code comment coverage)

#### Controls

* W - forward
* S - reverse
* A - steer left
* D - steer right
* SPACE - jump
* ESCAPE - pause menu
* Mouse for menu interactions

#### Notes

* Currently force & torque (outside of raycasts) do not have any kind of compensation for substep delta time; as a result clients with low FPS will experience a slow moving vehicle.

#### Referenced/Integrated Third Party Projects

* *Mutiplayer Shootout* - https://docs.unrealengine.com/en-US/Resources/Showcases/BlueprintMultiplayer/index.html
* *MMT_Plugin* - https://github.com/BoredEngineer/MMT_Plugin

<br/>

### Connect
---

<a href="https://elocnat.itch.io"><img src="https://i.imgur.com/s5iagnG.png" title="Play my games on https://elocnat.itch.io" alt="elocnat logo" width="48" height="48"></a> **Connect with me** to keep up with my current projects. **Help me out by following me & sharing my work!**

- **Visit my website** <a href="https://elocnat.com" target="_blank">(`elocnat.com`)</a> to browse my full portfolio!
- **Follow me** and **play my games** at <a href="https://elocnat.itch.io" target="_blank">`elocnat.itch.io`</a>
- **Follow me** on Twitter at <a href="https://twitter.com/elocnat" target="_blank">`@elocnat`</a>
- **Follow me** on GitHub at <a href="https://github.com/elocnatsirt" target="_blank">`@elocnatsirt`</a>
  - **Star** <a href="https://github.com/elocnatsirt/MP_Pawn_Racing" target="_blank">this project</a>!

### License
---

<a href="http://www.wtfpl.net/"><img src="http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-4.png" width="80" height="15" alt="WTFPL" /></a>

- **[WTFPL license](http://www.wtfpl.net/txt/copying/)**

As the license says you are free to do whatever you want with the code. Credit is always appreciated. Any included or referenced third party libraries, code, or other assets fall under the license of their respective creators.
