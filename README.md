# Blockchain Application

This is a simple blockchain application implemented in TypeScript. It demonstrates basic concepts of blockchain technology, including transactions, blocks, and mining.

## Features

- Create and manage transactions
- Generate blocks and add them to the blockchain
- Mine blocks to find a valid nonce
- Verify transactions using public and private keys

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Rajchal/block-chain.git
    cd block-chain
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

## Usage

1. Compile the TypeScript code:
    ```sh
    npm run dev
    ```

2. Run the application:
    ```sh
    node index.js
    ```

## Example

The following example demonstrates how to create wallets and send money between them:

```typescript
const Anjal = new Wallet();
const Ell = new Wallet();
const Anj = new Wallet();

Anjal.sendMoney(50, Ell.publicKey);
Ell.sendMoney(23, Anj.publicKey);
Anj.sendMoney(5, Ell.publicKey);

console.log(Chain.instance);

Collecting workspace information

Sure! Here is a 

README.md

 file for your blockchain application:

```md
# Blockchain Application

This is a simple blockchain application implemented in TypeScript. It demonstrates basic concepts of blockchain technology, including transactions, blocks, and mining.

## Features

- Create and manage transactions
- Generate blocks and add them to the blockchain
- Mine blocks to find a valid nonce
- Verify transactions using public and private keys

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Rajchal/block-chain.git
    cd block-chain
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

## Usage

1. Compile the TypeScript code:
    ```sh
    npm run dev
    ```

2. Run the application:
    ```sh
    node index.js
    ```

## Example

The following example demonstrates how to create wallets and send money between them:

```typescript
const Anjal = new Wallet();
const Ell = new Wallet();
const Anj = new Wallet();

Anjal.sendMoney(50, Ell.publicKey);
Ell.sendMoney(23, Anj.publicKey);
Anj.sendMoney(5, Ell.publicKey);

console.log(Chain.instance);
```

## Classes

### 

Transaction



Represents a transaction between a payer and a payee.

### 

Block



Represents a block in the blockchain. Contains a transaction, a timestamp, and a nonce.

### 

Chain



Manages the blockchain. Contains methods for adding blocks and mining.

### 

Wallet



Represents a wallet with a public and private key. Can send money by creating transactions.

## License

This project is licensed under the ISC License.
```

You can add this content to your `README.md` file.
You can add this content to your `README.md` file.