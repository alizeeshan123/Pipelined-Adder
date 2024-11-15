# Pipelined-Adder
This DSD project is the verified design of a "4-Stages Pipelined 4-bit Ripple Carry Adder" by cutting down the total "Datapath Delay" of a 4-bit Ripple Carry Adder into "1/4th" using "Pipelining" on "Xilinx-Vivado" tool using "Cut Set" concept.
<br>
I’ll introduce you to an amazing concept called "Pipelining" in microprocessors. <br>
<br> What makes a processor so fast? <br>
<br> Most people would think it’s the high clock frequency (GHz) or wide data bus, but those methods reached their limits years ago. We still use 3.2 GHz clocks and 64-bit data buses, so what’s the secret to faster processors? The answer is "Instruction Pipelining", a fascinating but complex idea. <br>
<br> In short, pipelining divides the critical circuit datapath delay into smaller segments. Each segment, or stage, works independently and processes data at higher speeds. Although this boosts performance, it introduces "Hazards" that must be managed.
