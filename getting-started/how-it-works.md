---
description: A detailed look at how Valut enables crypto payments through UPI
---

# How It Works

## The Valut Solution

Valut provides a seamless bridge between cryptocurrency and UPI payments, allowing users to spend their digital assets at any merchant that accepts UPI, without requiring merchants to understand or accept cryptocurrency directly.

## The Core Flow: Scan, Select, Pay

### 1. Scan
Open the Valut app and scan any UPI QR code. Whether you're at a restaurant, paying for groceries, or settling a utility bill – if they accept UPI, you can pay with Valut.

### 2. Select
Choose which cryptocurrency you want to use for this payment. The app will display:
- The amount in INR you're paying
- The equivalent amount in your selected cryptocurrency
- The 2% fee applied to the transaction
- The total amount that will be deducted from your crypto balance

### 3. Pay
Confirm the transaction, and Valut handles everything else. The payment is processed instantly, and the merchant receives INR through the standard UPI system – just like any other UPI payment.

## Behind the Scenes

What makes Valut possible is a sophisticated system working behind the scenes:

### Wallet Architecture
- Each user has a secure 2-of-2 multisig wallet (using Gnosis Safe)
- This provides security through shared control between you and Valut
- You maintain control of your assets while enabling Valut to process payments

### Payment Processing
1. When you initiate a payment, Valut verifies you have sufficient crypto balance
2. The required amount of cryptocurrency is transferred using pre-approved contract access
3. Valut instantly converts the crypto to INR through our liquidity pools
4. The payment is routed to the merchant via India's UPI system
5. The merchant receives INR in their account almost immediately

### Settlement and Confirmation
- You receive an immediate confirmation of your payment
- Transaction details are stored securely in your transaction history
- The merchant experiences this as a standard UPI payment – they don't need to know that cryptocurrency was used

## Technical Foundation

Valut is built on robust blockchain infrastructure:

- **Base OnchainKit Integration** for secure identity verification and wallet generation
- **Gnosis Safe Multisig** for secure, non-custodial wallet management
- **Smart Contracts** that enable instant settlement and pre-approved transactions
- **UPI Payment Gateway** integration for seamless processing through India's payment infrastructure

## Benefits for Users

- **Use Crypto for Daily Purchases**: Finally, make your digital assets useful for everyday transactions
- **Instant Settlement**: No waiting for blockchain confirmations
- **Competitive Rates**: Transparent conversion with a simple 2% fee
- **Wide Acceptance**: Use anywhere that accepts UPI (which is virtually everywhere in India)
- **Security**: Your private keys remain secure with the multisig architecture

## Benefits for Merchants

- **Zero Changes Required**: No new equipment, no new processes, no training needed
- **Standard UPI Settlement**: Receive payments in INR just like any other UPI transaction
- **No Crypto Exposure**: No need to understand cryptocurrency or manage digital assets
- **Instant Receipt**: Funds are received just as quickly as standard UPI payments

[Next: Registration & KYC →](registration-kyc.md)
