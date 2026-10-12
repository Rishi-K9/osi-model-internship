# OSI Model: The Seven Layers of Network Communication

## Objective
To understand the seven layers of the OSI (Open Systems Interconnection) model and identify common protocols associated with each layer.

## Project Document
The complete OSI Model layer chart, explanations, and interview questions are available in the PDF.

## OSI Model Layer Chart

| Layer Number | Layer Name | Main Function | Examples |
|---|---|---|---|
| 7 | Application | Provides network services to applications | HTTP, HTTPS, DNS, SMTP |
| 6 | Presentation | Handles data formatting, encoding, encryption, and compression | TLS/SSL, JPEG, UTF-8 |
| 5 | Session | Establishes, manages, and terminates communication sessions | RPC, NetBIOS |
| 4 | Transport | Provides end-to-end data delivery and port-based communication | TCP, UDP |
| 3 | Network | Handles logical addressing and routing | IP, ICMP |
| 2 | Data Link | Transfers frames within a local network | Ethernet, Wi-Fi MAC |
| 1 | Physical | Transmits raw bits through physical media | Cables, fiber optics, radio signals |

## How Data Travels
When a user opens a website, data travels down the OSI layers on the sending device and is transmitted over the network. The receiving device processes the data in reverse order.

## Key Protocol Examples
- HTTP/HTTPS: Application Layer (Layer 7)
- TCP: Transport Layer (Layer 4)
- IP: Network Layer (Layer 3)
- Ethernet: Primarily Data Link Layer (Layer 2), with physical specifications at Layer 1.

## Interview Questions and Answers

### 1. What is the OSI Model?
The OSI Model is a conceptual framework that explains network communication through seven layers.

### 2. Which layer uses IP?
IP operates at Layer 3, the Network Layer, and helps route packets between networks.

### 3. Which layer uses TCP?
TCP operates at Layer 4, the Transport Layer, and provides reliable, ordered data delivery.

## Configuration
The project documentation is maintained in README.md and PDF formats.

## Deployment
The documentation is published through this public GitHub repository.

## Rollback Evidence
GitHub commit history can be used to review changes and restore an earlier version of the documentation if required.

**Note:** This is a documentation-only project. No separate application deployment or rollback operation has been performed.

## Conclusion
The OSI model divides network communication into seven layers. Understanding these layers helps with network design, protocol identification, and troubleshooting.
