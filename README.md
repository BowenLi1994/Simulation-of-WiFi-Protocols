# Simulation-of-WiFi-Protocols

## Purpose
1. Experience with network simulation.
2. Better understanding of WiFi protocols.

## Instructions
1. Type "make" to compile the file
2. For traffic_generator program, it will generator the test cases:
  - ./traffic_generator num_node pkt_size offered_load num_pkts_per_node method [seed]
  - For the "method" parameter:  you can choice are exp and uniform [seed] is optional
3. For simulator, we implemented 2 simulators: dcf protocol and rts protocol.
  - ./simulator dcf filesname: to run the dcf protocol
  - ./simulator rts filesname: to run the rts protocol
