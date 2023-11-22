# AStar
a* path planning algorithm implementation and visualization based on C++ and matplotlib

## Installation

1.Conda Environment Setup
```
conda create -n [project_name] python=3.9
conda activate [project_name]
pip install matplotlib
```

2.Download Project
```c++
git clone https://github.com/hadleyhzy34/AStar.git
cd AStar
```

3.Modify `CMakeLists.txt` file

 go to file `CMakeLists.txt` and change `Python3_ROOT_DIR` to your own conda env folder.

4.Build project
```
mkdir build
cd build
cmake ..
make
./AStar
```

## Result visualization

![result](https://github.com/hadleyhzy34/AStar/blob/main/demo.png)
