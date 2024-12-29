# Port_sniffer

## Description
This is a simple port sniffer that can be used to scan open ports on a target machine. It is written in Python and uses the socket library to create a connection to the target machine and scan for open ports. The script takes a target IP address as input and scans a range of ports to check for open connections. If an open port is found, the script will print out the port number and the service running on that port.

---

## Installation

### Clone the repository
``` bash
git clone https://github.com/Wihyeongsu-Rust-projects/port_sniffer.git
```

---

## Usage

### Help
``` bash
cargo run -- -h
```
or
``` bash
cargo run -- --help
```

---

### Example

- Basic usage(with 4 threads)
``` bash
cargo run -- <target_ip>
```

- Manual usage
``` bash
cargo run -- -j <threads> <target_ip>
```
