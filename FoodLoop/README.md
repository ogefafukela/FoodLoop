# FoodLoop

FoodLoop is a blockchain-based application that helps reduce food waste by using token-based payments. It allows users to donate or exchange food items to reduce wastage and share resources effectively. Built on the **Internet Computer** platform, the application ensures decentralized and transparent management of food donations. The backend is powered by **Node.js**, **Express.js**, and **Azle**, ensuring secure and persistent data storage using the **StableBTreeMap**.

## Features
- Prevent food waste by exchanging or donating food items
- Payment system based on tokens to incentivize participation
- Decentralized and secure data storage on the blockchain
- Easy-to-use API for interacting with food donations and transactions
- Built with **Node.js**, **Express.js**, and **Azle**

## Installation

### Prerequisites
- Node.js (version 20 or later)
- DFX (Internet Computer SDK)

### Setup

1. Clone this repository:
   
   ```bash
   git clone https://github.com/your-username/foodloop.git
   cd foodloop
Install dependencies:

bash
Copy code
npm install
Start the DFX project:

bash
Copy code
dfx start
Deploy the canister:

bash
Copy code
dfx deploy
Run the application locally:

bash
Copy code
npm run dev
API Endpoints
POST /messages: Create a new message (food donation/exchange post).
GET /messages: Retrieve all messages (food donation/exchange posts).
GET /messages/:id: Retrieve a specific message by ID.
PUT /messages/:id: Update a message by ID (e.g., mark a donation as completed).
DELETE /messages/:id: Delete a message by ID.
License
This project is licensed under the MIT License - see the LICENSE file for details.