# OSI Model

OSI stands for Open System Interconnection model. It is used to understand how data is transferred from one computer to another computer. It means how they communicate with each other over the network.
The networking proceess is divided into 7 layers.

## 7 Layers of OSI model

![OSI model](https://media.geeksforgeeks.org/wp-content/uploads/20250825185948477480/OSI-Model.webp)


1. **Application Layer**
    This layer is the top of the OSI model and closest to the user.
    It provides services for network application with help of protocols like **FTP, HTTP, HTTPS, SMPT etc.** to perform user activity.

2. **Presentation Layer**
    Presentation layer receives data from Application layer in the form of characters and numbers and then Presentation layer converts it to machine understandable langauage i.e binary numbers. This layer is also called transportation layer.
    The presentation layer role's are:
    * Translation
    * Compression : reduces the number of bit that needs to be transmitted.
    * Encryption/Decryption
    
3. **Session Layer**
    Session layer is responsible for establising the connections between devices, management of the connection and termination of the session between two devices. It also provides authentication and authorization.

4. **Transport Layer**
    It's job is to make sure that data goes from one computer to another computer correctly.

    What it does:
    * Breaks big data into small pieces(segments).
    * Sends them to another computer.
    * Make sure they arrive in order and without error (using TCP) and as fast as possible(using UDP).

5. **Network Layer**
    The Network Layer is responsible for finding the best path for data to travel from one computer to another across different networks.

6. **Data Link Layer**
    The Data Link Layer handles communication within the same local network (LAN).
    It uses MAC addresses(like a permanent ID) to identify devices on the same network.

7. **Physical Layer**
    The Physical Layer is the lowest layer. It deals with the actual physical movement of bits(0s and 1s).
    This layer converts data into electrical signals or light pulses.


# Reference
    
    1. ![geeks for geeks](https://www.geeksforgeeks.org/computer-networks/open-systems-interconnection-model-osi/)