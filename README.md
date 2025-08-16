# DATAGRAM
<img width="1290" height="710" alt="image" src="https://github.com/user-attachments/assets/2ed56a52-78db-474a-bb89-f9457518a86d" />

## Datagram-testnet-node
Datagram is a real-time Hyperfabric DePIN powering the future of connected intelligence.

## Why run on VPS?
Helps preserve battery life.
VPS will give much reliable uptime.

## VISIT TO SIGN UP FOR TESTNET
[visit](https://dashboard.datagram.network?ref=907621454)

copy your API key and save it.
key is in Wallet > Licenses > Key
<img width="2880" height="1380" alt="image" src="https://github.com/user-attachments/assets/13bc0348-11f7-4940-84ac-2adf5a45f62f" />

## Step 1: Update system and install dependencies
    sudo apt update && sudo apt upgrade -y
    sudo apt install -y wget screen

## Step 2: Install Datagram cli node
    wget https://github.com/Datagram-Group/datagram-cli-release/releases/latest/download/datagram-cli-x86_64-linux

## Step 3: Move it to central path and make it executable
    sudo mv datagram-cli-x86_64-linux /usr/local/bin/datagram-cli && sudo chmod +x /usr/local/bin/datagram-cli

## Step 4: Create a screen and run the node
    screen -S datagram
.Run the node 

please replace "YOUR_API_KEY" with your actual API key

    datagram-cli run -- -key YOUR_API_KEY

if it looks like this then it's working fine
<img width="2790" height="640" alt="image" src="https://github.com/user-attachments/assets/ee917829-8c33-4bef-8087-3ae050cc710a" />
