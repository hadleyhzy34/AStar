# AStar
a* path planning algorithm implementation and visualization based on C++ and matplotlib

## Installation

```
conda create -n [project_name] python=3.9
conda activate [project_name]
pip install matplotlib
```

```c++
git clone https://github.com/hadleyhzy34/AStar.git
cd AStar
```

 go to file `CMakeLists.txt` and change `Python3_ROOT_DIR` to your own conda env folder.

```
mkdir build
cd build
cmake ..
make
./bin/AStar
```

## Result visualization

![result](https://github.com/hadleyhzy34/AStar/blob/main/demo.png)
