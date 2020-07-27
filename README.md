# jetson_nano

This repository holds the scripts/programs I use to set up the software development environment on my Jetson Nano.

To set Jetson Nano to 10W performance mode ([reference](https://devtalk.nvidia.com/default/topic/1050377/jetson-nano/deep-learning-inference-benchmarking-instructions/)), execute the following from a terminal:

   ```shell
   $ sudo nvpmodel -m 0
   $ sudo jetson_clocks
   ```
