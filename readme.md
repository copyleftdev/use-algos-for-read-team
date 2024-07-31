# Useful Algorithms for Red Teams

Welcome to the **Useful Algorithms for Red Teams** project! This repository is a collection of essential algorithms and tools tailored for offensive security professionals, specifically red teams. Each project demonstrates a different aspect of cybersecurity attack techniques, from network sniffing to password brute forcing, all implemented in Rust for optimal performance and security.

## Table of Contents
- [Projects](#projects)
  - [Port Scanner](#1-port-scanner)
  - [Password Brute Forcing](#2-password-brute-forcing)
  - [SQL Injector Tester](#3-sql-injector-tester)
  - [Subdomain Enumeration](#4-subdomain-enumeration)
  - [ARP Spoofing](#5-arp-spoofing)
  - [DNS Spoofing](#6-dns-spoofing)
  - [Buffer Overflow Exploitation](#7-buffer-overflow-exploitation)
  - [Network Sniffing](#8-network-sniffing)
  - [Shellcode Injection](#9-shellcode-injection)
  - [Credential Dumping](#10-credential-dumping)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Projects

### 1. Port Scanner
- **Description:** Performs a TCP SYN scan to identify open ports on a target system.
- **Path:** `port-scanner`
- **Usage:** Run the tool to scan a range of ports on a specified target IP.

### 2. Password Brute Forcing
- **Description:** Attempts to crack passwords by generating and testing possible combinations.
- **Path:** `password-brute`
- **Usage:** Provide the target hash and run the tool to attempt to find the matching password.

### 3. SQL Injector Tester
- **Description:** Tests for SQL injection vulnerabilities by injecting payloads into web applications.
- **Path:** `sql-injector-tester`
- **Usage:** Run the tool against a target URL to detect potential SQL injection vulnerabilities.

### 4. Subdomain Enumeration
- **Description:** Enumerates subdomains for a given domain to find potential attack vectors.
- **Path:** `enumerate-subdomains`
- **Usage:** Specify the target domain and run the tool to discover subdomains.

### 5. ARP Spoofing
- **Description:** Intercepts network traffic by spoofing ARP packets.
- **Path:** `arp-spoofing`
- **Usage:** Run the tool on a local network to start ARP spoofing.

### 6. DNS Spoofing
- **Description:** Redirects DNS queries to a malicious server.
- **Path:** `dns-spoofing`
- **Usage:** Run the tool to start spoofing DNS responses.

### 7. Buffer Overflow Exploitation
- **Description:** Demonstrates how to exploit a buffer overflow vulnerability.
- **Path:** `buffer-overflow`
- **Usage:** Run the tool with the appropriate payload to exploit the vulnerability.

### 8. Network Sniffing
- **Description:** Captures network packets for analysis.
- **Path:** `network-sniff`
- **Usage:** Run the tool to start capturing packets on the network interface.

### 9. Shellcode Injection
- **Description:** Injects and executes shellcode within a running process.
- **Path:** `shell-code`
- **Usage:** Provide the shellcode and run the tool to perform the injection.

### 10. Credential Dumping
- **Description:** Extracts credentials from a target system.
- **Path:** `credential-dumping`
- **Usage:** Run the tool to dump credentials from the target system.

## Installation

Each project is a separate Rust application. To get started, navigate to the desired project directory and build it using Cargo.

```sh
cd <project-directory>
cargo build --release
```

## Usage

To run any of the tools, navigate to the specific project directory and execute the compiled binary.

```sh
cd <project-directory>
cargo run --release
```

## Contributing

Contributions are welcome! If you have a new algorithm or improvement, feel free to fork this repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

