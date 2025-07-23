Overview
This Clarity smart contract enables subscription-based access control using STX payments. Users can subscribe for a fixed period (default: 30 days) by paying a set price. The contract tracks subscriptions and allows an admin to manage pricing, revoke access, and withdraw funds.

Features
Subscribe: Users pay STX to gain access for 30 days.
Check Access: Verify if a user’s subscription is active.
Admin Controls:
Update subscription price.
Revoke user subscriptions.
Withdraw collected STX.
Usage
subscribe: Users call this function to subscribe (requires payment).
check-access: Read-only function to check if a user is currently subscribed.
set-price: Admin can update the subscription price.
revoke: Admin can revoke a user's subscription.
withdraw: Admin can withdraw STX from the contract.
