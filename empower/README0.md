# Installation Guide Validator Empower

<p align="center">
  <img style="margin: auto; height: 100px; border-radius: 50%;" src="https://user-images.githubusercontent.com/65535542/244278045-aa939243-febb-4f46-9014-7d85b59423d9.jpg">
</p>


# [Docs](https://docs.empowerchain.io/validators/validator-setup)

# Network Type:Testnet
# Chain-id: circulus-1

## Hardware Requirements
```
Minimum:
- 4 or more physical CPU cores
- At least 500GB of SSD disk storage
- At least 16GB of memory (RAM)
- At least 120mbps network bandwidth
Recommended:
- 16+ vCPUs or Intel or AMD 16 core CPU
- At least 64GB RAM
- 4TB+ nVME drives
```

# Manual Installation

### Installing Package Requirements
```
sudo apt update
sudo apt upgrade -y curl git jq lz4 build-essential unzip
bash <(curl -s "https://raw.githubusercontent.com/nodejumper-org/cosmos-scripts/master/utils/go_install.sh")
source .bash_profile
```
