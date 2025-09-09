# gensyn

# 0g-STORAGE-NODE-NEW-SHORT-GUIDE-BY-NTEK-

> 🧠 Created by NTEK — Join our Telegram: [t.me/ntekearning2](https://t.me/ntekearning2)


## 💻 SYSTEM REQUIRMENT :

- Linux VPS (Ubuntu 20.04 or later)
- Minimum hardware: 4-core CPU, 8GB RAM, 200GB SSD


## ⚙️ PRE-SETUP

### 🟢 Add 0G RPC:

```
https://chainscan-galileo.0g.ai/
```

### 💧 GET FAUCET :

```
https://faucet.0g.ai/
```

### 🖥️ 0G NODE (ONE CLICK COMMAND)

## 1. ALL INSTALLTION :

```bash
sudo apt-get update && sudo apt-get upgrade -y && sudo apt install curl iptables build-essential git wget lz4 jq make protobuf-compiler cmake gcc nano automake autoconf tmux htop nvme-cli libgbm1 pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev screen ufw -y && curl https://sh.rustup.rs -sSf | sh -s -- -y && source $HOME/.cargo/env && rustc --version && wget https://go.dev/dl/go1.24.3.linux-amd64.tar.gz && \
