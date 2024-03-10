# polymer
## Polymer Role DEV

Polymer Update Get Role Polyverse Dev

- Open [https://gitpod.io/]
- Connect Github
- Create Workspace
- Open Github Dulu : [https://github.com/open-ibc/ibc-app-solidity-template/tree/main]
- Klik Use Template > Create New Repository
- Repository Name Isi : polymer-template
- Create Repo > Code Salin Link Git
- Back to Gitpod Pilih 
- Paste Link Git Yang Tadi di Copy Paste
- Pilih Vs Code, Standard
- Continue

di Terminal Gitpod Install Bahan Bahan

- ´npm install´
- ´nvm use 20´

- ´curl -L https://foundry.paradigm.xyz | bash´
- ´source /home/gitpod/.bashrc´
- ´foundryup´

- ´wget -qO - 'https://proget.makedeb.org/debian-feeds/prebuilt-mpr.pub' | gpg --dearmor | sudo tee /usr/share/keyrings/prebuilt-mpr-archive-keyring.gpg 1> /dev/null´
- ´echo "deb [arch=all,$(dpkg --print-architecture) signed-by=/usr/share/keyrings/prebuilt-mpr-archive-keyring.gpg] https://proget.makedeb.org prebuilt-mpr $(lsb_release -cs)" | sudo tee /etc/apt/sources.list.d/prebuilt-mpr.list´
- ´sudo apt update && sudo apt install just´

just install

- ´cp .env.example .env´

Open File .env (Nanti Kita isi Data Dari Alchemy and Blockscout)

👉 Edit Isian .env di Bawah :

PRIVATE_KEY_1='ISI-PRIVATE-KEY-WALLET-KALIAN'

OP_ALCHEMY_API_KEY='API DARI ALCHEMY'
BASE_ALCHEMY_API_KEY='API DARI ALCHEMY'
OP_BLOCKSCOUT_API_KEY='API DARI BLOCKSCOUT'
BASE_BLOCKSCOUT_API_KEY='API DARI BLOCKSCOUT'

➡️ Blockscout

- Open Link : Op Sepolia
- Add API KEY (Name Bebas) Copy API Taro di .env
- Open Link : Base Sepolia
- Add API KEY (Name Bebas) Copy API Taro di .env

➡️ Alchemy

- Opeen Link : https://dashboard.alchemy.com/apps
- Create 2 New App (OP and Base)
Salin Kedua API nya Taro di .env
- Claim Faucet OP sama BASE Dulu..
- Done, Back Terminal Paste

just do-it
