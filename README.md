# 🛠 ETHStorage-Trusted-Cremony-Guide
**Purpose:** Generate secure zk-SNARK parameters for EthStorage’s circuits, ensuring transparency, decentralization, and long-term security for the entire community.

<img width="1500" height="840" alt="477937681-0b5fa0a6-9e3a-4353-a739-27c8dd9943da" src="https://github.com/user-attachments/assets/d449dc75-851b-43ed-9ce6-cb7d245f3628" />

## **1. Update & Upgrade System**
----
## 📋 Participation Requirements
- **OS:** Linux, macOS, or Windows with WSL2.
- **GitHub:**  
  - Account ≥ 1 month old  
  - ≥ 1 public repo  
  - Follows ≥ 5 accounts & has ≥ 1 follower  
  - Allows GitHub Gist read/write access
- **Internet:** Stable connection with good upload speed.
- **Dependencies:** Node.js ≥ 18, npm ≥ 9.2.0 (install via NVM recommended).
-----

## 📌 Why Participate
- **Strengthen Security** : Safeguard zk-SNARK parameters with strong cryptography and secure protocols.
- **Ensure Decentralization** : Use multiple independent participants to eliminate single-entity trust.
- **Guarantee Transparency** : Make the process fully auditable and open-source for public verification.


## 🤝 How You Can Contribute
1. Join during the event window (Aug 13–22, 2025) and run the provided ceremony CLI tools to generate your randomness.
2. Submit your contribution to strengthen the setup.
3. Verify your participation and share proof to inspire others.

--------

## **Update & Upgrade System**
```
sudo apt update && sudo apt upgrade -y
```
## **Build Essential Tools**
```
sudo apt install -y build-essential \
  curl \
  wget \
  git \
  unzip \
  pkg-config \
  software-properties-common
```
## **Install NVM**
Required for ceremony CLI
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```
```
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"
```
```
nvm install 18
nvm use 18
nvm alias default 18
```
```
source ~/.bashrc
```
<img width="518" height="119" alt="Screenshot 2025-08-14 194359" src="https://github.com/user-attachments/assets/dcf6a5e0-0f48-45be-8033-c79d41f5af52" />


## **Create and Navigate into directory**
```
mkdir ceremony && cd ceremony
```
## **Install NPM package**
```
npm install -g @p0tion/phase2cli
```

## **Authenticate Github**
Running this line of code will show you alink to click that will direct you to [Github - http://github.com/login/device ](http://github.com/login/device)
```
phase2cli auth
```
<img width="1020" height="501" alt="Screenshot 2025-08-14 183812" src="https://github.com/user-attachments/assets/27718aff-b87f-42d6-982a-f7a162c552ed" />


- [ ] Authenticate Github and copy the code from terminal
- [ ] Paste code on Github page
- [ ] Check back terminal to confirm you're IN. 

## Open a new screen/session with command 
```
screen -S ceremony
```
### Contribute to Ceremony 
```
phase2cli contribute
```
- [ ] Use the arrow key, select the second option **(EthStorage V1 Trusted Setup Ceremony)**
- [ ] Select ENTER and continue
- [ ] Select ENTER again to use the Random selection. 
<img width="1911" height="306" alt="Screenshot 2025-08-14 190400" src="https://github.com/user-attachments/assets/04d45686-e627-4272-8672-3c0babe45c07" />


<img width="1919" height="222" alt="Screenshot 2025-08-14 190506" src="https://github.com/user-attachments/assets/045b73c2-bba6-4534-ad2d-7a74e003aff4" />


## Screen Commands
- **Minimize / Detach session:** `Ctrl + A + D`
- **Reattach session:** `screen -r ceremony`
- **List sessions:** `screen -ls`
- **Close session from outside:** `screen -XS ceremony quit`


## 📚 Resources
- [Official Blog Post](https://blog.ethstorage.io/join-the-ethstorage-v1-trusted-setup-ceremony/)


