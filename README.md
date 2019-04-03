# Tintin-Setup
[Tintin++](http://tintin.sourceforge.net) scripts for playing muds, including:

* Multiple map heirarchy handling with travel between maps/areas.
* "Graphical" gauge display
* Window handling (multiple swappable configurable information displays)
* Event handling (subscribe/unsubscribe multiple actions to a code event)
* Database integration
* File handling (linux)

This setup includes my scripts for [3Kingdoms mud](http://3k.org/)

This page is the only documentation on how all this works.

If you want to try it out anyway, run "tt++ start.tin"

Prompt detection works a lot better if you have your mud prompt set to have a newline after it.
E.G. "prompt >$nl$" in 3 Kingdoms

Folders:
* Data    - Character profile data files, Area & Map data files
* Local   - Personal scripts (put your own code here)
* Log     - Session/Chat/Other Data log files
* Mud     - Mud specific scripts
* System - General (non mud specific) scripts
