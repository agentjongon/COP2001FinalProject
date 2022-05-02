# COP2001FinalProject

Daisy Game:

Initial Design: -Slay the spire inspired game, almost like a rogue-like

Objective: For Daisy to reach the end of the path and get her bone.
             -By passing throigh mobs, bosses and mini-games
             -Mini-Games drop treasure if success, adds to points and aid in battle
             -Mobs/Bosses always drop loot
             -Loot and Treasure affect the health, magic, attack, defense or evasion of Daisy

Enemies:
       Boss:
             -Alligator baby
             -Big Fluffy Cat
             -Midnight Mlack Cat
       Mob:
             -Insects?
             -Raccoons
             -Ducks
             
       Battles are d&d based
            -All creatures have hp, mp, att, def and evasion. 
            -ALl creatures drop random loot if subdued(Takes random index from vector to get random loot, then pops that loot from vector)
            -If Daisy HP <= 0  during battle, restart whole game
            -Daisy wins/progresses when enemy HP <= 0
            
Loot: Upon mob dying, drops random loot, automatically attaches to Daisy
      -WOlf Set:
            -Wolf Ears: Increase HP, DEF
            -WOlf Pelt: Increase HP, DEF
            -Wolf Paws: Increase Att, Evasion
            
            -Same style of loot

Minigames:
      -Rock Paper Scissors against a bunny rabbit for his treasure
      -Tic-Tac-Toe against another chihuahua also in their quest for the bone
      -Snake game, where a garden snake will offer a treasure if you can complete the game
      -Spot the difference, with a chameleon
      -Judgement Decisions, get treasure and take random amount of health(1-10) until success, or avoid treasure and lose 5 health
      
      All of the minigames only give treasure if Daisy wins, generally lose health upon loss, otherwise progresses to next scene.
      
Treasures:
      -Wolf Claws: Increase Attack and MP
      -Megaphone: Increase MP
      -X-Ray goggles: Increase Evasion
      -Wolf Canines: Increase Attack
      -Small Bone: Increase HP, Def
      -others
      
Map:
      World Map consists of all the paths Daisy can take to her bone. With it all laid out there so that the player can see where he can go. Menu on top left with clickable thing showing current stats. Menu on bottom right, with list of key presses that can quit game etc.
      
      WOrld Map constantly updates everything.
      
      Battle Maps: Usually an image of the mob.
      
      Treasure Maps: Usually an image of the treasure and mini-game.
      
Version 1:
      Goal was to create just a singular linear path to create a baseline for the game.


FUTURE:
      Goal to implement all of the paths and mobs.
      
      
