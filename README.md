# Route Planning Project
<img src="map.png" width="600" height="450" />

## Dependencies for Running Locally
* cmake >= 3.11.3
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
* gcc/g++ >= 7.4.0
* IO2D
  * Installation instructions for all operating systems can be found [here](https://github.com/cpp-io2d/P0267_RefImpl/blob/master/BUILDING.md)
  * This library must be built in a place where CMake `find_package` will be able to find it
  * You can clone and install this _anywhere_ as long as you install it (last step from instruction) (At least with Ubuntu)


## Building
When cloning this project, be sure to use the `--recurse-submodules` flag. Using HTTPS:
```
git clone https://github.com/udacity/https://github.com/AbhinavMir/OpenStreetMap-in-CPP.git --recurse-submodules
```
or with SSH:
```
git clone git@github.com:udacity/https://github.com/AbhinavMir/OpenStreetMap-in-CPP.git --recurse-submodules
```
To compile the project, first, create a `build` directory and change to that directory:
```
mkdir build && cd build
```
From within the `build` directory, then run `cmake` and `make` as follows:
```
cmake ..
make
```
### Running
The executable will be placed in the `build` directory. From within `build`, you can run the project as follows:
```
./OSM_A_star_search
```
Or to specify a map file:
```
./OSM_A_star_search -f ../<your_osm_file.osm>
```
