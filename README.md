# MG4
## Devlog
Write your Devlog here.
The FloatAnimation script works by using the translate method within the transform compenent to move the fish food up or down the y axis depending on the value of the "_up" variable. Since this movement is in the Update() method, all code within this method is called every frame. The "_up" variable changes every time the "_timer" variable reaches or goes below 0. After "_timer" is less than or below 0, it changes the "_up" variable to its opposite boolean value, meaning it is changed to true if it is currently false and changed to false if it is currently true by using the "!". The Start() method is used to give the "_timer" variable an initial value so it can start decreasing and begin the cycle of up and down movements of the fish food.
## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)