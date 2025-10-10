# set_gpu_fans_public
Controlling the fan speed of an NVIDIA GPU on a headless linux system requires spoofing a display.
This can be used to gain a few percent additonal performance, at the cost of increased noise.
For installation and usage, read the comments in cool_gpu.

The script uses a polynomial to define a fan curve, and automatically switches to P0 performance mode when needed.

Rewritten from https://github.com/boris-dimitrov/set_gpu_fans_public