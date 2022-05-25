## Setup

1. Install dependencies

   ```bash
   npm install
   ```

## Running your app locally

1. Start React APP
   ```bash
   npm start
   ```

## Deploying Contract

1. Deploy Contract on Rinkeby:

   A. Add `WALLET_PRIVATE_KEY` and `ALCHEMY_API_KEY` in `.env`

   B. Run `deploy.js`:

   ```bash
   npx hardhat run scripts/deploy.js --network rinkeby
   ```

2. Deploy Contract Locally:

   A. Start a node:

   ```bash
   npx hardhat node
   ```

   B. Run `deploy.js` on localhost:

   ```bash
   npx hardhat run scripts/deploy.js --network localhost
   ```

### Thank You :)
