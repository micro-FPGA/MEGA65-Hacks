This was the very first design actually tested on the MEGA65 R2 PCB's.

No HDL coding just a connecting sample playback to IP that converts AXI-Stream to PWM. The sample playback only does deliver 16 bit one channel, so that stream is duplicated to play back same wave on Left and Right channels.

This design can actually be used on any Xilinx FPGA all that is needed is a clock (that may even be the internal clock!) and one output pin that has some connection to some "audible" output device.
