# AFTERMATH

This is a small 2d pixel art game. 

## Getting Started

All that needs to be done is for the SDL2 libraries to be installed on your linux machine and then run the compile line in Aftermath/src

### Prerequisites

SDL2 libraries must be installed, this can be done easily with one command lien arguement.

```
sudo apt-get install libsdl2-image-2.0-0 libsdl2-image-dev libsdl2-mixer-2.0-0
```

### Launching Game

To launch the game run the below command line arguement in Aftermath/srs

```
gcc main.c player.c background.c -lSDL2 -lSDL2main -lSDL2_image -lSDL2_mixer -lm -o main
```


## Built With

* [SDL](https://wiki.libsdl.org/) - Graphics framework used

## Authors

* **Calvin Stahoviak**

* **John Arguyes**
