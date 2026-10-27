# MG4
## Devlog
When the scene loads, the script's Start() method sets a _timer float equal to the _switchSpeed variable.
Then the Update() method translates the GameObject upwards, depending on whether or not the _up boolean returns True.
This is determined by if the _timer, which decreases according to Time.deltaTime, ever hits zero, which flips the boolean's value.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)