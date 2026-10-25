# MG4
## Devlog


### MG4 Devlog
- In the start method _timer is set to switch speed, which means the food will move in one direction for 3 seconds. 


- In the update method its checking to see if _up is true. If true then the food's y position increases based on the move speed * time.deltaTime. If false then the food's y position decrease using -movespeed and time.deltaTime. And time.deltaTime is subtracted from _timer each frame when _timer is <= 0.0 then the direction switches, the timer resets to switchspeed, and _up is set to !_up which activates the else and moves the food downward. This processes repeats and eventually !_up is set back to _up which switches the direction of the food to up again.



## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)