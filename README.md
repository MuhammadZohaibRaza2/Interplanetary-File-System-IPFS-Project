## Interplanetary File System (IPFS) Project

### Overview:
This project implements a distributed file-sharing system using the Interplanetary File System (IPFS) protocol. It utilizes concepts such as Distributed Hash Tables (DHTs) and B-Trees to enable efficient storage and retrieval of files across multiple machines in a peer-to-peer network.

### Project Group Members:
- **Muhammad Zohaib Raza**
  - GitHub: [MuhammadZohaibRaza2](https://github.com/MuhammadZohaibRaza2)

- **Muhammad Awais**
  - GitHub: [muhammadawais1315](https://github.com/muhammadawais1315)

- **Muhammad Umair Nawaz**
  - GitHub: [ummayrr](https://github.com/ummayrr)

### Description:
The project revolves around the implementation of a file-sharing system based on IPFS, where each file is represented by the hash of its content rather than its filename. It leverages the capabilities of DHTs, specifically Ring DHTs, to efficiently distribute and retrieve files across the network.

#### Key Features:
- **Distributed Hash Table (DHT):** Implements a circular identifier space for efficient storage and retrieval of files across multiple machines.
- **B-Trees:** Handles file storage and retrieval on individual machines, ensuring efficient insertion, deletion, and search operations.
- **IPFS Protocol:** Utilizes the IPFS protocol for decentralized and distributed file sharing without relying on a central server.
- **Secure Hash Algorithm (SHA-1):** Implements SHA-1 for generating unique file hashes and ensuring data integrity.
- **Visual Studio 2022 Community:** Developed using C++ environment in Visual Studio 2022 Community.
- **External Libraries:** Utilizes external libraries such as OpenSSL for SHA-1 hash generation.

### Classes and Data Structures:
The project includes several classes and data structures, including File, BTreeNode, BTree, Machine, FRT, FRTNode, DHTNode, and DHT. These classes handle various operations related to file management, machine handling, and routing.

### Time Complexity:
The project ensures efficient time complexity for major operations such as searching, inserting, and deleting files and machines. Operations are optimized to ensure quick and reliable access to data across the network.

### Evaluation:
Thorough testing has been conducted to ensure the accuracy and reliability of the implemented functionalities. The program includes a user-friendly interface with options for file operations, machine operations, viewing Finger Routing Tables (FRTs), and B-Trees.

### Conclusion:
This project provides a comprehensive exploration of distributed data structures, particularly DHTs and B-Trees. It demonstrates the effectiveness of these structures in creating a robust and efficient file-sharing system using the IPFS protocol. With thorough implementation and testing, the system ensures reliable storage and retrieval of files across multiple machines in a decentralized network.

## Project Details
- **Course**: CS-2001 Data Structures
- **Final Project**: Fall 2023

## License
This project is licensed under the terms of the MIT license.

## Requirements to Run:

- **Visual Studio Environment:**
  - Ensure you have Visual Studio 2022 Community edition installed on your system.

- **OpenSSL Library Inclusion:**
  - It is essential to include the OpenSSL library in your Visual Studio project.
  - To obtain and incorporate OpenSSL into your project, please follow the instructions provided below:
    - [Download OpenSSL 1.1.1](https://drive.google.com/file/d/16NRmKE2a3kwWns3eiVtMiLp1rIqniKOa/view?usp=drive_link)
  - Learn how to include OpenSSL 1.1.1 with Visual Studio by referring to the following guide:
    - [Tutorial on including OpenSSL 1.1.1 with Visual Studio](https://drive.google.com/file/d/1vPQWizLn__o958FUaeCPLEQfmuknOEar/view?usp=drive_link)
