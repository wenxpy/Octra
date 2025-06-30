# Octra Wallet Creation 

- Click to open  [CodeSpace](https://github.com/codespaces) then select a blank template.
- After opening the terminal follow below guide

```javascript
git clone https://github.com/octra-labs/wallet-gen.git
cd wallet-gen
```
```javascript
curl -fsSL https://bun.sh/install | bash
source ~/.bashrc
bun --version
```
```javascript
bun install
```
```javascript
bun run build
```
```javascript
bun start
```

-  After that, a pop-up will appear use it to open
-  Make sure you generate wallet and save all essential info.


# Week 1 Octra Tasks

### Enviroment
- Claim Faucet: https://faucet.octra.network/
- Visit: https://github.com/octra-labs/octra_pre_client
- Select `Open with Codespaces` then click `New codespace`
- Give some time to load the page.

### Dependencies installation
```javascript
pip install -r requirements.txt
```

### Create wallet.json and edit (replace by octra wallet info)
```javascript
cp wallet.json.example wallet.json
```

### Start sending transactions
```javascript
python cli.py send --to your octra wallet --amount 0.01
```

- That's it, complete minimum 10 transactions.
- Watch video guide on X
  
