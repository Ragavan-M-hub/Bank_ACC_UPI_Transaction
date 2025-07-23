# 🏦 Bank Account Management System with Twilio SMS Alerts

This Python script simulates a basic bank account system that supports deposit and withdrawal operations. It also sends SMS alerts to the user using the Twilio API and logs all transactions.

## 🚀 Features

- Create bank accounts with an initial balance
- Deposit money into the account
- Withdraw money (with insufficient balance checks)
- Receive SMS alerts for every transaction
- All actions are logged to a file: `bank_transactions.log`
- Custom exception handling for invalid transactions

## 🔧 Requirements

- Python 3.6+
- [Twilio Account](https://www.twilio.com/)
- Twilio phone number and API credentials

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/bank-sms-system.git
cd bank-sms-system
