# UART-implementation-in-FPGA
Designed and implemented a UART communication system in Verilog, developing and simulating both transmitter and receiver modules.
 In this project, we take a hands-on approach to developing a UART system using Verilog.
 The goal is to simulate and build a working communication module on the DE0-Nano
 FPGA board. We begin by creating Verilog modules that handle both transmitting and
 receiving operations. These are rigorously tested in simulation environments using tailored
 testbenches to ensure correctness.
 Once verified, the system is deployed onto the FPGA and connected to an external
 device via UART. Successful transmission is demonstrated by physically linking the Tx and
 Rx pins between the two devices and observing correct data exchange in real time.

 
UART Specifications
The communication protocol was implemented with the following specifications:

Baud Rate: 115200 bps

Reset: Active low

Clock Frequency: 50 MHz

Parity: None

Frame Format: 10 bits

       1 start bit

       8 data bits

       1 stop bit
