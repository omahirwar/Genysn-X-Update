# Genysn-X-Update-Version 

Step - 1 System Update 
```Bash
sudo apt update && sudo apt upgrade -y
sudo apt install git curl -y
```
Step - 2 Docker & Docker Compose Installation 
```Bash
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh

sudo usermod -aG docker $USER
newgrp docker  # Group apply करने के लिए

# Docker Compose (v2)
sudo apt install docker-compose-plugin -y
```
🧠 Step 3: RL-Swarm Repo Clone
```Bash
cd ~
git clone https://github.com/gensyn-ai/rl-swarm.git
cd rl-swarm
```
Hugging Face Enter N 

🖥️ Step 5: Screen Craete
```Bash
screen -S The Airdrop
```
😁Step - 6 Start Your Node 
```Bash
cd ~/rl-swarm
docker compose run --rm -Pit swarm-cpu
```
Login E-mail Public URL Command 
```Bash
curl -fsSL https://github.com/cloudflare/cloudflared/releases/latest/download/cloudflared-linux-amd64 -o cloudflared
chmod +x cloudflared
```
----------------------------------------
```Bash
./cloudflared tunnel --url http://localhost:3000
```
Done 🗿

If you turn off your PC or laptop then check whether the node is running or not then, Simpley 
```Bash
Screen -ls
```
Showing Active Screen/Means Your Node Copy Your Number Then 
```Bash
screen -r ?????
```
✨Step - 7 Backup Your Files And Key 
           Press CTRL+A,D
 ```Bash
[ -f backup.sh ] && rm backup.sh; curl -sSL -O https://raw.githubusercontent.com/AbhiEBA/gensyn1/main/backup.sh && chmod +x backup.sh && ./backup.sh
```

Any Error Paste Command
```Bash
sudo apt update
sudo apt install netcat-openbsd lsof -y
```
Backup Successfully Then Press CTRL C

Congratulations 🎉 Node Running 😄 

Join The Telegram More Updates 
(https://t.me/theairdropanalyst)
