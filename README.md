# My DAp

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

![User Interface Overview](./blog.png)

## How It Works

### Step 1: Connect Wallet

The first step is for the user to connect their stellar wallet address.

![Connect Wallet](./assets/connect-wallet.png)

Once connected, the user's wallet address and balance will be displayed.

### Step 2: Check Balance

After the wallet is connected, the user's current cUSD balance is displayed.

![Check Balance](./assets/check-balance.png)

*This balance is fetched directly from the stellar  wallet address .*

### Step 3: Send Money

Next, the user enters the amount they wish to send, selects the destination country, and provides the recipient's mobile money account.

![Send Money Form](./assets/send-money-form.png)

The DApp will convert the xlm amount to the local currency of the selected country.

### Step 4: Confirmation

After confirming the details, the user can send the money.

![Transaction Confirmation](./assets/confirmation.png)

*The confirmation screen shows the total amount to be deducted, including the transaction fee.*

---

## Technologies Used

- **React** for the frontend
- **Flutterwave API** for mobile money transfers
- **Stellar Blockchain**for xlm transactions
