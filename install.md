GLEW and GTK
```bash
sudo apt-get install libglew-dev libcanberra-gtk-module
```

GLFW
```bash
git clone https://github.com/glfw/glfw.git
cd glfw && mkdir build && cd build
cmake ..
make
```

OpenCV >= 4.0.0
```bash
git clone https://github.com/opencv/opencv/
cd opencv && mkdir build && cd build
cmake ..
make
```

RBGT: update path in ```line 19``` from ```examples/run_on_camera_sequence.cpp```
```bash
mkdir build && cd build
cmake ..
make
./examples/run_on_camera_sequence
```
