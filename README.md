# Learn RAC with Arasu

Oracle RAC architecture in 3D, from the server to a running cluster.

**Live site:** https://arasupathi.github.io/learn-rac-with-arasu/

Eight sections:

1. **RAC & Clusterware** – what RAC and Clusterware are, the history from Oracle Parallel Server to 26ai, every release side by side, use cases and how RAC compares with other high-availability databases.
2. **Server & Linux** – a 2U database node you can explode part by part, the Linux layers on top of it, and the RAC preparation steps.
3. **Network** – nodes, switches, core, DWDM and cables, one network at a time; a SCAN-connection animation; a subnet calculator that lays out a RAC address plan.
4. **Storage** – HBA, fabrics, the array opened up, drives, LUNs, multipath and ASM with two failure groups; mirroring and rebalance animations.
5. **RAC Architecture** – theory from basic to advanced (architecture and Clusterware, network, storage and ASM, application connectivity), a two-node Grid & CRS lab with 33 commands and the start-up sequence, and the connection flow from a click to the rows and back.
6. **Standard RAC** – a complete data hall with four nodes, failure scenarios by layer, a cluster console and log, the temperature slider and layer close-ups.
7. **Extended RAC** – two sites and a quorum, same scenarios.
8. **Create & play** – choose type, nodes, Linux, networks, storage and filesystems; build the cluster step by step; break anything and watch it react.

Everything runs in the browser from a single `index.html`. `three.min.js` (three.js r128) is the 3D library; `og.png` is the link preview.

Hostnames, addresses and incident messages are illustrative examples, not a real environment. Best on a laptop or desktop; works on tablets; readable on phones.
