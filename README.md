# platformer
Platformer game built using pygame

# controls
## Jump - Space bar
## movement - Left Right arrow key
## night mode toggle - 'N' key
![image](https://github.com/J-Karthik-palaniappan/platformer/assets/99670301/ef860c42-c5c6-4c3d-b400-b8f326785c86)
![image](https://github.com/J-Karthik-palaniappan/platformer/assets/99670301/1f7f5bec-b553-4349-a7c7-537ed5cf20f2)

# Code Logic
The maps are stored as images where every pixel color represents a particular tile
Sprite classes:
  Coin
  Life
  path
  enemy
  player

class 'level' takes in the map image and creates the world
class 'maingame' creates mutliple levels and handles them
