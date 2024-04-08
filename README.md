# Ore CLI

Ore CLI is a command-line tool for interacting with the Ore program on Solana.

## Setup

**Prerequisites:**
- Install Rust: [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install).
- Install gcc
```sh
sudo apt-get update
sudo apt-get install build-essential
```

**Build:**
```sh
cargo build --release
```

**Configuration:**
- Write private keys to `keys.txt`, one per line.
- Write RPC urls to `rpcs.txt`, one per line.

**Run:**
```sh
./supervision.sh
```

This will start Ore CLI using the specified configuration.
