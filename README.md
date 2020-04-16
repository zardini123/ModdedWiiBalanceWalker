# WiiControl

Currently under development, this program will allow users to connect a Wii Balance Board (or multiple) or Wii Motes to their computer and use it to play games or for other tasks.

These programs use the original source code from [Richard Perry's WiiBalanceWalker](https://web.archive.org/web/20160313121128/http://greycube.com/site/download.php?view.68).

## Project structure

**./WiiBalanceWalker_v0.4 (Frequency Version)**

Contains Visual Studio project of modified WiiBalanceWalker v0.4 where users must "waddle" side to side on the balance board to sneak, walk, or sprint.  The *frequency* of this waddling determines if the user is sneaking, walking, or sprinting.

**./WiiBalanceWalker_v0.4 (Proportional Mouse Version)**

Contains Visual Studio project of modified WiiBalanceWalker v0.4 where actions Forward, Backward, Left, and Right -- when set to mouse output -- will move the mouse proporionally to that of the center of balance (COB) position.  This gives users controlling the camera the ability to have analog control of the mouse, instead of the original WiiBalanceWalker's binary control (either moving the mouse (at a set speed) or not).

## Todo / Roadmap without a timeline

- Provide support for conecting more than one Balance Board, and provide action mapping per balance board
    - This will be done on a seperate branch to preserve the "waddle frequency" code, and still give users the ability to play using the two-exe "archetecture."
- Re-add "waddle frequency" as an option per balance board..
    - This will be added in multiple balance board branch.
- Re-add proportional mouse movement option per balance board.
    - This will be added in multiple balance board branch.
- Merge multiple balance board branch into master, and therefore remove the need for two exe's for the end user.
- Add Wii Mote support
- Add *physical arragement* mode
    - Give user the ability to arrange balance boards in 2D space like arraging montiors in system settings so multiple boards can be used like one logical controller.

## License

Richard Perry's WiiBalanceWalker source code, released in 2013, was released under the [*Microsoft Public License* (MS-PL)](https://opensource.org/licenses/MS-PL) (as noted in *FormMain.cs*).  As stated in the terms of the MS-PL license, the act of distributing Perry's software in source code form requires a complete copy of that license with this distribution.
