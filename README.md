# SubversionOS
SubversionOS™ - The Enigma That Hosts The Magick Ov Maelstrom-Messaging™

# Goal:
To Build An Off-OS Quazi-SMS-Encryption System for Secure-End-To-End Encrypted Messaging Over Local TCP/IP Sockets Through Data-Packets

# Step One:
Ascertain Plausability Of The 7-Steps* Of Execution Needed for ( 72424-42427 )

# SubversionOS - Telemetry Theory:
1. Snapdragon Mobile
2. Gunyah Base
3. Two Type-1 Hypervisors
4. One AnyOS on Android Kernel
5. Two SubversiveOS on Custom Kernel
6. Both Kernels need to open 8570.c For Hardware COMM communications or a USB Connection
7. SubversionOS hosts: MQTT Client & Server for Tunnel.c connection
8. We Connack between Kernel 1 and Kernel 2
9. We execute CryptoC++ Binaries
10. We transmit data over tunnel between Hypervisor via custom DataPackets
11. See AMT as example for OSI-Seven Layer Communication Transportation.

Note: Auto Connection?

Note: Accept Connection?

Note: We definitely can look into making use of TEE and AI to help.

Note: One of my Mind Expirments lead me to an issue where we may need to use and address RAM directly. However we must try and maining all operations on the Core-Dragon. Maybe we can explore the L2 and L3 cache? Unsure here.


# Suspected Issues:
We may run into several Key+Sharing Issues. Ideally we employ and encrypt ZK+Proofs Off OS along side on SubversionOS. (Note: My Nemesis=ZK+Proofs).

# Maelstrom-Messaging™
**Conceptual Model**
1. Layer 7 UI - User Enters Message x is Plain Text
2. MSG Encrypted with Key One & Dropped Down into Kernel
3. Key One Exchange w/ User Two
4. MSG x+enc crosses Kernel into SupervisionOS
5. MSG x obtains ZKProof SHA256 Encryption
6. Key 2 Passed Through/Stored In Reserved Memory Channel
7. Msg+Enc2+Enc1 Transports Back Into Main Kernel & Up Into OS
8. Packaged MSG X Sent to User 2 After 2nd Key is shared from Memory Storage into Kernel into OS
9. User 2 Obtains Package
10. Package X Drops Down & Over to Subversion OS
11. Enc2 Layer Removal Occurs
12. Enc1 Layer Removal Occurs
13. Msg X Exposed in SubversionOS off Main Kernel
14. Transport Local Key Engaged to send over and up to Layer 7 as it is decrypted at App level for End User UI in Plain Text

Note: We need two Custom MQTT Binaries - Both Client & Server to be ready to receive and transmit messages for Enc & Dec.

Note: We need a custom Kernel to sit inside a 2nd Type-1 Hypervisor.

Note: Maybe we should use a VirtualUSB instead of a vCOM or 8570 comm. channel.

# Speculative:
Can we reassign ownership permission of the Wireless.c kernel library from MainOS to SubversionOS?
