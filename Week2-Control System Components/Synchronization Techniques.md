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