# bitBalance

Self-hosted Bitcoin wallet balance tracker for **XPUB, YPUB and ZPUB**.

bitBalance allows you to monitor the balances of multiple Bitcoin wallets using your **own Electrs server**, keeping your data private and eliminating the need for third-party services.

Designed to run locally on **Umbrel**.

---

## Features

• Track multiple Bitcoin wallets  
• Supports **XPUB, YPUB and ZPUB**  
• Connects directly to your **local Electrs server**  
• No third-party APIs  
• Lightweight and simple interface  
• Fully self-hosted  
• Runs on **Umbrel**

---

## Screenshots

![bitBalance Screenshot](screenshot.png)

---

## How it works

bitBalance connects directly to your local **Electrs** server and queries address balances derived from the provided extended public keys.


XPUB / YPUB / ZPUB
↓
bitBalance
↓
Electrs
↓
Bitcoin Core


This ensures that:

• Your wallet information never leaves your node  
• No external APIs are used  
• Full privacy is preserved  

---

## Requirements

• Umbrel  
• Electrs installed

---

## Installation (Umbrel)

bitBalance can be installed directly from the **Umbrel App Store**.

After installation the app will automatically connect to your local **Electrs server**.

---

## Usage

1. Open bitBalance
2. Add a wallet name
3. Paste an **XPUB / YPUB / ZPUB**
4. The balance will be automatically tracked

You can monitor multiple wallets simultaneously.

---

## Privacy

bitBalance connects **only to your own Electrs server**.

No wallet data is sent to:

• third-party APIs  
• external services  
• analytics platforms

Everything runs locally on your node.

---

## Supported wallet types

| Type | Standard |
|-----|------|
| XPUB | BIP44 (Legacy) |
| YPUB | BIP49 (Nested SegWit) |
| ZPUB | BIP84 (Native SegWit) |

---

## Developer

Eduardo Zola

GitHub:  
https://github.com/egzola

---

## License

MIT License
