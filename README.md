# Rust Verusd RPC Server

This repository contains a Rust library for creating a Verus RPC server. The library is designed to be simple to use, yet flexible enough to handle the needs of a variety of applications.

## Getting Started

To get started with this library, you'll need to have Rust installed on your machine. If you don't have Rust installed, you can download it from the [official website](https://www.rust-lang.org/tools/install).

### Prerequisites

- Rust programming language
- Git

### Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/VerusCoin/rust_verusd_rpc_server.git
```

2. Navigate into the project directory:

```bash
cd rust_verusd_rpc_server
```

3. Build the project:

```bash
cargo build
```

### Usage

1. Configure the server by editing the Conf.toml file

2. Run the server:

```bash
cargo run
```

### Run using Docker
#### Requirement:
- [`docker`](https://docs.docker.com/get-docker/) - `v24.0.5,`

#### Build Image
```bash
docker build -t verus-rpc-server .
```

#### Execute
```bash
docker run -it --network host --rm --name verus-rpc-server verus-rpc-server
```
> Network `host` is used to enable communication to the Verus Node

##### Util Script
The above can also be run using the utilty script.
```bash
chmod +x docker-build.sh && ./docker-build.sh
```

### Contributing
Contributions are welcome! Please feel free to submit a pull request.
