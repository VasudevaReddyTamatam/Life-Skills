# OSI Model 

The **OSI (Open Systems Interconnection)** model is a framework used to understand and implement 
network communications between different systems. It consists of **seven layers**, 
each serving a specific function in the communication process. This model was developed by the 
**International Organization for Standardization (ISO)** in 1984 to ensure different networks and devices 
can communicate effectively.

## OSI Model Layers

![OSI Model layers picture](https://mikrotikusers.com/content/images/size/w960/2024/08/osi_layers.png)

1. ### Physical Layer

    - The Physical Layer is the lowest layer in the OSI model.
    - It deals with the physical connection between devices and the transmission of binary data (bits) over physical mediums such as cables and radio waves.
    - Examples: Ethernet cables, hubs.

2. ### Data Link Layer

    - The Data Link Layer ensures reliable data transfer between nodes on the same network.
    - It is responsible for error detection, error correction, and flow control.
    - Examples: Switches.

3. ### Network Layer

    - The Network Layer handles routing of data across different networks.
    - It determines the best path for data to travel from source to destination.
    - Examples: Routers, IP addresses.

4. ### Transport Layer

    - The Transport Layer ensures complete data transfer with error checking, flow control, and data segmentation.
    - It is responsible for end-to-end communication and reassembling packets into data.
    - Examples: TCP, UDP.

5. ### Session Layer

    - The Session Layer manages sessions or connections between applications.
    - It establishes, maintains, and terminates communication sessions.
    - Examples: APIs.

6. ### Presentation Layer

    - The Presentation Layer translates data into a format the application layer can understand.
    - It handles data encryption, decryption, compression, and decompression.
    - Examples: SSL, data encoding formats.

7. ### Application Layer

    - The Application Layer is the closest layer to the end-user and provides network services to applications.
    - It allows users to interact with software applications for data transfer and retrieval.
    - Examples: HTTP, FTP, SMTP.

## Importance of the OSI Model

The OSI model helps in standardizing network communication, making it easier to troubleshoot
network issues, develop protocols, and ensure compatibility between different types of network devices.
Each layer has a distinct role, allowing developers to work on specific parts of the communication process 
without affecting other layers.

## References

* [OSI Model - TechTerms YouTube](https://www.youtube.com/watch?v=vv4y_uOneC0)
* [OSI Model - Wikipedia](https://en.wikipedia.org/wiki/OSI_model)
* [OSI Model Explained - GeeksforGeeks](https://www.geeksforgeeks.org/layers-of-osi-model/)
* [OSI Model in Computer Networking - YouTube](https://www.youtube.com/watch?v=vv4y_uOneC0)




