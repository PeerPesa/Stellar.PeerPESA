# Peerpesa-Stellar

This DApp allows users to send  stablecoins to mobile number , interact with Stellar blockchain, and transfer funds via mobile money. Below is a step-by-step explanation of how the DApp works, with visuals to help guide users through the process.

## Table of Contents
1. [Overview](#overview)
2. [User Interface](#user-interface)
3. [How It Works](#how-it-works)
   - [Step 1: Connect Wallet](#step-1-connect-wallet)
   - [Step 2: Check Balance](#step-2-check-balance)
   - [Step 3: Send Money](#step-3-send-money)
   - [Step 4: Confirmation](#step-4-confirmation)
4. [Technologies Used](#technologies-used)

## Overview

This DApp facilitates the transfer of stablecoins from stellar wallets address to various mobile money platforms using Flutterwave. Below is a visual guide that walks through the entire process.

## User Interface

![User Interface Overview](https://github.com/user-attachments/assets/15785daa-72b2-431a-9c5a-d5cd1e678f67)

## How It Works

### Step 1: Connect Wallet

The first step is for the user to connect their stellar wallet address.

![Connect Wallet](https://github.com/user-attachments/assets/a8a6a9eb-817f-4d4e-aee8-2183aa2f4ab0)

Once connected, the user's wallet address and balance will be displayed.

### Step 2: Check Balance

After the wallet is connected, the user's current cUSD balance is displayed.

![Check Balance](https://github.com/user-attachments/assets/15785daa-72b2-431a-9c5a-d5cd1e678f67)

*This balance is fetched directly from the stellar  wallet address .*

### Step 3: Send Money

Next, the user enters the amount they wish to send, selects the destination country, and provides the recipient's mobile money account.

![Send Money Form](https://github.com/user-attachments/assets/877d4553-5c8a-4604-bcaf-890e2fe3ade3)

The DApp will convert the xlm amount to the local currency of the selected country.

### Step 4: Confirmation

After confirming the details, the user can send the money.

![Transaction Confirmation](https://github.com/user-attachments/assets/e8e0495c-cab3-4130-bbd1-0fc572b80986)

*The confirmation screen shows the total amount to be deducted, including the transaction fee.*

---

## Technologies Used

- **React** for the frontend
- **Flutterwave API** for mobile money transfers
- **Stellar Blockchain**for xlm transactions
