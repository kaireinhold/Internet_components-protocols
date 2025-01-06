# Internet Components & Common Internet Protocols



## Introduction

This document provides a brief overview of several key network protocols that are commonly used in internet communication and device interactions. These protocols play essential roles in ensuring data is transmitted securely, reliably, and efficiently across networks. They are crucial for various applications, including web browsing, file transfers, email access, and communication between Internet of Things (IoT) devices.

The following sections cover:
- **HTTPS**: Secure communication over the web.
- **TCP**: Reliable data transmission.
- **SSH**: Secure shell for remote access.
- **SFTP**: Secure file transfers.
- **FTPS**: Secure file transfer protocol.
- **IP/IPv6**: Internet protocols for data routing and addressing.
- **IMAP**: Secure and synchronized email access.

Understanding these protocols is essential for building secure, efficient, and reliable systems for both personal and professional use.




### HTTPS:
- Browsers send HTTPS/HTTP requests to servers, the server then responds with the resource needed.
- HTTP protocols have easy error messages (404, 503).
- HTTPS encrypts all data sent to the server, to avoid a data leak.
- HTTP is used by IoT Devices (Internet of Things, home devices) to communicate with each other.

- **Real World**: The user accesses their bank’s website through a browser using HTTPS. This ensures that all sensitive data, like account details and passwords, is encrypted during transmission, protecting it from hackers.

### TCP:
- Transmission Control Protocol (TCP) ensures accurate data transmission.
- TCP will resend lost or corrupted data in the form of packets.
- TCP reorders packets to the sent order upon arrival at their destination, ensuring that the data is presented correctly.

- **Real World**: When the user browses the web or watches a video online, TCP ensures that the data, such as web pages or video content, is received in the correct order. If any packets are lost, TCP retransmits them to ensure the data is delivered correctly and the user experiences no interruptions.

### SSH:
- SSH stands for **Secure Shell**.
- It is a network protocol used for secure connections between devices over an unsecured network.
- Primarily used for remote logins and command execution.
- SSH typically uses TCP port 22 by default.
  
- **Real World**: The user logs into a remote server to check the status of a project. Using SSH, they securely access the server over an unsecured network (e.g., public Wi-Fi), ensuring that any commands they run or data they access is encrypted and safe from eavesdropping.


### SFTP:
- **Secure File Transfer Protocol**.
- Used to securely transfer files between computers over an encrypted connection, as part of SSH (secure shell).
- SFTP encrypts data being sent along with authentication credentials (usernames and passwords), keeping data safe.

- **Real World**: The user needs to send a sensitive financial report to a colleague. They use SFTP to upload the file to a secure server, ensuring the file and authentication credentials are encrypted, keeping the data safe during transfer.

### FTPS:
- **File Transfer Protocol Secure**.
- FTPS is used to securely upload, download, and manage files between a client and a server.
- Ensures files are not altered or corrupted during transmission.
- FTPS protects sensitive data from being intercepted during transmission (passwords, file contents).

- **Real World**: The user uploads large project files to a company’s secure FTP server using FTPS. FTPS encrypts both the file content and login credentials, ensuring the files remain protected from interception or tampering during the transfer.

### IP/IPv6:
- Every server and client is identified by an IP address (IPv4 or IPv6).
- Data is divided into packets, IP ensures these packets are correctly routed to their destination.
- IP determines how quickly packets are routed, which could slow down transmission speed.
- IPv6 offers better reliability in modern networks.
- Provides IoT devices (household devices) unique addressing for communication.

- **Real World**: The user’s devices (laptop, smartphone, and smart thermostat) all use IP addresses to communicate with each other over the home network. IPv6 ensures that these devices can connect reliably and without the IP address limitations of older protocols like IPv4.

### IMAP:
- **Internet Message Access Protocol**.
- Allows email clients to retrieve messages from the email server.
- Allows emails to be synchronized between devices without having to be downloaded to each local device.
- Supports the use of folders for organization.

- **Real World**: The user accesses their email on both their laptop and smartphone. Using IMAP, their emails stay synchronized across all devices, so if they read or delete an email on one device, the changes are reflected on the other devices in real-time.


### Images found in repository image folder

## Helpful Recources:
- https://www.geeksforgeeks.org/types-of-internet-protocols/
- https://flywheel-it.co.uk/the-flywheel-blog/essential-network-protocols/
- https://www.ssh.com/academy/iot/ssh-iot-remote-access (SSH)
- https://www.kiteworks.com/risk-compliance-glossary/sftp/ (SFTP)
- https://www.cerberusftp.com/blog/ftps-vs-sftp-understanding-the-difference/ (FTPS vs SFTP)
- https://www.sftpplus.com/articles/2018/sftpplus-ipv6-readiness-article (SFTP, IPv6)

