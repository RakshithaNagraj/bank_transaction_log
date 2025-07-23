# 💸 Bank Account Manager with SMS Alerts (Twilio + Python)

This is a simple Python-based bank account system that simulates deposit and withdrawal operations while integrating **Twilio SMS** services to send real-time transaction alerts to users. It also features logging and custom exception handling for robust error reporting.

---

## 📌 Features

- 🔐 Custom exception handling for invalid operations (e.g., over-withdrawal, negative deposit).
- 📲 SMS notifications using [Twilio API](https://www.twilio.com/).
- 📄 Transaction logs saved to a local file (`bank_transactions.log`).
- ✅ Clean, modular class-based code with usage example.

---

## 🧠 Prerequisites

- Python 3.6+
- A valid Twilio account with:
  - **Account SID**
  - **Auth Token**
  - **Verified Twilio phone number**
  - **Your own verified phone number**

---

## 🛠️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/bank-account-sms-notifier.git
cd bank-account-sms-notifier
# bank_transaction_log
