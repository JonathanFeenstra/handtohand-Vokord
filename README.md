This is a plugin written for [Vokord](https://www.nexusmods.com/skyrimspecialedition/mods/129564) based on [colinswrath's plugin for the Hand to Hand add-on for Adamant](https://github.com/colinswrath/handtohand).
 
It catches hand to hand hits and allocates XP to Two Handed.

## Requirements
* [CMake](https://cmake.org/)
	* Add this to your `PATH`
	
## Register Visual Studio as a Generator
* Open `x64 Native Tools Command Prompt`
* Run `cmake`
* Close the cmd window

## Building
```
git clone 
cd handtohand-Vokord
git submodule update --init --recursive
cmake -B build -S .
```
