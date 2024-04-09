# 📒OpenChip2035
Hi, there. This project targets on simple, open, free and accessible SOC chip design to everyone.

# 🚀RoadMap

- ☑️ A UART transmitter peripheral based on the [wishbone](https://opencores.org/howto/wishbone) bus (pipelined mode, single access)  used as a template for future RTL, naming style, etc.
- 🔲 A hex bus to Wishbone bus module (hb2wbmaster), used to test wishbone peripherals.
- 🔲 A uart to bus module, refer to this [link](https://github.com/freecores/uart2bus).
- 🔲 A UART receiver based on wishbone bus.
- 🔲 To explore the SOC architecture design, the following issues need to be solved, which will be used to pay attention to the construction of future modules:
    + CPU architecture design, Harvard and von Neumann architecture, what does pipeline mean?
    + How the program is loaded and run, most likely ROM and RAM are required.
    + Interrupt mechanism, how the peripheral interrupt source is connected to the CPU and triggers the corresponding interrupt.
- 🔲 Timer
- 🔲 Spi
- 🔲 I2C
- 🔲 GPIO Matrix
