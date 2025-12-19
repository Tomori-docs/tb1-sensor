1.  Communication protocols: UART, SPI, I2C, CAN, USB, Ethernet, Wi-Fi, and
Bluetooth.

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

![](/file/2/MSbQ7W610GLhffwSk9g4z.png)



2. Serial communication could be simplex, half duplex, or full duplex:
Serial channels are classified in terms of their direction of transfer as simplex,
half duplex, or full duplex:

---
1. Simplex: 
![](/file/2/dnUYHi8SnonMpKVh01UHp.png)

Data transfer data in only one direction.
e.g., the ring network (a
type of computer network
topology where each
device (node) is
connected to exactly two
other devices, forming a
continuous closed loop or
ring.).

---
Half duplex: 
![](/file/2/4oW1IirnH9gnWZSS0CZ48.png)

Data transfer in
either direction, but in only
one direction at a time. e.g.,
the desktop serial bus, or
multi drop network (a
communication configuration
where multiple devices
(usually three or more) are
connected to a single shared
communication line or bus.)

---

Full duplex: 
![](/file/2/1XwS3ryKTA0eYreFxaq2c.png)

Data transfer in
both directions
simultaneously. e.g.,
telephone call, modern
ethernet network, Wi-Fi
networks, video conferencing
systems.







3. In asynchronous data transfer, the transmitter and receiver do not share a
common clock signal, whereas, in synchronous transfer, there is a common clock signal between the transmitter and receiver:


• A clock signal is needed to synchronize the receiver’s timing to the incoming
serial data so that the receiver can latch each data bit. Serial data transfers
can be classified as either asynchronous or synchronous based on the
nature of the clock signal.
• In asynchronous transfer, the transmitter and receiver do not share a
common clock signal. Each provides its own independent clock. Both clocks
run at the same nominal frequency. Synchronization is established on a
frame-by-frame basis, and only for the duration of each frame. The
advantage of asynchronous transfer is its low cost. It is used primarily where
transmission of frames is irregular, or where large blocks of data do not need
to be transmitted at high speed.
• In synchronous transfer, either a common clock signal exists between the
transmitter and receiver, or the receiver is capable of deriving a clock signal
from the transitions of the received data signal.

