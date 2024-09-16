# Ocean Incentivized Node

Meet Ocean: Tokenized AI & Data


**COMPUTE-TO-DATA**
Shift the computation towards the data instead, and not vice versa. Coupled with Data NFTs and Datatokens, users can remotely leverage machine learning and AI without relocating their assets, paving the way for novel revenue streams. It enables people to sell private data while preserving privacy, as an opportunity for companies to monetize their data assets.

**Rewards Breakdown** :
🚀 Ocean Noders, we give you the detailed incentive breakdown: [Rewards Link](https://blog.oceanprotocol.com/ocean-nodes-incentives-a-detailed-breakdown-0baf8fc98001)

💻5,000 $FET/weekly reward pool, starting August 22

🔑How to earn:

→Maximize Uptime: Longer node activity = higher reward chances
→Collect ONBs: Stack all 3 ONBs for 2x multipliers
→Keep It Up: Consistent performance each week increases your earnings

Site : [Ocean](https://oceanprotocol.com/) | Docs : [Oceandocs](https://docs.oceanprotocol.com/) | X : [X.com](https://x.com/oceanprotocol) |

| **Hardware** | **Minimum Requirement** |
|--------------|-------------------------|
| **CPU**      | 1 Cores                 |
| **RAM**      | 2 GB                    |
| **Disk**     | 4 GB                    |


Join : [Telegram](https://t.me/cryptoconsol)

Follow : [Twitter](https://www.x.com/cryptoconsol)

Subscribe : [Youtube](https://www.youtube.com/@cryptoconsole)

Crypto VPS : [https://vpsdime.com](https://vpsdime.com/a/4418/linux-vps)

Youtube Guide : [![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://www.youtube.com/watch?v=7CMaBFgaTl8)

### Install dependencies :
```
sudo apt-get update && sudo apt-get upgrade -y
sudo apt install curl -y
sudo apt install ca-certificates
```
### Install Docker :

Skip if you already have it

```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg

echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

sudo apt-get update
sudo apt-get install docker-ce docker-ce-cli containerd.io
docker version
```
### Install Docker Compose :

Skip if you already have it

```
VER=$(curl -s https://api.github.com/repos/docker/compose/releases/latest | grep tag_name | cut -d '"' -f 4)

curl -L "https://github.com/docker/compose/releases/download/"$VER"/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

chmod +x /usr/local/bin/docker-compose
docker-compose --version
```
### Add Permission :

First time users
```
sudo groupadd docker
sudo usermod -aG docker $USER
```


### Creat ocean folder :
```
mkdir ocean && \
cd ocean
```
### Run installer script:
```
curl -O https://raw.githubusercontent.com/oceanprotocol/ocean-node/main/scripts/ocean-node-quickstart.sh && chmod +x ocean-node-quickstart.sh && ./ocean-node-quickstart.sh
``` 

Watch the video to setup
```
ls -al
```
Edit **docker-compose.yml** using video

Alchemy RPC : https://dashboard.alchemy.com/

Chainlist : https://chainlist.org/

RPC File : https://t.me/cryptoconsol

Ocean Faucet : https://faucet.sepolia.oceanprotocol.com/

```
nano docker-compose.yml
```

### Start your Ocean Node:
```
docker-compose up -d
```
### Check logs :
```
docker-compose logs -f
```

Check peer ID : change port respectively - http://your_ip:8000/dashboard/ 

Check Rewards : https://nodes.oceanprotocol.com/

Join Disussion : [Crypto Console Telegram](https://t.me/cryptoconsol)

