# Termination-Detection
PlusCal/TLA+

N processes numbered 1..N connected by channels. A process can be in one of two possible states: 1)active or 2)idle. Initially all processes areactive, and all channels are empty.
A process that is in the active state can perform the following actions:
1. send a message
2. receive a message, or
3. change state to be idle

Process 0 is the detector process.
