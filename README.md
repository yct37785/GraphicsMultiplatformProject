# Graphics based multiplatform project
Attempt at developing a voxel engine that runs on Windows, Android and web. Core logic (physics, gameplay etc) is platform agnostic. Platform specific runner code and utilities (windows setup, I/O etc) calls and executes core logic.
## Windows
GLFW and GLEW with OpenGL 4.6
## Android
Android NDK to bound and run C++ code. JNI and OpenGL ES 3.0
## Web
WASM and EMSK. OpenGL ES 3.0
