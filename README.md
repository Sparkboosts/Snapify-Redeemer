
---

```markdown
# Snapify-Redeemer

Snapify-Redeemer is a powerful, automated Discord Nitro claiming tool. It uses Discord tokens to log into accounts, claim Nitro promotions using virtual credit card (VCC) details, and automatically redeem rewards such as Discord Nitro from promotions like the Snapify campaign.

> ⚠️ **DISCLAIMER:** This tool is for **educational purposes only**. Using auto-claim tools on Discord accounts you do not own or have permission to use is against Discord's Terms of Service. The use of this software may result in account termination.

---

## 🧠 Features

- Automatically logs in using provided Discord tokens
- Redeems Nitro via Snapify promotional codes
- Supports bulk operations with multiple tokens and VCCs
- Easy configuration via `config.json`
- CLI-based interface

---

## 🗂️ Folder Structure

```
Snapify-Redeemer/
│
├── input/
│   ├── tokens.txt         # List of Discord tokens
│   ├── vccs.txt           # List of VCCs for Nitro claim
│   └── proxies.txt        # Optional: list of proxies
│
├── config.json            # Configuration file
├── main.py                # Main execution script
├── keyauth.py             # Licencning functions
└── README.md              # This file
```

---

## ⚙️ Setup & Usage

### 1. Clone the Repository

```bash
git clone https://github.com/Sparkboosts/Snapify-Redeemer.git
cd Snapify-Redeemer
```

### 2. Install Dependencies

Make sure you have Python 3.8+ installed, then install the required packages:

```bash
pip install -r requirements.txt
```

### 3. Prepare Inputs

- `input/tokens.txt`: Add your **Discord tokens** (1 per line)
- `input/vccs.txt`: Add **virtual credit card details** in the format:
  ```
  CARD_NUMBER|MM|YY|CVV
  ```
- `input/proxies.txt` *(optional)*: HTTP/HTTPS proxies (1 per line)

### 4. Configure `config.json`

Edit the `config.json` file to match your needs:



## ▶️ Running the Tool

After everything is set up:

```bash
python main.py
```

The tool will start processing the tokens, logging in, and claiming Nitro if available.

---

## 🛑 Important Notes

- Using this tool violates Discord's TOS if misused.
- Avoid using your main account — use alt accounts only.
- Rotate proxies and tokens to reduce detection.
- Do not share your tokens publicly.

---

## 📬 Credits

- Developed by [Sparkboosts](https://github.com/Sparkboosts) Discord id (74dt)
- Educational use only. No responsibility for misuse.

---

## 🛡️ Disclaimer

This repository is for educational purposes only. The developers are not responsible for any misuse or damage caused by this software.

```

---
