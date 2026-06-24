#3. NETWORK CABLING

3.1  Copper cables

*Twisted pair cables have four pairs of wires twisted together to reduce electromagnetic interference (EMI), which helps maintain signal quality.
*There are two main types: unshielded twisted pair (UTP) and shielded twisted pair (STP), with STP offering extra protection for high-interference environments.
*Plenum-rated cables are specially designed for use in building spaces like drop ceilings or raised floors to prevent toxic fumes in case of fire.
*RJ-45 connectors with eight pins are used to terminate Ethernet cables, following wiring standards T568A or T568B.
*Cable categories (Cat5e, Cat6, Cat7, Cat8) define supported speeds and distances, with higher categories supporting faster data rates but often shorter distances, especially for Cat8 used in data centers.

3.2  Fiber cables

*Fiber-optic cables use light to transmit data, avoiding electromagnetic interference that affects copper cables.
*There are two main types: single-mode fiber (SMF) with a small core allowing one light path for longer distances, and multimode fiber (MMF) with a larger core supporting multiple light paths but shorter distances.
*The core and cladding in fiber cables have different glass types with distinct refractive indices, which keeps the light contained within the core through total internal reflection.
*Common fiber-optic connectors include SC, ST, and LC, each with different naming conventions.
*Single-mode fiber generally supports longer data transmission distances than multimode fiber, which can experience signal distortion due to multiple light paths.

3.3 Transceivers

*Transceivers add flexibility to Ethernet switches by allowing different media types and speeds without needing specific built-in ports.
*Common transceiver types include SFP (1 Gbps), SFP+ (10 Gbps), quad SFP+ (40 Gbps), and QSFP-DD (400 Gbps) for varying speed needs.
*BiDi transceivers can transmit and receive data over a single fiber strand by using different light frequencies, helping reduce fiber costs.
*Using compatible transceivers enables a wide range of connectivity options tailored to network requirements.

3.4 Straight-through vs. crossover cablesa

*Ethernet cables have eight wires connected to RJ-45 connectors; a straight-through cable has the same wiring order on both ends.
*Straight-through cables connect MDI devices (like PCs) to MDI-X devices (like switches), where transmit and receive pins are crossed internally on the switch.
*For older Ethernet standards (10Base-T and 100Base-TX), only four wires are used, with specific pins for transmit and receive.
*When connecting two MDI devices directly (like two PCs), a crossover cable is needed to swap transmit and receive pins.
*Modern switches support auto MDI-X, allowing straight-through cables to connect switches by automatically adjusting pin usage.
*Gigabit Ethernet (1000Base-T) uses all eight wires, so older wiring tricks like pair splitting are no longer viable and require rewiring for higher speeds.