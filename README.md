# [UIUC CS 415 Game Development](https://illinois-cs415.github.io/assignments/project.html): The Final Boss

In this project, we developed a side-scrolling action game inspired by Sekiro.

![menu](assets/Menu.gif)

Using art assets from the Unreal Engine Store, I led my team in implementing several core features:
-	Fluent and advance action system of the main character, including
  1) switching logic between sword-holding and boxing combo attack action systems,
  2) rolling and jumping to avoid enemy attacks
 	3) consuming energy to restore health
  4) tactics and attack skills to quickly restore health and launch a large-scale attack
  5) interaction system to talk to NPCs and interact with benches to save checkpoint.  Implement details is in Content/BluePrint/Character/Pawn/BP_Prototype
- Two types of NPCs with a dynamic dialogue system; NPCs can sell power items or guide players to the final boss, with dialogue that evolves as the game progresses
- Three melee attackers, one ranged attacker, and a final boss, each equipped with unique AI systems and action-switching logic
- Sound effects system for all characters' actions, and background music system for battle switching

Move demo:
![move](assets/Move.gif)

Combo demo:
![box combo](assets/box_combo.gif)
![sword combo](assets/sword_combo.gif)

Dialogue system demo:
![dialogue](assets/Talk_to_NPC.gif)

Combat demo:
![combat](assets/combat.gif)
