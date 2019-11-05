# CrossyRoad
This is a barebones recreation of the popular mobile game Crossy Road. There are several assets imported into the game but
most are not used. Additionally, the things the player can do are very limited; the player can really only move and there is
no way to win or lose.

This project was made using the Unreal Engine software.

==============================================================================
Assets Imported (Almost all assets were oddly recolored when imported)

o Chicken/Squashed Chicken

o Tree Frog/Squashed Tree Frog

o Mad Wizard/Squashed Mad Wizard

o Hipster Whale/Squashed Hipster Whale

o Grass

o Road

o River

o Blue Car

o Orange Car

o Purple Car (crossy_car)

o Taxi

o Trees (small, med, large, XL)

o Only the chicken, grass, road, river, and a few cars have been actually implemented. All else is in the files but arent in the game.

===============================================================================

Things to Look Out For

-Chicken doesnt hop but does move a set distance (teleports) whenever the player hits W A S or D.

-Chicken does not face the correct way when changing directions (always faces forwards).

-The level is continuously generated; grass road and river keep spawning and the area behind the chicken does get destroyed. Within the 
game however, the land seems to spawn a bit oddly but appears correctly the more the player advances.

===============================================================================

Download Process

-For the project to run properly, follow this format:

  -All files should be in the CrossyRoad folder. The folders within each .zip file should be extracted and placed within the folder the   .zip was found in.
  
  -The first things to look for when opening the CrossyRoad folder is Config, Content, Intermediate, Saved, and CrossyRoad.uproject. In    GitHub, Config, Content, and Intermediate are all found in one .zip. The Saved folder had to be split into 3 other .zip folders.
  
  -Inside the Saved folder should be 3 .zip folders: Autosaves, Backup, Config-Logs, and AutoScreenshot.png.

  -Summary:
    - CrossyRoad folder should have: Config, Content, Intermediate, Saved, and CrossyRoad.uproject
    
    - Saved folder should have: Autosaves, Backup, Config, Logs, and AutoScreenshot.png

===============================================================================
