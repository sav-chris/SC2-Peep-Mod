# Starcraft Peep Mod

Starcraft 2 Mod for playing round robin 1v1s in a lobby with many players. Custom Races are supported too.

# Folder Structure

    .
    └── Mod                     # Folder for the core Mod
       ├── src                  # Mod Source Code
       └── bin                  # The Mod saved as a deployable Project file
    ├── Docs                    # Folder for more documentation
    ├── Maps                    # Maps that use the Mod 
    ├── Test                    # Test Maps with test cases
    ├── Scripts                 # This folder was reserved in case i needed scripts 
    └── Media                   # Used for images and other media
    
# Package Diagram

The project is a [starcraft mod](https://s2editor-guides.readthedocs.io/New_Tutorials/01_Introduction/006_Mods/) which can be used by other starcraft [1v1 maps](https://liquipedia.net/starcraft2/Maps/Ladder_Maps/Legacy_of_the_Void). This mod in turn uses the [Scion Mod](https://sc2arcade.com/map/1/313549/) by [Solstice245](https://github.com/Solstice245/scion-keiron-dev). Documentation on the Scion mod gameplay [can be found here](https://starcraft-scion-custom-races.fandom.com/). 

![Package Diagram](Docs/Subpackages-Structure-Diagram.png)

