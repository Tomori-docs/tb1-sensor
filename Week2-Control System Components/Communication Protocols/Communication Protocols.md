Serial communication protocols between I/O devices and microcontrollers are:
• UART: Asynchronous communication as a full-duplex channel, through two
independent wires, connecting the RX pin of each endpoint to the TX pin on
the opposite side.
• Serial peripheral interface (SPI): Synchronised full-duplex communication
by using a clock line (SCK). The microcontroller share wires with two
peripherals: COPI (Controller out peripheral in) and CIPO (Controller in
peripheral out). The bus uses two separate select signals (CS) for each
peripheral.
• Inter-integrated circuit (I2C): Interconnecting multiple microcontrollers and
peripherals on the same two-wire bus. The two signals are serial clock (SCL)
and serial data (SDA). Unlike, SPI or UART, the bus is half-duplex.
• Controller area networks (CAN): Incudes multiple nodes. Each node
consists of a processor, a controller and a transceiver. CAN uses messages
over a pair of wires to identify each node.

• Universal Serial Bus (USB): Originally designed to replace UART. This
protocol works in host-device mode, with one side of the communication, the
device, exposing services that can be used by the controller, on the host
side.
• Ethernet, Wi-Fi, and Bluetooth: Some microcontrollers embed network
interfaces for wired or wireless communication that enables connection to
local networks or the internet for IoT and cloud applications.