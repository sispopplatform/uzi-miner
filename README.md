# Uzi

A RandomX CPU-miner for Ziesha cryptocurrency

source "$HOME/.cargo/env"
sudo git clone https://github.com/ziesha-network/uzi-miner
sudo cd uzi-miner
sudo cargo update
sudo cargo install --path .

## Usage

```
uzi-miner --node http://127.0.0.1:3030 --threads 32
```
