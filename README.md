# Starknet Account Recovery

If you don't have your seed phrase from Braavos/Argent X wallet - but have your private key - and have funds you'd like to move ASAP since there's no way to import using private key in either wallet - this is for you

NOTE: Your account must not be deprecated. This will not help you if your account is deprecated.

## Usage

1. Create a `.env` file
2. Copy over `.env.sample` to `.env` and fill in the required fields
3. Install npm dependencies (really only `starknet` and `dotenv`)
4. Modify `index.ts` to whatever contract addresses you need to transfer. It's set up for USDC - switch it out for whatever you need to transfer. Remember, ETH is also an ERC-20 on Starknet.
5. Run `npm run dev`
