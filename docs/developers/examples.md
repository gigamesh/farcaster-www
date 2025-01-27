# Examples

Learn how to build your own Farcaster apps by looking at examples of simple applications.

## Fetch a chronological feed

On your local machine, go through the following steps:

1. Check out [hub-monorepo](https://github.com/farcasterxyz/hub-monorepo) to your local machine.

2. Navigate to the `packages/hub-nodejs/examples/chron-feed` directory.

3. Install dependencies with `yarn install` or `npm install`.

4. Run `yarn start` or `npm start` .

:::info
Replace the FIDs at the top of the file with yours to see your messages.
:::

## Update your profile picture

On your local machine, go through the following steps:

1. Check out [hub-monorepo](https://github.com/farcasterxyz/hub-monorepo) to your local machine.

2. Navigate to the `packages/hub-nodejs/examples/write-data` directory.

3. Install dependencies with `yarn install` or `npm install`.

4. Update `MNEMONIC` and `FID` at the top of the file with your own.

5. Run `yarn start` or `npm start` .

:::info
write-data broadcasts to testnet by default, but provides instructions to submit to mainnet
:::

## Replicate data to Postgres DB

On your local machine, go through the following steps:

1. Check out [hub-monorepo](https://github.com/farcasterxyz/hub-monorepo) to your local machine.

2. Navigate to the `packages/hub-nodejs/examples/replicate-data-postgres` directory.

3. Follow the instructions in README.md

## Publish new casts

On your local machine, go through the following steps:

1. Check out [hub-monorepo](https://github.com/farcasterxyz/hub-monorepo) to your local machine.

2. Navigate to the `packages/hub-nodejs/examples/make-cast` directory.

3. Install dependencies with `yarn install` or `npm install`.

4. Update `MNEMONIC` and `FID` at the top of the file with your own.

5. Run `yarn start` or `npm start` .

:::info
make-cast broadcasts to testnet by default, but provides instructions to submit to mainnet
:::