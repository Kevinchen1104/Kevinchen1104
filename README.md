Hi, I'm Kevin. I work on computer architecture and RTL design: pipelined CPUs, caches, accelerators, and the verification that shows they work.

## Projects

**[rv32im-basys3-soc](https://github.com/Kevinchen1104/rv32im-basys3-soc)**
A five-stage RISC-V CPU and SoC (RV32IM-style, machine mode) with instruction and data caches, branch prediction, traps, and two matrix-vector accelerators. It runs GCC-compiled C on a Basys 3 at 100 MHz. The repo includes measured studies of cache sizing, victim caches, and when an accelerator pays for its transfer cost.

**[rtl-streaming-udp-filter](https://github.com/Kevinchen1104/rtl-streaming-udp-filter)**
A SystemVerilog Ethernet/IPv4/UDP filter that streams matching payload out one cycle after it arrives, at 125 MHz (1 Gb/s) on a Basys 3. Verified with a Python reference model, cocotb, SymbiYosys formal proofs, and a hardware test on the board.

## Tools

SystemVerilog, Verilog, Python, cocotb, Icarus Verilog, Verilator, Yosys, SymbiYosys, Vivado
