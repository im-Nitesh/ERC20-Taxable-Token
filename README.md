# ERC-20 Token with Advanced Features

This Ethereum ERC-20 token contract is designed to incorporate several advanced features to enhance functionality and control. Below are the key features implemented in this contract:

## Features

### 1. Tax Structure
   - **Buy Tax:** 5%
   - **Sell Tax:** 10%
      - 50% of the above taxes go into auto-liquidity.
      - 25% is burned.
      - 25% is sent to a specified wallet in the form of ETH.

### 2. Anti-Sniper Bot Feature
   - The contract includes an anti-sniper bot feature to mitigate sniper attacks and ensure fair trading.

### 3. Anti-Whale Mechanism
   - Implements an anti-whale feature, allowing a maximum of 2% of the total token supply to be traded per transaction. This helps prevent large transactions that could impact price stability.

### 4. Tax Exclusion/Inclusion
   - Owner-only function for tax exclusion/inclusion. The owner can designate specific addresses to be excluded or included in tax calculations.

## Usage

1. **Deploy the Contract:**
   - Deploy the contract on the Ethereum blockchain.

2. **Set Initial Parameters:**
   - Set initial parameters such as the auto-liquidity wallet, ETH reward wallet, and other configurable values.

3. **Manage Excluded/Included Addresses:**
   - Use the `excludeFromTax` and `includeInTax` functions to manage addresses that should be excluded or included in tax calculations.

4. **Utilize Advanced Features:**
   - Leverage the implemented tax structure, anti-sniper bot feature, and anti-whale mechanism to create a more secure and controlled token.

## Disclaimer

This contract is provided as a starting point and for educational purposes. Ensure you thoroughly test the contract on testnets before deploying it on the Ethereum mainnet. Smart contract development involves risks, and it's crucial to follow best practices and conduct thorough security audits.
