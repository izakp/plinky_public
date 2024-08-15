# Building on M1

1. Make Portaudio: `cd ../../modules/portaudio` and `./configure && make`
2. Download and install glfw
    - Get https://github.com/glfw/glfw/releases/download/3.4/glfw-3.4.bin.MACOS.zip
    - Unzip and cd to directory
    - `sudo cp libglfw* /usr/local/lib`
3. You should be able to `make`