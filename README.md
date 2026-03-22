This project introduces a trustless ride pooling system where passengers and drivers interact through smart contracts instead of a centralized platform.

Minimum 4 passengers required for a ride
Ride agreement stored on blockchain (immutable)
Payments handled via escrow smart contracts
Automatic penalty enforcement for cancellations
Problem:
Traditional ride pooling systems face:
Last-minute cancellations
Driver financial loss
Lack of trust between users
No strict enforcement of agreements

Solution:
This system uses blockchain technology to:
Create immutable ride agreements
Lock payments in smart contract escrow
Automatically deduct penalties for no-shows
Ensure fair compensation for drivers

⚙️ How It Works
Step 1: Ride Request
User enters:
Pickup location
Destination
Time

Step 2: Passenger Matching
System matches 4 passengers with similar routes.

Step 3: Smart Contract Deployment
A smart contract is created containing:
Ride ID
Passenger wallet addresses
Driver details
Pickup & drop points
Fare and penalty rules

Step 4: Payment Escrow
All passengers deposit fare into the smart contract.

Example:
4 passengers × ₹100 = ₹400 locked

Step 5: Pickup Verification
Passengers must confirm arrival using:
GPS / QR / OTP

Step 6: Penalty Enforcement
If a passenger does not show up:
Penalty → automatically transferred to driver

Step 7: Ride Completion
After ride completion:
Payment released to driver
Transaction recorded on blockchain

🔗 Key Blockchain Features
🔒 Immutability – agreements cannot be changed
🤝 Trustless System – no need for mutual trust
⚡ Automation – smart contracts enforce rules
💰 Escrow Payments – secure fund handling
📊 Transparency – all transactions are recorded

🧱 System Architecture:-
Application Layer
    ↓
Service Layer (Matching, Verification, Reputation)
    ↓
Smart Contract Layer (Ride, Payment, Penalty)
    ↓
Blockchain Layer (Ledger, Consensus)
    ↓
Infrastructure Layer (Wallets, IPFS, Nodes)

🛠️ Tech Stack:-
Component	Technology
Blockchain	Ethereum
Smart Contract	Solidity
Frontend	React / Flutter
Backend	Node.js
Wallet	MetaMask
Storage	IPFS

🔄 Workflow Summary:-
1. Request Ride
2. Match 4 Passengers
3. Deploy Smart Contract
4. Lock Payments (Escrow)
5. Verify Pickup
6. Deduct Penalty (if needed)
7. Complete Ride
8. Release Payment

📊 Example Scenario
Route: IIEST Shibpur → Howrah Station
Passengers: 4
Fare: ₹80 each
Total: ₹320

If one passenger cancels:
₹80 → transferred to driver as penalty

🚀 Future Scope
⭐ On-chain reputation system
🪙 Token-based campus payments
🗳️ DAO governance
🤖 AI-based ride matching
📍 Real-time GPS tracking
